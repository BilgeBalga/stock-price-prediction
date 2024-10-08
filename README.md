# 📈 Stock Price Prediction Project 📉

## Project Overview 
This project aims to predict whether it would be worthwhile to buy Tesla stock using machine learning techniques. I analyze historical stock data to create a predictive model that can guide investment decisions.

## 🛠️ Technologies Used </>
- Python
- Pandas for Data Manipulation
- Numpy for numerical operations
- Matplotlib and Seaborn for Data Visualization
- Scikit-learn for Machine Learning Models and Preprocessing
- XGBoost for gradient boosting

## 📚 Table of Contents
1. **Data Loading and Exploration**: I loaded Tesla stock data from a CSV file and performed initial exploratory data analysis (EDA) to understand the dataset's structure and characteristics.
2. **Feature Engineering**: I created new features from the existing data, including:
   - Extracting day, month, and year from the date
   - Creating a quarter-end indicator
   - Calculating open-close and low-high price differences
3. **Data Visualization**: I used various plots to visualize the data, including:
   - Line plots of closing prices over time
   - Distribution plots of key features
   - Box plots to identify outliers
   - Bar plots of yearly average prices
   - Correlation heatmap
4. **Model Development**: I developed and compared three different machine learning models:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - XGBoost Classifier
5. **Model Evaluation**: I evaluated the models using the ROC-AUC metric on both training and validation sets.

## 🏆 Results
The models showed varying degrees of performance:
- Logistic Regression achieved a validation accuracy of about 54%
- SVM performed slightly worse with a validation accuracy of about 46%
- XGBoost showed the best performance with a validation accuracy of about 57%

This project demonstrates the potential of using machine learning for stock price prediction. While the models show promise, it's important to note that stock market prediction is inherently challenging due to its complex and dynamic nature. The XGBoost model showed the best performance, suggesting that more complex models might be better suited for this task.

