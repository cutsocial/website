---
title:
layout: home
---

<section class="hero">
  <div class="hero-inner">
    <div class="hero-text">
      <h1>Behavioral experiments that run on the phones people already carry</h1>
      <p>Lens runs surveys, reaction-time tasks and live economic games in the browser, from one study file you can post on Prolific. Jamasp adds the sleep, heart-rate and activity data from participants' own Fitbits.</p>
      <p class="hero-actions">
        <a class="button button-primary" href="https://lens.cut.social/#/builder">Build a study</a>
        <a class="button button-quiet" href="{{ "/demo.html" | relative_url }}">Try the demos</a>
      </p>
    </div>
    <div class="hero-phones">
      <figure class="phone"><img src="{{ "/assets/img/home/lens-stroop.webp" | relative_url }}" width="260" height="504" alt="A Stroop trial in Lens: the word Green in green ink, with Red and Green answer buttons."></figure>
      <figure class="phone"><img src="{{ "/assets/img/home/lens-bart.webp" | relative_url }}" width="260" height="504" alt="The balloon risk task in Lens: an orange balloon, 63 points this round, and a button to cash them."></figure>
      <figure class="phone"><img src="{{ "/assets/img/home/lens-ultimatum.webp" | relative_url }}" width="260" height="504" alt="The ultimatum game in Lens: tokens being split between the participant and another player."></figure>
    </div>
  </div>
</section>

<section class="tool tool-lens">
  <div class="tool-text">
    <h2><a href="https://lens.cut.social/#/builder">Lens</a></h2>
    <p class="tool-status">In use since 2018. Version 2.0 came out in October 2026.</p>
    <p>A study is a list of pages: survey questions, Stroop, Go/No-Go, N-back, the balloon risk task, dictator and ultimatum games. Lens shows them in order, on a phone or a computer, in English, Persian or Arabic, and saves each participant's answers with the settings that produced them.</p>
    <p>New in 2.0: a study builder that shows each page as participants will see it, and two-player games where participants are paired as they arrive, with a computer partner if no one else does.</p>
    <p class="tool-links"><a href="https://lens.cut.social/#/builder">Open the study builder</a><a href="{{ "/demo.html" | relative_url }}">See every task</a><a href="https://github.com/cutsocial/lens">Code on GitHub</a></p>
  </div>
  <figure class="shot shot-wide">
    <img src="{{ "/assets/img/home/lens-builder.webp" | relative_url }}" width="1600" height="956" alt="The Lens study builder: a list of pages on the left, the settings of a Stroop page in the middle, and a live preview of the Stroop task on the right.">
    <figcaption>The study builder. Pick a page on the left, change it in the middle, and see it as participants will on the right.</figcaption>
  </figure>
</section>

<section class="tool tool-jamasp">
  <div class="tool-text">
    <h2><a href="https://jamasp.app">Jamasp</a></h2>
    <p class="tool-status">Piloted in 2025 with 41 participants over 65 days.</p>
    <p>Jamasp recruits people who already own a Fitbit through Prolific. Once they consent and link their device, it collects their sleep, heart-rate and activity data automatically, and researchers follow each study from a dashboard.</p>
    <p class="tool-links"><a href="https://jamasp.app">jamasp.app</a><a href="https://github.com/cutsocial/jamasp-public">Pilot code and data</a></p>
  </div>
  <figure class="shot">
    <img src="{{ "/assets/img/home/jamasp-dashboard.webp" | relative_url }}" width="1400" height="1088" alt="The Jamasp researcher dashboard: participants, wear time, resting heart rate, sleep and steps, with charts of heart rate and steps by hour of day.">
    <figcaption>A project's dashboard in Jamasp, with demo data.</figcaption>
  </figure>
</section>

<section class="tool tool-cut">
  <figure class="shot">
    <img src="{{ "/assets/img/home/cut-ultimatum.webp" | relative_url }}" width="1400" height="612" alt="Cut's ultimatum game: the participant and the other player each with a share of cupcakes, a scoreboard, and a Next Round button.">
    <figcaption>Cut's ultimatum game.</figcaption>
  </figure>
  <div class="tool-text">
    <h2><a href="{{ "/about.html" | relative_url }}">Cut</a></h2>
    <p class="tool-status">2014–2018, now retired.</p>
    <p>The original platform, built for live multiplayer ultimatum and dictator games, with computer partners and a study designer. Its games now run in Lens.</p>
    <p class="tool-links"><a href="{{ "/about.html" | relative_url }}">History</a></p>
  </div>
</section>

<section class="try">
  <h2>Try it</h2>
  <p>Each link opens a working demo. Change <code>/en</code> at the end of the address to <code>/fa</code> or <code>/ar</code> for Persian or Arabic.</p>
  <ul class="demo-list">
    <li><a href="https://lens.cut.social/#/demo-survey/en">Survey pages</a><span>Text, country, choice and slider questions</span></li>
    <li><a href="https://lens.cut.social/#/demo-stroop/en">Stroop</a><span>Name the ink color, not the word</span></li>
    <li><a href="https://lens.cut.social/#/demo-gonogo/en">Go/No-Go</a><span>Respond to consonants, hold back on vowels</span></li>
    <li><a href="https://lens.cut.social/#/demo-twochoice/en">Two-choice task</a><span>Same side for blue, opposite side for yellow</span></li>
    <li><a href="https://lens.cut.social/#/demo-nback/en">N-back</a><span>Is this letter the same as two letters ago?</span></li>
    <li><a href="https://lens.cut.social/#/demo-bart/en">Balloon risk task (BART)</a><span>Pump for points before the balloon pops</span></li>
    <li><a href="https://lens.cut.social/#/demo-dictator/en">Dictator game</a><span>Split tokens with another person</span></li>
    <li><a href="https://lens.cut.social/#/demo-ultimatum/en">Ultimatum game</a><span>Propose a split they can accept or reject</span></li>
    <li><a href="https://lens.cut.social/#/demo-multiplayer/en">Live two-player game</a><span>Open it in two windows, or wait 20 seconds for a computer partner</span></li>
    <li><a href="https://lens.cut.social/#/demo-lens2/en">Everything in one study</a><span>All the Lens 2 tasks and survey pages</span></li>
  </ul>
  <p class="try-classic">The original Lens designs (release <code>v1.0</code>) still run every earlier study unchanged:
  <a href="https://lens.cut.social/#/gonogo/en">2-alternative forced choice</a>,
  <a href="https://lens.cut.social/#/taskswitch/en">task switching</a>,
  <a href="https://lens.cut.social/#/simplified_taskswitch/en">simplified task switching</a>,
  and <a href="https://lens.cut.social/#/demo-comprehensive/en">every classic task in one study</a>.</p>
</section>
