# Credit_Risk_Analyis

## Overview of Analysis
  Credit risk is an inherently unbalanced classification problem due to good loans outnumbering risky loans.  In order to train and evaluate the models with unbalanced classes, six different machine learning methods were used:
  - ROS
  - SMOTE
  - Undersampling
  - SMOTEENN
  - Balanced Random Forest Classifier
  - Easy Ensemble Classifer
 

### Resources
- Data Source: [LoanStats_2019q1.csv](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/LoanStats_2019Q1.csv)

- Software:
 - Python 3.6.1
 - Jupyter Notebook
   - Libraries
     - Numpy
     - Pandas
     - Pathlib
     - Path
     - scipy
     - scikit-learn
     - imbalanced-learn
  - Collections
    - Counter  
 

## Results of Analysis

### ROS (Random Oversampling)
 
- #### Balanced Accuracy Score
![ROS_Balanced_Accuracy_score](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/ROS_Balanced_Accuracy_Score.png)
- #### Imbalanced Classification Report
![ROS_imbalanced_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/ROS_classification_report.png)
 
### SMOTE (Synthetic Minority Oversampling Technique)

- #### Balanced Accuracy Score
![SMOTE_Balanced_Accuracy_score](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/SMOTE_Balanced_Accuracy_Report.png)
- #### Imbalanced Classification Report
![SMOTE_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/SMOTE_classification_report.png)

### Undersampling

- #### Balanced Accuracy Score
![Undersampling_balanced_accuracy_score](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/Undersampling_balanced_accuracy_score.png)
- #### Imbalanced Classification Report
![Undersampling_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/Undersampling_classification_report.png)

### SMOTEENN (Combined Over and Undersampling)

- #### Balanced Accuracy Score
![SMOTEENN_balanced_accuracy_score](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/SMOTEENN_balanced_accuracy_report.png)
- #### Imbalanced Classification Report
![SMOTEENN_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/SMOTEENN_classification_report.png)

### Balanced Random Forest Classifier

- #### Balanced Accuracy Score
![BRFC_balanced_accuracy_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/BRFC_balanced_accuracy_report.png)
- #### Imbalanced Classification Report
![BRFC_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/BRFC_classification_Report.png)

### Easy Ensemble Classifier

- #### Balanced Accuracy Score
![EEC_balanced_accuracy_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/EEC_balanced_accuracy_report.png)
- #### Imbalanced Classification Report
![EEC_classification_report](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/EEC_classification_report.png)

## Summary

![Summary_chart](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/Summary_chart.png)



- ### Recommendation
It is recommended that the Balanced Random Forest Classifier be used to assist in machine learning due to it having the the best Balanced Accuracy Score of 78% and the best overall Average Recall of 91%.
