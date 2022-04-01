---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: course-single
---

# <a name="description">Overview</a>

{{ site.description }}

## <a name="goals">Learning Goals</a>

Upon completing this course, my goal is for you to be able to:
* Computationally analyze digital creative works comprised of text, images, and sound.
* Combine quantitative and qualitative analysis of a digital creative work.
* Visualize and summarize textual, musical, and visual information.
* Measure and visualize similarity of digital creative works.
* Employ algorithmic structures to synthesize original digital creative works.

## <a name="resources">Resources</a>

{% include resources.html content=site.resources %}

# <a name="calendar">Calendar</a>

| Date   |   Day   |   Topic/Activity           |   Assigned                                                       |   Due     |
|  ---   |   ---   |        ---                 |     ---                                                          |   ---     |
| 1/19   |   Weds  |  Introduction              | [Survey](https://forms.gle/QcKEsPYPYAfnsiAQ8)<br>Lab 1:[Creating a Corpus]({{site.baseurl}}/labs/corpus.html)
| 1/21   |   Fri   |  [Python Encodings](https://realpython.com/python-encodings-guide/)<br>[The Great Newline Schism](https://blog.codinghorror.com/the-great-newline-schism/)<br>[Unicode](https://home.unicode.org/)<br>[UTF-8](https://en.wikipedia.org/wiki/UTF-8)<br>[Texting in Ancient Mayan Hieroglyphs](https://www.neh.gov/humanities/2018/winter/feature/texting-in-ancient-mayan-hieroglyphs) | Lab 2: [Summary Statistics](https://www.kaggle.com/gabrielferrer/csci-270-lab-2-summary-statistics) | Lab 1     |
| 1/24   |   Mon   |  [Generators and Comprehensions](https://www.pythonlikeyoumeanit.com/Module2_EssentialsOfPython/Generators_and_Comprehensions.html)<br>[Zipf's Law](https://en.wikipedia.org/wiki/Zipf%27s_law)<br>[*hapax legomenon*](https://en.wikipedia.org/wiki/Hapax_legomenon)<br>[Markdown](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)
| 1/26   |   Weds  |  [Pandas](https://pandas.pydata.org/)<br>[Swadesh List](https://en.wikipedia.org/wiki/Swadesh_list)
| 1/28   |   Fri   |  [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)<br>[Why does tf-idf use a log?](https://www.quora.com/Why-does-TF-IDF-use-a-log) | Lab 3: [Document Clustering](https://www.kaggle.com/gabrielferrer/csci-270-lab-3-document-clustering)                                       | Lab 2     |
| 1/31   |   Mon   |  [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)<br>[UPGMA](https://en.wikipedia.org/wiki/UPGMA)
| 2/2    |   Weds  | 
| 2/4    |   Fri   |                            | Lab 4: [Sentiment Analysis](https://www.kaggle.com/gabrielferrer/lab-4-sentiment-analysis)                                            | Lab 3     |
| 2/7    |   Mon   |
| 2/9    |   Weds  | 
| 2/11   |   Fri   |                            | Lab 5: [Topic Modeling](https://www.kaggle.com/gabrielferrer/lab-5-topic-modeling)                                         | Lab 4     |
| 2/14   |   Mon   |
| 2/16   |   Weds  | 
| 2/18   |   Fri   |                            | Lab 6: [Algorithmic Art]({{site.baseurl}}/labs/art.html)                                            | Lab 5     |
| 2/21   |   Mon   | **Winter Break - No class**
| 2/23   |   Weds  | 
| 2/25   |   Fri   | [OpenCV](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html) | Lab 7: [Image Analysis](https://www.kaggle.com/gabrielferrer/csci-270-lab-7) | Lab 6     |
| 2/28   |   Mon   |
| 3/2    |   Weds  | 
| 3/4    |   Fri   | [Sonic Pi Tutorial](https://sonic-pi.net/tutorial.html) <br> [Live Coding Education](https://sonic-pi.net/files/articles/Live-Coding-Education.pdf) <br> [Note to Frequency Chart](https://www.doctormix.com/docs/Note-To-Frequancy-Chart.jpg) | Lab 8: [Algorithmic Music]({{site.baseurl}}/labs/music1.html)          | Lab 7     |
| 3/7    |   Mon   |
| 3/9    |   Weds  | 
| 3/11   |   Fri   | [Frequencies and Intervals](https://www.kaggle.com/gabrielferrer/frequencies-and-intervals)                           | Lab 9: [Musical Mode](https://www.kaggle.com/gabrielferrer/music-major-and-minor-analysis) | Lab 8     |
| 3/14   |   Mon   |
| 3/16   |   Weds  | 
| 3/18   |   Fri   |                            |                                                                  | Lab 9     |
| 3/21   |   Mon   | **Spring Break - No class**
| 3/23   |   Weds  | **Spring Break - No class**
| 3/25   |   Fri   | **Spring Break - No class**
| 3/28   |   Mon   |                            | Lab 10: [Music Clustering](https://www.kaggle.com/gabrielferrer/music-clustering)          
| 3/30   |   Weds  | 
| 4/1    |   Fri   |                            | Lab 11: Visual Novel                                             | Lab 10     |
| 4/4    |   Mon   |
| 4/6    |   Weds  | 
| 4/8    |   Fri   |                            |                                                                  | Lab 11     |
| 4/11   |   Mon   |                            | Final Project: Proposal
| 4/13   |   Weds  | 
| 4/15   |   Fri   |                            |                                                                  | Final Project: Proposal |
| 4/18   |   Mon   |                            | 
| 4/20   |   Weds  | 
| 4/22   |   Fri   |                            |                                                                  | Final Project: Progress Report |
| 4/25   |   Mon   |                            | 
| 4/27   |   Weds  | 
| 4/29   |   Fri   |                            |                                                                  | Final Project: Progress Report |
| 5/6    |   Fri 8:30-11:30 am|                                                                                    | Final Project: Presentation |

# <a name="assessment">Assessment</a>

## <a name="labs">Labs</a>

A total of 11 labs will be assigned throughout the semester, approximately one lab per week. 
Each submission will be assessed as either **Complete**, **Partially Complete** or **Missing**. The 
criteria for these assessments will be given for each lab.

| #  | Lab                                                                                            | Assigned | Due      |
|----|------------------------------------------------------------------------------------------------|----------|----------|
| 1  | [Creating a Corpus]({{site.baseurl}}/labs/corpus.html)                                         | 1/19     | 1/21     |
| 2  | [Summary Statistics](https://www.kaggle.com/gabrielferrer/csci-270-lab-2-summary-statistics)   | 1/21     | 1/28     |
| 3  | [Document Clustering](https://www.kaggle.com/gabrielferrer/csci-270-lab-3-document-clustering) | 1/28     | 2/4      |
| 4  | [Sentiment Analysis](https://www.kaggle.com/gabrielferrer/lab-4-sentiment-analysis)            | 2/4      | 2/11     |
| 5  | [Topic Modeling](https://www.kaggle.com/gabrielferrer/lab-5-topic-modeling)                    | 2/11     | 2/18     |
| 6  | [Algorithmic Art]({{site.baseurl}}/labs/art.html)                                              | 2/18     | 2/25     |
| 7  | [Image Analysis](https://www.kaggle.com/gabrielferrer/csci-270-lab-7)                          | 2/25     | 3/4      |
| 8  | [Algorithmic Music]({{site.baseurl}}/labs/music1.html)                                         | 3/4      | 3/11     |
| 9  | [Major and Minor](https://www.kaggle.com/gabrielferrer/music-major-and-minor-analysis)         | 3/11     | 3/18     |
|10  | [Music Clustering](https://www.kaggle.com/gabrielferrer/music-clustering)                      | 3/28     | 4/1      |
|11  | [Visual Novel]({{site.baseurl}}/labs/novel.html)                                               | 4/1      | 4/8      |

## <a name="groupwork">In-Class Assignments</a>

Many class periods will involve in-class group assignments, which will be hands-on activities relating either
to a recently submitted lab or to gaining a deeper understanding of the course material.

## <a name="finalproject">Final Project</a>

The [final project]({{site.baseurl}}/projects/project.html) for this course may take one of two forms:
1. You may apply a computational humanities tool to a dataset of your choice. 
2. You may create an original creative digital work. It may involve any combination of text, images, and music
that you wish. The creative work must have an algorithmic aspect at its core. 

Either form of project will require submitting the following:
* A project proposal.
* An oral presentation in the final exam period for the course.
* A paper, either analyzing your results or reflecting upon your creative work.
* All code used in creating the project, sufficient to digitally reproduce your work.

## Tokens

Each student begins the semester with **three tokens**. A student may spend a token in order to:
* **Extend** a deadline: An extended lab may be submitted by the start of the next class period after the
  original due date. The instructor must be notified of this extension prior to the original deadline. 
  Note that the final project may **not** be extended. 
* **Revise** a completed lab: A lab assessed as **Partially Complete** may be revised and resubmitted up to one
week after it has been graded.

A student may earn a token by booking and attending an office hours appointment. Each student may earn up to 
**three additional tokens** over the course of the semester from office hours visits.

Each student will have a channel in the Team for CSCI 270 for tracking their tokens. To spend a token, a student 
will add a message to the channel chat stating which project will be revised or extended. The message should include
the number of tokens now remaining as well. After each office hours visit, the instructor will add a message stating the 
new token total.

## <a name="grading">Specifications Grading</a>

* To earn an A in the course, a student will:
  * **Complete** the final project
  * **Complete** a minimum of 10 of the 11 labs, and at least **Partially Complete** the remaining lab.
  * Participate actively in at least 90% of in-class assignments.
* To earn a B in the course, a student will:
  * One of the following:
    * **Complete** the final project and a minimum of eight labs, and at least **Partially Complete** a minimum of two more labs.
	* **Partially Complete** the final project, **Complete** a minimum of 10 labs, and **Partially Complete** the remaining lab.
  * Participate actively in at least 80% of in-class assignments.
* To earn a C in the course, a student will:
  * One of the following:
    * **Complete** the final project and a minimum of six labs, and at least **Partially Complete** a minimum of two more labs.
	* **Partially Complete** the final project, **Complete** a minimum of eight labs, and at least **Partially Complete** a minimum of two more labs.
  * Participate actively in at least 70% of in-class assignments.
* To earn a D in the course, a student will:
  * At least **Partially Complete** the final project and a minimum of six labs.
  * Participate actively in at least 50% of in-class assignments.
  

 
<!--
# <a name="readings">Readings</a>

We will be using no textbook but instead supplemental material such as relevant
web-pages for the course. Readings will be assigned before material will be
covered in class. You are expected to review the material and come to class
prepared. As readings are assigned, they will be posted here.

| Date  | Reading |
|:--:||-----|
| Jan 21 | [Unicode](https://home.unicode.org/) |
| | [UTF-8](https://en.wikipedia.org/wiki/UTF-8) |
| | [Python Encodings](https://realpython.com/python-encodings-guide/) |
| | [The Great Newline Schism](https://blog.codinghorror.com/the-great-newline-schism/) |
| | [Texting in Ancient Mayan Hieroglyphs](https://www.neh.gov/humanities/2018/winter/feature/texting-in-ancient-mayan-hieroglyphs) |
| Jan 23 | [Pandas](https://pandas.pydata.org/) |
| | [plotnine](https://plotnine.readthedocs.io/en/stable/index.html) |
| | [A Layered Grammar of Graphics](https://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf) |
| | [english2.txt](data/english2.txt) |
| Jan 28 | [Zipf's Law](https://en.wikipedia.org/wiki/Zipf%27s_law) |
| Jan 30 | [Understanding the Nuances of Typography Classification](https://www.toptal.com/designers/typography/typeface-classification) |
| | [Typeface](https://en.wikipedia.org/wiki/Typeface) |
| | [Wordle](http://static.mrfeinberg.com/bv_ch03.pdf) |
| | [How the Word Cloud Generator Works](https://www.jasondavies.com/wordcloud/about/) |
| | [Stop Word List](data/stop-word-list.txt) |
| Feb 4 | [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) |
| | [Why does tf-idf use a log?](https://www.quora.com/Why-does-TF-IDF-use-a-log) |
| Feb 6 | [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity) |
| | [UPGMA](https://en.wikipedia.org/wiki/UPGMA) |
| Feb 11 | [Stemming Online](https://text-processing.com/demo/stem/) |
| | [Porter Stemmer](http://people.scs.carleton.ca/~armyunis/projects/KAPI/porter.pdf) |
| | [pyporter2](https://github.com/mdirolf/pyporter2) |
| | [WordNet Online](http://wordnetweb.princeton.edu/perl/webwn) |
| Feb 20 | [Word Embeddings](https://www.tensorflow.org/tutorials/text/word_embeddings) |
| | [Word2Vec](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf) |
| | [Word2Viz](https://lamyiowce.github.io/word2viz/) |
| | [GloVe](https://nlp.stanford.edu/projects/glove/) |
| | [Gensim Word2Vec](https://radimrehurek.com/gensim/models/word2vec.html) |
| Feb 25 | [Beta Distribution Calculator](http://keisan.casio.com/exec/system/1180573226) |
| | [Multinomial Distribution](https://en.wikipedia.org/wiki/Multinomial_distribution) |
| | [Visualizing Dirichlet Distributions](http://blog.bogatron.net/blog/2014/02/02/visualizing-dirichlet-distributions/) |
| | [Latent Dirichlet Allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation) |
| | [Probabilistic Topic Modeling](http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf) |
| | [LDA Details](https://courses.engr.illinois.edu/cs598jhm/sp2010/Slides/Lecture06.pdf) |
| | [Gensim Topic Models](https://radimrehurek.com/gensim/tut2.html) |
| Feb 27 | [Hu and Liu Opinion Lexicon](https://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html#lexicon) |
| | [AFINN Online](http://darenr.github.io/afinn/#) |
| | [VADER Explained](http://comp.social.gatech.edu/papers/icwsm14.vader.hutto.pdf) |
| | [NLTK Sentiment Library](http://www.nltk.org/api/nltk.sentiment.html) |
| | [NLTK Sentiment How To](http://www.nltk.org/howto/sentiment.html) |
| Mar 3 | [Why you should care about generative text](https://hackernoon.com/why-you-should-care-about-generative-text-52496cb74beb) |
| | [NaNoGenMo](https://nanogenmo.github.io/) |
| | [Botnik Predictive Writer](https://botnik.org/apps/writer/?source=589b43f09f1100d6a871cb9c3dda71a6) |
| | [Harry Potter and the Portrait of what Looked Like a Large Pile of Ash](https://botnik.org/harry-potter-chapter/) |
| Mar 10 | [Huffman Encoding](https://en.wikipedia.org/wiki/Huffman_coding) |
| | [Color Depth](https://en.wikipedia.org/wiki/Color_depth), [RGB Color Model](https://en.wikipedia.org/wiki/RGB_color_model) |
| | [BMP](https://en.wikipedia.org/wiki/BMP_file_format), [GIF](https://en.wikipedia.org/wiki/BMP_file_format), [PNG](https://en.wikipedia.org/wiki/Portable_Network_Graphics) |
| Mar 12 | [LZ77 Data Compression](https://towardsdatascience.com/how-data-compression-works-exploring-lz77-3a2c2e06c097) |
| | [LZSS Improvements](http://web.eecs.umich.edu/~sugih/courses/eecs281/fall07/lectures/lecture11.pdf) |
| | [Color Model Translator](http://colorizer.org/) |
| | [JPEG Format](https://en.wikipedia.org/wiki/JPEG) |
| | [YCbCr](https://medium.com/breaktheloop/what-is-ycbcr-964fde85eeb3) |


# <a name="inclasscode">In-Class Code</a>

When we write code together in class, it will be posted here!

| Date | Topic | Code |
|:----:|------||-----||
| T Jan 21 | Character Text Encodings | [UTF-8](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Character%20Encoding.ipynb) |
| R Jan 23 | Data Visualization Day 1 | [Summary Statistics](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Summary%20Statistics.ipynb) |
| T Jan 28 | Data Visualization Day 2 | [Summary Statistics Day 2](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Summary%20Statistics%20Day%202.ipynb) |
| R Jan 30 | Fonts and Word Clouds | [Word Clouds](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Word%20Cloud%20In%20Class.ipynb) |
| R Feb 20 | Stemming and Lemmatizing | [Stemming and Lemmatizing](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Stemming%20and%20Lemmatization.ipynb) |
| R Feb 20 | Word2Vec | [Word2Vec and Gensim](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Word%20Similarity%202020.ipynb) |
| T Feb 25 | Latent Dirichlet Allocation | [LDA Example](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/LDA%20Example%202020.ipynb) |
| R Feb 27 | Sentiment Analysis | [Sentiment Analysis](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Sentiment%20Analysis.ipynb) |
| R Mar 5 | Markov Chains | [Markov Chain In Class](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Markov%20Chain%20InClass.ipynb) |
| R Apr 16 | Epidemiology | [SIR Compartment Modeling](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/notes/Epidemiology.ipynb) |

<hr>
# Coursework

Each student has **four late days** to spend throughout the semester as they wish.
Simply inform the instructor any time *prior* to the due date for an assignment
that you wish to use a late day; you may then turn in the assignment up to 24
hours late. Multiple late days may be used on the same assignment. There are no
partial late days; turning in an assignment 2 hours late or 20 hours late will
both use 1 late day. Note that late days are intended to cover both normal
circumstances (you simply want more time to work on the assignment) and
exceptional circumstances (you get sick, travel for a game or family
obligation, *etc.*). After you have used up your late days, ~~late assignments
will receive at most half credit.~~ **you will be given more, because this is a
crazy semester. All work must be completed the day before final grades are due,
and you must be in communication with me when assignments are late.**

## <a name="labs">Labs</a>: 500 points

| #  | Name | Assigned | Due |
|:--:|-----||:--------:|:---:|
|0 | [Student Survey](https://forms.gle/6ebsJiBCqhQm2dFB6) | Jan 17 | Jan 21 |
|1 | [Creating a Corpus]({{site.baseurl}}/labs/corpus.html) | Jan 21 | Jan 23 |
|2 | [Summary Statistics]({{site.baseurl}}/labs/summary.html) | Jan 23 | Jan 31 |
|3 | [Clouds and Drawings]({{site.baseurl}}/labs/clouds.html) | Jan 30 | Feb 7 |
|4 | [Document Clustering](https://nbviewer.jupyter.org/url/hendrix-cs.github.io/csci270/labs/Lab%204%20-%20Document%20Clustering%202020.ipynb) | Feb 6 | Feb 14 |
|5 | [Topic Modeling]({{site.baseurl}}/labs/topic.html) | Feb 25 | Mar 4 |
|6 | [Sentiment Analysis]({{site.baseurl}}/labs/sentiment.html) | Mar 3 | Mar 7 |
|7 | [Detecting and Generating Language]({{site.baseurl}}/labs/markov.html) | Mar 6 | Mar 13 |
|8 | [Deep Dreams](https://deepdreamgenerator.com/) | Apr 2 | Apr 7 |
|9 | [Lullabies](http://sonic-pi.net/) | Apr 9 | Apr 14 |

Much of your experience with the techniques of
computational humanities in this course will be through weekly labs.
Each lab will be assigned in class with some time allotted to work through the materials, and will be due **in approximately one week**. All labs are weighted equally within the lab portion of your final grade.

On these labs, you can work with a partner on the lab assignments. Their name must be listed on any code you hand in as joint work. A partnership should only turn in a **single copy** of the assignment. If students working as partners wish to turn in a lab late, both students must use a late day.

### Class corpus

Many of our labs will be using the corpus below that we collected in Lab 1.
* [Corpus2020.zip](data/Corpus2020.zip)

## <a name="projects">Project</a>: 210 points

| #  | Name | Points | Assigned | Due |
|:--:|-----||:------:|:--------:|:---:|
|1 | [Final Project]({{site.baseurl}}/projects/project.html)  | 210  | Mar 19 | Apr 9 |

You will have a final project in this course.
Further details on the grading standards and handin instructions for each
project will be given when they are assigned.

## <a name="exams">Exams</a>: 250 points

| #  | Topics | Points | Date |
|:--:|-----||:------:|:----:|
|1 | text encoding, data processing, fonts, word clouds, and clustering | 100 | Feb 18 |
| 2 | ~~stemming, lemmatizing, topic modeling, sentiment analysis, and Markov models~~ | ~~150~~ | ~~Mar 17~~ |

There will be ~~two~~ **one** in-class exam~~s~~, the first worth 100 ~~and the
second worth 150~~ points of your final grade.
They will consist of short answer questions along with writing and debugging code.
There is no final exam; you will complete a final project instead, as described above under Projects.

## <a name="checkins">Checkins and Participation</a>: 40 points

Two times throughout the semester, you are expected to
make an office hours appointment and check in with me about the course. Each checkin
meeting will count for 20 points.
This will be conversation and feedback about your current progress and understanding.
These should be scheduled during the weeks shown
on the [course calendar](https://app.teamgantt.com/public/projects/calendar/2020-01-12?ids=1990087&projectIds=1990087&publicKeys=eh0JCy4TSjrP&userResourceIds=0).

## <a name="scale">Grading Scale</a>

| Score  | Grade  |
|:------:|:------:|
| 750-850  | A   |
| 650-749   | B   |
| 550-649   | C   |
| 450-549   | D   |
| 0-449     | F   |
-->
