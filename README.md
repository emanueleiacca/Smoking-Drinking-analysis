# Project Title: Health Risk Prediction
## Overview
This GitHub repository contains code for a project focused on predicting health risks based on various features. The dataset used in this project includes information about individuals, such as demographic details, health measurements, and lifestyle choices. The primary goal is to build classification models to predict two important health-related outcomes: smoking and/or drinking status

## Data Cleaning and Analysis:
You started by loading the dataset and taking an initial look at the data. You used various libraries like pandas, numpy, seaborn, and matplotlib for data manipulation and visualization.

### Handling Duplicates and Null Values:

Checked for the presence of null values using df.isnull().sum().
Identified and removed duplicate rows using df.drop_duplicates(keep='first', inplace=True).

### Statistical Analysis and Visualization:

Utilized various statistical measures and visualizations to gain insights into the dataset.
Created box plots for numerical variables like vision measurements, blood pressure, cholesterol, enzyme levels, etc.
Generated histograms for age, height, waistline, blood sugar, serum creatinine, etc.
Utilized count plots for categorical variables such as smoking status and sex.
Explored relationships using scatter plots and count plots for different variables.

### Correlation Matrix:

Converted categorical variables into numerical using one-hot encoding (pd.get_dummies).
Created a correlation matrix using sns.heatmap to identify relationships between features.

## Classification Tasks:
You proceeded with classification tasks using several algorithms:

### Decision Trees:

Implemented a Decision Tree Classifier for both smoking and drinking status.
Checked accuracy scores, and visualized the decision tree.

### Random Forest:

Applied Random Forest Classifier for smoking and drinking status.
Explored accuracy scores.

### Naive Bayes:

Employed Multinomial Naive Bayes for smoking and drinking status.
Utilized cross-validation for accuracy assessment.

### Support Vector Machines (SVM):

Applied SVM for both smoking and drinking status.
Explored accuracy scores and performed some hyperparameter tuning using GridSearchCV and Optuna.

### Stochastic Gradient Descent (SGD):

Implemented SGD for linear SVM.
Tuned hyperparameters and evaluated accuracy.

### Random Forest Hyperparameter Tuning with Optuna:

Utilized Optuna for efficient hyperparameter optimization.
Optimized the Random Forest Classifier for smoking and drinking status.

### LightGBM and XGBoost:

Applied LightGBM and XGBoost classifiers, optimizing hyperparameters using Optuna.
Obtained the best hyperparameters for improved accuracy.

### AdaBoost:

Employed AdaBoost with Decision Tree base estimators.
Utilized Optuna for hyperparameter optimization.

## Conclusion:

Provided a comprehensive analysis of the classification tasks, including data preprocessing, model implementation, and hyperparameter tuning.
Discussed the rationale behind algorithm selection, tuning decisions, and the interpretation of results.
Summarized the best hyperparameters obtained for each algorithm.

## Further Steps:
Discussed the possibility of using PCA for outlier detection and understanding the dataset.
Emphasized the importance of evaluating each algorithm's performance and selecting the best solution based on metrics discussed in class.
This detailed approach showcases a systematic exploration of data, thoughtful algorithm selection, and a structured methodology for model evaluation and optimization.






