---
layout: work
type: Lab
num: 6
worktitle: Sentiment Analysis
---

### Sentiment Analysis

Analyze your selected poem using AFINN.
Discuss which words have the largest effect on your overall
sentiment score for the document.

### Plot over time

Analyze each sentence of your selected book using AFINN.
Use the `moving_average` function to visualize the sentiment over time.
You will need to find a good window size for
the length of your text; too small and it is jittery noise, too large, and you only
get a few data points.

[Annotate your graph](https://matplotlib.org/3.1.3/tutorials/text/annotations.html#plotting-guide-annotation) where there are critical passages or plot points. Do your chosen annotations line up with the sentiment
found by AFINN? Why or why not?

### Movie Reviews

Download the [movieReviews.txt](../data/movieReviews.txt) file. This file has
8529 sentences from reviews, labeled with scores of 0 - 4, with 0 being very negative and
4 being very positive.

Use VADER to determine the sentiment of these reviews. What are the reviews
with the highest sentiment scores? What are the reviews with
the lowest sentiment scores?

Compare our sentiment scores with the labels provided. Find three reviews
where the VADER calculated scores disagree with the labels. Do you agree with VADER or
with the label? If you agree with the label, discuss why VADER might have made
a mistake, using the [details of the VADER algorithm](http://comp.social.gatech.edu/papers/icwsm14.vader.hutto.pdf).

## What to Hand In

Turn in your .ipynb file to the Lab 6 directory on Moodle.
