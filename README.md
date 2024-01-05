# Diabetes-Prediction-Model
This is a Machine Learning Project that demonstrated my knowledge of Data Exploratory Analysis and usage of Machine Learning Models like Logistic Regression in order to predict the number of people who would be positive for Diabetes from the given dataset.


# Data Exploratory Analysis
The sheet shows a number of historgrams, barcharts, and pie chart created in order to understand the total the number of people with a given precondition like a stroke or a high BMI. The usage of this information was to see if there was a link between any of these preconditions and diabetes. I concluded that a precondition was not a definite determining factor for an individual to get diabetes, but has the potential to be a factor.


# Logistic Regression Model
I used the Logistic Regression Model due to it being the best fit in order to predict a yes or no answer on wheather an individual would be positive for diabetes. 

          precision    recall  f1-score   support

           0       0.87      0.98      0.92     50745
           1       0.54      0.15      0.23      8350

    accuracy                           0.86     59095
   macro avg       0.71      0.56      0.58     59095
weighted avg       0.83      0.86      0.83     59095


Once the model was created, I created a confusion matrix in order to understand the data. While the model was confident on the number of people who would not get diabtes, the recall and score was not strong enough to say the person would contract diabtes. It held a precision score of 54%. 

# Conclusion

Diabetes is a complex disease with so many external enviromental factors that can play a huge role in determining wheather a person would contract the disease is or not. More research needs to be done, and more variables need to be included in order to determine a stronger answer on what factors can lead to an individual to be positive for diabetes. 
