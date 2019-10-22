# UC-ML-SVM

This group project for my Intermediate Applied Data Analysis class from the MscBMI Program at The University of Chicago involved running SVM Models. The code for this repository elaborates on the specific code used to run Support Vector Machine Models for a Kaggle dataset https://www.kaggle.com/c/gusto/data in R:

We ran five SVM Models to determine which was the best fit for the data, based on the results:
1. Support Vector Machine with Linear Kernel
- Parameters: 0.01-1000

2. Support Vector Machine with Radial Kernel
- Parameters: Cost and Gamma

3. Tuned Support Vector Machine with Radial Kernel
- Parameters: Values for cost and values
- Choose best values for Cost and Gamma and then re-run Radial model with those chosen values 

Note: Next two models are run after SMOTE as the data was slightly imbalanced. The original dataset had a slightly un-even distribution, making the model difficult to predict when faced with the test dataset. The SMOTE dataset resulted in a smaller train dataset and had a more equal distribution of the two outcomes.

4. Support Vector Machine with Linear Kernel after resampling with SMOTE
- Parameters: 0.01-1000 

5. Support Vector Machine with Radial Kernel after resampling with SMOTE
- Parameters: Cost and Gamma 

For the three best models (SVM SMOTE Linear, SVM SMOTE Radial and SVM Radial), confusion matrix's were created along and accuracy, specificity and sensitity were deduced. 
