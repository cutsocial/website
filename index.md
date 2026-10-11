---
title:
layout: home
---

<p class="lede">Open tools for running behavioral studies online: surveys, reaction-time tasks and live economic games in the browser, and wearable data from people who already own a device.</p>

<div class="projects">

  <div class="project">
    <p class="project-status">Live · Lens 2.0, October 2026</p>
    <h2><a href="https://lens.cut.social/#/builder">Lens</a></h2>
    <p>Runs a whole study (survey pages, Stroop, Go/No-Go, N-back, BART, ultimatum and dictator games) from one JSON file, at a link you can post on Prolific. New in 2.0: a study builder with live preview, and two-player games where participants are paired in real time, with a computer partner if no one else arrives.</p>
    <p>Works on phones and computers, in English, Persian and Arabic.</p>
    <p class="project-links"><a href="https://lens.cut.social/#/builder">Study builder</a> · <a href="{{ "/demo.html" | relative_url }}">Demos</a> · <a href="https://github.com/cutsocial/lens">Code</a></p>
  </div>

  <div class="project">
    <p class="project-status">Live · piloted 2025</p>
    <h2><a href="https://jamasp.app">Jamasp</a></h2>
    <p>Recruits people who already own a Fitbit through Prolific, links their device with their consent, and retrieves sleep, heart-rate and activity data automatically. Researchers follow each study from a dashboard.</p>
    <p>Piloted with 41 participants over 65 days.</p>
    <p class="project-links"><a href="https://jamasp.app">jamasp.app</a> · <a href="https://github.com/cutsocial/jamasp-public">Pilot code and data</a></p>
  </div>

  <div class="project">
    <p class="project-status">Retired · 2014–2018</p>
    <h2><a href="{{ "/about.html" | relative_url }}">Cut</a></h2>
    <p>The original platform, built for live multiplayer ultimatum and dictator games, with computer partners and a study designer. Its games now run in Lens.</p>
    <p class="project-links"><a href="{{ "/about.html" | relative_url }}">History</a></p>
  </div>

</div>

## Try it

Each link opens a working demo. Change `/en` at the end to `/fa` or `/ar` for Persian or Arabic.

- [Survey pages](https://lens.cut.social/#/demo-survey/en)
- [Stroop](https://lens.cut.social/#/demo-stroop/en), [Go/No-Go](https://lens.cut.social/#/demo-gonogo/en), [N-back](https://lens.cut.social/#/demo-nback/en), [BART](https://lens.cut.social/#/demo-bart/en)
- [Dictator game](https://lens.cut.social/#/demo-dictator/en), [ultimatum game](https://lens.cut.social/#/demo-ultimatum/en)
- [Live two-player ultimatum game](https://lens.cut.social/#/demo-multiplayer/en): open it in two windows to play yourself, or wait 20 seconds for a computer partner
- [Every Lens 2 task in one study](https://lens.cut.social/#/demo-lens2/en)

The original Lens designs (release `v1.0`) still run every earlier study unchanged, and some tasks exist only there:
[2-alternative forced choice](https://lens.cut.social/#/gonogo/en),
[task switching](https://lens.cut.social/#/taskswitch/en),
[simplified task switching](https://lens.cut.social/#/simplified_taskswitch/en),
and [every classic task in one study](https://lens.cut.social/#/demo-comprehensive/en).

More on the [demos page]({{ "/demo.html" | relative_url }}).
