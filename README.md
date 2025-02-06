# COLX 565: Sentiment Analysis

## Course Description

_Sentiment analysis_ in Natural Language Processing (NLP) and Computational Linguistics (CL) involves identifying and analyzing polarity—positive, negative, neutral, or mixed—within text. This course provides a structured introduction to sentiment analysis methods, situating it within _social meaning_. The course covers mostly appplications of modern deep learning methods with a focus on large language models (LLMs),  combining lectures with hands-on lab sessions to ensure a balance between theoretical understanding and practical implementation.

__Slack Channel__: cl-565_sentiment

## Course Learning Outcomes  

Upon completing this course, students will achieve the following learning outcomes:  

### 1. _Become familiar with_ the foundations of sociopragmatic meaning with a focus on sentiment analysis  
Students will develop an understanding of the relationship between **sociopragmatic meaning** and **sentiment analysis** in natural language processing. This includes:  
- defining **sociopragmatics** and understanding its role in **sentiment and emotion analysis**.  
- distinguishing between **sentiment, emotion, and opinion mining** in computational linguistics.  
- identifying key **datasets and evaluation metrics** for sentiment analysis.  
- recognizing how **culture, domain, and context** influence sentiment expression.  

### 2. _Apply_ classical methods and large language models (llms) for sociopragmatics  
Students will gain hands-on experience with both **classical NLP approaches** and **large language models (LLMs)** for sentiment analysis. This includes:  
- implementing **traditional machine learning classifiers** (e.g., Naïve Bayes, SVM, Logistic Regression) for sentiment tasks.  
- utilizing **word embeddings** (e.g., Word2Vec, GloVe) and **contextual embeddings** (e.g., BERT, RoBERTa) for improved sentiment representation.  
- fine-tuning **transformer-based LLMs** for **sentiment classification and sociopragmatic tasks**.  
- comparing and evaluating **the effectiveness, biases, and limitations** of different NLP techniques in sentiment analysis.  

### 3. _Design_ real-world sociopragmatics systems using llms and agentic workflows  
Students will explore how **LLMs and AI agents** can be used to build **real-world sentiment analysis applications**. This includes:  
- designing **LLM-powered systems** that process sentiment from real-world data sources (e.g., social media, customer reviews, financial news).  
- utilizing **prompt engineering and Chain-of-Thought (CoT) reasoning** to enhance LLM-based sentiment predictions.  
- developing **agentic workflows** where LLMs collaborate with external tools for sentiment classification.  
- addressing **real-time processing challenges** such as **sentiment drift, domain adaptation, and multilingual variations**.  

### 4. _Enhance_ text classification with explainability and retrieval-augmented models  
Students will learn to improve sentiment analysis models using **explainability techniques** and **retrieval-augmented generation (RAG)**. This includes:  
- implementing **explainability methods** (e.g., SHAP, LIME, attention visualization) to interpret sentiment predictions.  
- applying **RAG-based models** to incorporate external knowledge in sentiment classification.  
- exploring **hybrid sentiment analysis models** that combine **retrieval-based and generative AI**.  
- evaluating how **interpretability and retrieval mechanisms** improve model trustworthiness and fairness.  

### 5. _Critically evaluate_ societal considerations in text classification  
Students will engage in critical discussions on the **ethical and societal implications** of sentiment analysis. This includes:  
- identifying **bias and fairness issues** in sentiment analysis models and datasets.  
- assessing the **impact of sentiment models in multilingual and low-resource settings**.  
- discussing the **potential risks and misuse** of sentiment classification (e.g., misinformation, opinion manipulation).  
- analyzing the **environmental impact of large-scale NLP models** and strategies for sustainable AI.  

---


## Meeting times / locations

This is a live presentation class.  Students are expected to attend lectures when possible.  Recordings will be available, but should be used as a study tool
instead of a primary method of learning the material.

Classes meet Tuesday and Thursday at 9:30 a.m. - 11:00 am, in MCLD 3018.
Labs are Tuesday from 2-6 p.m., in ORCH 4018.
 

## Attendance

The MDS-CL is an *in-person* program - you are expected to attend classes and labs.  There will be no recordings of lectures.  Interaction in class has been shown to improve understanding, and collaborative environments improve learning.

Attendance will be taken with iClicker.  To receive full marks, you must attend 6 of 8 classes.  Attendance in fewer classes than these will result in a grade of 0 for attendance.  I understand that illness and emergencies happen (if you are ill, please do not come to class). 


## Assessments

This is both an __assignment- and project-based course__. You'll be evaluated as follows:

# Course Assessment Structure

| Assessment                             | Weight  | Due Date         | Submission Location |
|----------------------------------------|---------|------------------|---------------------|
| **Lab Practice 1**                     | 16%     | Feb 15, 11:59pm  | Submit to GitHub   |
| **Lab Practice 2**                     | 16%     | Mar 1, 11:59pm   | Submit to GitHub   |
| **Short Reflection 1**                  | 6%      | Mar 5, 11:59pm   | Submit to GitHub   |
| **Lab Practice 3 + Project Milestone 1** | 24%     | Mar 8, 11:59pm   | Online   |
| **Short Reflection 2**                  | 6%      | Mar 10, 11:59pm  | Submit to GitHub   |
| **Lab Practice 4 + Project Milestone 2** | 24%     | Mar 15 | Online |
| **Engagement & Participation**          | 8%      | Ongoing             | In-Class: iClicker + Discussions |



## Teaching Team

| Position           | Name    | Slack Handle | GHE Handle |
| :----------------: | :-----: | :----------: | :--------: |
| Main Instructor | Muhammad Abdul-Mageed |    `@Muhammad Mageed`       | `@amuham01`        |
| Lab Instructor | Jungyeul Park |    `@jungyeul`       | `@jungyeul` |
| Teaching Assistant | Yadong Liu |    `@Yadong Liu`       | `@yadliu`        |


## Lecture Details


| Lecture | Topic | Readings or Materials|
|:-------:|-------|--------------|         
| 1 | Course Intro., Sentiment Task | xxxx  |
| 2 | Classical Methods | xxxx  |
| 3 | Social Meaning (e.g., emotion, toxic language) | xxxx  |
| 4 | BERT, LLMs, CoT, Prompting, Instruction Finetuning | xxxx  |
| 5 | Real-World Sentiment: LLM Agents I | xxxx  |
| 6 | Real-World Sentiment: LLM Agents II| xxxx  |
| 7 | Real-World Sentiment: Sentiment Explanation, RAG | xxxx  |
| 8 | Societal Considerations: Low-Resource and Multilingual, Bias, Energy |


## Resources


1. [Speech and Language Processing, 3rd edition](https://web.stanford.edu/~jurafsky/slp3/) (J&M)
2. [Lexicon-based methods for Sentiment Analysis](https://www.mitpressjournals.org/doi/pdfplus/10.1162/COLI_a_00049) (LMSA)
3. [Sentiment Analysis and Opinion Mining](https://www.cs.uic.edu/~liub/FBS/SentimentAnalysis-and-OpinionMining.pdf) (SAOM)
4. [Modeling Arabic subjectivity and sentiment in lexical space](xyz)(ArabicSSA)
5. [EmoNet (Abdul-Mageed and Ungar)](https://www.aclweb.org/anthology/P17-1067.pdf)(EmoNet)
6. NLTK howtos for [WordNet](https://www.nltk.org/howto/wordnet.html) and [SentiWordNet](http://www.nltk.org/howto/logic.html).
7. [Stanford Sentiment Treebank](https://nlp.stanford.edu/sentiment/treebank.html) (StanfordSA)
8. [MPQA corpus and associated documentation](http://mpqa.cs.pitt.edu/corpora/mpqa_corpus/) (MPQA)
9. [GATE setup for MPQA](http://mpqa.cs.pitt.edu/annotation/set_up_gate/)
10. [Understanding Convolutional Neural Networks for Text Classification (Jacovi et al 2017)](https://arxiv.org/pdf/1809.08037.pdf)
11. [Target-dependent Twitter Sentiment Classification (Jiang et al. 2011)](https://www.aclweb.org/anthology/P11-1016.pdf)
12. [Adaptive Recursive Neural Network
for Target-dependent Twitter Sentiment Classification (Deng et al. 2014)](https://www.aclweb.org/anthology/P14-2009.pdf)
13. [SVM Rank](http://www.cs.cornell.edu/people/tj/publications/joachims_02c.pdf)
14. [Argument Mining: A Survey (AMAS)](https://www.mitpressjournals.org/doi/pdf/10.1162/coli_a_00364)
15. [Magnets for Sarcasm (Ghosh and Veale)](https://www.aclweb.org/anthology/D17-1050.pdf)
16. [Personality, Gender, and Age in the Language of Social Media (Schwartz et al)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0073791)
17. [Computational Sociolinguistics](https://www.mitpressjournals.org/doi/full/10.1162/COLI_a_00258)
18. [The Risk of Racial Bias in Hate Speech Detection (Sap et al.)](https://www.aclweb.org/anthology/P19-1163.pdf)
19. [Cloroplaths in Plotly](https://plot.ly/python/choropleth-maps/)
20. [the datetime library](https://docs.python.org/3/library/datetime.html)
21. [Langid paper](https://www.aclweb.org/anthology/P12-3005.pdf)
22. [ekphrasis package](https://github.com/cbaziotis/ekphrasis)
23. [Twitter POS tagger](http://www.cs.cmu.edu/~ark/TweetNLP/#pos)



## Policies

Please see the general [MDS policies](https://ubc-mds.github.io/policies/).

**Acknowledgements:** Many of the readings are from a previous course by Dr. Garrett Nicolai. 
