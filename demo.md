---
title: Demos
layout: test
---

Every demo below is a working Lens study. Each one opens in its own tab too, which is easier on a phone. Change `/en` at the end of a link to `/fa` or `/ar` to see Persian or Arabic, laid out right to left.

## Survey pages

Text, country, choice and slider questions. Missing answers are pointed out under the question, and horizontal choices stack on phones. [Open in a new tab](https://lens.cut.social/#/demo-survey/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-survey/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

## Reaction-time tasks

Stimulus onset and response times are recorded with the browser's high-resolution clock.

**Stroop.** [Open in a new tab](https://lens.cut.social/#/demo-stroop/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-stroop/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

**Go/No-Go**, with letters or icons. [Open in a new tab](https://lens.cut.social/#/demo-gonogo/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-gonogo/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

**N-back.** [Open in a new tab](https://lens.cut.social/#/demo-nback/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-nback/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

**Balloon Analogue Risk Task (BART).** [Open in a new tab](https://lens.cut.social/#/demo-bart/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-bart/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

## Economic games

**Dictator game.** Participants split tokens by dragging them between the two sides. [Open in a new tab](https://lens.cut.social/#/demo-dictator/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-dictator/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

**Ultimatum game**, against pre-recorded opponents. This one adds + and − buttons next to dragging, which helps on small screens. [Open in a new tab](https://lens.cut.social/#/demo-ultimatum/en)

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/demo-ultimatum/en" loading="lazy" frameborder="0" allowfullscreen=""></iframe>
</div>

**Live two-player ultimatum game.** Participants are paired as they arrive, first come, first served. If no one else arrives within the time the study sets, a computer partner plays instead, following one of Cut's original strategies. A debrief after the game says which it was. To play both sides yourself, [open the game](https://lens.cut.social/#/demo-multiplayer/en) in two windows; to meet the computer partner, open it once and wait about 20 seconds.

## Old designs

Lens 1 (release `v1.0`) still runs every earlier study unchanged:
[2-alternative forced choice](https://lens.cut.social/#/gonogo/en),
[task switching](https://lens.cut.social/#/taskswitch/en),
[simplified task switching](https://lens.cut.social/#/simplified_taskswitch/en),
and [every classic task in one study](https://lens.cut.social/#/demo-comprehensive/en), adapted from the instrument we used to study the Ramadan fast ([Rad, Ansarinia & Shafir, 2023](https://doi.org/10.1177/01461672211070385)).

## How a study is written

A study is one JSON file: a list of pages, shown in order, each with its own settings. This one is a welcome page followed by ten balloons of BART:

```json
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
```

Once published, it runs at `https://lens.cut.social/#/my-study/en`. The responses come back the same way: one record per participant, with each page's settings next to the answers, so the data describes itself.

You don't have to write the file by hand. The [study builder](https://lens.cut.social/#/builder) gives every page a form, previews it as participants will see it, flags problems as you type, and keeps the text for each language in the study file. The [Lens README](https://github.com/cutsocial/lens#readme) lists every page type and option.
