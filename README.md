# Atelier1_NLP
# My Scraping and NLP Pipeline Lab Report

## Objective:
The main goal of this lab was to gain hands-on experience with web scraping techniques and constructing a Natural Language Processing (NLP) Pipeline. Throughout this project, I aimed to extract data from Arabic web sources related to a specific domain, here are the links i used :
'https://www.bbc.com/arabic/articles/cd191zxrx5zo'
'https://www.bbc.com/arabic/articles/cg3q3q3zjd0o'
'https://www.bbc.com/arabic/articles/c876zz8rpp8o' ,i store it in a MongoDB database, and then apply various NLP techniques including text cleaning, tokenization, stop words removal, discretization, normalization, stemming, lemmatization, parts of speech tagging, and named entity recognition (NER). Additionally, I sought to compare the effects of different mechanisms such as stemming and lemmatization on the processed text.

## Work Done:
1. **Scraping:** I utilized libraries like  Beautiful Soup to scrape data from Arabic web sources pertaining to the specified domain.
2. **Data Storage:** The raw data was stored in a NoSQL database, MongoDB, for easy access and retrieval, using pymongo
3. **NLP Pipeline Establishment:** I constructed a comprehensive NLP Pipeline, which included:
    - Text Cleaning
    - Tokenization
    - Stop Words Removal
    - Discretization
    - Normalization
4. **Stemming and Lemmatization:** I implemented both stemming and lemmatization techniques on the text data and compared their effects on the processed text.
5. **Parts of Speech Techniques:** I applied parts of speech tagging using  rule-based but as for machine learning approaches, spacy isnt really well adapted for Arabic language.
6. **Named Entity Recognition (NER) Methods:** I employed NER methods to identify and categorize named entities within the text.

## Notes:
- At the conclusion of the lab, I provided a brief synthesis summarizing my learnings from the proposed activities.
- All of my work has been pushed to the GitHub repository.


## Tools Used:
- Kaggle / jupyter for collaborative coding environment
- GitLab/GitHub for version control and collaboration
- Farasa (pip install farasapy) and NLTK for NLP processing
