# Credit-Card-Fraud-Detection-model-Machine-Learning-project

 An end-to-end machine learning project to detect fraudulent credit card transactions using a simple yet effective Logistic Regression model.

This project demonstrates the steps involved in preprocessing, training, and evaluating a classification model on a real-world, imbalanced dataset. It focuses on clear explanations and interpretable results — ideal for data science beginners and portfolio building.

## 📂 Dataset

Source: Kaggle - Credit Card Fraud Detection

Size: 284,807 transactions

Classes:

0 → Legitimate transaction

1 → Fraudulent transaction (minority class)

## 🧰 Tools and Libraries

Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn (LogisticRegression, metrics, train_test_split)

## 🧪 Project Workflow

# 1. Data Cleaning

Removed 1,081 duplicate rows to improve data quality

Dropped Time column as it had no predictive significance

# 2. Feature Scaling

Applied StandardScaler to normalize the features

# 3. Model Building

Used Logistic Regression from Scikit-learn

Trained on the original imbalanced dataset

# 4. Evaluation Metrics

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

# 5. Final Results (Test Set)

Metric

Class 0 (Normal)

Class 1 (Fraud)

Precision

0.90

0.96

Recall

0.95

0.91

F1-score

0.93

0.93

Accuracy

93% overall

📌 Conclusion: The model performs well even without resampling, achieving high recall on the minority class.

## 📈 Confusion Matrix
A heatmap was generated to visualize how well the model differentiates between fraud and legitimate transactions.

## 📦 Future Improvements

Apply SMOTE or undersampling to handle class imbalance

Try more powerful models like Random Forest or XGBoost

Use GridSearchCV for hyperparameter tuning

Deploy as a web app using Streamlit

## 🙋‍♀️ About Me

I'm a data science enthusiast passionate about solving real-world problems through data. Feel free to connect with me on LinkedIn!
