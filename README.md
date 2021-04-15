# Bank Marketing Prediction
Predict customers' response to direct marketing campaigns.  

## Goal
Build a model that learns from historical bank marketing data. The model predicts whether the bank marketing campaign will succeed or not (i.e. the client will subscribe to a term deposit or not) as a result of marketing efforts.

## Data
The data is related to direct marketing campaigns of a Portuguese banking institution and contains information about the client (age, type of job, employment status, marital status, education level, loan status, account balance and preferred contact method), previous marketing outreaches to the client as well as social/economic context.  

## Methodology
Exploratory data analysis and modelling are implemented by using Python and jupyter notebook. The dataset stored in a .csv file is loaded and explored for missing values and low variability. Since the output from the model is expected to be binary ('yes' or 'no') related to the client's decision, a binary model is needed to be built by exploring classification algorithms such as decision tree, random forest, support vector machine (SVM) and neural networks. Models are evaluated by comparing the accuracy of the predictions and using the ROC curve.
