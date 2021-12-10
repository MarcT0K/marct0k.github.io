---
title: "Graph visualization: Scientology Web strategy"
date: 2021-12-08T08:12:24+01:00
tags: ["Academic project", "Graph", "Social sciences"]
summary: "I analyze the Web territory occupation using graphs and expose the very specific strategy deployed by the Church of Scientology to \"hack\" the Page Rank"
description: "I analyze the Web territory occupation using graphs and expose the very specific strategy deployed by the Church of Scientology to \"hack\" the Page Rank"
cover:
  image: "/images/sciento-min.png"
  alt: "Scientology Web network"
  caption: "Graph presenting the strategy of Web territory occupation deployed by the Church of Scientology."
  relative: false
showtoc: false
draft: false
---

# Academic context
I created this graph for **Franck Ghitalla**'s network science course. Each edge is a hyperlink and a node is a web entity. To create these graphs, I just needed to realize few simple crawls.

Thanks to this kind of graph, we can visualize and analyse strategies for occupation of web territory. We can also consider social organizations thanks to the web content production.

I studied the strategy of occupation of several groups : far right, Scientology and Jehovah's Witnesses. I chose to show only the graph about Scientology because I consider it as the most clean and atypical.

If you want to learn more about the analysis of the Web using graph, I strongly recommend the book [Qu'est-ce que la cartographie du Web?](https://books.openedition.org/oep/15358) (written by F. Ghitalla, D. Boullier and M. Jacomy) which compiles Franck's blog posts/publications about this question.

# Graph on Scientology's strategy of web occupation
Thanks to the graph above, we see an occupation of Web territory very well thought by the Church of Scientology. To create this graph, I just needed to crawl from scientology.org (with a fixed maximum depth). No data cleaning has been done.

[Web Version of the graph](/scientology-graph/index.html)
## *Legend*

* Node : Website/entity
* Edge : Hyperlink between two entities
* Colour/Size : node degree

# Graph analysis

* The Scientology Web **looks like an intranet**: there is no outbound link pointing at *Mainstream Web* like *Youtube*, etc.
* The nodes have an **extremely high degree** : usually for this kind of website sample, the entity with the highest degree is Youtube and isn't pointed by 90% of the websites.
* There is a **very high density** which creates this round shape.
* There are two poles: a religious one (scientology.org,...) and a cultural one (Dianetics.org,...)
* The further a website is from the centre, the more local the entity is(Scientologi.se, Scientology-Detroit.org,...)
* There are just few French nodes and their degrees are extremely low.

## Conclusions
Scientology deployed a very cleaver Web occupation. Firstly, we notice the existence of a cultural pole which could be an important entry point to the religious part of Scientology. The idea of not having outbound links in this cluster allows to keep the users in the Scientology Web. The big degrees grant a very good ranking by Google algorithms. Finally, the local entities have low degrees because they present an interest for "believers" who have a daily use of these websites. They are like the end of the road in the Scientology Web.

The low degree of French nodes is a strong argument to explain the small presence of Scientology in France (compared to other countries). Therefore, we notice that Scientology haven't succeeded in deploying their strategy of Web occupation in France yet.

It is important to understand that this strategy was a brilliant hack a decade (or even two) ago. The initial Google's **Page Rank algorithm** uses the notion of node degree to index the website. A web page with a high degree is seen as a very popular page. Hence, such page will have higher chance to be returned by Google when you search for something. Obviously, the Web technologies gained in maturity, and I am sure that modern indexation algorithm have some solutions to prevent these "hacks"... especially from such organizations.

Finally, I want to point out that this graph was done on November 2019. About a decade before that, Frank had followed the exact same procedure to study the strategy of the Church of Scientology. My first intent was to observe the evolution of this strategy. In contrary, we had observed that the strategy hadn't changed over a decade!

# Technologies
* Python (crawler)
* Gephi
* Hyphe