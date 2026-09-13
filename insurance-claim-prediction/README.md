\# Insurance Claim Prediction



\## Project Overview



This project develops a machine learning classification model to predict whether a customer is likely to purchase an insurance product.



The objective is to help an insurance marketing team identify high-potential customers and prioritize their marketing efforts using data-driven predictions.



\## Business Problem



Insurance companies may have large numbers of customers to target for marketing campaigns. Predicting which customers are more likely to purchase an insurance product can help improve campaign efficiency and customer targeting.



This project uses historical customer data to build and compare multiple machine learning classification models.



\## Project Workflow



1\. Data Loading and Understanding

2\. Data Preprocessing

3\. Train-Test Splitting

4\. Handling Class Imbalance using SMOTE

5\. Feature Extraction using PCA

6\. Model Training

7\. Hyperparameter Tuning

8\. Model Evaluation

9\. Model Comparison

10\. Business Insights and Conclusion



\## Machine Learning Models



The project evaluates multiple classification algorithms:



\- Logistic Regression

\- Decision Tree

\- Random Forest

\- Gradient Boosting

\- K-Nearest Neighbors

\- Artificial Neural Network (MLP)



\## Data Preprocessing



The following preprocessing techniques were applied:



\- Dataset exploration

\- Missing-value analysis

\- Duplicate-value analysis

\- Correlation analysis

\- Feature preparation

\- Train-test splitting

\- SMOTE for handling class imbalance

\- PCA for feature extraction



\## Hyperparameter Tuning



RandomizedSearchCV was used to tune the major machine learning models and identify suitable hyperparameters.



\## Project Structure



```text

insurance-claim-prediction/

│

├── data/

│   └── train.csv

│

├── notebooks/

│   ├── 01\_data\_loading\_and\_understanding.ipynb

│   ├── 02\_data\_preprocessing.ipynb

│   ├── 03\_data\_splitting\_and\_smote.ipynb

│   ├── 04\_model\_training.ipynb

│   ├── 05\_hyperparameter\_tuning.ipynb

│   └── 06\_model\_evaluation\_and\_conclusion.ipynb

│

├── dashboard/

│   └── insurance-claim-dashboard.html

│

├── README.md

├── requirements.txt

├── LICENSE

└── .gitignore

