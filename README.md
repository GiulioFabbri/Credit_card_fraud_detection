## Credit card fraud detection
This tutorial shows how to investigate the best model for detecting fraudulent credit card transactions,  
but starting with a **very unbalanced real dataset**  
(https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

To **solve the class imbalance** we will try:
- undersampling (reduce the dataset for having 50% fraudolent and 50% real transactions) 
- weighted undersampling (for limiting the data loss of the undersampling)

The **models** we will use are:

- Logistic Model
- Random Forest
- Gaussian Naive Bayes
- Support vector Classifier
  
They will be trained using **scikit-learn** and specifically optimized using **GridSearchCV**.
