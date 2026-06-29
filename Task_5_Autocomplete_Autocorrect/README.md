# Task 5: Autocomplete and Autocorrect Data Analytics

Level: 2

## 📌 Project Overview
This project focused on the efficiency and accuracy of Natural Language Processing (NLP) algorithms for text prediction. I implemented an Autocomplete engine based on word frequency and an Autocorrect feature using the Levenshtein Distance algorithm.

## 🛠️ Tech Stack
* **Python:** Core logic and NLP processing.
* **Regex:** For text cleaning and tokenization.
* **Collections (Counter):** For efficient word frequency analysis.
* **Levenshtein Distance:** For calculating spelling similarity.

## 🧠 Key Logic
1. **NLP Preprocessing:** Cleaned and normalized text data using Regex to ensure a consistent word corpus.
2. **Autocomplete:** Built an efficient predictive engine that searches the corpus for the most frequent words matching the user's input prefix.
3. **Autocorrect:** Implemented the Levenshtein distance algorithm to measure the "edit distance" between a misspelled word and a correct dictionary, providing accurate spelling suggestions.

4. ## 📂 Dataset
This project uses a text dataset for Natural Language Processing. Due to GitHub's 100MB file size limit, the raw data file is not included in this repository. 

*To run this notebook:*
1. Download the dataset from (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Place the file in the same folder as this notebook.
3. Update the `file_path` variable in the code if necessary.
