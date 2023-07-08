# Superconductor-Critical-Temperature-Prediction
Machine Learning model to predict Critical Temperature of Semiconductors based on various features.

Project Description:
1.Developed a machine learning model to predict the critical temperature of superconductors based on their physical and chemical properties from a dataset of  21,263 superconductors with 82 features.
2.Performed Feature Selection to select the features with maximum correlation with Tc.
3.Hyperparameter Tuning is performed using GridSearchCV on three regression models- Linear Regression, Random Forest Regression, and Support Vector Regression (SVR) to maximise predictive accuracy and to select the model with best accuracy and R2 score.
4.Performance Evaluation: Random Forest Regression Model is selected as best model which achieves an R2 score of 0.927, indicating a strong correlation between the predicted and actual critical temperatures. It also gives a Mean Squared Error of 84.42.
