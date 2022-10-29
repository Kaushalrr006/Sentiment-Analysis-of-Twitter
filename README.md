# Sentiment-Analysis-of-Twitter
Hate Speech is a widespread problem that degrades a person or people based on their race, religion, gender or disability. 


INTRODUCTION

The exponential growth of social media such as Twitter and
community forums has revolutionized communication and
content publishing, but is also increasingly exploited for the
propagation of hate speech and the organization of hate-based
activities. The anonymity and mobility afforded by such
media has made the breeding and spread of hate speech –
eventually leading to hate crime – effortless in a virtual landscape
beyond the realms of traditional law enforcement. The
term ‘hate speech’ was formally defined as ‘any
communication that disparages a person or a group on the
basis of some characteristics (to be referred to as types of hate
or hate classes) such as race, color, ethnicity, gender, sexual
orientation, nationality, religion, or other characteristics. In
the UK, there has been significant increase of hate speech
towards the migrant and Muslim communities following
recent events including leaving the EU, the Manchester and
the London attacks. In the EU, surveys and reports focusing
on young people in the EEA (European Economic Area)
region show rising hate speech and related crimes based on
religious beliefs, ethnicity, sexual orientation or gender, as
80% of respondents have encountered hate speech online and
40% felt attacked or threatened. Statistics also show that in
the US, hate speech and crime is on the rise since the Trump
election. The urgency of this matter has been increasingly
recognized, as a range of international initiatives have been
launched towards the qualification of the problems and the
development of counter-measures. Building effective counter
measures for online hate speech requires as the first step,
identifying and tracking hate speech online. For years, social
media companies such as Twitter, Facebook, and YouTube
have been investing hundreds of millions of euros every year
on this task, but are still being criticized for not doing enough.
This is largely because such efforts are primarily based on
manual moderation to identify and delete offensive materials.


METHODOLOGY

Machine Learning:
A. Dataset
In this study, we have used publicly available data set of
tweets from various accounts on various topics. This dataset
contains about 1048576 tweets. In this study, we will only
focus on the hateful, positive as well as the neutral tweets. In
this dataset, the tweets can be categorized on the basis of
aspects and their polarities. For making the dataset easy for
classification, different columns are present. There are five
columns ['target', 't_id', 'created_at', 'user', 'text']. The
unwanted columns are removed as they might affect the
prediction results. The dataset is trained and tested after the
dataset is uploaded successfully. Further, their polarities can
be positive, negative, or neutral.
B. Logistic regression:
Logistic regression is a statistical analysis method used to
predict a data value based on prior observations of a data set.
Logistic regression has become an important tool in the
discipline of machine learning. The approach allows an
algorithm being used in a machine learning application to
classify incoming data based on historical data. As more
relevant data comes in, the algorithm should get better at
predicting classifications within data sets. Logistic regression
is a very appropriate model to do hate speech detection
because it is very tricky for any model or even humans to
classify weather the text is hateful or not. Ergo, as logistic
works on historical data and trains itself, it gives very accurate
results when tested.
C. NLTK:
The Natural Language Toolkit, or more commonly NLTK, is
a suite of libraries and programs for symbolic and statistical
natural language processing (NLP) for English written in the
Python programming language. NLTK includes graphical
demonstrations and sample data. NLTK is intended to support
research and teaching in NLP or closely related areas,
including empirical linguistics, cognitive science, artificial
intelligence, information retrieval, and machine learning.
D. Sklearn:
Scikit-learn is a free software machine learning library for the
Python programming language. It features various
classification, regression and clustering algorithms including
support vector machines, random forests, gradient boosting,
and is designed to interoperate with the Python numerical and
scientific libraries NumPy and SciPy.

E. Accuracy
The classifier performance is evaluated by calculating true
positives (TP), false positives (FP), true negatives (TN), and
false negatives (FN). These four numbers constitute a
confusion matrix. This evaluation refers to the total number
of instances that are correctly classified by the trained model.
Real time tweets twitter analysis:
A. Textblob
TextBlob is a python library for Natural Language Processing
(NLP).TextBlob actively used Natural Language ToolKit
(NLTK) to achieve its tasks. NLTK is a library which gives
an easy access to a lot of lexical resources and allows users to
work with categorization, classification and many other tasks.
TextBlob is a simple library which supports complex analysis
and operations on textual data. TextBlob is a Python library
for processing textual data. It provides a simple API for diving
into common natural language processing (NLP) tasks such
as part-of-speech tagging, noun phrase extraction, sentiment
analysis, classification, translation, and more.
B. Tweepy
Tweepy is an open-source Python package that gives you a
very convenient way to access the Twitter API with Python.
Tweepy includes a set of classes and methods that represent
Twitter’s models and API endpoints, and it transparently
handles various implementation details. By using Tweepy,
you could deal with low-level details having to do with
requests, data serialization, authentication, and rate limits.
This will reduce the time consumption and error. Tweepy also
supports OAuth 2 authentication. OAuth 2 is a method of
authentication where an application makes API requests
without the user context. Use this method if you just need
read-only access to public information.

