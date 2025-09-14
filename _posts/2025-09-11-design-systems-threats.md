---
title: Threats and opportunities for mature design systems
tags:
  - ux
  - tech
  - a11y
  - civic-tech
layout: post
permalink: /design-systems-threats
description: A big part of my day job is making sure that teams use our website's design system appropriately. Here are some traps I see and ideas for how to help the design system and the humans who use it thrive.
---
My day job for the past couple of years has been [design governance](https://bradfrost.com/blog/post/a-design-system-governance-process/) for a very large website. Put simply, my team helps keep this giant website consistent and accessible for our millions of users. 

Our digital ecosystem is big, and there are scores of teams using our design system to build their products ([What is a design system?](https://www.nngroup.com/articles/design-systems-101/)). Our design system has been around a while, it's super-robust, and it has buy-in across the organization. My team's main job is to meet with other teams throughout their design process to make sure that the teams' products align with the rest of the website, meet web and accessibility standards, and of course, use our design system appropriately.

This doesn't happen all the time, but there are some recurring patterns I've observed as product teams work with our design system. I don't think this is unique to our context; I'd wager that these are totally normal things that happen when a design system matures and is in active use by a lot of teams. 
## 1. Design by number
### What it is
Instead of designing an experience or an interaction, the team puts design system components on a page (or in a Figma file) to create an interface, without thinking about the actual user experience. Components are chosen because of how they look, not because of what they do. It’s not UX so much as paint by number. The design has features you recognize, but that’s where the familiarity ends.
### Why it happens
- **Inexperienced designers**: Designers who take this approach are often new or inexperienced, undersupported, or stretched too thin.
- **Free-ranging stakeholders:** A non-designer stakeholder is exerting undue influence on the design, or is being inflexible about business rules, and designers are not empowered or knowledgeable enough to push back. Common signals that a stakeholder is pulling the strings:
	- ”We'll need to get approval for that change.”
	- “Our stakeholder said we need to do it this way.”
### The result
If you have a pre-launch QA process for products (as we do), those design issues, if not caught early, result in a ton of problems that need to be fixed before the product goes live. If those findings aren't deemed important enough to fix before go-live, they go to the team's backlog to die, and the user experience suffers.

If the product ships as-is, it looks like the rest of your site in some ways, but it’s unusable, inaccessible (or 508-compliant only, rather than truly accessible) and you’re not sure what it’s supposed to do. It doesn’t actually help your users.
### Interventions
- **Designers: Focus on clearly defining the problem to be solved**, creating user flows before moving to the toolbox of high-fidelity tools.
- **Designers: Design for mobile first** Designing for a small screen (or high browser zoom) streamlines design and really forces decision-making about the most important elements and interactions. If the page was laid out in one long line, what should the sequence of elements be? What headings would need to be present to help convey the content grouping and hierarchy? This results in a more accessible experience for most users, especially users who rely on assistive technologies like screen readers.
- **Leaders: Mentor junior teams and designers.** This problem is not specifically a design system problem, but it’s exacerbated by a readily available component library. It’s moreso an underdeveloped design ethos. Seasoned, user-centered UX designers who are trusted, mentored, and supported to do good work will know and do better. These folks not only have more experience, but are also prepared to push back when stakeholders ask for something that’s a bad solution. Junior designers can grow into this skillset if they have good mentors.
## 2. First-solution inertia
### What it is
Because robust design systems and Figma libraries make it easier to rapidly develop high-fidelity prototypes, a team’s early design ideas can sometimes ossify too fast. At first glance, the solution seems good. On second glance, it’s clear there is something not quite right, and there is an increasing number of boo-boos being covered up. The sunk cost fallacy leads teams to keep as much of what they’ve got as possible, even if what they actually need to do is scrap it and start again.
### Why it happens
- **Jumps to solutioning:** The design problem hasn’t been completely defined. Key information, constraints or business rules are missing.
- **Favoritism:** Someone (maybe a non-designer stakeholder?) has fallen in love with an early solution and doesn’t want to change course.
- **Iteration creep:** The design started as one thing, but has iterated so much that its functionality has left the bounds of its original design completely and no longer makes sense.
- **Hotfix glue gun:** The design doesn’t accommodate unanticipated stress cases, or doesn’t do well in user testing. “Adjustments” are made by adding on hotfixes rather than addressing the root issue.
- **Looming deadlines:** a team is far down the road with a high-fidelity design and it’s hard to stop, or to incorporate late-breaking changes, before they have a deadline to complete their work.
### The result
The result is something that just ain't quite right, an incomplete or overly complex solution that has gaps for some users with “non-standard” use cases. It's an increasingly brittle interface that makes maintenance a bottomless pit until it can be rebuilt. This’ll create frustrating experiences for users, and it'll be an interface that they have to learn over and over again.
### Interventions
- **Designers: Go lo-fi first, even when hi-fi is easy:** Build lower-fidelity artifacts early in the process, even when it’s easier to jump straight into the weeds with design software. Focus on user flows, rather than getting every single detail right in the wireframes.
- **Designers: Research early:** Do research with users before letting the design harden.
- **Designers: Engage peer reviewers:** Get another set of heuristic eyes on your designs. (Either through a governance process or via peer feedback.) Bring your questions.
- **Leadership: Build in slack time:** Account for time in the project to make potentially breaking changes. Ensure the team is consistently revisiting those user flows from earlier in your design process to make sure you're solving the right problems the right way.
## 3. Disengagement
### What it is
Teams use the design system to design experiences (perhaps quite well!) but don’t contribute to the design system’s growth. Or, they may craft workarounds when the design system doesn't do things *exactly* as needed, rather than suggesting changes.
### Why it happens
- **Lack of support from leadership:** Teams aren’t incentivized, encouraged, or given space to contribute back to the design system and allow it to continue to grow, so it stagnates.
- **Technical debt**: Teams don't have time to contribute to the design system because their backlog is too big, they're moving too fast, or they are simply prioritizing other work.
- **Gatekeeping:** The process for contributing to the design system is opaque, or onerous, or locked down to only one team (or person!). If community members feel like they can't or shouldn't contribute to the design system, they don't. 
- **Inflexible/rigid design system:** The design system isn't helping the teams solve their problems, or is incomplete. Or, the team's engagement with the design system is more punitive ("Fix this or else") than generative ("Let's make sure this component does what you need it to do"). Rather than being seen as a toolbox, it's a checkbox.
### The result
The implications for this are system-wide. The overall user experience of your digital ecosystem can suffer. Stale, inflexible experiences don’t evolve with the times, or worse, teams abandon design system components to craft their own experiences, creating long-term maintainability problems. The end result is a degraded experience for your users, a maintainability quagmire, and inconsistent designs across your platform. In my work context, this is something we work very hard to avoid.
### Interventions
- **Leadership: Prioritize contributions:** Product owners/product managers build time in for their teams to contribute to the design system, and actively encourage them to do so.
- **Design system leads: Make contributions a snap:** Design system owners should pave avenues for teams to make or suggest updates to the design system. The process for new additions to the design system, code updates or new documentation should be well-documented, communicated, and streamlined, including (and especially) for newcomers or novice coders.
- **Governance and design system leads: Listen and adapt**: Inflexible, brittle design systems with overly complicated processes, obtuse approval processes, or hard-to-use tech stacks are expensive to maintain because they are brittle. It's crucial to have clear processes for using, expanding on, updating, or even retiring items from the design system. Humans who are responsible for the design system want product designers to use the system in a consistent way; but conversely, they must be listening for ways the design system can flex to meet changing needs.

## tl;dr: Design systems are people
Technology is people. Design systems are people, too. Most of the issues here, and their solutions, involve deeply human stuff like relationship-building, conversation, clear documentation, conflict resolution, and feedback loops. 

Like any other technology, design systems need attentive care, maintenance, upgrades, and human stewards to ensure that they're used to do the thing they're supposed to do. The key is being prepared to support the entire design system, including the people who are building with it.