---
title: "Trying out SimpleAnalytics with no (external) Javascript"
tags:
  - tech
  - privacy
layout: post
permalink: /no-external-js-simpleanalytics
description: Trying out a lightweight, privacy-focused analytics tool for my site after 15 years of Google Analytics bloatware.
---
I've been really enjoying myself since I [moved my website from Wordpress to Jekyll](/first-post-with-jekyll/) earlier this year. It's required me to think more deeply about what functionality I actually want on my website, rather than rolling with a massive set of defaults, most of which I never really used fully.

One thing that's been missing is being able to have an idea of which pages on my website are getting visits, and what some of the referring sites are. 

After successfully setting up [Webmentions for Jekyll](https://github.com/aarongustafson/jekyll-webmention_io) to capture incoming mentions from other website creators (an entirely different post!), I decided to look for an easy way to collect usage data from the site. 

## Measuring use, not users

Before I started looking at options, I reflected on what data I wanted to gather:

- which pages on my site are being accessed,
- how many times, and
- how people got there.

I didn't want to collect data about the **people** using my site - just how it's being used.

## Tech requirements

I've worked with a number of web analytics tools over the years - AwStats, Urchin, Google Analytics, Matomo. GA is the giant player because it is free and thus ubiquitous. (Check out the [Google Analytics stats on BuiltWith](https://trends.builtwith.com/analytics/Google-Analytics/) if you want to truly see how popular it is.) And as the adage goes, when a product with this many features is free, it's because you and your users are the product.

Beyond my privacy concerns with Google Analytics, I just don't need all of that! I get overwhelmed when I log in to check on other projects I'm working on because the UI is just so impenetrable. I don't need all that data, and I certainly don't need to be calling all those Javascript files and trackers all over my website.

When I started looking at alternatives, I wanted a tool that:

- Has a non-Javascript option
- Only collects the info I want to collect
- Doesn't invade my visitors' privacy
- Is hosted or easily hosted by me
- Is easy to use and understand
- Is low-cost

## Choosing SimpleAnalytics

I did some shopping around, and to my delight, there are some really fantastic options out there for privacy-respecting analytics packages, many of them from Europe due to the [GDPR requirements](https://gdpr-info.eu/).

Of the many products I explored, [SimpleAnalytics](https://www.simpleanalytics.com/) was one that matched my list of requirements best because it [can be used without Javascript](https://docs.simpleanalytics.com/without-javascript). 

## No Javascript required

The instructions for installing SimpleAnalytics are straightforward: call an external Javascript file, and if your users have Javascript turned off, use a tracking GIF as a fallback. The GIF returns less data than the Javascript method does (which is actually great!). Even better, the image file can be the primary way that data makes it to SimpleAnalytics, rather than just a fallback.

## But also maybe some light Javascript

After tinkering with the GIF-only analytics implementation a bit, I realized I could send more information consistently using the GIF if I [added some parameters](https://docs.simpleanalytics.com/without-javascript#:~:text=These%20are%20the%20values%20we%20can%E2%80%99t%20get%20with%20the%20pixel%20alone%3A) to the URL for the image file. The data points I really wanted to capture reliably were `referrer`, which isn't available by default with the GIF, and `page path` , which can be reported less reliably using the GIF.

To be able to identify these variables and add them to the link to the GIF, I'd need to add some Javascript on the page. One of the things I loved about moving to Jekyll was that I didn't have any Javascript on my site, but adding these few lines was an acceptable compromise for me - still better than calling a huge external file, and it also allowed me to hand-tailor what attributes I sent to analytics. 

Here's where I landed - a quick script in the footer template of my site that...

- pulls in the full hostname and pathname of the current page
- grabs the referring URL if there is one
- concatenates everything into the full URL to the GIF
- builds an `<img>` tag to render the GIF on the page and send the analytics

### Code

{% gist c77eefc786fb2574160c21d30ef9e61a %}

**Note:** I wrote [another version of this script that collects the user's time zone](https://gist.github.com/erinrwhite/c77eefc786fb2574160c21d30ef9e61a/70400a3976833bc29b83d0192f53b2a53aa1e4fe), just to complete the set of attributes that can be sent using the GIF with SimpleAnalytics. 

**Second note:** Yes, I realize that embedding a Gist is embedding an external Javascript. The difference here is that it's not on every single page of my site, and it isn't tracking users.

## We'll see!

The SimpleAnalytics free plan keeps the data for only 30 days, which is also a feature and not a bug to me. I signed myself up for weekly reports in my email inbox so I can set it and forget it.

This is yet another example of [choosing to change tech platforms](/goodbye-spotify) and just seeing what happens. This is a really low-stakes test for me and was very gratifying to get up and running. 

## Postscript: Making shit feels good

With this and my other tech-focused posts this year, I've been finding a lot of grounding during a time of looming fascism in the USA by being able to enter a flow state, learn some new stuff, and create something with my hands. [Ethan Marcotte](https://ethanmarcotte.com/wrote/parker/) has written about this on his blog and I continue to think about how, coupled with other actions in our communities, making things can be a way to keep sane and build a future we want to see. Even if it's 12 lines of Javascript code.