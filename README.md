# Machine Learning Models: Cancer Cases and Treatment Costs
* Performed data preparation (transformed variables, clustering) and EDA (descriptive statistics, simple visualization) to understand more about the dataset
* Built Prediction (Regression Tree, Linear Regression) and Classification (KNN, Logistic Regression, Boosted Tree, Bagged Tree) models to predict annual cancer cases
* Evaluated models above using RMSE, accuracy, confusion matrix, F1 scores to determine best prediction and best classification model
* Compared best hand-crafted models with DataRobot's -- resulting in:
    * __Best Classification Model__: Hand-crafted Bagging Tree with 0.93 Accuracy score (_successfully beat DataRobot!_)
    * __Best Prediction Model__: DataRobot's Random Forest Regressor with RMSE of 418.02


### Background
This is a project for a course to learn about various ML models and their applications. The dataset was obtained from [here](https://data.world/exercises/linear-regression-exercise-1/workspace/file?filename=cancer_reg.csv) and [here](https://data.world/xprizeai-health/expenditures-for-cancer-care). This folder contains the R code that I wrote to wrangle the data as well as apply clustering (Hierarchical and K-Means) and classification (Logistic Regression and KNN) models to find the best fitting one. 


## View html files here
### Unsupervised Learning
* [Clustering](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/report2_clustering.html)

### Supervised Learning
* [Classification: KNN & Logistic Regression](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/report2_classification.html)
#### Trees & Ensemble Models
* [Classification Tree](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/Report3_ClassificationTree.html)
* [Regression Tree](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/Report3_RegressionTree.html)
* [Random Forest](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/Report3_RandomForests.html)
* [Boosted Trees](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/Report3_BoostedTrees.html)
* [Bagged Trees](https://htmlpreview.github.io/?https://github.com/crystalhariga/cancer_ml/blob/main/Report3_BaggedTrees.html)
