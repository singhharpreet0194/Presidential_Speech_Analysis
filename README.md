# Inaugural Speech Analysis Project

## Introduction

🎙️ This project focuses on analyzing inaugural speeches from Presidents of the United States. Specifically, we'll be examining speeches by President Franklin D. Roosevelt in 1941, President John F. Kennedy in 1961, and President Richard Nixon in 1973 using Python and the NLTK library.

## Project Files

📁 [Business Report - Ensemble.pdf](Business+Report_ensemble2.pdf)

📁 [Jupyter Notebook: Project_ensemble_2.ipynb](Project_ensemble_2.ipynb)

## Project Steps

### 2.1 Character, Word, and Sentence Counts

- Find the number of characters, words, and sentences for each of the three speeches.

### 2.2 Removing Stopwords

- Remove all stopwords from the three speeches.

### 2.3 Most Occurring Words

- Identify the most frequently occurring word in the inaugural address for each president after removing stopwords. Mention the top three words.

### 2.4 Word Clouds

- Plot word clouds for each speech after removing stopwords.

## Code Snippet for Speech Extraction

```python
import nltk
nltk.download('inaugural')
from nltk.corpus import inaugural

# Extract speeches
inaugural.fileids()
inaugural.raw('1941-Roosevelt.txt')
inaugural.raw('1961-Kennedy.txt')
inaugural.raw('1973-Nixon.txt')
