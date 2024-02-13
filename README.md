# Sales Prediction Using Python 💼💰

Welcome to the Sales Prediction project repository! This project focuses on predicting sales based on advertising expenditures across multiple channels using various machine learning algorithms.

## Introduction ℹ️

This project aims to analyze the advertising dataset and build predictive models to forecast sales based on expenditures on TV, radio, and newspapers. Aspiring Data Scientists will find this project informative for learning data preprocessing, exploratory data analysis (EDA), model selection, hyperparameter tuning, and evaluation.

## Dataset 📊

The advertising dataset contains information on advertising expenditures (TV, radio, newspaper) and corresponding sales figures.

## Dependencies 🛠️

Ensure you have the following dependencies installed in your environment:
- pandas==1.3.3
- seaborn==0.11.2
- scikit-learn==0.24.2
- xgboost==1.5.1
- scipy==1.7.1

You can install them using `pip install -r requirements.txt`.

## Project Structure 📁

The project consists of the following components:
- Importing Libraries
- Loading Dataset
- Preprocessing the Data
- Data Analysis
- Train-Test Split
- Model Selection
- Hyperparameter Tuning
- Model Performance Evaluation
- Final Model Selection

## Getting Started 🚀

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook `Sales_Prediction.ipynb` to follow along with the project.
4. Explore, modify, and experiment with the code to enhance your understanding and skills.

## Model Selection 🤖

Several machine learning models were trained and evaluated for this project:
- Random Forest Regressor
- K-Nearest Neighbors Regressor
- Linear Regression
- Support Vector Machine (SVM)
- XGBoost
- Lasso
- Ridge

Based on the evaluation metrics, XGBoost Regressor was selected as the final model due to its superior performance.

## Model Performance 📊

XGBoost Regressor:
- R2 Score: 0.9558638498476749
- Mean Squared Error: 1.3746027420341036
- Mean Absolute Error: 0.8681395928064982

## Hyperparameter Tuning 🔍

Hyperparameter tuning was performed using Randomized Search CV to optimize the XGBoost model's performance.

## Contributions 🤝

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## Thank You 🙏

Thank you for exploring this project! If you have any questions or feedback, feel free to reach out.

Happy coding and may your sales predictions be accurate! 💼💸
