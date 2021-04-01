# Data Modelling

The problem at hand is a binary classification in which we will be attempting to predict whehter a person will seek treatment or not based on the surrounding corporate environment. The target variable that will be used is - **have you ever sought treatment for a mental health disorder from a mental health professional?**. For each model following steps will be performed - 
1. Splitting the data into training and testing set
2. Handling target class imbalance
3. Training the model with grid search for fetching best performing hyperparameters
4. Evaluation of model
5. Checking fairness of model
6. Interpretation of model

For this usecase, we will only be utilizing the emsemble models as they can perform as good or sometimes better than the individual models that are used for building those emsembles. Following are the models that are used -
1. Random Forests

In order to check how good the models are, we need to evaluate models based on certain metrics. Since ours is an binary clasisfication, we will be evaluating our models on the following evaluation metrics:
1. Sensitivity (True Positive Rate)
2. Sensitivity (True Negative Rate)
3. Presion
4. Recall
5. F1 score
