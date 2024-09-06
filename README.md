Fraud detection in credit card transactions is the scope of the project using Logistic Regression. The dataset used contains transaction data which is anonymous and labeled as either a legitimate transaction Class 0 or a fraud transaction Class 1. The correct classification of the transaction and fraud detection would be an uphill task to overcome in this project due to the presence of an imbalanced dataset.

Project Workflow
Data Collection:

This dataset ranges from credit card transactions and has a great imbalance between the legitimate and fraudulent classes. Data Preprocessing:

Missing values are checked and handled in the dataset.
Self-aloof data sets are made for both the legitimate and fraudulent transactions for analyses.
Summary statistics are created to investigate the disparities among the two classes. Handling Imbalanced Data

The data is highly imbalanced, ranging from a small fraction of fraudulent cases.
To handle this, some under-sampling is applied to create a Balanced Dataset by reducing the number of Legitimate Transactions equalling Fraudulent Transactions.
Splitting the Data:

Data is split into features X and targets Y; target relates to fraudulence in a transaction.
Further segregation is done into training and testing sets in an 80:20 ratio.
Model Training:

Use Logistic Regression to classify the transactions.
The model is trained on the training data and the performance is evaluated in terms of accuracy on both the training and testing datasets.
Model Evaluation:

The accuracy score both for the training and test data have been computed as a performance measure of the model.
Results:

The Logistic Regression model demonstrated effectiveness in the classification of both the legitimate and fraudulent classes accurately.
With the under-sampling technique, the model handled the class imbalance in the dataset with very good performance.
