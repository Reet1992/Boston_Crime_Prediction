# Boston_Crime_Prediction

The Boston Crime Dataset represents the offense occurred in different location. The location comes with the "District","Street"
and with "latitude & Longitude" location. This project repository tells about the primary analysis of current statistics of offense(crime0 occurred. Then made prediction models by selecting particular features. "DecisionTreeClassifier()" in Python and "ctree()" In R Studio. To upgrade the accuracy of the DecisionTreeclassifier() model i had to apply feature selection method. By applying ohter features,when i got a better Accuracy then compare two tree models with bagging method. With the k Fold crosss validation, The accuracy Score is 1.0. This happened because the test Data set is a part of the train Data set. Unfortunately, there is no sperately test Data Available. The Dataset was huge, so there was enough Data to train and test even though i split it into 7:3 raio.
As for now, the test accuracy is 98.56% in selecting the "District" and "Offense_code_group" as feature.

In later i have also applied to see the clustering of offense_code_group and have found out the widest street approach between two cluster of offense with SVM maximized margin.
Here, we need to remember that the label is "Level_of_violation" which has only four cateogry ( 'Strong', 'Medium', 'low', 'Non-violation'). This label column is made based on the frequency of the offense_code_group.

# Output file : crime_prediction.ipynb
