# liver-disease-classification

This project was completed as part of a Masters degree in Health Data Science.

The [Indian Liver Patient dataset](http://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29) was used for this study.

As part of the study, I selected two classification models and present the following for both - 
  a) supervised learning on training data
  b) optimization of hyper-parameters
  c) model evaluation including but not limited to confusion matrix, precision, recall, F1 and AUC
  d) sensitivity analysis

kNN and Random Forest classifier were the two chosen models

Exploratory data analysis showed
  a) several highly skewed varaibles - Scikit learns PowerTransformer class was used within the model pipelines to handle skewness in the data. 
  b) several highly correlated variables - dimensionality reduction and feature extraction was done using PCA.

Grid search was done on each model evaluation criteria – accuracy, precision, recall, F1 score and AUC. The training data was then fit to find the best hyperparameters for each. The predicted outputs and classification reports were generated using the best fit parameters. Lastly, confusion matrices and ROC plots for each of the optimized models were visualized. Sensitivity analysis was done for both models to show the performance with a small change in one of the hyperparameters.
