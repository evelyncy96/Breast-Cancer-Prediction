# Breast-Cancer-Prediction

The dataset I used in this practice comes from the famous dataset on kaggle. This dataset contains 569 observations, 30 features, and a binary target variable.
I built classification models using **Decision Tree, KNN, Logistic Regression, and SVM** to predict the diagnose result of breast cancer.

I performed nested cross validation among all the models to avoid overfitting and find the best model, and the mean accuracy of nested cross validation of each model is: Decision Tree (0.934),KNN (0.964), Logistic Regression (0.963) and SVM (0.977). 
**The best model is SVM with the best parameter C = 100, gamma = 0.0001, kernal = 'rbf'. I then created a model with SVM and made the prediction on test data, and the model accuracy on test data is 0.9035 along with recall positive 0.88 and precision positive 0.74.**

In addition, I presented the drew the ROC curve and lift curve as below. The ROC curve is pretty close to the top-left corner, showing the performance is not bad.

For more information, please refer to the folowing website:
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

