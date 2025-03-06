# NBA Game Outcome Classification - Will the Home Team Win?

## Overview
This project explores the use of machine learning techniques to predict the outcome of NBA games, specifically whether the home team will win. The study leverages historical game statistics and advanced predictive modeling to analyze key factors influencing match results.

## Data
The dataset consists of structured box score summaries of NBA games from 2003 onward, collected using the `nba_api` Python module. Key preprocessing steps include:
- Identifying home and away teams
- Merging duplicate game records
- Removing incomplete data
- Calculating rolling averages of key statistics over the last 10 games
- Introducing an Elo rating system to assess team strength dynamically

## Exploratory Data Analysis (EDA)
Initial data analysis reveals:
- Home teams win approximately 58% of games
- Key performance metrics, such as points scored and defensive rebounds, show differences between winning and losing teams
- A correlation matrix highlights relationships between game statistics

## Predictive Models
Two machine learning models were implemented:
1. **Logistic Regression** - A baseline model for binary classification
2. **Support Vector Machine (SVM)** - A more complex classifier for improved prediction accuracy

## Conclusion
The results indicate that machine learning can provide meaningful insights into NBA game outcomes. While no single statistic guarantees a win, a combination of features, including historical performance and Elo ratings, contributes to accurate predictions.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Jędrzej Kocięcki - Applied Computer Science, Wrocław University of Science and Technology

