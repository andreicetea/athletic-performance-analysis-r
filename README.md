# Predicting Athletic Performance using Machine Learning in R

This project aims to predict the categorical variable *performance_category* (athletic performance level) using several predictor variables and well-known machine learning methods.  With a synthetic dataset consisting of 15,000 chinese students, the data was divided into a training, validation and test subset. Thereafter, four types of model was compared: 

1) Multinomial Lasso Regression,
2) Multinomial Elastic Net Regression,
3) XGBoost Classification and
4) Neural Network Classification.

Among the different model types, the overall validation accuracy (and other measures of model evaluation like sensitivity) was quite similar between the regression models and neural network, and was by far the worst for our XGBoost model. For reasons stated in the report, we deemed our final elastic net model to be the best model for analysing this dataset. 

This project was created as part of a university machine learning course for statisticians. The synthetic dataset used is publicly available on Kaggle under a CC0 Public Domain license: 
* [Student Sports Performance Dataset](https://www.kaggle.com/datasets/colabsss/student-sports-performance-dataset)

> **Note:** The full report (`.pdf`) is in Swedish. Code comments (`.Rmd`) are also largely in Swedish.

Licensed under the [MIT License](LICENSE)  
