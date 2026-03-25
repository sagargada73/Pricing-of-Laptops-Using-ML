# Laptop Price Prediction using Machine Learning

## Introduction
This repository contains the analysis and machine learning model implementation for the laptop pricing dataset. The goal is to predict various prices of laptops based on multiple attributes using different machine learning techniques. This project explores various regression techniques to determine the best model for predicting laptop prices accurately.

## Dataset Used
The dataset used in this analysis is `LaptopPricing.csv`, which contains various features related to laptops such as:
- `CPU_frequency`
- `RAM_GB`
- `Storage_GB_SSD`
- `CPU_core`
- `OS`
- `GPU`
- `Category`
- `Price` (Target variable)

## Table of Contents
1. Data Import and Cleaning
2. Exploratory Data Analysis (EDA)
3. Model Evaluation
4. Over-fitting, Under-fitting, and Model Selection
5. Ridge Regression
6. Grid Search

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook

## Strategy
1. **Data Import and Cleaning:**
   - Loaded the dataset into a Pandas DataFrame.
   - Checked for missing values and handled them appropriately.
   - Encoded categorical variables and standardized numerical features.

2. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of numerical features.
   - Identified correlations between different attributes and price.
   - Box plots and scatter plots were used to understand feature significance.

3. **Model Building and Training:**
   - Implemented various machine learning models including:
     - Linear Regression
     - Ridge Regression
     - Decision Tree Regressor
     - Random Forest Regressor
   - Used Grid Search to optimize hyperparameters.
   - Handled overfitting and underfitting by comparing models.

4. **Performance Evaluation:**
   - Evaluated models using metrics such as:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared score
   - Compared different models to determine the best-performing one.

## Conclusion
- Explored various machine learning models to predict laptop prices accurately.
- Ridge Regression performed well in preventing overfitting.
- Hyperparameter tuning using Grid Search improved model accuracy.
- The results demonstrate that laptop prices can be effectively estimated based on key specifications.



## Author
Om Doshi

GitHub Profile: OmDoshi13

