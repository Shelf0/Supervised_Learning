# Supervised_Learning
Supervised Learning


Unscaled Data prediction 

Random Forest Classifier would perform better as it has more categorial data than numeric which is typically not suitable for Logistic Regression.




Unscaled data Results:

The Random Forest Classifier performed far better then the logistic regression model. 2020 First Quarter testing score was : 0.520 for Logistic regression model. Random forest 2020 First Quarter testing score was : 0.635



Scaled Data Prediction:

Scaling will have positive impact to improve accuracy of the gradient descent algorithm such as Logistic Regression while tree-based algorithms such as Random Forest Classifier do not. 


Scaled Data Results:

Scaling the data improved the logistic regression model predictions. The train and test scores increased from 0.649, 0.520 to 0.713, 0.723 respectively. 
There is significant improvement in prediction. It is likely that the large numbers in some of the features are affecting the prediction. Scaling the data helps in giving an equal weight to all features.
Random Forest Classifier model predictions did not change much with scaling, likely because the decision tree technique does not assume a linear relationship and does not have model coefficients that can 
be affected by the magnitude of the values in the features