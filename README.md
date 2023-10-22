# Credit_risk_prediction
Using KNeighborsClassifier

In this challenge we are trying to predict the credit risk for a customer based on Good credit or Bad.

The data comes in a categorial format for most of the column. I addressed this problem by transoming those columns to numeric usinf LabelEncoder technique.

Scaling the data is an import step for using the KNighborsClassifier method. After spliting the data into train and test I scaled the data to get better performance.

The model did not give impressive result for the Good credit prediction so I used SMOTE to oversample the data and run the classification report where the results 

acheived was acceptable.

I also tried RandomUnderSampler method always using the scaled data, result was ok but acheived better result with SMOTE.

Lastley I used SVM where the model was not able to capture the bad credit with 0% precision and recal, the model performed better when introducing SMOTE and 

RandomUnderSampler where the percentange was arrond 50% for both.

As a conculsion the KNighborsClassifier with using SMOTE is the one that we can count on.

TensorFolw method :

In the CREDIT1 nb file I used TensorFlow. With this technique I put attention to the outliers in the amount column. After removing the outliers , scaled the date to 

proceed with TensorFlow method. The loss was very min but the accuracy was not that great.
