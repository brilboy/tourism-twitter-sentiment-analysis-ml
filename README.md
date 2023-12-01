# Study of Perceptions and Desires to Travel in Bali: Twitter Big Data Analysis

## Overview
This GitHub repository contains the code and analysis for a study focused on understanding perceptions and desires related to travel in Bali during the transition from the COVID-19 pandemic to the endemic phase. The analysis is based on Twitter big data, and machine learning techniques were employed to gain insights from the collected data.

## Key Features
- Utilized machine learning models such as Random Forest, Support Vector Machine, and CART Decision Tree to predict Twitter data trends.
- Evaluated model performance using accuracy and F1 score metrics.
- Applied RandomizedSearchCV to optimize the models, employing differentiated hyperparameters for each model.
- Identified Support Vector Machine as the best-performing model, achieving 79% accuracy and an 87% F1 score.
- Visualized data characteristics using Seaborn and Matplotlib libraries.

## Data Collection
- Utilized the Selenium library to scrape 81,000+ tweets from Twitter.
- Data collection spanned from November 1, 2021, to November 31, 2022.
- Conducted thorough data cleansing using Python, resulting in 60,000+ cleaned tweets.
- Implemented cleaning processes, including the removal of news-related tweets, duplicate entries, bot-generated tweets, stopwords, and lemmatization.

## Data Labeling and Visualization
- Labeled 12% of the cleaned data to facilitate sentiment analysis and categorization of willingness to visit Bali.
- Utilized WordCloud visualizations to showcase sentiment categories (positive, neutral, negative) and visitation categories (visit, not visit).

## Getting Started
To replicate the study and explore the findings, follow these steps:

Clone the repository:

   ```bash
   git clone https://github.com/brilboy/tourism-twitter-sentiment-analysis-ml.git
   ```

## Libraries and Tools
- Python 3.x
- Selenium
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- WordCloud

## Acknowledgments
We would like to express our gratitude to the open-source community and the developers of the libraries used in this study. Contributions and feedback are welcome to enhance the quality and scope of this research.
