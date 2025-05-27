# GROUP_6_TITANIC-SURVIVAL-PREDICTION
# 🚢 Titanic Survival Prediction

This project focuses on predicting the survival of passengers aboard the RMS Titanic using machine learning techniques. It is a classic binary classification problem and serves as an excellent introduction to data science and predictive modeling.

## 📁 Dataset

- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- **Files**:
  - `train.csv` – Training dataset with labeled survival outcomes.
  - `test.csv` – Test dataset for making predictions.
  - `gender_submission.csv` – Example submission file.

## 🎯 Problem Statement

Given information about the passengers such as age, sex, ticket class, etc., the goal is to predict whether a passenger survived (`Survived = 1`) or not (`Survived = 0`) during the Titanic shipwreck.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for data visualization)
- Scikit-learn
- Jupyter Notebook / Google Colab

## 🔍 Data Preprocessing

Key preprocessing steps included:
- Handling missing values (e.g., imputing age and embarked values)
- Encoding categorical variables (e.g., Sex, Embarked)
- Feature engineering (e.g., extracting titles from names, creating family size feature)
- Scaling numerical features

## 🤖 Modeling

Models experimented with:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Model performance was evaluated using cross-validation and accuracy scores.

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC-AUC Curve (if applicable)

## ▶️ How to Run

1. Clone the repository:
