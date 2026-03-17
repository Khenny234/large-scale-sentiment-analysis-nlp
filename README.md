# Large-Scale Sentiment Analysis and Predictive Modelling Framework

## Overview

This project presents the design and implementation of a large-scale Natural Language Processing (NLP) and predictive modelling framework for analysing Amazon Fine Food Reviews.

The system processes over **568,000 customer reviews**, transforming unstructured text into structured sentiment insights and predictive outputs. It combines text preprocessing, feature engineering, multi-model benchmarking, and business intelligence delivery to support sentiment monitoring and data-driven decision-making.

## Objectives

- Build an end-to-end NLP pipeline for large-scale sentiment analysis
- Benchmark multiple machine learning and deep learning models
- Evaluate model performance using structured metrics
- Deliver insights through an interactive Power BI dashboard

## Dataset

The project uses the **Amazon Fine Food Reviews** dataset, containing over **568,000 reviews** with associated metadata and review scores.

## Workflow

The project pipeline consists of the following stages:

1. **Data Ingestion**
   - Load and inspect review data
   - Handle missing values and duplicates

2. **Text Preprocessing**
   - Lowercasing
   - HTML and punctuation removal
   - Tokenisation
   - Stopword removal
   - Lemmatisation

3. **Feature Engineering**
   - TF-IDF vectorisation
   - CountVectorizer
   - Topic modelling with LDA

4. **Sentiment Analysis**
   - VADER sentiment scoring
   - Sentiment categorisation into positive, negative, and neutral

5. **Model Development**
   - Multinomial Naive Bayes
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
   - LSTM
   - Temporal Convolutional Network (TCN)
   - Hybrid Model

6. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Comparative model ranking

7. **Analytics Delivery**
   - Power BI dashboard for sentiment monitoring and trend analysis

## Model Performance

The framework benchmarked seven models with the following overall accuracy scores:

| Model | Accuracy |
|------|----------|
| Random Forest | 0.98 |
| SVM | 0.97 |
| TCN | 0.96 |
| Logistic Regression | 0.95 |
| Multinomial Naive Bayes | 0.93 |
| Hybrid Model | 0.91 |
| LSTM | 0.88 |

The **Random Forest model** achieved the best overall performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Power BI

## Project Outputs

This project includes:

- NLP preprocessing and sentiment analysis notebook
- model benchmarking results
- clean visualisations for model comparison
- system architecture diagram
- Power BI dashboard screenshot / report

## Key Contribution

I led the end-to-end design and implementation of this framework, including:

- defining the analytical approach
- engineering the preprocessing pipeline
- building and benchmarking multiple models
- integrating predictive outputs into a stakeholder-facing analytics dashboard

## Business Relevance

This project demonstrates how large-scale unstructured customer feedback can be transformed into structured business intelligence. The solution is directly applicable to digital platforms, e-commerce, and customer insight teams seeking to improve product quality, customer experience, and decision-making through sentiment analytics.

## Repository Structure

```text
project/
│
├── Final Thesis Analysis.ipynb
├── Final Thesis Analysis.pdf
├── Kenny power bi.pdf
├── architecture.png
├── model_accuracy_clean.png
├── model_ranking.png
└── README.md
