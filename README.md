# Taxi Price Prediction
This project focuses on building a machine learning model to predict taxi trip prices using multiple regression algorithms. The goal is to clean and analyze the data, identify key factors influencing prices, and compare model performances to select the best predictor.

## **Project Structure**
* README.md
* rv3.ipynb 
* taxi_trip_pricing.csv

## **Data Preprocessing**

* Handling missing values
* Exploratory data analysis (EDA)
* Correlation analysis
* Feature engineering
* Outlier detection & handling

## **Exploratory Data Analysis**

**The notebook includes:**

* Distribution of trip distances

* Heatmap of correlated features

* Visualizations of fare vs. distance

* Time-based pricing patterns


## **Machine Learning Models**

**These models were built and compared:**

**Linear Regression**
* Performance metrics:

R² Score: 71

**SVR (Support Vector Regression) Best Model**
* Performance metrics:

R² Score: 62 → 82

**Decision Tree**
* Performance metrics:

R² Score: 57 → 70

**Random Forest**
* Performance metrics:

R² Score: 75 → 78

**XGB**
* Performance metrics:

R² Score: 79

## **Key Results**

* Distance is the strongest factor influencing price

* SVR outperformed Linear Regression in capturing non-linear behavior

* A clean and reusable ML workflow was implemented

## **Tools Used**

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn

* Jupyter Notebook

