****** Inverted Index and Boolean Search ********

This is a python program which builds inverted index from the docx files in /data folder. And it would return doc ID against the 
boolean retrival queries

Stemmer used - Porter Stemmer from NLTK package
Lemmantizer - NLTK package based Lemmantizer
Tokenizer - NLTK based Tokenizer

This program does the following work - 

1. Builds an inverted index from data files in /data folder and saves the index in index.docx file in the same workng directory

2. Returns document IDs for Boolean queries.
Query format - ( term1 op term2 )
Operators - and, or, not (all lower case)

Short Flow of events - 

1. From the given path of input docs, generate the Inverted index and store it in a data structure.
Also store it in a file index.docx.

2. Take the input query from the user in format - ( term op term ).

3. Show the list of doc ID which contain the term

Test Queries and output - test.txt
