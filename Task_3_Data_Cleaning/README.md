# Task 3: Data Cleaning

Level: 1

## 📌 Project Overview
The objective of this project was to take a raw, messy dataset and perform data cleaning and preprocessing to prepare it for analysis. I utilized the famous **Airbnb New York City (2019)** dataset to demonstrate how to handle missing values, standardize formatting, and ensure data integrity.

## 🛠️ Tech Stack
* **Python:** Scripting and logic.
* **Pandas:** Data manipulation, inspection, and missing value imputation.
* **Matplotlib & Seaborn:** Visualizing the clean data distribution.

## 🧹 Cleaning Operations Performed
1. **Data Inspection:** Identified over 10,000 missing values across critical columns like `last_review` and `reviews_per_month`, as well as missing `name` and `host_name` entries.
2. **Handling Missing Data:**
    * Replaced missing text data (`name`, `host_name`) with the logical placeholder `"Unknown"`.
    * Imputed missing numerical data (`reviews_per_month`) with `0`, representing listings with no reviews.
    * Replaced missing date entries (`last_review`) with `"Not Reviewed"`.
3. **Verification:** Confirmed zero duplicate rows and zero remaining null values in the dataset.
4. **Export & Visualization:** Exported the newly cleaned dataset to a CSV and generated a distribution chart of NYC room types to verify data structure.

## 🔗 Live Demonstration
*Pending Video Upload* 
