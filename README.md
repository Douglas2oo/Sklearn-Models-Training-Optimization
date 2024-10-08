# Data-Analysis

## Brief Introdution
Multi scikit-learn models training & hyperparameter optimization process. 

With model performance visulization, report generation and method summary(Chinese Version).

## Data Source File
``` python
path = '/sklearn multi models training & optimization/requirements & introduction/Account_Level_Analysis.xlsx' 
```

## File Structure
```
|-- undefined
    |-- README.md
    |-- sklearn multi models training & optimization
        |-- Models1.ipynb
        |-- Models2.ipynb
        |-- model_report1.pdf
        |-- model_report2.pdf
        |-- 项目总结.pdf
        |-- img
        |   |-- account_category_distribution.png
        |   |-- ada_KOL.png
        |   |-- ada_Transfer.png
        |   |-- bagg.png
        |   |-- et.png
        |   |-- forest.png
        |   |-- gbrt_KOL.png
        |   |-- gbrt_Transfer.png
        |   |-- knn.png
        |   |-- KOL_Estimated_distribution.png
        |   |-- lasso.png
        |   |-- linear.png
        |   |-- mean_error.png
        |   |-- mean_error2.png
        |   |-- rating1.png
        |   |-- rating2.png
        |   |-- ridge.png
        |   |-- svm_KOL.png
        |   |-- svm_Transfer.png
        |   |-- Transfer_Estimated_distribution.png
        |   |-- tree_KOL.png
        |   |-- tree_Transfer.png
        |-- requirements & introduction
            |-- Account_Level_Analysis.xlsx
            |-- Intro to DA.pptx
            |-- requirements.txt
```

## Models Distribution

### Models1.ipynb / model_report1.pdf

* Linear Regression
* Decision Tree Regression
* Ridge Regression
* Lasso Regression
* SVM Regression

### Models2.ipynb / model_report2.pdf

* KNN Regression
* Random Forest Regression
* Adaboost Regression
* GBRT Regression
* Bagging Regression
* Extra Tree Regression

## File Content

### Models1.ipynb & Models2.ipynb

* Import Data
* Data Pre-processing
* **Visualization: Key Data Distribution (Models1.ipynb)**
* Data Structure Modification
* Dataset Splitting
* Model Training
* Hyperparameter Optimization
* Model Performance Evaluation
* Model Performance Visualization
* Report Generation Feature

### model_report1.pdf & model_report2.pdf

* **Visualization: Key Data Distribution (model_report1.pdf)**
* Data Pre-processing
* Dataset Splitting
* Model Training & Optimization Comparison
    1. Parameters
    2. Performance Score
    3. Performance Visualization
* Comparison of MSE & Average MSE
* Comparison of Performance Score
