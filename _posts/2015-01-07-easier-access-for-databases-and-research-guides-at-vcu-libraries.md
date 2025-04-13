---
id: 212
title: 'Easier access for databases and research guides at VCU Libraries'
date: '2015-01-07T10:00:10-05:00'
author: erinrwhite
layout: post
guid: 'http://erinrwhite.com/?p=212'
permalink: /easier-access-for-databases-and-research-guides-at-vcu-libraries/
categories:
    - Libraries
    - Projects
    - UX
    - IA
---

Today VCU Libraries launched a couple of new web tools that should make it easier for people to find or discover our library’s databases and research guides.

This project’s goal was to help connect “hunters” to known databases and help “gatherers” explore new topic areas in databases and research guides<sup>[1](#footnote1)</sup>. Our web redesign task force identified these issues in 2012 user research.

## 1. New look for the databases list

Since the dawn of library-web time, visitors to our [databases landing page](https://apps.library.vcu.edu/dblist/) were presented with an A to Z list of hundreds of databases with a list of subject categories tucked away in the sidebar.

[![new db list]({{site.baseurl}}assets/2013-2024//2015/01/Screen-Shot-2015-01-06-at-4.07.58-PM-300x266.png)](https://apps.library.vcu.edu/dblist/)The new design for the databases list presents a few ways to get at databases, in this order:

**For the hunters:**

- Search by title with autocomplete (new functionality)
- A to Z links

**For the gatherers:**

- Popular databases (new functionality)
- Databases by subject

And, on [database subject pages](https://apps.library.vcu.edu/dblist/category/77) and [database search results](https://apps.library.vcu.edu/dblist/search?q=medicine), there are links to related research guides.

## 2. Suggested results for search

Building on the search feature in the new database list, we created an AJAX Google Adwords-esque add-on to our search engine (Ex Libris’ Primo) that recommends databases or research guides results based on the search query. For longer, more complex queries, no suggestions are shown.

![suggested results]({{site.baseurl}}assets/2013-2024//2015/01/Screen-Shot-2015-01-06-at-4.19.18-PM-300x259.png)Try these queries:

- [cinahl](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,cinahl)
- [dissertations](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,dissertations)
- [psycinfo](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,psycinfo)
- [art history](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,art+history)
- [surgery](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,surgery)
- [video games violence](http://search.library.vcu.edu/primo_library/libweb/action/dlSearch.do?institution=VCU&vid=VCU&search_scope=all_scope&dym=true&query=any,contains,video+games+violence) (no matches)

Included in the suggested results:

- [Database](https://apps.library.vcu.edu/dblist/) titles and descriptions, which are being indexed in the VCU Libraries search engine
- [Subject guide](http://guides.library.vcu.edu/) and [How do I… guide](http://guides.library.vcu.edu/home/howdoi) titles using the LibGuides 1.0 API

## 3. Updates to link pathways for databases

To highlight the changes to the databases page, we also made some changes to how we are linking to it. Previously, our homepage search box linked to popular databases, the alphabet characters A through Z, our subject list, and “all”.

![old A-Z links]({{site.baseurl}}assets/2013-2024//2015/01/Screen-Shot-2015-01-06-at-12.51.22-PM-300x156.png)

The intent of the new design is to surface the new databases list landing page and wean users off the A-Z interaction pattern in lieu of search.

![Screen Shot 2015-01-06 at 12.50.20 PM]({{site.baseurl}}assets/2013-2024//2015/01/Screen-Shot-2015-01-06-at-12.50.20-PM.png)

The top three databases are still on the list both for easy access and to provide “information scent” to clue beginner researchers in on what a database might be.

Dropping the A-Z links will require advanced researchers to make a change in their interaction patterns, but it could also mean that they’re able to get to their favorite databases more easily (and possibly unearth new databases they didn’t know about).

## Remaining questions/issues

- Research guides search is just okay. The results are helpful a majority of the time and wildly nonsensical the rest of the time. And, this search is slowing down the overall load time for suggested results. The jury is still out on whether we’ll keep this search around.
- Our database subject categories need work, and we need to figure out how research guides and database categories should relate to each other. They don’t connect right now.
- We don’t know if people will actually *use* the suggested search results and are not sure how to define success. We are tracking the number of clicks on these links using Google Analytics event tracking – but what’s good? How do we know to keep this system around?
- The change away from the A-Z link list will be disruptive for many and was not universally popular among our librarians. Ultimately it should be faster for “hunters”, but we will likely hear groans.
- The database title search doesn’t yet account for common and understandable misspellings<sup>[2](#footnote2)</sup> of database names, which we hope to rectify in the future with alternate titles in the metadata.

## Necessary credits

**Shariq Torres**, our web engineer, provided the programming brawn behind this project, completely rearchitecting the database list in Slim/Ember and writing an AJAX frontend for the suggested results. Shariq worked with systems librarians **Emily Owens** and **Tom McNulty** to get a Dublin Core XML file of the databases indexed and searchable in Primo. Web designer **Alison Tinker** consulted on look and feel and responsified the design for smaller-screen devices. A slew of **VCU librarians** provided valuable feedback and QA testing.

---

1. I believe this hunter-gatherer analogy for information-seeking behaviors came from Sandstrom’s [An Optimal Foraging Approach to Information Seeking and Use](http://www.jstor.org/stable/4308969) (1994) and have heard it in multiple forms from smart librarians over the years.
2. Great info from Ken Varnum’s [Database Names are Hard to Learn](http://www.lib.umich.edu/blogs/library-tech-talk/database-names-are-hard-learn) (2014)