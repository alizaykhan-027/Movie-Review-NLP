# *Movie Reviews Analysis Project*  

This repository contains a comprehensive analysis of movie reviews using various Natural Language Processing (NLP) techniques and models. The workflow includes exploratory data analysis, sentiment classification using both traditional and deep learning models, and topic modeling with BERTopic to discover themes and genres.

---

## *Table of Contents*  
1. [Introduction](#introduction)  
2. [Datasets](#datasets)  
3. [Project Workflow](#project-workflow)  
    - [EDA](#1-exploratory-data-analysis-eda)  
    - [Sentiment Classification](#2-sentiment-classification)  
    - [Topic Modeling](#3-topic-modeling)  
5. [Results](#results)  
---

## *Introduction*  
This project aims to analyze movie reviews, extract meaningful insights, classify sentiments, and assign genres to reviews. 

---

## *Datasets*  
- *Dataset:* A dataset of 50k imdb movie reviews, containing columns for review text and corresponding sentiment labels (positive/negative).  
- *Preprocessing:* Cleaned and tokenized the data for analysis.  

---

## *Project Workflow*  

### *1. Exploratory Data Analysis (EDA)*  
- Conducted an initial analysis of the dataset to understand its structure, distribution, and patterns.  
- Visualized sentiment distribution and word frequencies.  

File: Dataset_analysis.ipynb  

---

### *2. Sentiment Classification*  

#### *Traditional Machine Learning Models*  
- Implemented models like Naive Bayes, Logistic Regression  
- Evaluated their performance using accuracy and F1-score.  

File: training_traditional_machine_learning_model.ipynb  

#### *Deep Learning Models*  
- Built models using LSTM sentiment classification.  
  

File: training_deep_learning_model.ipynb  

---

### *3. Topic Modeling*  
- Used BERTopic to identify and name topics within reviews.  
- Mapped topics to genres such as Horror, Comedy, Drama, etc.  
- Visualized the distribution of topics and analyzed genre-wise reviews.  

File: topic_modeling.ipynb  
---
## *Results*  
1. *Sentiment Analysis:*  
   - Achieved X% accuracy with traditional models.  
   - Achieved Y% accuracy with deep learning models.  

2. *Topic Modeling:*  
   - Identified and visualized key topics and mapped them to genres.  
   - sorted best and worst reviews by genre.  
