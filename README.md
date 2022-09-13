# Micro-Credit-Defaulter-Model

Modelling part![image](https://user-images.githubusercontent.com/96686888/189964292-258737ec-87fa-421b-a5b8-e74aefedb2bb.png)

* We know that this is classification problem so we use accuracy score, classification report and confusion matrix  as our evaluation matrix. We also see the AUC score  and also plot the AUC_ROC curve for our final model.
* As we know this dataset is imbalance so we don’t too much focus on accuracy score . We see the precision and recall  value along with f1_score.
* First we see the result without doing any sampling technique and for that I use Logistic Regression with K-Fold cross validation and hyper-parameter tuning. 
* We also use Random Forest Classifier  as our evaluation model without using hyper-parameter  tuning because our dataset is too large and it takes more than hour to give the result.

Conclusion!

 So here 'RandomForestClassifierModel' is the best model out of all model tested above and by looking this we can conclude that our model is predicting around 92% of correct results for Label ‘0’ indicates that the loan has not been payed i.e. defaulter. 

![image](https://user-images.githubusercontent.com/96686888/189964197-6ab9526c-b177-433f-b788-61bf59de6132.png)


