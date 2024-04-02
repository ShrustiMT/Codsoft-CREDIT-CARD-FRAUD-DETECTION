# Codsoft-CREDIT-CARD-FRAUD-DETECTION
The code is used to detect fraud using machine learning models such as RandomForestClassifiers and DecisionTreeClassifiers. 

First, use LabelEncoder to load training and test datasets, preprocesses them, and encodes categorical variables. It then trains the RandomForest Classifier and DecisionTree Classifier models on training data. 

Use both models to predict the labels of test data once training is complete. And Evaluates the performance of the models by calculating accuracy and generating a classification report to assess precision, recall, and F1-score.
RandomForestClassifier Accuracy = 99.76%
DecisionTreeClassifier Accuracy = 99.54%

Furthermore, it visualizes the confusion matrix to understand the model's performance in classifying fraud and non-fraud transactions. Finally, it plots the Receiver Operating Characteristic (ROC) curve and computes the Area Under the Curve (AUC) to measure the model's ability to distinguish between fraud and non-fraud transactions.
