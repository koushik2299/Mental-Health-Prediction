# Mental Health Prediction

This project aims to predict mental health outcomes based on a survey dataset. The goal is to build a machine learning model that can accurately predict mental health outcomes and help identify individuals who may be at risk for mental health problems.

# Dataset
The dataset used in this project is the Mental Health in Tech Survey, which contains responses from 1,295 individuals working in the tech industry. The survey includes questions about mental health conditions, treatment, and attitudes towards mental health in the workplace.

# Methodology
The following steps were taken to build the mental health prediction model:

Data cleaning and preprocessing: The survey data was cleaned and preprocessed to remove missing values, encode categorical variables, and normalize the data.

Feature selection: The most important features were selected using feature importance techniques such as random forest classifier and gradient boosting classifier.

Model training and selection: Several machine learning models were trained and evaluated, including logistic regression, k-nearest neighbors, decision tree classifier, random forest classifier, gradient boost classifier, adaboost classifier, and XGB classifier. The best-performing model was selected based on evaluation metrics such as accuracy, precision, recall, and F1 score.

Model evaluation: The selected model was evaluated using cross-validation and test set evaluation. The evaluation metrics were used to assess the performance of the model and identify areas for improvement.

Results
The final model achieved an accuracy of 85% and an F1 score of 0.83, indicating good performance in predicting mental health outcomes. The most important features identified by the model were age, gender, family history of mental health conditions, and work interference due to mental health.

# Future Work
Some areas for future work include:

Collecting more data from a broader range of industries and demographics to improve the generalizability of the model.
Exploring the use of deep learning models and natural language processing techniques to analyze unstructured data such as text responses in the survey.
Integrating the mental health prediction model into a web application or chatbot to provide personalized mental health support and resources to individuals.

# References
Mental Health in Tech Survey
Scikit-learn
TensorFlow
Keras
