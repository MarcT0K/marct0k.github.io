---
title: "CCS 2023, my first security conference"
date: 2023-12-06T13:26:42+01:00
tags: ["Conference", "Privacy", "Security"]
summary: "In November 2023, I attended my first security conference: CCS 2023. So, how was it?"
description: "In November 2023, I attended my first security conference: CCS 2023. So, how was it?"
cover:
  image: "/images/new_haven.jpg"
  alt: "Late afternoon photo of Nyhavn with all the christmas light"
  caption: "Credits: Marc DAMIE (CC-BY)"
  relative: false
showtoc: false
draft: false
---

As every few years, the ACM Conference on Computer and Communications Security (a.k.a. "CCS") was organized in Europe. This time, the city of Copenhagen had the ~~burden~~ privilege of greetings security experts from all over the world. For the occasion, the security group of the University of Twente organized a collective trip to CCS.

# The organization

## The trip

My trip was paid by Inria, so I had some freedom regarding transportation. Anyway, for environmental reasons, I decided to take the train. The rest of the group also took the train... but the University of Twente hadn't given them the choice. Hence, we went all together on a 9-hour train ride to Copenhagen with 2 connections. From my perspective, 9–10 hours seems the maximum train trip I would do to go to a conference. If the train travel time exceeds 10 hours, I think I would go by plane. Indeed, 10 hours already requires a full day to travel and it can get much longer if any of the trains is delayed. 

This observation raises many questions regarding how researchers should reduce their carbon footprint. In computer science, travels to attend conference represent a major part of carbon emissions. The choice of a conference location is then a key leverage to minimize carbon footprint. Unfortunately, most conferences happen in the US. Even if the US host a significant part of the scientific community, I believe this choice does not minimize the carbon footprint. Interestingly, some researchers calculated the carbon footprint of AI conference and estimated the same footprint if they had been organized somewhere else: http://arxiv.org/abs/2311.14692. Apparently, Central Europe or China are the best locations if we want to minimize carbon footprint. I hope security conference will take this into account in the future. However, I am also aware that this practice could limit the diversity of destinations. Anyway, most security conferences are only organized in the US, so this diversity argument sounds a bit weak right now.

## The venue

The trip was a bit long, but we finally arrived in Copenhagen and were able to enjoy the conference. The congress center seemed ideal for such an event: neither too big nor too small. It was located next to many hostels, so we could book affordable rooms easily. There was plenty of food, coffee, and tea to occupy the breaks. While I had rather low expectations for food, I must admit the quality was nice.

Overall, I want to **congratulate the organizers** and all the people who contributed to the organization. Everything went smoothly.

Even if the overall experience was great, I must talk publicly about one detail, so the Internet won't forget about it: the program interface. The program was available on the website and it has been one of the worst Web UI experiences I've ever had. I discussed it with other colleagues and there was a perfect common agreement. The navigation was so bad that someone implemented a pure HTML website, much easier to navigate! Anyway, this detail did not prevent me from enjoying the talks 🙃.

# Discovering the security research community

## My first security conference... but my second scientific conference 

Even though I already have two published papers, CCS was my first conference. Unfortunately, I published my first USENIX paper during the "COVID years", so the conference was remote. CCS was then my first broad contact with the security research community. My presence in this conference felt very naturally. One year ago, I had attended an ML conference and I felt totally overwhelmed by the conference and the scientific content. The conference size was similar, but I felt much more lost.

I don't know for sure why it felt so natural in CCS; but I may have a couple of ideas. First, I now have more experience. Over the last year, I attended multiple scientific events, especially in the security field. During CCS, I even talked to researchers I had met during these events! Hence, I am now more prepared for large conferences and their flow of presentations. Second, I consider myself a privacy researcher. My initial training is in ML, but I don't intend to make ML the center of my future research. In the context of my Ph.D., ML provides interesting problems to solve, but I hope my future career would have a larger scope. Therefore, the presentations I saw at CCS are much closer to my pure research interests than what I saw at ECML-PKDD.

## Some open debates

Besides the talks, the program was marked by two interesting events: the 30th anniversary and the "CCS business meeting." On the one hand, for the 30th anniversary, the first ever CCS chair presented a brief retrospective of CCS from the first edition with 25 attendees to the 1K attendees we have nowadays. This presentation was a great occasion to understand how top conferences started from nothing. After this presentation, there was a panel discussion to debate about various questions related to CCS such as diversity, reviewing process, and the future of the conference. The business meeting was a general assembly of ACM SIGSAC. The chair presented the current situation of SIGSAC and discussed the future directions. In both events, I appreciated the openness of the discussion. These events must be very common among scientific communities. However, this was a happy discovery for me. Scientific communities are rather obscure organizations; only researchers know about them. This hidden self-organization may lead to many issues, but this transparency seems to be the sign of a healthy organization.

One may argue that it is not perfectly open as only the people present in the room can take part in the discussion. Anyway, who would watch a livestream of a CCS business meeting? 😅

## Is it healthier than the ML community?

Finally, my previous post about ECML-PKDD was extremely critical of the ML conference. I do not redevelop everything here, but many issues are still shared. Presentations are not very accessible because they are overly specialized. The capitalistic interests are less obvious, but I believe they are also present (a bit developed in the next section). More generally, all scientific communities share many problems. However, I believe some aspects are better in the security community than in the ML community.

First, the ML community is getting enormous, which creates an unhealthy competition between researchers. Everyone is in the hurry of publishing papers because everyone fears that someone else will publish their idea first. The ML literature simply looks like an unstoppable flow of noisy information. There are always multiple concurrent works, so it is difficult to study a line of work. Up to now, the security community is still small enough so one can follow the latest discoveries. For example, everyday I read the ArXiv RSS feed of security papers. I can read **all the titles** and skim through the appendices. However, I cannot do the same for the ML RSS feed because there are too many papers posted every day. For ML papers, I need to type some keywords to filter the papers.

This size issue is also very visible in the reviewing process. The ML reviewing process seems rather random as they are so many papers to review. The program committee cannot enforce clear standards, as it is the case in security. Hence, I believe the security community is **for now** healthier.

# My regrets/hopes

My previous paragraphs put a positive light on security research. However, I still have some concerns/regrets/hopes. As mentioned before, the community seems healthy, but there are multiple improvements possible.

## A community fighting unnamed attackers

My main critic is regarding the security motivations. A thousand researchers spent a week talking about security weaknesses and attack defenses, but I've not heard the name of a potential attacker. We are a community spending hours defending against anonymous attackers. This observation is a clear symptom of the "apolitical" stand wanted by many researchers. I believe we should name the organizations behind the threats. Often, we hear about a vague "hacker". However, many recent large-scale attacks have been orchestrated by national security agencies from China, Russia, the US, or anywhere else in the world (even the European Union).

While state agencies seem to be an essential adversary for system or network security, Big Tech companies are the main threat for privacy researchers. However, privacy researchers rarely name Google, Microsoft, or TikTok as a privacy threat. Many research directions even try to make these systems "privacy-preserving"... even though they are profitable thanks to personal data exchanges. Hence, these privacy research lines clearly have some "hidden" capitalistic interests. I would appreciate more open and political discussions about the alternatives.

More generally, I would like to see more researchers talking concretely about the threats. Cybersecurity is considered a strategic sector in all modern democracies. It feels a bit nonsensical to act as if our research is purely apolitical. Obviously, it may lead to conflict as attendees are funded by different countries, with possibly orthogonal political interests. It could be the occasion to finally think about our contradictions as a community;e.g., accepting money from Big Tech companies in privacy/security conferences while they don't comply with privacy laws. Within western societies, the average citizen's trust in science is decreasing. I believe these contradictions contribute to some mistrust.

To sum up, cybersecurity and privacy are two highly political issues. Security conferences should have open debates (e.g., via targeted keynotes) to understand the shortcomings of our research. The goal is not to create conflict for conflict. My goal is to take a step back and understand whether some lines of work fail at solving the real-world security and privacy issues.

## The need for alternative publication formats

My second concern is the publication venues. As many computer science sub-field, computer security researchers essentially publish in conference. This habit leads to weird situations where researchers may like to present remotely in conferences. The motivations for these remote presentations are diverse: from visa issues to a lack of time/interest. In any case, the absence of alternative to security conferences for good research papers is an issue. Some fields such as ML have multiple high-quality journals. Security research should also have high-quality journals, so we have a choice between journal and conferences depending on our personal constraints.

During CCS 30th anniversary, all the panel agreed that TOPS was now an excellent place to publish security papers. This common agreement is great news, but we may need a couple of other journals. Moreover, as a community, we should also pay more attention to these journal papers, so they become as visible as conference papers. 

## Scalability of the reviewing process

Finally, the 30th anniversary panel discussion was also the occasion to sketch the future of CCS. According to the chairs' estimation, the conference size should double within a few years. Everything would be doubled: number of attendees, numbers of submissions, number of papers. The panel tried to be reassuring about our capacity (as a community) to scale. ML was taken as an example as they manage to scale. However, I believe the panel participants were too optimistic. Everyone in ML complains about the quality of the review process. Hence, the security community should soon learn from the issues identified in the ML community before the community gets too large. Even if I have no certainty, I feel like changing significantly the reviewing process would become particularly slow once the community is much larger. Unfornately, I am still a young Ph.D. student so I won't be able to have any significant roles in the upcoming changes. I simply hope the community manages to scale while maintaining the same quality standard.

# Conclusion

This is end of this new episode of my conference diary. This post was a bit messy. My goal was simply to present my first thoughts about the conference and the community. Despite my few concerns, I appreciated the conference. This event helped me make a first step into the security community. Moreover, I believe my criticism is an essential part of my early research career. These PhD years are an ideal moment to understand how the scientific world works and what could be my place there. I try also to see these concerns in a more positive way: my future contribution within our community could be to fix these elements I perceive as issues.

**Anyway, CCS was a great experience and I hope I will soon have a paper published there to meet the community again.**
