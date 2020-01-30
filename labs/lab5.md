---
title: 'CSCI 270 - Lab 5 - Topic Modeling'
...

[CSCI 270](../index.html) - Lab 5\
Topic Modeling
==================================

------------------------------------------------------------------------

Description
-----------

### On a Mac

Open up the terminal and type

    conda env list

Hopefully you only see the "root" environment. Then type

    source activate root

to get the mappings correct for your programs. Now type

    python

and you should get the Anaconda version 3.X. Here is what I see

    Python 3.6.1 |Anaconda 4.4.0 (x86_64)| (default, May 11 2017, 13:04:09)
    [GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.57)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

Now in the python console, type

    import nltk
    nltk.download()

Use this GUI to find the WordNet corpus and download it.

Next, exit out of python, back to the terminal. Time to install
[gensim](https://radimrehurek.com/gensim/install.html). The easiest way
I found was to type

    easy_install -U gensim

### On a Windows Machine

Open up the Anaconda Prompt and type

    conda env list

Hopefully you only see the "root" environment. Then type

    activate root

to get the mappings correct for your programs. Now type

    python

and you should get the Anaconda version 3.X. Here is what I see

    Python 3.6.1 |Anaconda 4.4.0 (x86_64)| (default, May 11 2017, 13:04:09)
    [GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.57)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

Now in the python console, type

    import nltk
    nltk.download()

Use this GUI to find the WordNet corpus and download it.

Next, exit out of python, back to the terminal. Time to install
[gensim](https://radimrehurek.com/gensim/install.html). The easiest way
I found for Windows was to type

    pip install -U gensim

If this doesn't work, try

    conda install -c anaconda gensim

### Data Cleaning

The subsequent steps again assume you have clean data with only tokens
separated by whitespace. Use the code from Lab 4 to load each document,
and then save the cleaned version to a new directory of only clean text
files, retaining the original file names.

### Stemming

Use the nltk Stemming library to stem each word for each of the
documents in the corpus.

Record the number of unique tokens before and after stemming.

Which document shrunk by the largest percentage?

### Lemmatizing

Use Wordnet to find the most commonly used Lemma, its definition, and
its hyponyms, for the following words:

-   sleeping
-   in
-   god
-   boats
-   walked
-   twisting
-   apple

Do any of these words have antonyms found in WordNet?

Which two words in the above list are the most similar according to
WordNet?

Which word has the largest hypernym closure (in other words, which word
is the most specific?)

### Word Vectors

Calculate the Word2Vec representation for the books corpus, and find the
10 most similar words to the following words:

-   sleep
-   in
-   god
-   boat
-   walk
-   twist
-   apple
-   hobbit

Discuss your results, note in particular those you expected to see, and
develop a hypothesis for those that are unexpected.

Find four main characters, each from a different books in our corpus.
What 10 words are most similar to each of these according to the
Word2Vec calculations? Research any words or characters unfamiliar to
you and discuss why they might be similar.

Test out the **man** is to **king** as **woman** is to **?** analogy
using the books dataset.

Analyze two other analogies that test two different
[relationships](http://www.mhhe.com/socscience/english/spears/stu3/studisk/verbal_analogies/va_intro.htm)
commonly found between words in analogies.

### Latent Dirichlet Allocation

Use the [LdaModel
class](https://radimrehurek.com/gensim/models/ldamodel.html) from gensim
to find five topics for our books corpus. Discuss the topics found and
any patterns you see.

For each topic, use this model to find the document that is most
relevant. Discuss the sensibility of this matching.

What to Hand In
---------------

Turn in your .ipynb file to the Lab 5 directory on Moodle.

------------------------------------------------------------------------

© Mark Goadrich, Hendrix College
