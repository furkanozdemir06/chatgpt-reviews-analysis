# ChatGPT Reviews Analysis

This repository contains a Data Science and Sentiment Analysis project on user reviews of ChatGPT using Python and Jupyter Notebook.

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Architecture & Workflow](#project-architecture--workflow)
- [Technologies & Libraries Used](#technologies--libraries-used)
- [Key Analysis & Findings](#key-analysis--findings)
- [How to Run](#how-to-run)

---

## 🎯 Overview
The primary goal of this project is to analyze user feedback and ratings for the ChatGPT application from the Google Play Store dataset (`chatgpt_reviews.csv`). The analysis covers data cleaning, exploratory data analysis (EDA), rating distribution, sentiment trends over time, and text analysis of customer feedback.

---

## 📊 Dataset
- **File Name:** `chatgpt_reviews.csv`
- **Description:** Contains user reviews, star ratings, review dates, user locations, and helpfulness votes for ChatGPT.
- **Key Columns:**
  - `review`: Text content of the user review.
  - `rating`: Star rating given by the user (1 to 5).
  - `date` / `review_date`: Timestamp of the review submission.
  - `thumbs_up`: Number of users who found the review helpful.

---

## 🛠️ Project Architecture & Workflow

1. **Data Loading & Preprocessing:**
   - Loading `chatgpt_reviews.csv` into a Pandas DataFrame.
   - Handling missing values and null entries in text and ratings.
   - Parsing dates into standard datetime formats.

2. **Exploratory Data Analysis (EDA):**
   - Statistical summary of ratings and review lengths.
   - Distribution of star ratings (1 to 5 stars).
   - Trend analysis: Review volume and average rating over time.

3. **Text Processing & Sentiment Analysis:**
   - Text cleaning (tokenization, removing stopwords, lowercasing, removing special characters).
   - Sentiment classification (Positive, Neutral, Negative).
   - Extracting frequent words and n-grams from top positive and negative reviews.

4. **Data Visualization:**
   - Bar charts for rating distributions.
   - Line plots for temporal trends.
   - Word clouds / frequency charts for key user feedback themes.

---

## 🧰 Technologies & Libraries Used
- **Python 3.x**
- **Jupyter Notebook / Google Colab**
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical calculations.
- **Matplotlib & Seaborn:** Data visualization and plot styling.
- **NLTK / SpaCy:** Natural Language Processing (NLP) for text preprocessing.
