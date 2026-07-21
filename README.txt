# House Price Prediction using Linear Regression

A Machine Learning project that predicts house prices based on different house characteristics using **Linear Regression**.

This project demonstrates the complete Machine Learning workflow for a regression problem, including data exploration, preprocessing, model training, evaluation, and model saving.

---

## Project Purpose

The main purpose of this project is to implement the complete Machine Learning workflow using **Linear Regression** as a **baseline regression model**.

Since house prices are influenced by complex and non-linear relationships, **Linear Regression is not expected to achieve the highest performance on this dataset**. However, it provides a solid foundation for understanding data preprocessing, feature engineering, model training, and evaluation before experimenting with more advanced regression algorithms.

---

## Dataset

**Dataset:** Housing Prices Dataset

The dataset contains information about different houses and their selling prices.

### Target Variable

- Price

### Features

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Exploratory Data Analysis (EDA)

The following analysis was performed:

- Dataset Overview
- Data Types
- Statistical Summary
- Missing Values Check
- Duplicate Values Check
- Histograms
- Boxplots
- Correlation Matrix
- Correlation Heatmap

---

## Data Preprocessing

The preprocessing pipeline included:

- Handling Categorical Features
- Binary Encoding
- One-Hot Encoding
- Removing Outliers using the IQR Method
- Splitting Features and Target
- Train-Test Split

---

## Model

**Regression Algorithm**

- Linear Regression

---

## Model Performance

The model was evaluated using the following regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

| Model Version | R² Score |
|---------------|---------:|
| Before Removing Outliers | **0.6529** |
| After Removing Outliers | **0.6684** |

Removing outliers using the IQR method slightly improved the model performance, demonstrating that extreme values had a modest impact on the regression model.

### Correlation Heatmap

![Correlation Heatmap](images/heatmap.png)

### Actual vs Predicted Prices

![Actual vs Predicted Prices](images/prediction.png)

---

## Future Improvements

Future versions of this project will focus on improving prediction performance by experimenting with more advanced regression algorithms instead of relying only on Linear Regression.

Planned improvements include:

- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter Tuning
- Feature Engineering
- Building an interactive web application for real-time house price prediction

---

## Author

**Mohamed Gamal**

Machine Learning & Deep Learning Engineer

- GitHub: https://github.com/mogamal1111
- LinkedIn: https://www.linkedin.com/in/mohamed-gamal-85795735b