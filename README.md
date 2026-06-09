# Mumbai Housing Price Prediction

A machine learning project focused on predicting housing prices using a Mumbai real-estate dataset containing over 72,000 property records.

The project involves data cleaning, exploratory data analysis (EDA), feature engineering, geospatial analysis, model comparison, and hyperparameter optimization to build an accurate housing price prediction model.

---

## Project Overview

Accurate housing price prediction is a challenging problem due to the influence of multiple factors such as location, area, amenities, and neighborhood characteristics.

This project aims to estimate property prices in Mumbai by leveraging machine learning techniques and extensive feature engineering on a large-scale real-estate dataset.

---

## Dataset

- Mumbai Housing Dataset
- 72,000+ property records
- Multiple housing attributes including:
  - Location
  - Area
  - Amenities
  - Property specifications
  - Pricing information

---

## Features Implemented

### Data Cleaning

- Missing value handling
- Duplicate removal
- Data type corrections
- Outlier inspection

### Exploratory Data Analysis (EDA)

- Distribution analysis
- Correlation analysis
- Price trend visualization
- Feature relationship studies

### Feature Engineering

- Property attribute transformations
- Derived housing metrics
- Geospatial feature generation

### Geospatial Analysis

To better capture location-based pricing effects, geospatial features were engineered, including:

- Distance-from-sea calculations
- Location-based feature extraction

The impact of these features was evaluated during model development. While they provided useful insights, certain regional anomalies introduced inconsistencies in prediction performance, leading to careful feature selection in the final model.

---

## Machine Learning Pipeline

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Geospatial Analysis
5. Model Training
6. Hyperparameter Optimization
7. Model Evaluation
8. Housing Price Prediction

---

## Models Evaluated

The following regression models were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- CatBoost Regressor

---

## Hyperparameter Optimization

To improve model performance, hyperparameter tuning was performed using:

- RandomizedSearchCV

This allowed efficient exploration of parameter combinations and helped identify the best-performing model configuration.

---

## Results

### Final Model Performance

**Best Model:** Random Forest Regressor (Optimized)

| Metric | Score |
|----------|----------|
| R² Score | 0.9328 |
| Mean Absolute Error (MAE) | ₹1,707,104 |

### Key Findings

- Random Forest delivered the strongest overall performance among the evaluated models.
- CatBoost was also explored and produced competitive results.
- Hyperparameter tuning using RandomizedSearchCV significantly improved model performance.
- The final model explains approximately **93.3% of the variance** in housing prices.
- Geospatial features provided additional location context, although some anomalies reduced their effectiveness in the final prediction pipeline.

---

## Technologies Used

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn
- Random Forest
- CatBoost
- RandomizedSearchCV

---

## Future Improvements

- Improve geospatial feature engineering
- Integrate GIS-based location features
- Deploy the model as a web application
- Implement real-time property valuation
- Experiment with advanced ensemble models

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Geospatial Analysis
- Regression Modeling
- Hyperparameter Optimization
- Model Evaluation
- Machine Learning Pipeline Development

---

## Author

**Anshu Mukhopadhyay**

B.Tech – Metallurgical and Materials Science Engineering  
Minor – Mathematics and Computing  
National Institute of Technology Warangal

---

## Keywords

Machine Learning • Data Science • Housing Price Prediction • Random Forest • CatBoost • Geospatial Analysis • Feature Engineering • Scikit-learn • Python • Real Estate Analytics
