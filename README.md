Customer Churn Prediction using Logistic Regression
📌 Objective

The objective of this project is to build a Logistic Regression model that predicts whether a customer will churn (leave the service) based on customer information such as tenure, services subscribed, contract type, payment method, and other features. The project demonstrates the complete machine learning workflow including data preprocessing, model training, prediction, and evaluation.

📂 Dataset

Dataset Name: Telco Customer Churn Dataset

Source: Kaggle

Dataset Link:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Note: The dataset is not included in this repository. Please download it from the Kaggle link above.

🛠️ Libraries Used
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Modules Used:

LabelEncoder
train_test_split
LogisticRegression
accuracy_score
precision_score
recall_score
f1_score
confusion_matrix
⚙️ Methodology
Imported the required Python libraries.
Loaded the dataset using Pandas.
Explored the dataset using head(), info(), and describe().
Identified features and target variable (Churn).
Checked for missing values.
Converted TotalCharges to numeric and handled missing values.
Encoded categorical variables using Label Encoding.
Split the dataset into 80% training and 20% testing data.
Trained a Logistic Regression model.
Predicted churn for test data.
Evaluated the model using Accuracy, Precision, Recall, and F1 Score.
Visualized results using Confusion Matrix.
📊 Results

The Logistic Regression model was successfully trained and evaluated using classification metrics.

Evaluation Metrics:

Accuracy
Precision
Recall
F1 Score

The model performs well overall but has some misclassifications, especially in identifying all churn customers.

✅ Conclusion

This project demonstrates the use of Logistic Regression for predicting customer churn. The model achieves good accuracy but misses some churn cases. Improving recall and using advanced models can further enhance performance.

📁 Repository Structure

Assignment-2/
│── Assignment-2.ipynb
│── README.md

Author

Name: Riya Shukla
Registration Number: 23BCE11293
Application Number: IN26012655
Batch Number: 2(B)
