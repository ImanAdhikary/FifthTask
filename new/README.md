<<<<<<< HEAD
# FifthTask
=======
# 📊 Heart Disease Prediction using Decision Trees and Random Forest

This project aims to predict the presence of heart disease in patients using classical machine learning models. It demonstrates model training, overfitting control, feature importance analysis, and cross-validation evaluation on a binary classification problem.

## 📂 Dataset

Heart Disease Dataset
Shape: 1025 rows × 14 columns
Target Variable: target (0: No Heart Disease, 1: Heart Disease)
✅ Tasks Performed

## 1️⃣ Train a Decision Tree Classifier and Visualize the Tree
Built a DecisionTreeClassifier using scikit-learn.
Visualized the decision tree structure with plot_tree.
Tuned parameters like criterion, splitter, max_depth, and min_samples_split.

## 2️⃣ Analyze Overfitting and Control Tree Depth
Observed overfitting on deeper trees (high training accuracy but low test accuracy).
Controlled overfitting by adjusting:
max_depth
min_samples_leaf
min_samples_split
max_leaf_nodes
Noticed better generalization at optimal tree depth.

## 3️⃣ Train a Random Forest Classifier and Compare Accuracy
Trained a RandomForestClassifier.
Compared accuracy scores with the Decision Tree.
Random Forest achieved better test accuracy and reduced overfitting due to ensembling.

## 4️⃣ Interpret Feature Importances
Extracted and visualized feature importances from the trained Random Forest and trained Decision Tree.
Identified the most significant features contributing to heart disease prediction.
  1. Most significant featue for Random Forest Classifier is 'thalach' and 'oldpeak'
  2. Most significant featue for Decision Tree Classifier is 'cp' (it may change after every run)

## 5️⃣ Evaluate Models using Cross-Validation
Performed k-fold cross-validation (cv=100) for both Decision Tree and Random Forest.
Calculated average accuracy across folds.
Random Forest consistently outperformed Decision Tree in terms of cross-validated accuracy.
## 📈 Results Summary

### Decision Tree():
#### Using all parameters :
     Training accuracy 76% and test accuracy 75%
#### Using only max depth = 3 :
     Training accuracy 86% and test accuracy 81%

### Random Forest():
    Training accuracy 100% and test accuracy 99%
     
Note: Actual values will vary based on hyperparameters and random state.
>>>>>>> 7d5a235 (Decision tree and random forest)
