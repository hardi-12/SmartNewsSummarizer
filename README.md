# Smart News Summarizer

## Introduction
We tend to read multiple news articles on a daily basis but a certain news topic may not contain 
all the relevant information. We can have an insightful information out of the comprehensive 
articles that will help us save a lot of time and energy. Text summarization is a way of minimizing 
a textual document to a meaningful summary by preserving its information content and the overall 
meaning. Here an extractive based multi-document summary is presented to summarize news 
articles from different news sites which describe about the same topic. This will help us enhance 
the readability of a particular news article without missing any important points. The first-level 
summary generates the summary of each article on the topics. Sentiment Analysis is performed on 
the first-level summary to understand the variation in related news articles. The second level 
summary generates the summary of the combined first-level summaries of two or more related 
articles on a topic. The situation is even worse for the people who are visually impaired or have 
lost their ability to see. The inability of these people to read text has a huge impact on their lives. 
There are a number of methods for blind people to read text. So, we present a method for visually 
impaired people based on the sense of sound which is obviously better and more accurate than the 
sense of touch. We can have an insightful information out of the comprehensive articles that will 
help us save a lot of time and energy. 

## Summarization Process
![Block Diagram](https://user-images.githubusercontent.com/58966938/142477207-a9d9a4ce-d351-474d-a34a-8b769013e97c.jpg)

## Libraries to be used
**1. NumPy:** NumPy is a library for the Python programming language, adding support for 
large, multi-dimensional arrays and matrices, along with a large collection of high-level 
mathematical functions to operate on these arrays.
**2. Nltk:** The Natural Language Toolkit, or more commonly NLTK, is a suite of libraries and 
programs for symbolic and statistical natural language processing for English written in 
the Python programming language.
**3. Re:** The Python module re provides full support for Perl-like regular expressions in Python.
The re module raises the exception re.error if an error occurs while compiling or using a 
regular expression.
**4. TextBlob:** It is an open-source python library for processing textual data. It performs 
different operations on textual data such as noun phrase extraction, sentiment analysis, 
classification, translation.
**5. Gensim:** It is an open-source library for unsupervised topic modeling and natural language 
processing, using modern statistical machine learning. Gensim is implemented in Python 
and Cython for performance 
19
**6. Sciket-learn:** Scikit-learn is a free machine learning library for Python. It features various 
algorithms like support vector machine, random forests, and k-neighbours, and it also 
supports Python numerical and scientific libraries like NumPy and SciPy .
**7. Pattern:** Pattern is an open-source python library and performs different NLP tasks. It is 
mostly used for text processing due to various functionalities it provides. Other than text 
processing Pattern is used for Data Mining
**8. Cython:** It is a programming language that aims to be a superset of the Python 
programming language, designed to give C-like performance with code that is written 
mostly in Python with optional additional C-inspired syntax. Cython is a NumFOCUS 
affiliated project.
**9. Heapq:** In Python, it is available using “heapq” module. The property of this data structure 
in Python is that each time the smallest of heap element is popped(min heap). Whenever 
elements are pushed or popped, heap structure in maintained. The heap[0] element also 
returns the smallest element each time.
**10. gTTs:** gTTs (Google Text-to-Speech) is a Python library and CLI tool to interface with 
Google Translate text-to-speech API. We will import the gTTs library from the gTTs
module which can be used for speech translation. The text variable is a string used to store 
the user's input.

