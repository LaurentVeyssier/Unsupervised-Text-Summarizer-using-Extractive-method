# Unsupervised-Text-Summarizer
This module summarizes any text using extractive summarization, an unsupervised technique.

## Description
The notebook takes any text file as input and summarize using extrative technique.
Sentences for the document are ranked against each other in terms of similarity. Using TextRank, top pages are then extracted to form the summary capturing most of the content of the text file.

TextRank is an extractive and unsupervised text summarization technique:
![](asset/TextRank.png)

The notebook manages French accentuated characters.

## How to use
- download and run the notebook
- place your text files into the same folder
- text files must be continuous (no back space).

## Results

input document :

![](asset/input.PNG)

Generated summary with 5 sentences target :

![](asset/output.PNG)
