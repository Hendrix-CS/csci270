---
layout: work
type: Lab
num: 1
worktitle: Creating a Corpus
---

## Overview

## Step 1 - Installing Anaconda

To analyze our text data this semester, we will be using Anaconda and
Jupyter Notebooks, and hosting these on our own computers. What we will be
doing is usually to large for the free cloud-based notebooks like
Azure.

The [Anaconda Installation](https://docs.anaconda.com/anaconda/install/)
page lists many instructions for multiple operating systems. Follow the
instructions that make sense to you, choosing the Python 3.7 version.

### Open a Jupyter Notebook

Now we can test to see that everything is working. Follow
[these instructions](https://docs.anaconda.com/anaconda/install/verify-install/)
or mine below to get the `root` environment ready.

Then, type `jupyter notebook` and a browser window should appear.
From here, you can make a notebook as I have demonstrated in class.

### On a Mac

Open up the terminal and type

    conda env list

Hopefully you only see the `root` environment. Then type

    source activate root

to get the mappings correct for your programs.

### On a Windows Machine

Open up the Anaconda Prompt and type

    conda env list

Hopefully you only see the `root` environment. Then type

    activate root

to get the mappings correct for your programs.

## Step 2 - Adding Modules

### Using pip

At the anaconda prompt with the `root` environment activated, type:

    pip install matplotlib
    pip install pandas
    pip install plotnine
    pip install scipy
    pip install numpy
    pip install nltk
    pip install gensim
    pip install afinn
    pip install graphviz
    pip install pyknon
    pip install music21

### In Python

Now type

    python

and you should get the Anaconda version 3.X. Here is what I see

    Python 3.7.4 (default, Aug 13 2019, 15:17:50)
    [Clang 4.0.1 (tags/RELEASE_401/final)] :: Anaconda, Inc. on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

Now in the python console, type

    import nltk
    nltk.download()

* Use this GUI to find the WordNet corpus and download it.
* Use this GUI to find the "book" link in the "Collections" tab and download it. This will load many datasets and libraries.
* Also install the VADER library and collection.

## Step 3 - Files for Analysis

In this class we will be analyzing various expressions of the human
condition through language, art, and music. To assist us and make our
work personally valuable, you will be gathering text, images, and sound
files for the class to analyze in subsequent labs.

### 3.1 - Poem

First, it will be useful to have a small dataset for exploring our
algorithms and generating examples.

Find a small poem or lyrics to a song written in English that holds
meaning for you.

Save your poem as a plain text document with a short, meaningful file
name. (with file extension `.txt`) Your file size for this poem should
be no more than 20KB, and be saved using UTF-8 encoding.

### 3.2 - Book

To find statistical patterns in text data, we need a large amount of
text.

Find a book/novel/treatise/creative work of fiction that has meaning to you, stored in an
electronic format. You should either find the novel available without
cost, or purchase the ebook (look for versions without DRM so we can
access the raw data).

Save your book as a plain text document with a short, meaningful file
name. (with file extension `.txt`) Your file size for this document
should be no less than 150KB, and be saved using UTF-8 encoding.

If your book is in another file format, such as `.epub`, it must be converted
to a plain text document. [Calibre](https://calibre-ebook.com/download)
can assist with this conversion.

### 3.3 - Image

Find an image of art stored in an electronic file format (PNG, JPEG,
TIFF, BMP, SVG, etc) that has meaning to you. This file must be at least HD
quality (1920 x 1080 pixels in size).

### 3.4 - Instrumental Music

Find a piece of instrumental music (no singing) stored in an electronic
file format (mp3, MIDI, etc) that has meaning to you.

## Step 4 - Reflection

For each of your selections, answer the following questions:

-   What makes this selection interesting to you?
-   What do you estimate is the reading level for this text? (only
    answer for Poem and Book)
-   Would you say this selection conveys an overall positive or negative
    sentiment?
-   Formulate a research question you hope to answer by analyzing this
    selection computationally.

This reflection must also be written as a plain text document, not using
any word processing software, saved as `reflection.txt`.

## What to Hand In

Turn in one file for each of the above steps on
[Moodle](http://moodle.hendrix.edu).
