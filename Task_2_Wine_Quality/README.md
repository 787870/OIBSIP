# Task 2: Wine Quality Prediction

Level: 2

## 📌 Project Overview
The objective of this project was to build a machine learning classification model to predict the quality of wine based on its physicochemical attributes. 

## 🛠️ Tech Stack
* **Python:** Scripting and logic.
* **Pandas & NumPy:** Data manipulation and analysis.
* **Scikit-Learn:** Machine learning modeling, `StandardScaler` for data normalization, and performance evaluation.
* **Seaborn & Matplotlib:** Data visualization.

## 🧠 Machine Learning Process
1. **Data Preprocessing:** Inspected the dataset for missing values and analyzed the distribution of wine quality scores.
2. **Feature Scaling:** Applied `StandardScaler` to ensure all chemical properties (like sulfur dioxide and chlorides) were evaluated on an equal mathematical scale.
3. **Model Training & Comparison:** Split the data into an 80/20 train-test split. Trained and evaluated three different algorithms simultaneously:
   * **Random Forest** (Winner: 69.87% Accuracy)
   * **Support Vector Classifier (SVC)** (63.76% Accuracy)
   * **Stochastic Gradient Descent (SGD)** (50.22% Accuracy)
4. **Visualization:** Generated a bar chart to clearly compare the predictive performance of the three models.
