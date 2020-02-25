---
layout: work
type: Lab
num: 5
worktitle: Topic Modeling
---

### Data Cleaning

The subsequent steps again assume you have clean data with only tokens
separated by whitespace. Use the code from Lab 4 to load each document,
and then save the cleaned version to a new directory of only clean text
files, retaining the original file names.

### Stemming

* Use the nltk Porter Stemmer to stem each word for each of the
documents in our corpus.

* Record the number of unique tokens before and after stemming.

* Which document shrunk by the largest percentage?

### Lemmatizing

Use Wordnet to find the most commonly used Lemma, its definition, and
its hyponyms, for the following words:

-   sleeping
-   in
-   god
-   up
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

Calculate the Word2Vec representation for the Books corpus, and find the
10 most similar words to the following words:

-   sleep
-   in
-   up
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
to find five topics for our books corpus.

Discuss the topics found and
any patterns you see.

For each topic, use this model to find the document that is most
relevant. Discuss the sensibility of this matching.

## What to Hand In

Turn in your .ipynb file to the Lab 5 directory on Moodle.
