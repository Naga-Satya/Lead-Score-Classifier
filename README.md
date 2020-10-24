# Lead-Score-Classifier

*Aim of building the Model: To classify a customer of the data with 35 different different attributes

*Analysis performed:

Imputed missing values in continuous features by mean/median detection using boxplot analysis
Imputed categorical missing values as follows: 
 (i) Meaningful missing imputation 
 (ii)Frequent value imputation
Normalised the target variable to gaussian ditribution
Dropped highly Imbalanced features: 
 (i) Highly skewed/imbalanced columns 
 (ii)Highly missing valued columns
Binning of less frequent categorical values of a respective column
*Model Built: 
Classic Logistic Regression Model

*Methods used to find important features:
 (i)  p value significance
 (ii) Eliminating features by checking multi-collinearity
 (iii)Recursive Feature Elimination
 
*Performace Metric focussed on:
Sensitivity of the model.
