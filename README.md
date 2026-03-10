# Weather Precipitation Type Prediction using Machine Learning

## Project Overview

This project analyzes historical weather data to predict **precipitation type (rain or snow)** using machine learning models. The goal is to understand how meteorological variables such as temperature, humidity, and pressure influence precipitation.

This project was developed as a **final project during my undergraduate studies** and demonstrates a complete machine learning workflow including data cleaning, exploratory data analysis, feature engineering, model training, and evaluation.

---

## Dataset

This project uses the **Szeged Weather Dataset**.

Author: Norbert Budincsevity  
Source: https://www.kaggle.com/datasets/budincsevity/szeged-weather

Dataset characteristics:

- ~96,000 weather observations
- Target variable: **Precip Type**
- Features include temperature, humidity, wind speed, visibility, and pressure

For repository size considerations, the dataset included in this repository may contain a **sample subset** of the original dataset.

---

## Methods

The following steps were performed:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Train-test split and feature scaling
- Handling class imbalance using **SMOTE**
- Model training and comparison:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Hyperparameter tuning using **GridSearchCV**
- Model evaluation and feature importance analysis

---

## Results

Tree-based models achieved the best performance, with **~99–100% accuracy** in predicting precipitation type.

Temperature was identified as the most influential feature, which aligns with the relationship between temperature and snowfall conditions.

---

## Limitations

Several limitations should be considered when interpreting the results:

- Precipitation type is strongly influenced by **temperature**, making the classification task relatively simple for machine learning models.
- Some features in the dataset are closely related (e.g., temperature and apparent temperature), which may introduce **redundant information**.
- The dataset contains weather observations from **a single geographic location (Szeged, Hungary)**, which may limit how well the model generalizes to other regions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## Author

**Arvin Butiong**  
Aspiring Data Analyst
