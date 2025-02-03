# COLX 565: Sentiment Analysis

## Course Description

_Sentiment analysis_ in Natural Language Processing (NLP) and Computational Linguistics (CL) involves identifying and analyzing polarity—positive, negative, neutral, or mixed—within text. This course provides a structured introduction to sentiment analysis methods, covering mostly modern deep learning techniques (with brief reference to classical methods). It combines lectures with hands-on lab sessions to ensure a balance between theoretical understanding and practical implementation.

__Slack Channel__: cl-565_sentiment

## Course Learning Outcomes

Upon completion of this course, students are expected to:

1. Apply appropriate resources when carrying out lexicon-based polarity classification
2. Identify challenges and potential solutions associated with identifying sentiment targets
3. Carry out fine-grained sentiment analysis with large datasets using appropriate machine learning techniques 
4. Track sentiment over time, space, and topic using social media datasets 



## Meeting times / locations

This is a live presentation class.  Students are expected to attend lectures when possible.  Recordings will be available, but should be used as a study tool
instead of a primary method of learning the material.

Classes meet Tuesday and Thursday at 9:00 a.m., in SCRF 208.
Labs are Tuesday from 2-6 p.m., in ORCH 4018.

## Attendance

The MDS-CL is an *in-person* program - you are expected to attend classes and labs.  Recordings will be provided, but are intended for review, only.  Interaction in class has been shown to improve understanding, and collaborative environments improve learning.

Attendance will be taken with iClicker.  To receive full marks, you must attend 6 of 8 classes.  Attendance in fewer classes than these will result in a grade of 0 for attendance.  I understand that illness and emergencies happen (if you are ill, please do not come to class).  If the class average attendance is above 20 students, then everyone will receive full attendance marks.


## Assessments

This is an __assignment-based course__. You'll be evaluated as follows:

| Assessment       | Weight  | Due Date         | Location |
|------------------|---------|------------------|----------|
| Lab Assignment 1 | 14%     | Feb 17, 11:59pm| Submit to Github |
| Lab Assignment 2 | 14%     |  Mar 2, 11:59pm| Submit to Github |
| Quiz 1           | 20%     |  TBA | Online | 
| Lab Assignment 3 | 14%     |  Mar 9, 11:59pm | Submit to Github |
| Lab Assignment 4 | 14%     |  Mar 16, 11:59pm | Submit to Github |
| Quiz 2           | 20%     | TBA | Online  |
| Attendance       | 4%     | N/A | iClicker |


## Teaching Team

| Position           | Name    | Slack Handle | GHE Handle |
| :----------------: | :-----: | :----------: | :--------: |
| Main Instructor | Garrett Nicolai |    `@garrett nicolai`       | `@gnicolai`        |
| Lab Instructor | Jungyeul Park |    `@jungyeul`       | `@jungyeul` |
| Teaching Assistant | Yadong Liu |    `@Yadong Liu`       | `@yadliu`        |


## Lecture Details


| Lecture | Topic | Readings or Materials|
|:-------:|-------|--------------|         
| 1 | Course Intro.; Sentiment Analysis Task | xxxx  |
| 2 | Methods: Classical Methods, BERT | xxxx  |

| 3 | Social Meaning (Emotion); Data Labeling | xxxx  |
| 4 | Methods: LLMs, CoT, Prompting, Instruction Finetuning | xxxx  |

| 5 | LLM Agents I, Sentiment Explanations | xxxx  |
| 6 | LLM Agents II, Low-Resource SA | xxxx  |

| 7 | RAG | xxxx  |


| 2 | Classification with Polarity Lexicons| LMSA, 2.1-2.7 | 
| 3 | Machine Learning for Sentiment Analysis | Jacovi et al 2017, Jiang et al. 2011 (section 4), Deng et al. 2014 (Sections 2 + 3)|
| 4 | Emotion, Personality, and Author Profiling | J&M 21.1, J&M 21.7-21.8, EmoNet, Schwartz et al |
| 5 | Relevance (Subjectivity, Targets, and Aspects) | StanfordSA, MPQA, GATE setup, SOAM 4.1, SAOM 5.1-5.3 | 
| 6 | Challenges in Sentiment Analysis | SAOM 4.4, SAOM 3.6, SAOM 11, SOAM 12, SVM Rank, AMAS,Ghosh and Veale |                        
| 7 | Tracking sentiment in space and time  |Cloroplaths, datetime|
| 8 | Challenges for NLP in social media | Langid paper, ekphrasis |



| Lecture | Topic | Readings or Materials|
|:-------:|-------|--------------|         
| 1 | Polarity Lexicons| J&M 21.2-21.6  |
| 2 | Classification with Polarity Lexicons| LMSA, 2.1-2.7 | 
| 3 | Machine Learning for Sentiment Analysis | Jacovi et al 2017, Jiang et al. 2011 (section 4), Deng et al. 2014 (Sections 2 + 3)|
| 4 | Emotion, Personality, and Author Profiling | J&M 21.1, J&M 21.7-21.8, EmoNet, Schwartz et al |
| 5 | Relevance (Subjectivity, Targets, and Aspects) | StanfordSA, MPQA, GATE setup, SOAM 4.1, SAOM 5.1-5.3 | 
| 6 | Challenges in Sentiment Analysis | SAOM 4.4, SAOM 3.6, SAOM 11, SOAM 12, SVM Rank, AMAS,Ghosh and Veale |                        
| 7 | Tracking sentiment in space and time  |Cloroplaths, datetime|
| 8 | Challenges for NLP in social media | Langid paper, ekphrasis | 


## Resources


1. [Speech and Language Processing, 3rd edition](https://web.stanford.edu/~jurafsky/slp3/) (J&M)
2. [Lexicon-based methods for Sentiment Analysis](https://www.mitpressjournals.org/doi/pdfplus/10.1162/COLI_a_00049) (LMSA)
3. [Sentiment Analysis and Opinion Mining](https://www.cs.uic.edu/~liub/FBS/SentimentAnalysis-and-OpinionMining.pdf) (SAOM)
4. NLTK howtos for [WordNet](https://www.nltk.org/howto/wordnet.html) and [SentiWordNet](http://www.nltk.org/howto/logic.html).
5. [Stanford Sentiment Treebank](https://nlp.stanford.edu/sentiment/treebank.html) (StanfordSA)
6. [MPQA corpus and associated documentation](http://mpqa.cs.pitt.edu/corpora/mpqa_corpus/) (MPQA)
7. [GATE setup for MPQA](http://mpqa.cs.pitt.edu/annotation/set_up_gate/)
8. [Understanding Convolutional Neural Networks for Text Classification (Jacovi et al 2017)](https://arxiv.org/pdf/1809.08037.pdf)
8. [Target-dependent Twitter Sentiment Classification (Jiang et al. 2011)](https://www.aclweb.org/anthology/P11-1016.pdf)
9. [Adaptive Recursive Neural Network
for Target-dependent Twitter Sentiment Classification (Deng et al. 2014)](https://www.aclweb.org/anthology/P14-2009.pdf)
10. [SVM Rank](http://www.cs.cornell.edu/people/tj/publications/joachims_02c.pdf)
11. [Argument Mining: A Survey (AMAS)](https://www.mitpressjournals.org/doi/pdf/10.1162/coli_a_00364)
12. [Magnets for Sarcasm (Ghosh and Veale)](https://www.aclweb.org/anthology/D17-1050.pdf)
13. [EmoNet (Abdul-Mageed and Ungar)](https://www.aclweb.org/anthology/P17-1067.pdf)
14. [Personality, Gender, and Age in the Language of Social Media (Schwartz et al)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0073791)
15. [Computational Sociolinguistics](https://www.mitpressjournals.org/doi/full/10.1162/COLI_a_00258)
16. [The Risk of Racial Bias in Hate Speech Detection (Sap et al.)](https://www.aclweb.org/anthology/P19-1163.pdf)
17. [Cloroplaths in Plotly](https://plot.ly/python/choropleth-maps/)
18. [the datetime library](https://docs.python.org/3/library/datetime.html)
19. [Langid paper](https://www.aclweb.org/anthology/P12-3005.pdf)
20. [ekphrasis package](https://github.com/cbaziotis/ekphrasis)
21. [Twitter POS tagger](http://www.cs.cmu.edu/~ark/TweetNLP/#pos)

## Policies

Please see the general [MDS policies](https://ubc-mds.github.io/policies/).
