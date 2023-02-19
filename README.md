# Stroke-Prediction
Introduction

This project aims to build a model that predicts whether a person is at risk of having a stroke. The data used in this project was obtained from Kaggle and contains information about patients such as age, gender, hypertension, heart disease, smoking status, BMI, and glucose level.

Methodology

The data was preprocessed by cleaning missing values and converting categorical features into numerical values. Exploratory data analysis was conducted to gain insights into the data. The data was then split into training and testing sets, and various machine learning algorithms were used to build models that predict whether a patient has had a stroke. The models were evaluated using metrics such as accuracy, area under the curve (AUC), and F1 score.

Results

Logistic regression was found to be the best model for this dataset, with an AUC of 0.85 and an accuracy score of 0.941. However, the models had a hard time correctly predicting if a patient had a stroke due to the imbalanced dataset. The models were better at predicting the true negative labels compared to the true positive labels.

Discussion and Conclusion

To improve the effectiveness of the models, SMOTE (Synthetic Minority Oversampling Technique) can be used to give the minority data class more weight. Another solution is to collect more data of stroke patients. Overall, Logistic Regression is the best model for this dataset, but further improvements can be made by addressing the imbalance in the dataset and collecting more data.

Repository Contents

data: contains the stroke data file

stroke_prediction.ipynb: Jupyter notebook containing the data preprocessing, exploratory data analysis, and machine learning modeling

README.md: this file containing an overview of the project

Installation

Clone this repository to your local machine
Ensure that you have Jupyter Notebook installed
Open the Jupyter Notebook and run the code in the notebook

Credits

The data used in this project was obtained from Kaggle: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

The project was completed as part of a data science course by Chirs Bai at University of Colorado
