---
title: "ECML-PKDD, my first ML conference: between discovery and disillusions"
date: 2022-10-18T15:19:20+01:00
category: ["Conference"]
summary: I attended my first conference in person and wanted to share the perspective of a young doctoral student full of ideals on scientific work.
description: I attended my first conference in person and wanted to share the perspective of a young doctoral student full of ideals on scientific work.
cover:
  image: "/images/ecml_pkdd.jpg"
  alt: "ECML-PKDD 2022 image"
  caption:
  relative: false
showtoc: false
draft: false
---

Since this post contains some criticism, a preliminary disclaimer is necessary. The conference was well organized, and I congratulate the chairs for this great event. Social events, food, venue, etc. everything was great. My criticism will be more on what is nowadays considered as good scientific work in the ML community. This criticism is obviously not limited to ML. I attended an ML conference, so I limit my discussion to the ML community even if I suppose that similar observations can be made in other communities. Hence, the concerns exposed in this post are not specific to ECML-PKDD or its organization. Moreover, I do not want to seem rude or smug, the goal of this post is simply to share the first (positive and negative) impressions of a naive and young PhD student at an ML conference. See this post more as the first page of my research life diary rather than as a structured criticism of the scientific practices.

# Discovering a scientific conference with fresh eyes 🤓

ECML-PKDD 2022 was my first in-person conference. I didn't know what to expect. Some of my colleagues told me about conferences they went to such as ICML, but I knew ECML-PKDD was smaller. Anyway, it was hard to picture exactly how it would feel to be in a scientific conference. At first, I was a bit amazed by the fact that such big scientific event can happen while the general public totally ignore their existence.

## Specialized conference but already so many unknown topics

As a PhD student, I was overwhelmed by the program. So many topics, so many papers, and among them, very few that I can fully understand. It was a humbling experience to see how narrow my knowledge is. I used this as an opportunity to get first intuitions about many unknown concepts. When I started my research work, I always wanted to have a perfect understanding of everything I read. I spent days on some articles just to grasp all the details. With this kind of events, I learn to look for general insights and leave the details for later. Considering how rich scientific literature is, I cannot afford the price of exhaustiveness.

For example, I don't work on concept drift in ML (concept drift defines a change in the distribution between the training data and real-world data). When I am listening to a talk about concept drift, I don't even want the details because I already ignore the state of the art. I except from the speaker to explain why this paper changed the landscape of concept drift but not precisely how. What I want is a sort of before/after photo like for a hair cut but for a scientific object. I want to understand why this new hair cut (state of the art in the case of scientific objects) is different and avoid as much as possible all the hair cutting process. Maybe someday, I'll work on concept drift and having concise conclusions I can remember is key so I have a starting point when this day happens. I should keep the detail discovery for the day I actually need them… because I'll forget them anyway.
Finally, these expectations are also inline with the time left to the presenters. A presenter should not even try to give details in a 10-minute presentation. Any attempt would result in a snorkel-like exercise where the speaker don't breathe during 10 minutes to spare no detail.

## Poster session are kinda cool

Before coming to ECML-PKDD, I was not convinced by the poster format. I felt like it was an old habit that researchers maintained as a tradition. I couldn't imagine how wrong I was. Poster sessions are better than anything else to discuss with other researchers. It is way better than slides to encourage interactions. Moreover, it forces the presenter to adapt the presentation to her audience. You can't have an already written text that you read (as some speakers do with Powerpoint). The presentation seems more authentic, and I feel more comfortable asking stupid questions. Indeed, in front of a crowd, you always have an expert asking a super precise and intelligent question. I cannot take the mic after this person and ask a basic and possibly stupid question.

## Brilliant researchers are way too normal

Finally, ECML-PKDD was an occasion to see some brilliant researchers such as Francis Bach or Yann Le Cun. I studied in a small French university, so I had less opportunities than other (Parisian) students to meet researchers of such world renown. I was a bit disappointed by how normal they seemed. I was expecting quirkier researchers. In the past, I read some stories about the mathematician Norbert Wiener and I wanted to meet such unique personalities. There are two solutions to this enigma: either researchers act normal in public to avoid having funny stories published about them by their peers, or ML has become so mainstream that we lost all sense of quirkiness in the process :clown_face:.

# Disillusions 😢

Now, it is the tough part for me and possibly, the juicy part for you: it is time for some criticism.
I encountered three main issues: over-specialization, (capitalistic) motivations of the papers, *publish or perish*.

## Over-specialization 🔬

This first issue is related to my expectations for the presentations. Paper are more and more specialized and some of them can barely be understood by researchers which are not expert in the studied sub-field. I had a similar remark on my first paper but the problem became so real when I attended ECML-PKDD. I saw presentations of ML papers from which I cannot draw any conclusion because I was unable to understand anything. It can then be a beginner mistake.

I believe this is a more general issue. An ML conference is already a specialized conference and any participant should be able to understand (at least partially) most presentations. It is clearly not the case and it reminded me a conversation I had during a summer school. Last August, I was in Saarbrucken for a summer school on sustainable AI and I met a PhD student in philosophy who asked the ML PhD students something like: "But you cannot even understand each other research right?" (she said that, in Philosophy, any peer is usually able to give feedback). We kinda answered that it is not totally true. I don't expect any CS student to understand what we do, but having any ML researcher would already be a good first goal.

I am myself working at the edge of several CS fields: security, cryptography, and ML. Now that I am advancing in my PhD, I saw that many researchers just look at what is published in their sub-community at the risk of reinventing the wheel. Over-specialization is a problem because it makes the conference participation less interesting than what it could be; but it is also a problem for scientific production!

I am probably judging researchers a bit too quickly there. Having a fixed community is also convenient for collaboration and publication but I still want to emphasize this impression I got.

## Capitalistic motivations of the papers 💶

I want to start this paragraph by a simple statement: *everything is political, including scientific work*. I am one of those researchers who find irritating the claim of "apolitical work". I don't have time (and qualifications) to detail this topic, but I suggest [1] by L. Wiener which is a great starting point for this kind of discussions.

Many papers had motivations that I find quite worrying. In the conference, you can hear all the buzzwords promoted by industry. Usually, these papers improve an industrial use case. This is not fundamentally bad but it represents a large part of the conference. We have very few papers promoting applications with societal impact. The only impact I foresee for these papers is even more Big Tech companies, more monopolies, etc. For example, several talks on recommender systems explained how to improve Amazon-like recommendation systems. We live in a world where recommender systems are unfair, where recommender systems create filter bubbles and may promote extremist ideas… but the motivation is to improve by 1% Amazon recommendation so they can sell us more shitty items that we don't need.

This point of view might seem a bit harsh, but I am a young student who will have to deal with many crises in the future: climate, increase of far-right influence, etc. What I observe is some research (made with public money) to contribute to private interest while there are plenty of challenges to overcome nowadays.
I believe we should be more careful at our expectations in terms of motivations. These papers are usually applied papers where poor motivations induce poor quality, whatever the improvements is "shown" in the figures.

Recently, I read [2] by Rogaway which detailed such criticism for the cryptography community. Rogaway highlights the role of cryptographers and questions the interests of the current research works. He even identified when a split happened in the crypto community: when the cryptographers started doing *cryptography for cryptography* instead of *cryptography for the people*. I think a similar discussion is necessary among AI researchers. We need to define the exact role of ML research in our societies. Yann Le Cun gave a first answer to this question during his keynote: he promoted autonomous intelligence (via self-supervised learning). This idea seems very similar to what the founders of AI imagined. However, I can also criticize this vision and ask whether it truly fits the current challenges of our societies? Some researchers (such as Romain Couillet [3]) are developing a discourse about frugal AI and even question whether a sustainable AI can even exist considering the carbon footprint of the modern ML models. Finally, there is also the issue of developing AI for the people. Currently, most AI models are only used by big companies to increase profit. Then, I want to add another question: can we use AI to *truly* improve the average human being daily life?

## Publish or perish: motivations of the researchers 💀

Now, that I talked about motivations of the papers, I should talk about motivations of the researchers. I am not discovering the *publish or perish* concept (i.e., the pressure to publish more and more publish to succeed in academic careers). However, I discovered how researchers behave according to it. Usually, all researchers discussing this concept agree that it is a problem. But, in this conference, it became more obvious that many of them fully accepted it. I can give a concrete example: during a poster session, I discussed with a PhD student that presented vaguely his work without any conviction. At the end of our discussion, he even said that he published it because you are excepted to have at least three papers by the end of your PhD. I was astonished by his sentence. I am sure that this attitude is shared by many researchers who don't dare saying it as explicitly as this student.

I had the same feeling during a Scientific Writing class where I was part of the minority defending that the first motivation when submitting a paper must always be "having results to share with the scientific community". Professional success can be only be a positive side effect. To justify that, I tried an analogy with surgery. A surgeon must undergo a surgery if and only if it is necessary to the patient. The fact that the surgery may bring money or success to the surgeon should never be a motivation… at least that's what I expect from my surgeon.

I understand that many of us would appreciate a position in academia. However, I don't think we should develop an unhealthy attitude to achieve our personal goal. These research are funded with public money and, even if the media give little attention to Science, we should be careful in being exemplary. Our profession is still highly respected and we must maintain this trust. Moreover, we are all researchers in ML, and we cannot argue that we absolutely need a job in academia to live. One can make good money in industry with an ML degree. I acknowledge that academic researcher can be a dream job, but we should not support a toxic system to reach this goal.

# Conclusion: what about me?

After all this criticism, you may want to confront me and ask whether I am such a perfect scientist producing excellent scientific work with pure motivations. First, I am literally nobody in the scientific community. I have two published papers, and I am early enough in my PhD not to worry about actions I should take to preserve my academic career. I have no authority, and I totally accept that one may consider all my thoughts are rubbish from a young student who doesn't understand the scientific world.  However, my thoughts might be interesting because they confront the current scientific practices with the naive and ideal expectations of a PhD student.  

Undoubtedly, I will publish over-specialized papers (and already did!), I'll have papers with purely capitalistic motivations, etc. **However, I'll also try to have scientific practices that converge as much as possible towards the ideals I had in me on September 19, 2022, when I arrived in ECML-PKDD.**

# References 📚

1. Winner, L. (2017). Do artifacts have politics?. In Computer Ethics (pp. 177-192). Routledge.
2. Rogaway, P. (2015). The moral character of cryptographic work. Cryptology ePrint Archive.
3. Couillet, R. et al. (2022). L’intelligence artificielle peut-elle devenir un outil convivial? [Preprint](http://polaris.imag.fr/romain.couillet/docs/articles/IAconviviale_v2.pdf). In French only.
