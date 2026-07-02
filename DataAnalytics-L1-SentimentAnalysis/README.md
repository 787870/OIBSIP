# Task 4: Sentiment Analysis

Level: 1

## 📌 Project Overview
The objective of this project was to develop a Natural Language Processing (NLP) machine learning model capable of classifying the emotional tone of text data. Using a dataset of over 162,000 tweets, I built a sentiment analysis model to categorize public opinion into positive, negative, and neutral sentiments.

## 🛠️ Tech Stack
* **Python:** Scripting and logic.
* **Pandas & NumPy:** Data manipulation and cleaning.
* **Scikit-Learn:** Machine learning modeling, text vectorization, and performance evaluation.
* **Seaborn & Matplotlib:** Data visualization.

## 🧠 Machine Learning Process
1. **Data Preprocessing:** Cleaned the dataset by identifying and dropping missing values to ensure model accuracy.
2. **Text Vectorization:** Utilized Scikit-Learn's `CountVectorizer` to transform English text into a mathematical matrix (limiting to the 5,000 most frequent words).
3. **Model Training:** Split the data into 80% training and 20% testing sets. Trained a **Multinomial Naive Bayes** classifier to recognize sentiment patterns.
4. **Evaluation & Visualization:** The model achieved an impressive **93.30% overall accuracy**. Generated a comprehensive classification report and a Seaborn bar chart to visualize the overall distribution of sentiments across the dataset.

## 🔗 Live Demonstration
Video Demo: https://www.linkedin.com/posts/mohammed-aslam-a-363568298_oasisinfobyte-oasisinfobytefamily-internship-activity-7475389770391814145-V3pD?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEf8WfsBpelwj07-q2VSFslYYAiwlYpd4uw
