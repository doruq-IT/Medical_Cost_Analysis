# doruq-IT
## Introduction

Regression analysis is a fundamental part of machine learning, often used to predict a continuous target variable based on one or more input features. This project focuses on using Lazy Prediction, a method that automates the model selection and evaluation process, combined with the GradientBoostingRegressor model to perform regression analysis on a given dataset.

## Project Overview

1. **Data Exploration:** The dataset is explored to understand its structure, features, and relationships. Statistical summaries, data visualizations, and correlation analysis are performed.

2. **Lazy Prediction:** Lazy Prediction is employed to quickly assess the performance of multiple regression models. It automates the model fitting and prediction process, providing initial insights into the viability of different algorithms.

3. **GradientBoostingRegressor:** The GradientBoostingRegressor, a powerful ensemble learning technique, is chosen for further analysis. It is trained, tuned, and evaluated to predict the target variable more accurately.

4. **Model Evaluation:** The trained model's performance is evaluated using R2, MAE, and MSE metrics. These metrics provide a quantitative assessment of the model's ability to make accurate predictions.

5. **Results and Conclusion:** The project concludes by summarizing the insights gained, the effectiveness of the GradientBoostingRegressor model, and the overall findings of the analysis.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
