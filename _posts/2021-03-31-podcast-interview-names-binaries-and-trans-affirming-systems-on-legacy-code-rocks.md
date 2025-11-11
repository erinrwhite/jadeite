---
id: 364
title: 'Podcast interview: Names, binaries and trans-affirming systems on Legacy Code Rocks!'
date: '2021-03-31T17:38:50-04:00'
author: erinrwhite
layout: post
permalink: /podcast-interview-names-binaries-and-trans-affirming-systems-on-legacy-code-rocks/
tags: speaking libraries tech ux trans
---

In February I was honored to be invited to join Scott Ford on his podcast [Legacy Code Rocks!](https://www.legacycode.rocks/episodes/93/). I’m embedding the audio below. [View the full episode transcript](https://docs.google.com/document/d/e/2PACX-1vSD3JAZVDuYSbhQASCdUwAzBx1XDlzvWWi01rPOl7Qt_IdZCNRrNnGdinwtv4MA2vlTvqdo1GYg4Zwj/pub) — thanks to trans-owned [Deep South Transcription Services](https://www.facebook.com/DeepSouthTranscriptionServices)!

I’ve pulled out some of the topics we discussed and heavily edited/rearranged them for clarity.

## Names in systems

### Legal name vs. name of use

Let’s think about Facebook’s former [Real name policy](https://www.cbc.ca/news/technology/facebook-real-names-1.3367403#:~:text=Facebook%20requires%20people%20to%20%22provide,who%20they're%20connecting%20with.&text=When%20the%20company%20receives%20a,such%20as%20a%20driver's%20licence.). Early on Mark Zuckerberg even said that having two names showed a [lack of integrity](https://michaelzimmer.org/2010/05/14/facebooks-zuckerberg-having-two-identities-for-yourself-is-an-example-of-a-lack-of-integrity/).

The underlying assumption was that there’s one name that everybody always uses, and only people with malicious intend would do anything different. The notion that people are using different identities to “trick” others is also a common, harmful [trope used to demonize and discredit trans people](https://www.vox.com/identities/2016/5/13/17938090/transgender-people-tricks-confused).

We now widely acknowledge that people are called different names in different circumstances either because of familial or professional relationships, different eras of their lives, different contexts, or because of a change in their gender identity.

People’s **legal names** may stay the same, but their **names of use** vary. That was the thing that got me thinking about trans-affirming systems design.

What would a world look like where trans folks actually see themselves in systems rather than simply accommodated? What if if they truly were affirmed and celebrated?

One way to do that is to allow people to say what their names are. There are very few contexts when we actually need folks’ full legal first names.

### Not “edge cases”

Allowing for name flexibility is an example of a technology that helps a lot of different people. For example, of the 140 people on staff at our library, about a third of us are using names that are different from our full legal first name. People are going by middle names or by more familiar versions of first names, like Jimmy instead of James; or are using totally different names. While some people would see an errant name field as a minor annoyance, for other folks it’s a safety issue. It’s one change that’s a big quality of life increase for a lot of folks.

## Binaries

Then there’s the gender binary. Computers run on binaries. As technologists we love the idea of ones and zeros, simplifying things when possible: off/on, yes/no; and frequently we do that with gender too. You’ve got a form asking for gender (typically unnecessarily) and there’s only two options.

### Gendered stereotypes serve no one

We know full well that when we provide gender data it is often used to sell us things based gender stereotypes. When systems are actively reinforcing the gender binary, the result is reductive and uninspiring, and something that doesn’t reflect the lived gender experience of most people, whether they are trans or not.

### Trans/cis binary

Another gender-related binary: either you’re trans or you’re cis. That’s a false binary. People’s gender identities change throughout their lives. There’s valid expressions of gender identity that are neither/nor, that are both/and, so to create that wall between trans and cis is really harmful for all, and cashes out as violence against people who don’t conform.

So many trans people I know don’t think they are “trans enough.” And so many cis people spend so much time trying to prove that they are manly or womanly enough. It’s exhausting.

### Everybody has a gender

It’s important for folks who identify as cisgender to to think about and question their genders. You have gender(s)!

Ask yourself, How does my gender impact how I move through the world? How does it impact how I interact with people, and how I present myself, how I dress? It’s not just trans people that should be thinking about this. Just reflect on what your gender is, and how you do it. There’s so much richness there, even within within the cisgender and transgender buckets, there’s just so much.

### Binaries create inequalities

Binaries in themselves can be violent. As humans, we categorize things as a survival mechanism so that we don’t have to spend all our energy processing every single sensory input.

At the same time, when we have categories that pit things against each other with a clear delineating line between, those differentiations create inequality.

One harmful binary at the root of American culture: either you’re white or you’re not, and you’re less than. The foundation of the U.S. is the exploitation and oppression of nonwhite people, Black and brown people. In technology, a binary might be “technical” and “non-technical” people. Those types of less-than/greater-than binaries occur across identities and sectors including gender.

Once you start to perceive all the binaries you can’t unsee them. Understanding how detrimental they are helps us understand how the systems we build can reject them and instead reflect the rich bouquet of lived human experience.

## Making trans-affirming systems

**Audit how how names are handled.** Do you require a legal name for anything? If not, let people choose their name, let people update it. Does that name cascade to their username? Are they able to change a username? If I signed up 10 years ago and now I need to change my username, I want to bring over my entire history, am I able to do that?

**Follow that up with a gender audit**. Are you asking for gender anywhere? Why do you actually need it? Are you asking for people to indicate gender or a title? Add the gender-inclusive Mx. to the honorifics field and if possible make it optional because some folks are just not into it.

**Images.** If you’re using stock photography or other images on your site, do they represent diversity of lived experiences? Do you have folks who are not white, who are not young, who are disabled, who maybe aren’t conventionally gender presenting? Folks dressed in different types of clothing or with different gender presentation? There’s a few different open photo libraries on the web — the broadly gender spectrum collection comes to mind.

**Content.** Think about the the content of the web and how users are communicated with in the language that we use. Singular “they” instead of “he or she.”

More on my A List Apart article, [Trans-inclusive design](https://alistapart.com/article/trans-inclusive-design).

## Closing

I recently read [Design Justice](https://design-justice.pubpub.org/) and can’t recommend it highly enough. Constant learning is our life’s work. We can’t stay stagnant. We have to keep pushing ourselves, talking to people, and making sure that what we’re building is something that’s going to serve everybody.