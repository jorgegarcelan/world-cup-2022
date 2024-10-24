
# ⚽ FIFA World Cup 2022 Match Prediction

## 📖 Project Overview

This project aims to predict the outcomes of FIFA World Cup 2022 matches using various machine learning models. We leverage international football match data from 2004 to 2022 to build a predictive model that helps determine the winner of each stage, up to the final match of the world’s biggest sporting event.

## 🎯 Problem Statement

Predicting the outcome of a football match is inherently challenging due to the variability and complexity of sports. Our goal is to develop a model that accurately predicts the outcomes of FIFA World Cup matches, specifically targeting the 2022 World Cup in Qatar.

## 🗂️ Dataset

We used a dataset comprising 3,083 international matches played between January 2004 and June 2022. The dataset includes:
- Teams
- FIFA rank of both teams
- Average FIFA player ratings for defense, midfield, and offense
- Tournament performance points
- Neutral venue indicator

We cleaned the dataset by removing null values and irrelevant matches to prepare it for machine learning models.

> **Note**: This project is an adaptation of the dataset available on Kaggle: [FIFA World Cup 2022 Dataset](https://kaggle.com/datasets/brenda89/fifa-world-cup-2022/data)

## ⚙️ Methods Used

We experimented with various supervised machine learning models to determine the best approach:

1. **Naive Bayes (Gaussian)**
   - Baseline model with decent performance but limited by the assumption of feature independence.
   - Accuracy: ~59%

2. **K-Nearest Neighbors (KNN)**
   - Imputed missing values and demonstrated the highest accuracy for match predictions.
   - Performance improved through careful feature selection.

3. **Random Forest**
   - A decision tree-based model designed to handle large datasets with multiple features.
   - Accuracy: ~69%

## 🏆 Tournament Simulation

In addition to predicting individual matches, we created a simulation of the entire 2022 FIFA World Cup tournament. Using the match prediction model, we simulated all the stages of the tournament, from the group stage to the final, predicting the outcomes based on team performance metrics. The simulation provides a full run-down of the tournament’s progression based on historical match data and model predictions.

## 📊 Results

Our models showed varied performance, with the Random Forest model yielding the highest accuracy at 69%. While predicting football match outcomes is difficult due to the inherent uncertainty, our models demonstrated robust performance on average, despite occasional surprising results in real-life matches.

## 🔍 Conclusion

Football matches are inherently unpredictable, and even with the best available data and models, predicting the outcome of individual matches remains a challenge. Our study highlights that while predictive models can provide good average results, some outcomes will defy expectations, as seen in the 2022 World Cup (e.g., Japan vs. Germany, Saudi Arabia vs. Argentina).

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-url
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook to train the models and make predictions:
   ```bash
   jupyter notebook Code.ipynb
   ```

4. Follow the instructions in the notebook to experiment with different models and features.

## ✨ Course Information

This project was completed as part of the **CS4641 - Machine Learning** course at **Georgia Tech** during **Fall 2022**.
[Link to course website](https://mahdi-roozbahani.github.io/CS46417641-fall2022/)


## 👥 Authors

- Jorge Garcelán (jgarcelan3@gatech.edu)
- Carlos Pérez
- Luis Pérez
- Jean-Pierre Boudreaux
- Akiyuki Shigematsu
