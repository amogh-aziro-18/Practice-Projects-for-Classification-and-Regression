**Practice AI/ML Projects**

Project Overview:

This repository contains two distinct machine learning projects:

**Used Car Price Prediction:** A regression project that predicts the selling price of used cars.

**Titanic Survival Prediction:** A classification project that predicts the survival of passengers on the Titanic.

**Important Note:**

This repository has been updated with a new file structure for better organization. The code and data for each project are now located in dedicated, descriptive folders to ensure clarity and maintainability.

**For the Used Car Price Prediction project: Please refer to the used-car-price-prediction/ folder.**

**For the Titanic Survival Prediction project: Please refer to the titanic-survival-prediction/ folder.**

The individual files previously existing at the repository's root are outdated. For the latest code and analysis, please refer to the files within these new directories.

**1. Used Car Price Prediction (Regression)**

**Project Goal:** To build a model that accurately predicts the selling price of used cars based on their features.

**Key Steps:**

1. Data Cleaning: Handled missing values and extracted numerical data from columns with mixed data types.

2. Feature Engineering: Created the car_age feature for predicting depreciation.

3. Modeling: Trained and evaluated multiple models, with Random Forest Regressor being the best performer.

4. Results: The final model achieved a Test R² score of 0.931, demonstrating high accuracy.

**2. Titanic Survival Prediction (Classification)**

**Project Goal:** To predict whether a passenger on the Titanic survived or not based on their personal and travel details.

Methodology:

1. Data Cleaning: Addressed missing values and prepared data for modeling.

2. Model Training & Tuning: A variety of classification algorithms were tested, including Logistic Regression, SVC, KNN, Random Forest, Gradient Boosting, XGBoost, and LightGBM.

3. Hyperparameter Tuning: Used GridSearchCV with StratifiedKFold for robust hyperparameter tuning.

4. Results: The best-performing model was XGBoost, which achieved a cross-validation accuracy of 0.8440.

Other strong contenders were Gradient Boosting and Random Forest, indicating that ensemble methods were particularly effective for this dataset.

How to Run the Projects

Clone the repository:

Bash

git clone https://github.com/amogh-aziro-18/Practice-AI-ML-Projects-aziro-fresher-.git

Install the required packages:

Bash

pip install pandas numpy scikit-learn matplotlib seaborn xgboost lightgbm joblib
Run the Notebooks: Navigate to the respective project folders and open the notebooks in a Jupyter environment to execute the code and view the analysis.

Author
amogh-aziro-18
