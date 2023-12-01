# Study of Perceptions and Desires to Travel in Bali: Twitter Big Data Analysis

## Overview
This GitHub repository contains the code and analysis for a study focused on understanding perceptions and desires related to travel in Bali during the transition from the COVID-19 pandemic to the endemic phase. The analysis is based on Twitter big data, and machine learning techniques were employed to gain insights from the collected data.

## Contribution to Society

This project holds significant value for society in multiple ways:

1. **Predictive Insights for the Travel Industry:** By employing machine learning models on Twitter data, the project provides predictive insights into the sentiments and desires of the public regarding travel. This information can be invaluable for the travel industry in adapting and tailoring their services to meet the evolving needs and expectations of potential travelers.

2. **Public Health Awareness:** Understanding the sentiments and intentions of individuals during the transition from the pandemic to the endemic phase can contribute to public health awareness. Authorities and healthcare professionals can use this information to gauge public willingness to travel and tailor health measures accordingly.

3. **Data-Driven Decision-Making:** The project showcases the power of data-driven decision-making. By using advanced analytics and machine learning, it sets an example of how big data can be harnessed to gain valuable insights, fostering informed decision-making in various sectors.

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

## Results

The final results, visualizations, and detailed analysis are available in the Jupyter notebooks. Feel free to explore and gain insights into the study of perceptions and desires related to travel in Bali during the transition from the COVID-19 pandemic to the endemic phase.

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
