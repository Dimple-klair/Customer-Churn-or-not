# Customer Churn / Binary classification model 

Business Objective: Customer churn is a big problem for telecommunications companies. Indeed, their annual churn rates are usually higher than 10%. For that reason, they develop strategies to keep as many clients as possible. This is a classification project since the variable to be predicted is binary (churn or loyal customer). The goal here is to model churn probability, conditioned on the customer features.

Data Set Details: The data file telecommunications_churn.csv contains a total of 19 features for 3333 customers. Each row corresponds to a client of a telecommunications company for whom it has been collected information about the type of plan they have contracted, the minutes they have talked, or the charge they pay every month

The telecommunications industry experiences an average of 15-25% annual churn rate, and it costs 5-10 times more to acquire a new customer than to retain an existing one, that's why customer retention has now become even more important than customer acquisition.
Finding those factors that increase customer churn is important to take necessary actions to reduce this churn. So, The main goal of our project is to develop an understanding of the cause of customer churn which assists telecom operators to predict customers who are most likely subject to churn, and what to do to retain the most valuable customer.

OUR CLASSES ARE IMBALANCED .HENCE WE USED (STRATIFY =Y) WHILE TRAIN_TEST SPLIT
(X,Y,random state=45,test_size=0.30,stratify=y/or target var.name)

FOR IMBALANCED DATASET
we use RandomOverSampler

Use pickle to save model and Streamlit to deploy it

