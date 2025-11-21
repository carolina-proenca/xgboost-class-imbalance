Project developed as part of the Machine Learning I course in the second semester of the 2024/2025 academic year

Modification of XGBoost for Class Imbalance Treatment

Project Description

This project aims to implement, modify, and evaluate a classification algorithm to deal with a specific data characteristic: class imbalance in binary classification problems. We used the Gradient Boosting Trees (XGBoost) algorithm, implemented from scratch, as a basis and proposed a modification to make the model more robust in datasets with unbalanced classes, without using external resampling techniques.

Objectives

  - Implement the standard version of the XGBoost algorithm from scratch, without using ready-made libraries (such as scikit-learn).
  - Empirically evaluate the performance of the standard model on unbalanced datasets.
  - Propose and implement a modification to the algorithm to improve its robustness against imbalance.
  - Compare the performance between the standard version and the modified version using benchmark datasets.

Methodology

Base algorithm: Gradient Boosting Trees inspired by XGBoost. Proposed modification:

  - Application of weights, giving greater weight to the minority class during training
  - Application of Hellinger Gain Distance in the splits of the first tree Data: Public benchmark sets for binary classification with different levels of imbalance. Evaluation: Performance metrics focused on imbalanced classification, such as F1-score, PR-AUC, AUC-ROC.
