---
layout: work
type: Lab
num: 10
worktitle: Analyzing Songs
---


## Overview

Throughout this semester, we have been analyzing works of art in terms of **sentiment**
and **similarity**. In this lab, you will apply what you have learned in order to analyze
vocal music.

## Assignment

* Create a Kaggle notebook and share it with me.
* In that notebook, add the 
[Vocal Music](https://www.kaggle.com/datasets/gabrielferrer/vocal-music-hendrix-csci-270-spring-2024) and
[Vocal Music Lyrics](https://www.kaggle.com/datasets/gabrielferrer/vocal-music-lyrics-hendrix-csci-270-spring-2024)
data sets.
* Review Labs 2, 3, 4, 5, 8, and 9, paying careful attention to the criteria therein
for sentiment and similarity.
* Write up a couple of paragraphs in your notebook summarizing your insights with regards
to sentiment and similarity in those labs.
* For **Level 1 credit**, develop a sentiment analyzer for vocal music. It can be as simple as a numerical rating
for positive and negative sentiment, or it can be more complex, yielding a variety
of different sentiments. 
  * It should employ both text-based and music-based sentiment analysis.
  * Assess all of the vocal music entries using your analyzer.
  * Write a brief response to its evaluation of each song.
  * Feel free to modify your analyzer until you find it to be satisfactory.
* For **Level 2 credit**, develop a similarity metric for vocal music.
  * It should employ both text-based and music-based similarity analysis.
  * Create a dendrogram showing the similarity relationships for the entire corpus.
  * Feel free to modify your metric until you find it to be satisfactory.
* Assess the similarity metric as follows:
  * For each song, are its nearest neighbors subjectively similar to it? Why or why not? 
    What aspects of your metric correspond well (or less well) to your subjective impressions?
* Import whatever libraries you need. You may use any Python library you want. If it
  is a library we haven't previously used in the course, briefly describe it.
* Write a detailed description of the designs of your analyzers. Focus on the rationale
  of every design decision you make. Assess how well they correlate to your human
  intuitions about sentiment and similarity.
* For **Level 3 credit**, find another student in the class who has completed Level 1 and
  Level 2. Compare and contrast your approaches to similarity and sentiment analysis.
  Write a reflective paragraph where you assess what the other student did in comparison
  with your approach, discussing their relative advantages and disadvantages.
