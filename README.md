# Mobile Price Prediction

## Overview
A machine learning project that predicts mobile phone prices based on hardware specifications such as RAM, battery power, camera quality, internal storage, and screen size. The project explores both regression and clustering approaches to analyze pricing patterns.

## Objective
To build and compare multiple machine learning models that predict mobile phone prices using technical specifications, and to identify natural groupings among phones using clustering techniques.

## Dataset
The dataset includes features such as RAM, battery capacity, camera megapixels, screen dimensions, and connectivity options, along with price as the target variable.

## Tools & Technologies
- Python
- Pandas, NumPy (data handling)
- Scikit-learn (model building)
- Matplotlib/Seaborn (visualization)
- Google Colab

## Approach

### Regression Models (Price Prediction)
Multiple models were trained and compared:
- Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN)
- Gradient Boosting Regressor

**Gradient Boosting gave the highest R² score** and was selected as the best-performing model. Hyperparameter tuning was performed to further optimize its performance.

### Clustering (Pattern Analysis)
Two clustering techniques were compared to group phones by similar characteristics:
- K-Means Clustering
- Hierarchical Clustering

**Hierarchical Clustering produced better-defined clusters** compared to K-Means for this dataset.

## Key Steps
1. Data cleaning and exploratory data analysis (EDA)
2. Feature selection and preprocessing
3. Training and evaluating multiple regression models
4. Hyperparameter tuning on the best-performing model (Gradient Boosting)
5. Comparing clustering approaches (K-Means vs Hierarchical)

## How to Run
1. Open `MINI_PROJECT.ipynb` in Google Colab or Jupyter Notebook
2. Run all cells in order
3. Ensure the dataset file is in the same directory (or update the file path in the notebook)


## Author
Devi Shri — Third-year ECE student, Kings College of Engineering
