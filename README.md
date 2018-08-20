# health-wellness-NLP-project

## Overview
This text analytics project scrapes articles about a topic of interest from vetted sources on the web and presents a concise summary of the most important points from the conglomerate of articles, along with the most frequent words.  While the code presented here can be applied to articles on any topic, the goal of this project is to extract key information from the abundance of health and wellness information available online.  Doing so efficiently and accurately encourages awareness of different health issues and solutions, promotes preventative healthcare, and delivers more focused health information.

## Prerequisites
The code was written in Python 2.7 and the following Python packages are required:<br>
bs4 - BeautifulSoup, used for web scraping<br>
nltk - natural language toolkit<br>
networkx - builds a network graph, includes PageRank function<br>
gensim - for topic modeling with LDA

## How to run
The repository includes the links text file, which is the input for 'Text Extraction with BeautifulSoup'.  The output is the corpus_cleaned text file, which is also the input to 'TextRank Summmary'.  The links file is curated by the user to ensure the sources are reliable.

## References
@davidadamojr repo link: https://github.com/davidadamojr/TextRank/blob/master/textrank/__init__.py <br>
TextRank: Bringing Order into Texts - R. Mihalcea and P. Tarau (2004)
https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/
