---
title: Trans-inclusive design for the Prosocial Design Network
tags:
  - trans
  - ux
  - tech
  - speaking
layout: post
permalink: /trans-inclusive-design-prosocial
---
The kind folks at the [Prosocial Design Network](https://www.prosocialdesign.org/) asked me to be a guest at this month's "pro-social," a very low-key virtual gathering for folks interested in creating more inclusive digital spaces.

More about PDN:

> The Prosocial Design Network connects research to practice toward a world in which online spaces are healthy, productive, respect human dignity, and improve society.

They shared the questions in advance, which I very much appreciated! Here are my prepared notes - we certainly didn't cover it all during the call.

## What principles should be front of mind in designing inclusive digital spaces, particularly social spaces?

**First off, hire people with different lived experiences from yours.** Hire trans people. Hire Black people. Hire disabled people. Hire disabled Black trans people. Let them cook. Listen to them. Otherwise you are, as my wife says, "Pissing into the wind."

**Prioritize accessibility.** Ensure spaces are accessible for users on many devices, using different device settings, in different contexts in the real world including with assistive technologies. Often accessibility is an afterthought. Shift left and allow it go drive your design and architecture decisions from the jump. For social apps, this includes setting smart defaults - i.e. requiring folks to add alt text if they're uploading images.

**Keep your tech stack light and boring.** Design for a 4-year-old Android phone on a 3g connection, with bandwidth paid for by the megabyte. Bloatware takes longer to load and harms or disincentivizes participation from folks on slower connections or older tech. 

**Design for trust, privacy and safety.** Design for people to be able to protect their privacy, control what they share and what they see.
 - Don't ask for information you don't need, and tell people why you're asking for what you do need. 
 - Make privacy and sharing settings crystal clear. 
 - Remind folks that no site is 100% secure even if you're encrypting every bit.
 - Provide feedback/reporting mechanisms. 
 - Allow people to block/opt out of interacting with others or groups, or types of content. 
 - Don't overpromise! If you have gaps or areas still under development, name them. 
 - Have good documentation and support. Don't leave people wondering what to do. 
 - Look to successful, intentionally-designed communities - like [BlackSky](https://blog.rudyfraser.com/an-internet-of-many-autonomous-communities/) - for cues about designing inclusive, safe spaces.

**Allow people to define themselves.** The way you do it ain't the way everybody else does it.
 - Be aware of **any** type of binary options when it comes to identifying themselves - not just gender, but everything else. Are you technical or nontechnical? Employed or unemployed? Full-time or part-time? In all of these cases it's not so clear. 
 - Think in terms of checkboxes, not radios. Tagging, not categorizing.
 - Give people freedom in choosing avatars or profile images.
 - Give people freedom to change/update usernames and login email addresses without hassle.
 - Don't make inferences about who people are or what they'd like based on their gender, race or other things that they choose to share with you.
 - Confront your own ideas about people having one "true identity" - like a real name policy or assuming that everyone has the same interactions with everyone in their lives in every context. We certainly know this is true because 4chan exist(ed) - but let's also remember that this might be the way that a trans person tries on a new name for the first time.

You may have noticed this isn't necessarily specific to trans-inclusive design. That's because this is the kind of work that, by considering folks in marginalized positions, benefits everyone. It's the curb cut effect for accessibility AND privacy AND safety AND inclusion. By focusing our design on the margins we include everyone between them too.

### Since you wrote your article in 2019, what are fails sites continue to make when it comes to trans inclusive design?

The biggest fail I continue to see is that folks are asking for gender or sex information at all, because it is usually not needed. It usually means that this data is being brokered into a database somewhere and sold for money. 

I don't need to tell you my gender to book a hotel. Why are you asking for it?

The unnecessary asking for gender gets worse now that we are seeing a rollback of  previous progress in inclusive design we had made in the past few years. We'd been doing so well! The US Web Design system [had a really thoughtful pattern](https://web.archive.org/web/20250123072001/https://designsystem.digital.gov/patterns/create-a-user-profile/gender-identity-and-sex/) about asking for gender that was starting to roll out to all these government forms. But now agencies are in the process of **removing** the pattern for asking for gender in an inclusive way, and replacing it with a [binary option for sex](https://designsystem.digital.gov/patterns/create-a-user-profile/sex/). 

These design systems changes are in addition to removing all references to being trans from websites, and no longer offering services or information for trans people. It's a very literal erasure of trans identity. It's really upsetting, scary, and for trans folks, it's existential.

I encourage practitioners to plan ahead for the moment when you are asked to do something that you know is wrong. That day will come. What will you say? What will you say no to? What's your red line?

### What new concerns do you have with AI and do you have any advice for tech folk?

I have a lot of concerns with AI. I do think there are useful applications for the technology, **and** 99.99% of the applications out there are either actively predatory, passively harmful, gratuitous and mid, or all of the above. And they are **all** harming [the environment](https://jacobin.com/2024/06/ai-data-center-energy-usage-environment/) and [our health](https://interestingengineering.com/energy/us-ai-data-center-air-pollution).

1. **Garbage in, garbage out.** AI is pattern recognition. And the patterns it's trained on are filled with bias! Bias harms people who are in the minority. According to a recent study out of Stanford:
    > "synthetically generated texts from five of the most pervasive LMs ...perpetuate harms of **omission, subordination, and stereotyping** for minoritized individuals with intersectional race, gender, and/or sexual orientation identities." - [Laissez-Faire Harms: Algorithmic Biases in Generative Language Models (2024)](https://arxiv.org/abs/2404.07475)

2. **...and this includes code.** When AI is trained on design patterns or code that is widely popular, but that also includes a lot of code that's inaccessible or unusable, the resulting code is also inaccessible or unusable. We should also be extremely wary of any AI tool that claims it can [refactor a codebase](https://www.wethebuilders.org/posts/what-it-really-takes-to-migrate-cobol) written in a language that most modern coders are not using.
  
3. **AI is a tool of capitalism and state violence.** Generative AI is being used to consolidate, analyze, and generate information in a way that can be used to surveil, prosecute, incarcerate, and [kill people](https://en.wikipedia.org/wiki/AI-assisted_targeting_in_the_Gaza_Strip).
  
4. **AI is seen as a smart humanoid.** People tend to [believe algorithms more than each other](https://www.nature.com/articles/s41598-021-87480-9) as task complexity increases - but we also tend to view AI as human-like. We anthropomorphize AI tools by giving them human-like names or designing them as chat prompts, rather than command prompts, which leads us to believe that we are in fact talking with another living being rather than a computer. It also leads some folks to think that [AI will become sentient](https://www.nytimes.com/2025/04/24/technology/ai-welfare-anthropic-claude.html). It won't, actually, but it will if humans believe that it is, which is perhaps worse.

5. [**AI is mid.**](https://www.nytimes.com/2025/03/29/opinion/ai-tech-innovation.html) And by that, I mean that what it produces is functionally a middle-of-the-road, average, non-"edge case" output. This flattens our differences and creates a "norm" which actually does not exist. Individual people aren't "normal", but AI sure likes to tell us that's a thing, and that really harms people who are far from that norm. Saying that everyone is the same denies the fact that we are all weird as hell. It's our differences that make us stronger, more creative, better.
  
6. **Critique is painted as fear.** Proponents of AI say that skeptics are "afraid" of AI or don't understand it. I, for one, am not afraid of it - I'm deeply frustrated by how folks are using it. I **do** understand it! I know too much. Dismissing AI detractors as "fearful" allows proponents to dismiss valid critique outright rather than engage with it. It's a strawman argument.
   
   If you are AI-critique curious:
   - [Algorithmic Justice League](https://www.ajl.org/)
   - [Distributed AI Research Institute](https://www.dair-institute.org/)
   - [Mystery AI Hype Theater 3000](https://www.dair-institute.org/maiht3k/) 
   - [We deserve better than an AI-powered future](https://www.characterworks.co/blog/we-deserve-better-than-an-ai-powered-future) 

### My AI wishlist for technologists
**Don't make AI your main thing.** Charles Eames said, "Never delegate understanding." Don't rely on AI alone to make decisions about what's true, certainly not for core parts of your work.

**Understand the bias** that ships with your LLM. Do everything you can to critically evaluate outputs for inaccessible, biased or otherwise harmful content.

**If you don't need to use AI, don't.**  Do something else. Turn off default settings that include AI. Switch your search engine to DuckDuckGo and turn off AI features. Turn off Apple intelligence. Turn off Google Gemini. Take a harm-reduction approach to your tech use. (FWIW, this is my approach to eating animal food products. I'm not vegan or even completely vegetarian, but I don't build my food habits around animal products, which reduces how many animal products I consume.)

 **Advocate for sustainable, safe AI**, including regulation and environmental mitigation measures. Individual choices get us down the road a piece, but what we really need is to mitigate the impacts at a high level.

**Engage your discomfort.** If someone critiques AI and it makes you uncomfortable, listen to understand and be open to changing your mind. Most of the folks who are warning about the harms of AI are minoritized people - Black and brown women, queer and trans people. Believe them!

### Since you wrote your article in 2019, what are fails sites continue to make when it comes to trans inclusive design?

The biggest fail I continue to see is that folks are asking for gender or sex information at all - because it is usually not needed. It usually means that this data is being brokered into a database somewhere and sold for money. I don't need to tell you my gender to book a hotel. Why are you asking for it?

The unnecessary asking for gender gets worse now that we are seeing a rollback of  previous progress in inclusive design we had made in the past few years. We'd been doing so well! Like, the US Web Design system [had a really thoughtful pattern](https://web.archive.org/web/20250123072001/https://designsystem.digital.gov/patterns/create-a-user-profile/gender-identity-and-sex/) about asking for gender that was starting to roll out to all these government forms. But now agencies are in the process of **removing** the pattern for asking for gender in an inclusive way, and replacing it with a [binary option for sex](https://designsystem.digital.gov/patterns/create-a-user-profile/sex/). (In addition to removing all references to being trans from websites, and no longer offering services or information for trans people.) It's really upsetting and scary. For trans people, the issue is existential.

I encourage folks on the call to plan ahead for the moment when you are asked to do something that you know is wrong. That day will come. What will you say? What will you say no to? What's your red line?

### What new concerns do you have with AI and do you have any advice for tech folk?

I have a lot of concerns with AI! I do think there are useful applications for the technology, **and** 99.99% of the applications out there are either actively predatory, passively harmful, gratuitous and mid, or all of the above. And they are **all** harming the environment.

I'll distill my concerns into a few buckets:

- **Garbage in, garbage out.** AI is pattern recognition. And the patterns it's trained on are filled with bias! Bias harms people who are in the minority. According to a recent study out of Stanford:
  
  > "synthetically generated texts from five of the most pervasive LMs ...perpetuate harms of **omission, subordination, and stereotyping** for minoritized individuals with intersectional race, gender, and/or sexual orientation identities." - [Laissez-Faire Harms: Algorithmic Biases in Generative Language Models (2024)](https://arxiv.org/abs/2404.07475)

  ...and to extrapolate this garbage-in/garbage-out concept to AI-generated code, when AI is trained on design patterns or code that is inaccessible or unusable, the resulting code is also inaccessible or unusable. Or the combination of accessible components might not be accessible.
  
- **AI as a tool of state violence.** Generative AI, like most technologies, is being used in service of capital and state interests to harm people. It's used for predictive policing, and consolidating information in a way that can be used to surveil, prosecute, and incarcerate people. And most often those folks are not white, not cisgender, not disabled.
  
- **The AI mystique** - people tend to believe what they read online already, but now that it's AI, folks are more likely to believe what they're told. "If a computer says it, it's true + the word "intelligence" in AI + AI tools being positioned as human because they are chatbots = people believing what they're reading. That's not good for a number of reasons, going back to the notion of replicating bias but also the sheer volume of bullshit--outright incorrect information--that's generated. It's harmful.

- **AI is mid.** And by that, I mean that what it produces is functionally a middle-of-the-road, average, non-"edge case" output. This not only flattens our differences, but it also reinforces a "norm" which actually does not exist. Individual people aren't "normal" but AI sure likes to tell us that's a thing, and that really harms people who are far from that norm. And saying "everyone is the same" actually detracts from the cool and true thing, which is that we are all weird as hell.
  
- **Critique is painted as fear.** Proponents of AI say that skeptics are "afraid" of AI or don't understand it, but real talk, I am not afraid of it - I'm deeply frustrated by how folks are using it. I **do** understand it! I know too much. Dismissing AI detractors as "fearful" allows proponents to dismiss valid critique outright rather than engage with it. It's a strawman argument.

My AI takeaways for technologists:
- **Don't make it your main thing.** Charles Eames said, "Never delegate understanding." Don't rely on AI alone to make decisions about what's true, certainly not for core parts of your work.
- **Understand the bias** that ships with your LLM. Do everything you can to critically evaluate outputs for inaccessible, biased or otherwise harmful content.
- **If you don't need to use AI, don't.** Turn off default settings that include AI. Do something else. Switch your search engine. Turn off your Apple intelligence. Turn off Gemini. Not everything has to be a part of the knowledge graph. 
	- FWIW, this is my approach to eating animal products. I'm not vegan or even vegetarian. I just don't build my food habits around meat.
- **Engage your discomfort.** If someone critiques AI and it makes you uncomfortable, listen to understand and be open to changing your mind. Most of the folks who are warning about the harms of AI are minoritized people - Black and brown women, queer and trans people. Believe them!

### Are there any questions you think researchers could help answer regarding trans-inclusive design?

This is an excellent question. Some of the things I'd ask folks to understand include...

**What are ways we can design for trust and safety?** How can we create digital spaces where people feel safe? What are some of the ways we can foster trustworthiness?

**What would trans-informed design look like?** How can we use the very concept of transness - boundary-crossing, liminality, non-binary thinking - to expand our thinking about how technologies can be used, and to what ends?
  
Oliver Haimson is studying this very thing, and his new book [Trans Technologies](https://direct.mit.edu/books/oa-monograph/5913/Trans-Technologies) is available for free, open access, from MIT Press.
 
 **How might trans-inclusive digital design change IRL service design?** We're already seeing this as part of our work in Civic Tech, moving from automation to true digital transformation. We all know that real-world constraints map to technological design choices. How then do we transform the tech stack and use that to change our very service delivery model?