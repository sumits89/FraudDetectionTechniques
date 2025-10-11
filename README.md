# Anomaly and Fraud Detection Techniques

A collection of Jupyter Notebooks to show different ways to implement anomaly and fraud detection. This example workshop will use a dataset from Kaggle that is used for Credit Card Fraud detection. 

## Dataset:

The dataset used in this series of examples is publicly available at https://www.kaggle.com/mlg-ulb/creditcardfraud

The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on http://mlg.ulb.ac.be/BruFence and http://mlg.ulb.ac.be/ARTML

## Metrics
- The **AUC-ROC** Curve is a way to judge how well a classification model can tell the difference between two groups (e.g., "Fraud" vs. "Not Fraud"). While 1 is a perfect score, 0.8-0.9 is a solid performance.An AUC of 0.90 means that if you randomly select one fraudulent transaction and one legitimate transaction, your model will give the fraudulent one a higher score (e.g., a higher probability of being fraud) 90% of the time
- Recall ( TP/ (TP+FN))
- Precision ( TP/(TP+FP)
- F1 Score 

## Methods:

### - Supervised Methods (Decision Trees Classification):

This method uses a classification algorithm (XGBoost) given the fact that the dataset has both Fraud and Non-Fraud transactions.

-------------------


### - Unsupervised Methods:

#### 1- Autoencoders
#### 2- Random Cut Forest
#### 3- Isolation Forest


-------------------
