# Task 3: Credit Card Fraud Detection

Level: 2

## 📌 Project Overview
The objective of this project was to build a machine learning model capable of detecting fraudulent credit card transactions. A major challenge in this dataset was extreme class imbalance (less than 0.2% of transactions were fraudulent), requiring specific data preprocessing techniques.

## 🛠️ Tech Stack
* **Python:** Scripting and logic.
* **Pandas & NumPy:** Data manipulation and analysis.
* **Scikit-Learn:** Machine learning modeling (`LogisticRegression`) and performance evaluation (`classification_report`, `confusion_matrix`).
* **Seaborn & Matplotlib:** Data visualization.

## 🧠 Machine Learning Process
1. **Exploratory Data Analysis (EDA):** Analyzed the dataset and identified a massive class imbalance (284,315 normal transactions vs. 492 fraudulent transactions).
2. **Data Balancing:** Applied **Undersampling** to create a perfectly balanced 50/50 dataset, preventing the model from heavily biasing toward the majority class.
3. **Model Training:** Trained a **Logistic Regression** classifier on the balanced data using an 80/20 train-test split.
4. **Evaluation:** The model achieved an outstanding **92% Accuracy and F1-Score**. I generated a Confusion Matrix to visualize the model's precise breakdown of True Positives, False Positives, True Negatives, and False Negatives.

*Note: The dataset used for this project is the European Credit Card Fraud dataset. Due to GitHub's file size limits, the 493MB CSV was not uploaded to this repository. You can download the raw data from Kaggle to run this notebook locally.*

## 🔗 Live Demonstration
*Pending Video Upload*
