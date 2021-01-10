# SVM Support Vector Machines

* Your overall goal is to use the wine dataset shown to develop a machine learning model that attempts to predict if a wine is "Legit" or "Fraud" based on various chemical features. 

# Code and Resources Used

* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn.
* Data Source: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support           Systems, Elsevier, 47(4):547-553, 2009.


# About Data:

Fraud in Wine:https://en.wikipedia.org/wiki/Wine_fraud

* Wine fraud relates to the commercial aspects of wine. The most prevalent type of fraud is one where wines are adulterated, usually with the addition of cheaper products (e.g. juices) and sometimes with harmful chemicals and sweeteners (compensating for color or flavor).
* Counterfeiting and the relabelling of inferior and cheaper wines to more expensive brands is another common type of wine fraud.

* A distribution company that was recently a victim of fraud has completed an audit of various samples of wine through the use of chemical analysis on samples. The distribution company specializes in exporting extremely high quality, expensive wines, but was defrauded by a supplier who was attempting to pass off cheap, low quality wine as higher grade wine. The distribution company has hired you to attempt to create a machine learning model that can help detect low quality (a.k.a "fraud") wine samples. They want to know if it is even possible to detect such a difference.

# Data Cleaning:

* As data is already in usable format, so no cleaning process is followed here.

# EDA

# Model Building
First, split the data into train and tests sets with a test size of 10%.

* I tried SVClassifier model and evaluated them using Acuuracy_Score, Precision and Recall. 
* I have used hyper parameter tunning as Data is imbalanced.

# Model performance
The SVC model has below performace metrics.

* Accuracy_Score : 
* Precision : 
* Recall : 
