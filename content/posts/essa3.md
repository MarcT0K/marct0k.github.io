---
title: "ESSA3, an amazing workshop about Searchable Encryption"
date: 2023-06-20T15:02:19+01:00
category: ["Conference", "Searchable Encryption", "Cryptography", "Privacy"]
summary: In early June 2023, Searchable Encryption researchers gathered to discuss past and future achievements in this area...and I was there!
description: In early June 2023, Searchable Encryption researchers gathered to discuss past and future achievements in this area...and I was there!
cover:
  image: "/images/Bertinoro.jpg"
  alt: "Photo of Bertinoro from Wikimedia Commons"
  caption:
  relative: false
showtoc: false
draft: false
---

[ESSA](https://essa23.bici.events/) (Encryption for Secure Search and other Algorithms) is a workshop organized every few years to discuss the advances in Searchable Encryption (SE). This third edition (like the previous two editions) was organized in Bertinoro (Italy) by Sasha Boldyreva and Adam O'Neill. Thanks to one of my PhD advisors, I received an invite and was able to attend this event.

Due to various reasons (primarily the COVID pandemic), I never had the opportunity to present my previous papers physically. Hence, I hadn't met anyone from the SE community. Hence, it was the perfect occasion to get to know the community. Moreover, we even had new results to present, so the timing was ideal.

First and foremost, I want to **thank Sacha and Adam** for the organization. I enjoyed this event so much. I consider this kind of event to be more fruitful than any top-tier conference to build collaborations and plant the seeds of future scientific breakthroughs;

# The venue

The workshop was organized in an old stone building atop a hill. From the venue, we have an astounding view of the Emilia-Romagna region. Unfortunately, the week has been quite rainy, but we had a few sunny breaks to enjoy the view... and take a group photo!

The building is an old castle/monastery. The rooms are a bit austere, but you feel like you are in a spiritual retreat. The conference room even looks like an old chapel with painted walls and ceilings. I really love the atmosphere it gives to the event.

The only downside of the venue is its location: Bertinoro is not easy to reach. However, the venue is excellent once there, so it can be worth it. Some researchers only came from the US for this event, so I cannot complain about the travel time. For European researchers attending this event, I suggest taking the train and stopping in Milan or Bologna for one or two nights. In my case, I could not make the whole train travel in a day, so it was a perfect excuse to visit another city on my way to Bertinoro.

# The community

It was great to meet the SE community. We were about 20 participants. Despite the absence of a few major researchers, the event size was nice for having meaningful discussions. The SE community is more or less divided into two blocks: the cryptanalysts (attacking the schemes) and the cryptographers (proposing schemes). This duality helps to develop exciting debates. The attendees were super nice, and I was glad to meet them.

I often compare various scientific habits since my PhD is at the intersection of several communities (i.e., security, cryptography, privacy, and machine learning). While it is insightful as a PhD student to discover the different ways to build scientific communities, I must appear annoying because I sometimes point out how things can be better in another community 🙃. However, it was not the case in Bertinoro since I praised how the ML community's habits (and size) are problematic compared to the security community's.

# The talks

Surprisingly, I wrote three attack papers, but I had no clue how SE was implemented in practice. The SE design talks were then the occasion to fill my ignorance. On the other hand, I obviously liked the talks presenting novel attacks. These papers are fun to build. Like many security researchers, it is easy to catch my attention with new attack problems. If I had to highlight only one talk, I would mention Tianxin's presentation about MongoDB. It is an essential reminder that real-world deployments require us to be extra careful with the implementation details. Otherwise, all our theoretical efforts will be worthless in the end.

My overall takeaway from these talks is that the attack literature has been rather prolific over the last few years. The efforts in SE constructions continued. It is now time to confront these lines of work.

# My talk

You may wonder what I presented during this workshop. This is an excellent question! During ESSA, we want to gather feedback about a new idea called "statistical risk assessment". Like many people in the room, we have been part of the attack literature, ten years of successive "highly accurate" attacks. However, a key question remains after ten years: should we deploy SE? Indeed, these papers (including ours) tell us that some attacks can be effective. However, they do not tell us whether they are problematic in real-world use cases. Our idea is to provide an experimental protocol to decide whether a specific use case is secure or not. The literature already contained the intuition that the attack accuracy is use-case dependent. Hence, we provide a rigorous method to assess the risk.

This paper was tricky to write because it is unusual for the security community. Instead of theoretical guarantees/bounds, we propose to rely on statistical guarantees. We gathered positive feedback at ESSA, and I was super happy about it. The paper is still under review, so we are not there yet, but it is a good first sign. This idea has many implications (not only in SE), so I am looking forward to the feedback from the community.

If you want to take a look at my slides, you can find them here: {{< ref "presentations/essa3_sse_risk_assess.pdf" >}}.

# What's next in Searchable Encryption?

Since this event aims to shape the future of SE, I think it would be good to give my point of view on the question. I consider it time to implement real-world applications. MongoDB Queryable Encryption is a good first step but a general-purpose library. We need a concrete and **public** application to advertise the interest of SE. For example, implementing an encrypted search index for a popular messaging application (e.g., Matrix) would fulfill this goal. Such a project would require efforts from both the construction sub-community to provide a **scalable** and adequate scheme and the attack sub-community to quantify the risks **precisely**.

Currently, SE is somewhat of a side project for me, so I won't be proactive in that direction immediately. However, I would love to be part of such efforts if someone is interested in my takes on statistical risk assessment.
