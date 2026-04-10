# Titanic Survival Prediction

## Overview

This project explores the Titanic dataset to understand the factors that influenced passenger survival and builds a machine learning model to predict survival outcomes. It combines data analysis, visualization, and classification techniques to deliver meaningful insights from historical data.

The goal is not only to achieve good predictive performance, but also to interpret the data and identify patterns that contributed to survival.

---

## Problem Statement

Given passenger details such as age, gender, ticket class, and fare, the objective is to predict whether a passenger survived the Titanic disaster.

---

## Approach

### 1. Data Preparation

* Handled missing values in features like Age and Embarked
* Removed irrelevant columns such as Cabin, Name, and Ticket
* Converted categorical variables into numerical format

### 2. Exploratory Data Analysis

* Analyzed survival distribution across different features
* Identified trends based on gender, class, and age
* Visualized key relationships using graphs

### 3. Model Building

* Used Logistic Regression for classification
* Split dataset into training and testing sets (80/20)

### 4. Evaluation

* Measured model performance using accuracy score
* Compared predicted results with actual outcomes

---

## Tools and Technologies

* Python
* Pandas and NumPy for data manipulation
* Matplotlib and Seaborn for visualization
* Scikit-learn for machine learning

---

## Key Insights

* Gender played a significant role in survival (higher survival rate for females)
* Passengers in higher classes had better chances of survival
* Age and fare also showed noticeable influence

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
```

2. Navigate to the project directory:

```bash
cd titanic-survival-prediction
```

3. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. Run the project:

```bash
python app.py      # for visualizations
python main.py     # for model training and evaluation
```

---

## Project Structure

ML PROJECT/

* app.py
* main.py
* train.csv
* Visualization/

  * imgs/

---

## Results

The model achieves a reliable accuracy score and demonstrates how simple machine learning techniques can effectively solve classification problems when combined with proper data preprocessing and analysis.

---

## Future Work

* Experiment with advanced models such as Random Forest and Gradient Boosting
* Perform hyperparameter tuning to improve performance
* Build a user interface for real-time predictions

---

## Author

Ashwin Yadav

---

## Acknowledgment

This project uses the Titanic dataset made available on Kaggle for educational and research purposes.
