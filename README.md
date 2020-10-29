# Wine-Quality-Prediction
![wine-images-high-resolution-free-download](https://user-images.githubusercontent.com/63126292/97619738-96eda680-19ee-11eb-8b50-323cd9900bca.jpg)

1. Objectives: 
* The goal of this kernel is to find the best approach to identify the quality of wines. We will go through the basic EDA and visually identify the quality 
Moreover, I also applied multiple ML models to make the prediction respectively. Each of the models would have its own strength.
* There are two different notebooks. One is for red wine, and another one is for white wine

2. Dataset
* The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).
* Acknowledgements
 This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality , I just shared it to kaggle for convenience. (I am mistaken and the public license type disallowed me from doing so, I will take this down at first request. I am not the owner of this dataset.
* P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

3. Analysis Process
* Import libraries and dataset
* Understand the data
* Feature engineering
* Machine Learning Algorithms
* Conclusion

4. Machine learning models
* To make both red wine and white wine is relevant, I use the same models for two datasets
* Logistic Regression
* K-Nearest Neighbor Classifier
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Classifier

5. Outcome
* The best model for Red Wine is Logistic Regression (AUC 56.9%)
* The best model for White Wine is Random Forest Classifier (AUC 70.2%)
