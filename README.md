# ChatGPT-Reviews-Analysis
NLP-based sentiment and issue analysis of ChatGPT user reviews using TextBlob and Python.

🤖 ChatGPT Reviews Sentiment Analysis (NLP Project)
📌 Project Overview

This project analyzes user reviews of ChatGPT using Natural Language Processing (NLP) techniques in Python.

The objective is to understand:

Overall user sentiment

Common issues in negative reviews

Sentiment trends over time

Relationship between ratings and sentiment

All insights are derived directly from the provided dataset.

🎯 Problem Statement

Users have shared a wide range of feedback about ChatGPT through ratings and written reviews.

This project aims to:

Perform sentiment analysis

Identify common complaints

Track sentiment trends over time

Provide actionable recommendations

🛠 Tools & Libraries Used

Python

Pandas

TextBlob

Matplotlib

Seaborn

WordCloud

📊 Key Analysis Performed
1️⃣ Sentiment Analysis

Calculated sentiment polarity using TextBlob

Classified reviews into Positive, Negative, and Neutral

Visualized sentiment distribution

2️⃣ Issue Identification

Filtered negative reviews

Extracted most frequent complaint keywords

Generated word cloud for common issues

3️⃣ Rating vs Sentiment Analysis

Compared rating scores with sentiment polarity

Identified correlation between ratings and emotional tone

4️⃣ Time-Series Analysis

Calculated monthly average sentiment

Plotted sentiment trend over time

Identified highest and lowest sentiment months

Added 3-month moving average for trend smoothing

5️⃣ Extreme Review Detection

Identified most positive review using idxmax()

Identified most negative review using idxmin()

📈 Key Insights

Majority of reviews show positive sentiment.

Some recurring issues appear in negative reviews.

Sentiment trends fluctuate across months.

Rating scores strongly align with sentiment polarity.

Addressing recurring complaints can improve user satisfaction.

📌 Business Impact

This analysis helps:

Understand customer satisfaction

Detect recurring product issues

Monitor user perception over time

Support product improvement decisions

Convert qualitative feedback into actionable insights

🚀 Future Improvements

Use VADER or BERT for more advanced sentiment analysis

Apply topic modeling (LDA) for better issue detection

Build interactive dashboard using Streamlit

Perform deeper correlation analysis

📂 Project Structure
ChatGPT_Reviews_Analysis.ipynb
chatgpt_reviews.csv
README.md

🧠 Project Type

Natural Language Processing (NLP)
Sentiment Analysis
Customer Feedback Analytics

✨ Author
Aman Kosre
