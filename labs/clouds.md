---
layout: work
type: Lab
num: 3
worktitle: Clouds and Drawings
---

# Overview

Besides bar graphs and scatter plots, there have been many alternate creative methods
for visualizing the statistical properties of a document. There is also a certain
creativity to the display of text through the individual glyph descriptions of
a font. In this lab, we'll explore two visualization techniques and explore the
process of creating a font.

### Creating a Font

Follow the instructions at [Calligraphr](https://www.calligraphr.com/en/docs/tutorial1/)
about how to create a free font using their software. The font you create can be your
own handwriting, or any other artistic interpretation of the standard English
and numerical characters.

In step 8 of the tutorial, you should inspect your font and select on individual
characters to edit and standardize your font. Try to make sure the bottom of the characters
is at the [baseline](https://en.wikipedia.org/wiki/Baseline_(typography)), the
top of the capital letters is near the [cap height](https://en.wikipedia.org/wiki/Cap_height),
and the lower case letters are near the [x-height](https://en.wikipedia.org/wiki/X-height) line.

Write a description of your font, discussing it in terms of the common
[typeface categories](https://en.wikipedia.org/wiki/Typeface)
of Serif, Sans-Serif, Script, Monospaced, and Display. If your font does not follow
the standard above about the baseline, x-height, and cap-height, justify your creative choices.

Install this font on your computer, and use a Word Processing software to
format your Poem in this font. (Google Docs cannot import new fonts.)
Export a PDF of this document for submission.

### Word Clouds

Use the code discussed in class to create a Word Cloud for your
Book, using the font you created above.

To get this to work, you will most likely have to [delete and reset the
font cache](https://scentellegher.github.io/visualization/2018/05/02/custom-fonts-matplotlib.html) from `matplotlib`.
This took me a while to get right, please stop by for help when you need it.

Use the `english2.txt` word list to change the color of the words in
the cloud, where words that are not found in English are shown in
Red, while those in English are shown in Black.

The text of some elements in a Word Cloud is often rotated 90 degrees.
Investigate [Text Rotation](https://matplotlib.org/examples/pylab_examples/text_rotation.html)
in matplotlib and incorporate it into your Word Cloud, so that each word
has a 50% chance of being displayed vertically.

### Sentence Drawing

A [Sentence Drawing](http://www.stefanieposavec.com/writing-without-words) can
be constructed from a document to visualize the flow and rhythm of the
text. Implement the following algorithm and create a diagram for your
document.

-   Start at point 0,0, pointing north
-   For each sentence in your document
    -   Draw a line forward where the length is the number of words in
        the sentence
    -   Turn right 90 degrees

If your document is very large, only draw this image for the first
section/chapter.

What insights on your document can you gather from this image?

### What to Hand In

Turn in your PDF and .ipynb file to the Lab 3 directory on Moodle.
