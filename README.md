# 💳 Credit Card Fraud Detection using Machine Learning

A Machine Learning project that detects fraudulent credit card transactions using multiple classification algorithms and imbalance handling techniques. Since fraud transactions are extremely rare compared to genuine transactions, this project applies data preprocessing, SMOTE oversampling, and anomaly detection methods to improve prediction performance.

---

## 📌 Project Overview

Credit card fraud detection is one of the most important applications of Machine Learning in the financial sector. The dataset used in this project is highly imbalanced, where fraudulent transactions represent only a small fraction of the total data.

This project demonstrates how different machine learning models perform on imbalanced data after applying preprocessing and balancing techniques.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions accurately.
- Handle highly imbalanced datasets using SMOTE.
- Compare the performance of multiple Machine Learning models.
- Explore anomaly detection using Isolation Forest.
- Evaluate models using standard classification metrics.

---

## 🚀 Features

- Data preprocessing and cleaning
- Feature scaling using StandardScaler
- Handling class imbalance using SMOTE
- Train-Test Split
- Logistic Regression model
- Random Forest Classifier
- XGBoost Classifier
- Isolation Forest (Anomaly Detection)
- Model comparison using accuracy scores
- Performance evaluation with confusion matrix and classification report
- Data visualization

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Jupyter Notebook

---

## 📂 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── project_4.ipynb          # Main Jupyter Notebook
├── creditcard.csv           # Dataset (Not included if large)
├── README.md
```

---

## 📊 Workflow

1. Import required libraries
2. Load the credit card dataset
3. Explore class imbalance
4. Visualize fraud vs genuine transactions
5. Perform feature scaling
6. Split dataset into training and testing sets
7. Apply SMOTE for balancing classes
8. Train multiple machine learning models
9. Evaluate model performance
10. Compare model accuracy
11. Detect anomalies using Isolation Forest

---

## 🤖 Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Isolation Forest

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📉 Data Preprocessing

- Removed unnecessary features
- Standardized transaction amount
- Handled class imbalance using SMOTE
- Split dataset into training and testing data

---

## 📊 Visualizations

The project includes:

- Fraud vs Normal Transaction Distribution
- Model Accuracy Comparison
- Confusion Matrices

---

## 💡 Key Learning Outcomes

- Working with highly imbalanced datasets
- Applying SMOTE for oversampling
- Comparing multiple ML algorithms
- Understanding anomaly detection techniques
- Evaluating classification models effectively

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
```

2. Navigate to the project folder

```bash
cd Credit-Card-Fraud-Detection
```

3. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

4. Open the notebook

```bash
jupyter notebook project_4.ipynb
```

5. Run all cells.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deep Learning implementation
- Real-time fraud detection API
- Model deployment using Flask or Streamlit
- Interactive dashboard

---

## 📚 Dataset

The project uses the **Credit Card Fraud Detection Dataset**, which contains anonymized credit card transactions labeled as fraudulent or genuine.

> Note: Due to GitHub file size limitations, the dataset may not be included in this repository.

---

## 👨‍💻 Author

**Hemang Chouhan**

B.Tech CSE (AI & Data Science)

Interested in Machine Learning, Artificial Intelligence, Data Science, and Software Development.

---

## ⭐ If you found this project useful, don't forget to Star the repository!
