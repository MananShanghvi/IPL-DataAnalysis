# IPL-Data Analysis
This project analyzes historical IPL match data and predicts the outcome of a match between two teams using Machine Learning models. The dataset is cleaned, visualized, and both Logistic Regression and Random Forest models are trained to predict which team will win a match.

<details>
<summary>Table of Contents</summary>

- [Overview](#Overview)
- [Technologies](#Technologies)
- [Dataset](#Dataset)
- [Modeling](#Modeling)
- [Visualization](#visualization)
- [Installation](#Installation)
- [Results](#results)

</details>


## 📑Overview
In this project, we analyze IPL match data to predict match outcomes. The data is preprocessed to remove missing values and duplicates, then visualizations are created to understand match trends. We train two machine learning models — Logistic Regression and Random Forest — and compare their performance in predicting the match winner.

## 💻Technologies
- Python 3.8+
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## 📈Dataset
> The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/)

> The dataset includes historical IPL matches with columns such as:
- team1: Name of the first team.
- team2: Name of the second team.
- toss_winner: Team that won the toss.
- toss_decision: Whether the toss-winning team chose to bat or field.
- venue: The venue where the match took place.
- winner: The team that won the match.

## 💡Modeling
> We use two models to predict match winners:
- Logistic Regression: A simple classification model that predicts the probability of a win for one team over another.
- Random Forest Classifier: An ensemble learning model that uses multiple decision trees to improve prediction accuracy.

> Model Comparison
  Both models are trained and evaluated. The performance of each model is compared based on:
- Accuracy
- Confusion Matrix

## 📊Visualization
> Several visualizations were created to understand the data and the performance of models:
- Confusion Matrix: To visualize correct and incorrect predictions.
- Team win statistics: Bar plot showing the number of matches won by each team.
- Venue statistics: Number of matches played at each venue.

## 📂Installation
To run this project locally, follow these steps:

> Clone the repository:
```bash
gh repo clone MananShanghvi/IPL-DataAnalysis
```
> Navigate to the project directory:
```bash
cd IPL-DataAnalysis
```
> Ensure you have the dataset (matches.csv) in the project directory.

## ⏳Results
> Both models provide decent performance in predicting match outcomes, with the Random Forest classifier generally outperforming the Logistic Regression model in terms of accuracy and feature importance.
> Key evaluation metrics include:
- Accuracy: Random Forest achieved better accuracy in the majority of test cases.
- Confusion Matrix: Shows the number of correct and incorrect predictions.
