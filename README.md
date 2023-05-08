# Assignment5-text-analysis
Assignment 5 in Machine Learning : Text Analysis

This is our fifth and final assignment in our course called Machine Learning.
In this assignment we were asked to predict and evaluate if the story teller is a male or a female, according to the text they wrote.

First of, what we did is that we wanted to clean our text, so that we will have a clean text with words and spaces only.
Then, we applied preprocessing to our text, using MinMaxScaler, and selecting the k best features in our dataset, and applied the dataset to look like a feature vector.

Then we made 5 different models, and defined every model its potenial parameters that can give them the best fit for the features we had, and we checked which of them was the best for our model using GridSearchCV.

Later on, what we did is we created a function that gets the specific model with X_train, X_test, y_train, and y_test, to fit the model and try to predict with the model, then, we used evaluation to get the f1_score but we needed to get f1_score_average, so we did f1_score while male is positive section and f1_score while female is positive section and divided them by 2 to get the average of both of them.

Finally, we used all of the functions and implemented them for the df_test, and trained it with the SDG model, to get the predictions on to the df_test which one is male and which one is female.
