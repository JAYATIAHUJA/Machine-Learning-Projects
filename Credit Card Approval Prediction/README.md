# 💳 Credit Card Approval Prediction — ML Project 1

Welcome to a comprehensive machine learning project focused on predicting credit card approval status using real-world data and modern ML techniques. This notebook walks you through every step: from raw data to actionable insights and robust models.

Inspired by the YouTube channel: [Data Science with Onur](https://www.youtube.com/@DataSciencewithOnur)

---

## 📁 Project Structure

- **Credit_card.csv**: Main dataset containing applicant information.
- **Credit_card_label.csv**: Labels indicating credit approval status.
- **Notebook_1.ipynb**: Jupyter notebook with all code, analysis, and results.

---

## 🧠 Problem Statement

**Objective:**  
Predict whether a credit card application will be approved or rejected based on applicant information.

**Business Value:**  
Automating credit approval helps financial institutions make faster, data-driven decisions, reducing manual effort and bias.

---

## 🚀 Workflow Overview

1. **Data Loading & Merging**
   - Import applicant and label data using pandas.
   - Merge datasets on `Ind_ID` for unified analysis.

2. **Data Cleaning**
   - Drop irrelevant columns (`Type_Occupation`).
   - Handle missing values by dropping rows with NA.
   - Remove duplicates for data integrity.

3. **Exploratory Data Analysis (EDA)**
   - Generate summary statistics and info.
   - Visualize distributions and relationships:
     - Bar plots (income by gender)
     - Pie charts (credit approval status)
     - Boxplots, violin plots, and groupby aggregations for deeper insights.

4. **Feature Engineering**
   - Select relevant features: `Car_Owner`, `Propert_Owner`, `Annual_income`, `EDUCATION`, `label`.
   - Encode categorical variables using `LabelEncoder`.

5. **Model Preparation**
   - Split data into features (`X`) and target (`Y`).
   - Train-test split (80/20).
   - Standardize features using `StandardScaler`.

6. **Model Building & Evaluation**
   - **Logistic Regression**: Baseline classifier.
   - **K-Nearest Neighbors (KNN)**: Hyperparameter tuning with `GridSearchCV`.
   - **Support Vector Machine (SVM)**: Hyperparameter tuning with `GridSearchCV`.
   - Evaluate models using accuracy score.

7. **Results & Insights**
   - Print model accuracy for each classifier.
   - Display best hyperparameters found via grid search.
   - Discuss business implications and next steps.

---

## 🛠️ Tools & Libraries

- **Python**: Core language
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn**: Visualization
- **scikit-learn**: Machine learning models and utilities

---

## 📊 Key Insights & Visuals

- **Income Distribution:**  
  Visualize how income varies by gender, marital status, and education.
- **Approval Rates:**  
  Pie charts and bar plots reveal approval/rejection patterns.
- **Feature Relationships:**  
  Boxplots and violin plots highlight correlations and outliers.

---

## 💡 How to Run

1. Place all files in the same directory.
2. Open `Notebook_1.ipynb` in Jupyter Notebook or Visual Studio Code.
3. Run cells sequentially to follow the workflow.
4. Ensure required libraries are installed:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

---

## 📌 Project Goals

- Practice real-world data cleaning and EDA.
- Build and compare multiple ML models.
- Learn hyperparameter tuning with grid search.
- Document a reproducible ML workflow.

---
🌟 If you find my work interesting, feel free to star ⭐ this repo and follow my journey!
