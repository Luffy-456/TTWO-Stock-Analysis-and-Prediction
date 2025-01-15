# Take-Two Interactive Stock Analytics and Prediction

This repository contains a comprehensive project focused on analyzing and predicting stock prices for Take-Two Interactive using machine learning techniques. The project emphasizes data preprocessing, visualization, and implementing robust machine learning models for accurate predictions.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Dataset Overview](#dataset-overview)
4. [Features](#features)
5. [Technologies Used](#technologies-used)
6. [Machine Learning Models](#machine-learning-models)
7. [Data Visualization](#data-visualization)
8. [Results and Accuracy](#results-and-accuracy)
9. [Conclusion](#conclusion)
10. [Future Scope](#future-scope)
11. [How to Use](#how-to-use)
12. [Acknowledgements](#acknowledgements)
13. [Disclaimer](#disclaimer)

---

## Introduction

Stock market prediction is a critical domain in finance, where machine learning is increasingly applied to improve forecasting accuracy. This project employs supervised machine learning models to analyze historical stock data of Take-Two Interactive and predict future stock prices. By leveraging Python’s extensive libraries, this project integrates data analysis, visualization, and predictive modeling.

---

## Project Objectives

- To analyze historical stock data and uncover meaningful patterns.
- To predict stock prices using various regression models.
- To evaluate model performance and select the best algorithm for accurate predictions.
- To visualize relationships and trends in the dataset.

---

## Dataset Overview

The dataset used in this project contains historical stock data, including key features such as:

- **Open**: Opening price of the stock.
- **Close**: Closing price of the stock.
- **High**: Highest price during the trading session.
- **Low**: Lowest price during the trading session.
- **Volume**: Number of shares traded.

Data preprocessing steps include handling missing values, feature selection, and train-test splitting for model evaluation.

---

## Features

1. **Data Analysis**:

   - Summary statistics.
   - Detection and handling of missing/duplicate values.
   - Central tendency and variability metrics.

2. **Data Visualization**:

   - Heatmaps, box plots, scatter plots, and regression plots.

3. **Model Training and Evaluation**:

   - Implementation of regression models.
   - Metrics for assessing model accuracy and performance.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - **Data Manipulation**: Pandas, NumPy
  - **Visualization**: Matplotlib, Seaborn
  - **Machine Learning**: scikit-learn

---

## Machine Learning Models

1. **Decision Tree Regressor**:

   - Creates decision trees to map input features to target variables.
   - Provides feature importance for better interpretability.

2. **Random Forest Regressor**:

   - Ensemble method that combines multiple decision trees.
   - Reduces overfitting and improves prediction accuracy.

3. **Extra Trees Regressor**:

   - Uses additional randomness in feature selection and split point determination.
   - Enhances generalization and computational efficiency.

---

## Data Visualization

1. **Box Plot**: Highlights data distribution and potential outliers.
2. **Correlation Heatmap**: Displays relationships between numerical features.
3. **Scatter Plot**: Examines trends and patterns between two variables.
4. **Regression Plot**: Fits and visualizes linear regression lines.
5. **Histogram**: Analyzes the frequency distribution of variables.
6. **Pair Plot**: Provides pairwise scatter plots for multiple features.

---

## Results and Accuracy

- **Decision Tree Regressor**: Demonstrated moderate accuracy but prone to overfitting in some cases.
- **Random Forest Regressor**: Outperformed other models with high accuracy and robustness to overfitting.
- **Extra Trees Regressor**: Showed competitive performance with added randomness improving generalization.

Visualization of predictions vs. actual values indicates the effectiveness of these models in capturing stock price trends.

---

## Conclusion

This project successfully demonstrated the application of machine learning for stock price prediction. The Random Forest Regressor proved to be the most reliable model, balancing accuracy and generalization. Insights derived from this analysis can aid investors in making informed decisions.

---

## Future Scope

1. **Incorporation of Sentiment Analysis**:

   - Analyze financial news and social media trends to refine predictions.

2. **Deep Learning Models**:

   - Implement advanced techniques such as LSTMs and GRUs for sequential data analysis.

3. **Automated Trading**:

   - Develop pipelines for real-time stock trading based on predictive models.

4. **Enhanced Visualization**:

   - Create interactive dashboards for better decision-making.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone "https://github.com/Luffy-456/TTWO-Stock-Analysis-and-Prediction.git"
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ml.ipynb
   ```
4. Explore the results and visualizations.

---

## Disclaimer

This project was created solely for educational purposes and as a fun exploration of machine learning techniques. It is not intended for professional trading or financial decision-making. Use any insights derived from this project at your own discretion.
