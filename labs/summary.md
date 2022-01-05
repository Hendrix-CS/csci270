---
layout: work
type: Lab
num: 2
worktitle: Summary Statistics
---

## Description

Our first attempt to summarize our documents is to calculate and
visualize statistical information. Use a Kaggle Notebook to track your
analysis of your data. Write the answers for each section inline with
Markdown blocks, and section your document with Header blocks. Be sure
to cite any outside sources you use for Python reminders and snippets of
code.

{% include important.html content="Repeat the following steps for both your poem and book documents." %}

### General Statistics

Open the file and load the text into memory. Calculate the following
statistics:

-   How many total characters?
-   How many letters?
-   How many sentences?
-   How many tokens?
-   How many word types? (unique tokens)

Your tokens should not include any punctuation, only alphanumeric
characters. Based on your own intuitions and examination of your documents,
devise and implement a definition of a sentence.

### Frequency Counts

Find the frequency counts for the letters in your document. Create a
barplot to display this data, with the tick marks labeled with the
appropriate letter.

Find the frequency counts for the lengths of tokens in your document.
Create a barplot to display this data.

Find the frequency counts for the numbers of tokens in the sentences in your document.
Create a barplot to display this data.

Compare and contrast these graphs.

### Reading Level

Write a function to calculate the Flesch-Kincaid Grade Level Formula:

[![](https://readable.io/images/content/4_fkgl.png)](%20https://readable.io/content/the-flesch-reading-ease-and-flesch-kincaid-grade-level/)

Assess the reading level of your document using your function. Use the
**number of vowels** in your document as a substitute for the total
number of syllables.

Does this match your assumptions?

### Zipf's Law

Find the frequency counts for the tokens in your document. Rank the
tokens in descending order based on their counts.

Create a log-log plot where the x-axis is the rank of the token, and the
y axis is the frequency count for that token.

Add to your plot a line graph of Zipf's law, where the y value is the
frequency count of the top ranked token divided by the x value.

Discuss how closely your document follows Zipf's law.

Calculate the frequency of each of these frequency counts. What percent
of your tokens are only found in the document once? These are known as
*[hapax legomena](https://en.wikipedia.org/wiki/Hapax_legomenon)* which
means "read only once." When translating texts, these tokens are
difficult to process because they lack repeated statistical context
clues for their meaning.

## What to Hand In

Share your Kaggle notebook with me by the deadline.
