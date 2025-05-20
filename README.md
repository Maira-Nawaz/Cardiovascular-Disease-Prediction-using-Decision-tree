# Cardiovascular-Disease-Prediction-using-Decision-tree

Predicting the presence of cardiovascular disease using health data and Decision Tree classification.

##  Project Overview

This project was completed as part of a **Kaggle competition**, where the objective was to build a machine learning model that can **predict whether a patient has cardiovascular disease** based on features such as age, blood pressure, cholesterol levels, lifestyle habits, etc.

I used a **Decision Tree Classifier** from `scikit-learn` to build the model and achieved a **Kaggle leaderboard score of 0.71500** 🎯.



##  Dataset Description

* **Training Data:** 4000 records with 11 features + target column `cardio`
* **Test Data:** 1000 records (no target), includes an `id` column for submission
* **Target Variable:**
  `cardio`

  * `0`: No cardiovascular disease
  * `1`: Has cardiovascular disease

### Features Used:

* `age`: Patient's age (in days)
* `gender`: 1 = women, 2 = men
* `height`, `weight`: Physical metrics
* `ap_hi`, `ap_lo`: Systolic and diastolic blood pressure
* `cholesterol`, `gluc`: Blood test results (1 = normal, 2 = above normal, 3 = well above normal)
* `smoke`, `alco`, `active`: Lifestyle indicators

  
##  Tools & Libraries Used

* Python 
* `pandas`, `numpy` for data handling
* `scikit-learn` for modeling and evaluation


##  Model & Evaluation

###  Model Used:

* `DecisionTreeClassifier()` from `sklearn.tree`
  
###  Evaluation Metrics:

* **Accuracy:** `~72%` on validation set
* **Precision, Recall, F1-Score:** Computed using `classification_report`
* **Kaggle Score:** `0.71500`

  
##  Final Thoughts

This project gave me hands-on experience in:

* Applying classification models to health data
* Preparing a Kaggle-ready submission
* Evaluating model performance with meaningful metrics

  
##  Author

**Maira Nawaz**

[LinkedIn](https://www.linkedin.com/in/mairanawaz/) | [Kaggle](https://www.kaggle.com/mairanawaz) | [Github](https://github.com/Maira-Nawaz)


