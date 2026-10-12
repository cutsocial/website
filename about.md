---
title: About
date: 2018-09-25 08:37:54 +0000
layout: test
---
# Why Cut

Cut was created to take advantage of people's growing presence online and the use of web technologies in behavioral and social science research. Broadly, I aimed for two things:

* **Usability**: Make it easy to use engaging, sophisticated research instruments in studies, beyond simple multiple-choice questions and scales. Some tools built by psychologists are too narrow in their use. Others are so general that they take extensive effort to learn. A balance between these two poles was needed.

* **Adaptability**: Run these instruments on any device. People today use their phones more than their computers for most things outside work. Phones also reach a much larger population, in arguably more ecologically valid settings, at much lower cost. No one studying modern humans can ignore mobile devices.

Both aims still guide the work. A third has been added since: lining up what people do in a study with how they live, by joining task data with the sleep, heart-rate and activity data their own wearables already record.

## History

**Cut, 2014–2018.** The first version had live multiplayer ultimatum and dictator games over WebSockets, computer opponents, game and study-flow designers, MTurk management, and several languages. A second version (around 2018) moved study design into a JSON editor. Both are retired.

**Lens, 2018–present.** Lens kept Cut's idea of describing a whole study in one JSON file and made it run well on phones. It has collected data for published research, including a series of studies on the Ramadan fast. [Lens 2.0](https://github.com/cutsocial/lens/releases/tag/v2.0) (October 2026) adds a study builder and a refreshed design for the tasks, and brings back Cut's live two-player games: real-time pairing, Cut's original computer strategies, a debrief that tells participants whether they played a person or a computer, and a full record of every move.

**Jamasp, 2021–present.** Jamasp recruits people who already own a Fitbit, through Prolific, and retrieves their wearable data automatically after they consent and link their device. A pilot ran with 41 participants over 65 days in 2025; its [code and aggregate data](https://github.com/cutsocial/jamasp-public) are public.

## People

- [Mostafa Salari Rad](https://salarirad.github.io/), The New School for Social Research: idea and design of Cut, Lens and Jamasp
- Morteza Ansarinia: development of Cut and the original Lens
- [Arman Radmanesh](https://armanradmanesh.com): Jamasp, and later work on Lens

## Support and research

Development was funded by The New School and the Association for Psychological Science (APS).

Research using these tools:

- Rad, M. S. (2025). Self-deprivation and cognition in Ramadan: Could fasting practice improve inhibitory control? *Religion, Brain & Behavior*, 1–26. [doi:10.1080/2153599X.2025.2487277](https://doi.org/10.1080/2153599X.2025.2487277)
- Rad, M. S., Ansarinia, M., & Shafir, E. (2023). Temporary self-deprivation can impair cognitive control: Evidence from the Ramadan fast. *Personality and Social Psychology Bulletin*, 49(3), 415–428. [doi:10.1177/01461672211070385](https://doi.org/10.1177/01461672211070385)

## Using Lens

Lens's code is public. Build a study in the [study builder](https://lens.cut.social/#/builder), try the [demos]({{ "/demo.html" | relative_url }}), or read the [documentation and code on GitHub](https://github.com/cutsocial/lens). If you use it in your research, cite the [release](https://github.com/cutsocial/lens/releases) your data came from.

I would love to hear your feedback.
