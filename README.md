# DA5401 - Assignment 4: GMM-Based Synthetic Sampling

*Name: Aaradhya Dashore* <br>
*Roll No: ME22B089*
---
## Abstract
This assignment addresses the extreme class imbalance in a credit card fraud dataset by implementing and comparing three approaches:
1. **Baseline** – Logistic Regression trained on the imbalanced data.  
2. **GMM-only** – Oversampling minority (fraud) class using Gaussian Mixture Model.  
3. **GMM + CBU** – Combined Clustering-Based Undersampling of the majority class with GMM-based oversampling of the minority.  

## Key Points
- **Part A**: Loaded dataset, explored imbalance, trained baseline Logistic Regression.  
- **Part B**: Selected optimal GMM components using AIC/BIC; implemented both GMM-only oversampling and GMM+CBU combined workflow.  
- **Part C**: Evaluated all models on the untouched test set using Precision, Recall and F1.  
