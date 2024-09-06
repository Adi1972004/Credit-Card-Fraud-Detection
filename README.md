# Credit-Card-Fraud-Detection
Project Title: Detection of Credit Card Fraud Using Machine Learning

Overview: The following project makes use of designing a system based on machine learning for detecting fraudulent credit card transactions. Detection of fraud is a key aspect for any financial institution as this helps them avoid financial losses while protecting the interest of their customers. A real-world labeled dataset containing fraudulent and non-fraudulent transactions will be used in this project to which various machine learning techniques will be applied with an aim to detect probable fraudulent cases.

Steps Involved:

Data Import and Preprocessing:

It reads the dataset creditcard.csv into a pandas DataFrame. Basic EDA consists of exploring the first and last few rows to get an idea of the types of variables and missing values in the dataset. Cleaning and Feature Selection of Data:

Cleaning will be performed, which may comprise handling missing values, scaling features, selecting relevant features that provide value to the fraud prediction. Imbalanced Data Handling:

This is a very imbalanced dataset since fraudulent transactions are very rare compared to the number of normal ones; thus, some techniques have been used in this regard to balance the classes, such as resampling by oversampling fraud cases and undersampling legitimate cases, or the Synthetic Minority Over-sampling Technique, popularly known as SMOTE. 
Splitting the Data:

This is done through the Scikit-learn library via a method known as train_test_split, which ensures that the model is trained on one subset and then tested on another for its performances. Model Selection and Training

Multiple machine learning models are fitted on the preprocessed dataset, including but not limited to: Logistic Regression, Decision Trees, Random Forest, and Support Vector Machines.
Each of these different models developed should be compared to determine the best in class for fraud detection.
Evaluation Metrics:

The key results are presented in terms of Accuracy, Precision, Recall, and F1-score since such metrics can provide an insight into the trade-offs of catching fraud and minimizing false positives.
Finally, a ROC Curve is calculated, and its AUC is used as a way to visualize and quantify the classification performance of this model.
Results and Analysis:

Based on the correct identification of fraudulent transactions, the comparison of the performance for different models is used to gain insights. Further, the best model with a better balance between precision and recall is identified as the top model.
Conclusion: This project successfully applies machine learning techniques to the problem of credit card fraud detection. By balancing the dataset and choosing appropriate models, the project will try to create a solution that can be deployed in real-world environments for identifying fraudulent transactions at high accuracy while reducing the false alarm rate.

