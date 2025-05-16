# Sentiment-Analysis-using-NLP

🏢 COMPANY: CODTECH IT SOLUTIONS


👤 NAME: VIJAYREDDY MARAM


🆔 INTERN ID: CT06DA368


📂 DOMAIN: DATA ANALYTICS


⏳ DURATION: 6 WEEKS


👩‍🏫 MENTOR: VAISHALI


🚀 Sentiment Analysis on Textual Data using NLP | Internship Project


📌 Project Overview


This project was developed as part of my internship to demonstrate skills in Natural Language Processing (NLP) for sentiment analysis. The goal was to process real-world textual data (like tweets or reviews), classify them into sentiments (Positive, Negative, Neutral), and extract meaningful patterns and insights using machine learning techniques.

📊 Dataset Used


This project uses the Twitter US Airline Sentiment Dataset, which contains thousands of tweets directed at various airlines in the United States.

The dataset includes fields like:

text – the tweet content

airline_sentiment – labeled as positive, neutral, or negative

airline – which airline was mentioned

negativereason – reason for negative sentiment (if any)

This kind of dataset simulates real-world opinion mining scenarios useful in social media analysis and customer feedback systems.

🧰 Tools & Technologies Used


Google Colab – Cloud-based environment to run the notebook

Python – Core programming language

Pandas – Data handling and transformation

NLTK – Text preprocessing (stopwords, stemming)

Scikit-learn – Vectorization, model training, evaluation

Matplotlib & Seaborn – For visualizations

WordCloud – To generate word clouds for sentiment analysis


🛠️ Key Tasks


✅ Data Preprocessing


Cleaned tweets by removing URLs, punctuation, and stopwords

Applied stemming for normalization


📊 Class Imbalance Analysis


Visualized sentiment distribution

Analyzed imbalance across classes (negative was dominant)



🔡 Feature Engineering


TF-IDF vectorization to convert text into numerical format

🤖 Model Building
Trained a Logistic Regression classifier

Evaluated with accuracy, precision, recall, and F1 score


📈 Evaluation Metrics


Confusion matrix, classification report

Accuracy and weighted F1 score printed

🧪 Sample Predictions


Ran model on random samples and displayed actual vs. predicted sentiments

☁️ Sentiment Word Analysis

Generated WordClouds and bar plots for common positive and negative keywords

🔍 Insights


The majority of tweets had negative sentiment — likely reflecting customer complaints.

Common negative words included "late", "cancelled", "lost", "delay".

Positive tweets featured words like "thank", "helpful", "great".

Logistic Regression performed well with TF-IDF vectors for text classification.


🧠 Real-World Applications


Social Media Monitoring – Analyze brand perception on platforms like Twitter

Customer Feedback Systems – Automatically detect negative feedback

Product Review Mining – Summarize public opinion on e-commerce platforms

Political Sentiment – Track sentiment on political campaigns


✅ Final Deliverable


A fully-commented, well-structured Google Colab notebook that includes:

Text cleaning and preprocessing

Model training and evaluation

Class imbalance analysis

Visual insights via charts and word clouds

Sample predictions for verification


📸 Output Snapshots


Confusion Matrix

![Image](https://github.com/user-attachments/assets/b12fb734-3297-4b7b-9064-d288fcd3fead))



WordCloud - Positive


![Image](https://github.com/user-attachments/assets/60d54e5e-74a7-42ce-9ad9-26ff2ffd32be)


WordCloud - Negative


![Image](https://github.com/user-attachments/assets/60d54e5e-74a7-42ce-9ad9-26ff2ffd32be)




Sample Predictions


![Image](https://github.com/user-attachments/assets/58e6ad23-63f2-4970-b40c-8954bb783598)

