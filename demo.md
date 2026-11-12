---
title: Demos
layout: test
---

<p class="demo-intro">Every demo here is a working Lens study. Pick a task to try it right here; each one opens in its own tab too, which is easier on a phone. Change <code>/en</code> at the end of a link to <code>/fa</code> or <code>/ar</code> to see Persian or Arabic, laid out right to left.</p>

<div class="demo-browser">

<nav class="demo-nav" aria-label="Demos">
  <a class="demo-nav-item" href="#survey">
    <img src="{{ '/assets/img/demo/survey-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Survey pages</strong><small>Text, country, choice and slider questions</small></span>
  </a>

  <p class="demo-nav-group">Reaction-time tasks</p>
  <a class="demo-nav-item" href="#stroop">
    <img src="{{ '/assets/img/demo/stroop-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Stroop</strong><small>Name the ink color, not the word</small></span>
  </a>
  <a class="demo-nav-item" href="#gonogo">
    <img src="{{ '/assets/img/demo/gonogo-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Go/No-Go</strong><small>Respond to some letters, hold back on others</small></span>
  </a>
  <a class="demo-nav-item" href="#twochoice">
    <img src="{{ '/assets/img/demo/twochoice-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Two-choice task</strong><small>Same side or opposite side, by color</small></span>
  </a>
  <a class="demo-nav-item" href="#nback">
    <img src="{{ '/assets/img/demo/nback-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>N-back</strong><small>Same as two letters ago?</small></span>
  </a>
  <a class="demo-nav-item" href="#bart">
    <img src="{{ '/assets/img/demo/bart-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>BART</strong><small>Pump the balloon, cash in before it pops</small></span>
  </a>

  <p class="demo-nav-group">Economic games</p>
  <a class="demo-nav-item" href="#dictator">
    <img src="{{ '/assets/img/demo/dictator-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Dictator game</strong><small>Split tokens by dragging them</small></span>
  </a>
  <a class="demo-nav-item" href="#ultimatum">
    <img src="{{ '/assets/img/demo/ultimatum-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Ultimatum game</strong><small>Propose a split; they accept or reject</small></span>
  </a>
  <a class="demo-nav-item" href="#dice">
    <img src="{{ '/assets/img/demo/dice-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Dice allocation</strong><small>Decide privately which die is yours</small></span>
  </a>
  <a class="demo-nav-item" href="#multiplayer">
    <img src="{{ '/assets/img/demo/multiplayer-thumb.webp' | relative_url }}" alt="" width="112" height="168">
    <span><strong>Live two-player ultimatum</strong><small>Paired with whoever arrives next</small></span>
  </a>

  <p class="demo-nav-group">More</p>
  <a class="demo-nav-item demo-nav-text" href="#old-designs">
    <span class="demo-nav-badge" aria-hidden="true">v1</span>
    <span><strong>Old designs</strong><small>Lens 1 tasks, still running</small></span>
  </a>
  <a class="demo-nav-item demo-nav-text" href="#how-a-study-is-written">
    <span class="demo-nav-badge" aria-hidden="true">{ }</span>
    <span><strong>How a study is written</strong><small>One JSON file per study</small></span>
  </a>
</nav>

<div class="demo-panels">

<section class="demo-panel" id="survey">
  <h2>Survey pages</h2>
  <p>Text, country, choice and slider questions. Missing answers are pointed out under the question, and horizontal choices stack on phones.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-survey/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-survey/en" title="Survey pages demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="stroop">
  <h2>Stroop</h2>
  <p>Stimulus onset and response times are recorded with the browser's high-resolution clock.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-stroop/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-stroop/en" title="Stroop demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="gonogo">
  <h2>Go/No-Go</h2>
  <p>With letters or icons. Stimulus onset and response times are recorded with the browser's high-resolution clock.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-gonogo/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-gonogo/en" title="Go/No-Go demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="twochoice">
  <h2>Two-choice task</h2>
  <p>2-alternative forced choice. A star appears on the left or right: blue means answer on the same side, yellow the opposite side.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-twochoice/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-twochoice/en" title="Two-choice task demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="nback">
  <h2>N-back</h2>
  <p>Respond when a letter matches the one two letters before it.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-nback/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-nback/en" title="N-back demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="bart">
  <h2>Balloon Analogue Risk Task (BART)</h2>
  <p>Each pump grows the balloon and the points for the round, until the participant cashes in or the balloon pops.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-bart/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-bart/en" title="BART demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="dictator">
  <h2>Dictator game</h2>
  <p>Participants split tokens by dragging them between the two sides.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-dictator/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-dictator/en" title="Dictator game demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="ultimatum">
  <h2>Ultimatum game</h2>
  <p>Against pre-recorded opponents. This one adds + and − buttons next to dragging, which helps on small screens.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-ultimatum/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-ultimatum/en" title="Ultimatum game demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="dice">
  <h2>Dice allocation</h2>
  <p>Each round there are two dice, a blue one and an orange one. Participants decide privately which is theirs and which is the other person's, roll both, then give each die to a person and get the points on theirs. The private choice isn't recorded, so self-serving choices show up only over many rounds: honest players keep the higher die about half the time. Based on a Cut prototype from 2018.</p>
  <p class="demo-actions"><a class="demo-open" href="https://lens.cut.social/#/demo-dice/en" target="_blank" rel="noopener">Open in a new tab</a></p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-dice/en" title="Dice allocation demo" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="multiplayer">
  <h2>Live two-player ultimatum game</h2>
  <p>Participants are paired as they arrive, first come, first served. If no one else arrives within the time the study sets, a computer partner plays instead, following one of Cut's original strategies. A debrief after the game says which it was.</p>
  <h3 class="demo-steps-title">Watch two people get matched</h3>
  <ol class="demo-steps">
    <li>Tap Start in the game below.</li>
    <li>Copy the link and open it in a private (incognito) window, another browser or your phone. Each one counts as a separate participant.</li>
    <li>Tap Start there too. The two find each other within seconds, and you play both sides.</li>
  </ol>
  <div class="demo-copy">
    <input type="text" readonly value="https://lens.cut.social/#/demo-multiplayer/en" aria-label="Link to the live game" onfocus="this.select()">
    <button type="button" class="demo-copy-button" data-copy="https://lens.cut.social/#/demo-multiplayer/en">Copy link</button>
  </div>
  <p class="demo-note">To meet the computer partner instead, tap Start below and wait about 20 seconds.</p>
  <div class="demo-container">
    <iframe src="https://lens.cut.social/#/demo-multiplayer/en" title="Live two-player ultimatum game" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
  </div>
</section>

<section class="demo-panel" id="old-designs">
  <h2>Old designs</h2>
  <p>Lens 1 (release <code>v1.0</code>) still runs every earlier study unchanged:</p>
  <ul>
    <li><a href="https://lens.cut.social/#/gonogo/en">2-alternative forced choice</a></li>
    <li><a href="https://lens.cut.social/#/taskswitch/en">Task switching</a></li>
    <li><a href="https://lens.cut.social/#/simplified_taskswitch/en">Simplified task switching</a></li>
    <li><a href="https://lens.cut.social/#/demo-comprehensive/en">Every classic task in one study</a>, adapted from the instrument we used to study the Ramadan fast (<a href="https://doi.org/10.1177/01461672211070385">Rad, Ansarinia &amp; Shafir, 2023</a>)</li>
  </ul>
</section>

<section class="demo-panel" id="how-a-study-is-written">
  <h2>How a study is written</h2>
  <p>A study is one JSON file: a list of pages, shown in order, each with its own settings. This one is a welcome page followed by ten balloons of BART:</p>
{% highlight json %}
{
  "studyId": "my-study",
  "redirectTo": "https://app.prolific.com/submissions/complete?cc=XXXX",
  "views": [
    { "id": "welcome", "type": "text2", "instruction": true,
      "text": "Welcome! This takes about 10 minutes." },
    { "id": "bart", "type": "bart2", "reward": 5, "maxPumps": 20,
      "safePumps": 1, "trials": 10 }
  ]
}
{% endhighlight %}
  <p>Once published, it runs at <code>https://lens.cut.social/#/my-study/en</code>. The responses come back the same way: one record per participant, with each page's settings next to the answers, so the data describes itself.</p>
  <p>You don't have to write the file by hand. The <a href="https://lens.cut.social/#/builder">study builder</a> gives every page a form, previews it as participants will see it, flags problems as you type, and keeps the text for each language in the study file. The <a href="https://github.com/cutsocial/lens#readme">Lens README</a> lists every page type and option.</p>
</section>

</div>
</div>

<script>
(function () {
  var root = document.querySelector('.demo-browser');
  if (!root) return;
  var panels = Array.prototype.slice.call(root.querySelectorAll('.demo-panel'));
  var links = Array.prototype.slice.call(root.querySelectorAll('.demo-nav-item'));
  // Old anchors from the single-page version of this page
  var aliases = { 'survey-pages': 'survey', 'reaction-time-tasks': 'stroop', 'economic-games': 'dictator' };

  function find(id) {
    id = aliases[id] || id;
    for (var i = 0; i < panels.length; i++) if (panels[i].id === id) return panels[i];
    return null;
  }

  // Scroll the menu itself (not the page) so the chosen item is in view
  var nav = root.querySelector('.demo-nav');
  function reveal(a) {
    if (nav.scrollWidth > nav.clientWidth) {
      var left = a.offsetLeft; // .demo-nav is positioned, so offsets are relative to it
      if (left < nav.scrollLeft || left + a.offsetWidth > nav.scrollLeft + nav.clientWidth) {
        nav.scrollLeft = left - (nav.clientWidth - a.offsetWidth) / 2;
      }
    } else if (nav.scrollHeight > nav.clientHeight) {
      var t = a.offsetTop;
      if (t < nav.scrollTop || t + a.offsetHeight > nav.scrollTop + nav.clientHeight) {
        nav.scrollTop = t - 12;
      }
    }
  }

  function show(id, fromClick) {
    var panel = find(id) || panels[0];
    panels.forEach(function (p) { p.hidden = p !== panel; });
    links.forEach(function (a) {
      var on = a.getAttribute('href') === '#' + panel.id;
      if (on) {
        a.setAttribute('aria-current', 'true');
        reveal(a);
      } else {
        a.removeAttribute('aria-current');
      }
    });
    if (fromClick) {
      if (window.matchMedia('(max-width: 860px)').matches) {
        // Phones: keep the row of thumbnails on screen, with the demo below it
        if (nav.getBoundingClientRect().top < 70) nav.scrollIntoView({ block: 'start' });
      } else if (root.getBoundingClientRect().top < 0) {
        panel.scrollIntoView({ block: 'start' });
      }
    }
  }

  root.classList.add('is-tabbed');
  links.forEach(function (a) {
    a.addEventListener('click', function (e) {
      e.preventDefault();
      var id = a.getAttribute('href').slice(1);
      if (history.replaceState) history.replaceState(null, '', '#' + id);
      show(id, true);
    });
  });
  window.addEventListener('hashchange', function () { show(location.hash.slice(1)); });

  // "Copy link" buttons
  Array.prototype.forEach.call(root.querySelectorAll('[data-copy]'), function (b) {
    b.addEventListener('click', function () {
      var text = b.getAttribute('data-copy');
      var done = function () {
        b.textContent = 'Copied';
        setTimeout(function () { b.textContent = 'Copy link'; }, 2000);
      };
      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText(text).then(done, function () { b.previousElementSibling.select(); });
      } else {
        b.previousElementSibling.select();
      }
    });
  });
  show(location.hash.slice(1));
})();
</script>
