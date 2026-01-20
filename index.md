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

<!-- Notes for next time

Move to a Level structure for each assignment.
* Level 1, 2, and 3 for each one.
  * Achieving Level 1 should be really easy!
* Also work in an on-time bonus
* Lab 1 has only one level - it is all or nothing - 2 credits
* Labs 2-11 each have three levels - 4 credits each - 40 credits
* 42 total credits - grades would be:
  * A: 39-42 (allows three late/less complete submissions - must still do something for every lab)
  * B: 31-38
  * C: 23-30
  * D: 15-22
  
Final project
* If you do everything you state, it is complete
* If you fall short, partially complete
* Goals are negotiable right up to submission
-->

## <a name="resources">Resources</a>

{% include resources.html content=site.resources %}

# <a name="calendar">Calendar</a>

| Date   |   Day   |   Topic/Activity           |   Assigned                                                       |   Due     |
|  ---   |   ---   |        ---                 |     ---                                                          |   ---     |
| 1/21   |   Weds  |  Introduction              | [Survey](https://forms.gle/VLRVHjUAisWP5R9J8)<br>Lab 1: [Creating a Corpus]({{site.baseurl}}/labs/corpus.html)
| 1/23   |   Fri   |  [Python Encodings](https://realpython.com/python-encodings-guide/)<br>[The Great Newline Schism](https://blog.codinghorror.com/the-great-newline-schism/)<br>[Unicode](https://home.unicode.org/)<br>[UTF-8](https://en.wikipedia.org/wiki/UTF-8)<br>[Texting in Ancient Mayan Hieroglyphs](https://www.neh.gov/humanities/2018/winter/feature/texting-in-ancient-mayan-hieroglyphs) | Lab 2: [Summary Statistics](https://www.kaggle.com/gabrielferrer/csci-270-lab-2-summary-statistics) | Lab 1     |
|
| 1/26   |   Mon   |  [Generators and Comprehensions](https://www.pythonlikeyoumeanit.com/Module2_EssentialsOfPython/Generators_and_Comprehensions.html)<br>[Zipf's Law](https://en.wikipedia.org/wiki/Zipf%27s_law)<br>[*hapax legomenon*](https://en.wikipedia.org/wiki/Hapax_legomenon)<br>[Markdown](https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html)
| 1/28   |   Weds  |  [Pandas](https://pandas.pydata.org/)<br>[Swadesh List](https://en.wikipedia.org/wiki/Swadesh_list)
| 1/30   |   Fri   |  [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)<br>[Why does tf-idf use a log?](https://qr.ae/pKB7IJ) | Lab 3: [Document Clustering](https://www.kaggle.com/gabrielferrer/csci-270-lab-3-document-clustering)                                       | Lab 2     |
|
| 2/2    |   Mon   |  [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)<br>[UPGMA](https://en.wikipedia.org/wiki/UPGMA)
| 2/4    |   Weds  | [Word2Vec](https://wiki.pathmind.com/word2vec)
| 2/6    |   Fri   | [TextRank](https://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf) | Lab 4: [Finding Meaning](https://www.kaggle.com/gabrielferrer/lab-4-finding-meaning)                                            | Lab 3     |
|
| 2/9    |   Mon   | [VADER](https://www.researchgate.net/publication/275828927_VADER_A_Parsimonious_Rule-based_Model_for_Sentiment_Analysis_of_Social_Media_Text) 
| 2/11   |   Weds  | [BERT](https://arxiv.org/pdf/1810.04805.pdf)
| 2/13   |   Fri   |             | Lab 5: [Sentiment Analysis](https://www.kaggle.com/gabrielferrer/lab-5-sentiment-analysis)                                          | Lab 4     |
|
| 2/16   |   Mon   | **NO CLASS: Winter Break**
| 2/18   |   Weds  | **NO CLASS: Away at Conference**
| 2/20   |   Fri   | **NO CLASS: Away at Conference**
|
| 2/23   |   Mon   | [Turtle Graphics](https://docs.python.org/3/library/turtle.html)    | Lab 6: [Algorithmic Art](https://www.kaggle.com/gabrielferrer/lab-6-algorithmic-art)                                            | Lab 5     |
| 2/25   |   Weds  | [OpenCV](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
| 2/27   |   Fri   | [RetinaFace](https://arxiv.org/abs/1905.00641) 
|
| 3/2    |   Mon   | [DeepFace](https://research.facebook.com/publications/deepface-closing-the-gap-to-human-level-performance-in-face-verification/) | Lab 7: [People in Paintings](https://www.kaggle.com/gabrielferrer/lab-7-people-in-paintings) | Lab 6     |

| 3/4    |   Weds  | [librosa](https://librosa.org/doc/latest/index.html)
| 3/6    |   Fri   | [Sonic Pi Tutorial](https://sonic-pi.net/tutorial.html) <br> [Live Coding Education](https://sonic-pi.net/files/articles/Live-Coding-Education.pdf) <br> [Note to Frequency Chart](https://www.doctormix.com/docs/Note-To-Frequancy-Chart.jpg)
|
| 3/9    |   Mon   | | Lab 8: [Algorithmic Music](https://www.kaggle.com/code/gabrielferrer/lab-8-algorithmic-music) | Lab 7
| 3/11   |   Weds  | 
| 3/13   |   Fri   |  [Frequencies and Intervals](https://www.kaggle.com/gabrielferrer/frequencies-and-intervals) | Lab 9: [Music Clustering](https://www.kaggle.com/code/gabrielferrer/lab-9-music-clustering)
|
| 3/16   |   Mon   | **NO CLASS: Off-campus Appointment** | | Lab 8     |
| 3/18   |   Weds  | 
| 3/20   |   Fri   |                            |                                                                  | Lab 9     |
|
| 3/23   |   Mon   | **NO CLASS: Spring Break**
| 3/25   |   Weds  | **NO CLASS: Spring Break**
| 3/27   |   Fri   | **NO CLASS: Spring Break**
|
| 3/30   |   Mon   |                            | Lab 10: [Analyzing Songs]({{site.baseurl}}/labs/songs.html)
| 4/1    |   Weds  | 
| 4/3    |   Fri   |                            | 
|
| 4/6    |   Mon   |                            | Lab 11: [Visual Novel]({{site.baseurl}}/labs/novel.html)  | Lab 10
| 4/8    |   Weds  | 
| 4/10   |   Fri   | **NO CLASS: Away at Conference** 
|
| 4/13   |   Mon   |      | 
| 4/15   |   Weds  |               |    | Lab 11
| 4/17   |   Fri   | Final Project      | [Final project]({{site.baseurl}}/projects/project.html): Proposal                      | 
|
| 4/20   |   Mon   |                            |                           | Final Project Proposal
| 4/22   |   Weds  |                            |                           | 
| 4/24   |   Fri   |                            |                           | 
|
| 4/27   |   Mon   |                            |                           | 
| 4/29   |   Weds  |                            |                           | [Final project]({{site.baseurl}}/projects/project.html): Progress Report                             
| 5/1    |   Fri   |                            |                           | [Final project]({{site.baseurl}}/projects/project.html): Progress Report |
| 5/7    |   Thr 8:30-11:30 am|                                                                                    | [Final project]({{site.baseurl}}/projects/project.html): Presentation |

# <a name="assessment">Assessment</a>

## <a name="labs">Labs</a>

A total of 11 labs will be assigned throughout the semester, approximately one lab per week. 
Each submission will be assessed as either **Complete**, **Partially Complete** or **Missing**. The criteria for these assessments will be given for each lab.

| #  | Lab                                                                                            | Assigned | Due      |
|----|------------------------------------------------------------------------------------------------|----------|----------|
| 1  | [Creating a Corpus]({{site.baseurl}}/labs/corpus.html)                                         | 1/21     | 1/23     |
| 2  | [Summary Statistics](https://www.kaggle.com/gabrielferrer/csci-270-lab-2-summary-statistics)   | 1/23     | 1/30     |
| 3  | [Document Clustering](https://www.kaggle.com/gabrielferrer/csci-270-lab-3-document-clustering) | 1/30     | 2/6      |
| 4  | [Sentiment Analysis](https://www.kaggle.com/gabrielferrer/lab-4-sentiment-analysis)            | 2/6      | 2/13     |
| 5  | [Topic Modeling](https://www.kaggle.com/gabrielferrer/lab-5-topic-modeling)                    | 2/13     | 2/20     |
| 6  | [Algorithmic Art](https://www.kaggle.com/gabrielferrer/lab-6-algorithmic-art)                  | 2/20     | 2/27     |
| 7  | [People in Paintings](https://www.kaggle.com/gabrielferrer/lab-7-people-in-paintings)          | 2/27     | 3/6      |
| 8  | [Algorithmic Music](https://www.kaggle.com/code/gabrielferrer/lab-8-algorithmic-music)         | 3/6      | 3/13     |
| 9  | [Music Clustering](https://www.kaggle.com/code/gabrielferrer/lab-9-music-clustering)           | 3/13     | 3/17     |
|10  | Analyzing Songs                                                                                | 3/30     | 4/6      |
|11  | [Visual Novel]({{site.baseurl}}/labs/novel.html)                                               | 4/6      | 4/15     |

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

Each student begins the semester with **six tokens**. 
* Send Dr. Ferrer a message on Teams to spend a token.
* Students may **spend** tokens as follows:
  * Spend **one** token to submit a revised version of an assignment, in the event the assignment is not Complete.
  * Spend **two** tokens to request an extension on an assignment deadline. 
    * When requesting an extension, specify the new deadline that you think will suffice.
    * Most deadline requests will be approved, but the instructor reserves the right to limit extensions if he deems them unreasonable.
  * Spend **three** tokens to submit an assignment after its deadline (including extended deadlines).
* To earn additional tokens:
  * Earn **one** token by booking and attending an office hours appointment. 
    * A student may earn up to **one token per week** from attending office hours, and a maximum of **six** tokens over the course of 
      the semester.
  * Earn **four** tokens by creating a 2-4 minute video educating a viewer about a concept from the course.
* Students may not go into token debt - to spend tokens, a student must have a positive balance.

## <a name="grading">Specifications Grading</a>

* To earn an A in the course, a student will:
  * **Complete** the final project
  * **Complete** all 11 labs
* To earn a B in the course, a student will:
  * One of the following:
    * **Complete** the final project and a minimum of eight labs, and at least **Partially Complete** a minimum of two more labs.
	* **Partially Complete** the final project, **Complete** all 11 labs
* To earn a C in the course, a student will:
  * One of the following:
    * **Complete** the final project and a minimum of five labs, and at least **Partially Complete** a minimum of two more labs.
    * **Partially Complete** the final project and a minimum of eight labs, and at least **Partially Complete** a minimum of two more labs.
    * **Complete** all 11 labs
* To earn a D in the course, a student will:
  * One of the following:
    * **Complete** the final project and a minimum of three labs, and at least **Partially Complete** a minimum of one more lab.
    * **Partially Complete** the final project and a minimum of five labs, and at least **Partially Complete** a minimum of two more labs.
    * **Complete** a minimum of eight labs, and at least **Partially Complete** a minimum of two more labs.
  
