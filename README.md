# SageMaker-XGBOOST-Algo

Used XGBOOST to train and test, on BankingApplication Data, to predict if the customer will buy the Product/Service provided by the Bank.
Data was priorly One Hot Encoeded.
Services Used: S3 Bucket, AWS SageMaker.
Created an S3 bucket, stored the CSV file there, along with Test and Train Data.
Used a Built in XGBOOST Model provided by the AWS to perform the predictions.
Deployed the model once it was fitted into the train and test dataset.
Model was then evaluated based on Confusion Matrix(Results are imbalanced because of an Imbalanced Dataset).
Once done, deleted the bucket and notebook Instance so as to refrain from incurring high charges.


