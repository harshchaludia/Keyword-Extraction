# Keyword-Extraction :
Implementation of Keyword Extraction using NLTK Library

# Implementation :
1) Tokenizing the extract.
2) Lemmatization (to find also keywords that appear in different forms).
3) Removing stopwords.
4) For every term in the current extract compute the term frequency (how many times the term occurs in the extract)
5) Each word scores are caclulated by dividing degree of the word by its frequency.
6) For every term in the current document, and every document in the set, compute the tf-idf:
7) The phrase scores are calculated by adding individual scores of each of the words which form the members of the phrase. 
8) The top n highest scoring candidate keywords are presented as the final exctracted keywords for the system. 

# Tools & Technologies used :
Python Compiler, NLTK Library & Jupyter Notebook
