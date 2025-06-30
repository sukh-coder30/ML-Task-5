# ML-Task-5
This assignment focuses on predicting the presence of heart disease using supervised machine learning models. It explores and compares Decision Tree Classifiers and Random Forests using the Cleveland Heart Disease dataset.

Objectives
Train a Decision Tree Classifier
Visualize the Decision Tree structure
Analyze overfitting and control model complexity via max_depth
Train and evaluate a Random Forest Classifier
Interpret feature importances
Evaluate model performance using cross-validation
==============================================================================================================================
1. Load and Prepare Data
Loaded the heart disease dataset from CSV

Separated features and target variable

Performed train/test split (80/20)

2. Decision Tree Classifier
Trained a default Decision Tree on the training data

Visualized the tree structure using plot_tree()

Observed overfitting: high training accuracy but lower test accuracy

Controlled overfitting by tuning max_depth parameter

3. Random Forest Classifier
Trained a Random Forest with 100 trees and limited depth

Compared its performance with the Decision Tree

Achieved better generalization and higher test accuracy

4. Feature Importance
Extracted and plotted feature importances from the Random Forest

Identified top contributing features (e.g., cp, thal, ca)

5. Cross-Validation
Applied 5-fold cross-validation to assess model stability

Reported mean accuracy and standard deviation across folds



