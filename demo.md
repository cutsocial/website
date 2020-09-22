---
title: Demo
layout: page
---

### Balloon Analogue Risk Task (BART)

BART is a measure of risk-taking developed by Lejuez et al. ([2002](https://pubmed.ncbi.nlm.nih.gov/12075692/)). A ball or a balloon is shown to the subjects. Each time they tap on it, the ball gets pumped and becomes a little bigger. And with each pump, subjects receive a certain number of points. However, if the ball explodes, they lose their points in that round. They can choose to cash out their points and save them before the ball explodes. In the end, the acumulated points are converted to real-life values and paid to the subjects.

The task is administered in multiple rounds (N). The probability of balloon exploding is determined using an array of N numbers in random order. With each pump, a number is selected from this array without replacement. If that number is equal to a 1, the balloon explodes. Since the number selected is not replaced, with each pump, the probability of the ball exploding increases. Specifically, the probability that the ball explode in the first round is 1/N. If it doesn't explode, in the second round that probability increases to 1/(N-1). This goes on until the last round where the probability of balloon exploding is 1/1 or 100%.

BART has an intuitive setup; it resembles real-life expereince of blowing up a balloon. It has high test-retest reliability, and predicts real-life outcomes. In the words of White et al., [2008](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4244869/):

> Risk behavior on the BART correlates with real-world risk behavior such as alcohol use, cigarette and drug use, gambling, stealing, unsafe sex ([Lejuez et al., 2002](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4244869/#R25); [2003a](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4244869/#R23),b), and trait measures of risk-taking propensity (e.g. sensation seeking and trait impulsivity, [Lejuez et al., 2002](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4244869/#R25); trait psychopathy, [Hunt et al., 2005](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4244869/#R19)).

  
A major advantage of the task is that it doesn't not require probability calculation or gambling, both of which are good methods of measuring risk-taking. But they require  some familiairty with the concepts that are limited to the particular age groups and samples. This makes BART more sutiable for cross-cultural research.


The code snippet needed to set the options of the task on Cut are shown next to it. The experimenter can set the number of rounds and the maximum number of pumps (i.e., in how many pumps the balloon has to explode).

<div class="demo-container">
  <iframe src="https://lens.cut.social/#/bart/en" frameborder="0" allowfullscreen=""></iframe>
</div>

    "views": [
	    {
		    "id": "bart",
		    "type": "bart",
		    "reward": 10,
		    "maxPumps": 20,
		    "safePumps": 1,
		    "trials": 25
		}
	]

