# Subscription Conversion Prediction Using Machine Learning

## 📌 Project Overview

Subscription-based businesses have many free users, but only a portion of them convert into paid subscribers. This project uses **Artificial Intelligence and Machine Learning** to predict which free users are likely to become paid customers based on their engagement behavior.

The project is designed as a **supervised binary classification** problem where the model predicts whether a user will convert to a paid subscription.

---

## 🎯 Business Problem

The objective is to identify free users who have a higher likelihood of converting into paid subscribers.

This prediction can help businesses:

* Identify high-potential users
* Prioritize conversion campaigns
* Personalize offers and messaging
* Improve marketing efficiency
* Understand user engagement signals related to conversion

---

## 🤖 Machine Learning Problem

This project is a **Supervised Binary Classification** problem.

### Target Variable

`Converted`

* `1` → User became a paid subscriber
* `0` → User did not become a paid subscriber

---

## 📊 Dataset

The dataset contains user-level engagement information.

### Features Used

| Feature                | Description                                        |
| ---------------------- | -------------------------------------------------- |
| `Age`                  | Age of the user                                    |
| `Days_Since_Signup`    | Number of days since signup                        |
| `Sessions`             | Number of user sessions                            |
| `Visits`               | Number of visits                                   |
| `Features_Used`        | Number of product features used                    |
| `Avg_Session_Minutes`  | Average session duration                           |
| `Trial_Days_Used`      | Number of trial days used                          |
| `Support_Interactions` | Number of support interactions                     |
| `Converted`            | Target variable indicating subscription conversion |

The raw dataset used in the project contains **119 records and 10 columns** before preprocessing.

---

## 🔄 Project Workflow

```text
Raw User Data
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Train / Test Split
      ↓
Machine Learning Models
      ↓
Model Evaluation
      ↓
Best Model Selection
      ↓
Conversion Probability Prediction
```

---

## 🧠 Machine Learning Models

Three classification algorithms are used and compared:

### 1. Logistic Regression

Used as an interpretable baseline classification model.

### 2. Decision Tree Classifier

Captures non-linear relationships and decision rules in the data.

### 3. Random Forest Classifier

Uses an ensemble of multiple decision trees to make predictions.

---

## 📏 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix
* Classification Report

These metrics help compare model performance from different perspectives.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 📁 Project Files

```text
subscription-conversion-prediction-ml/
│
├── Subscription_Conversion_Prediction_ML_Project_Final.ipynb
├── subscription_conversion_100_users_dirty.csv
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/subscription-conversion-prediction-ml.git
```

### 2. Open the notebook

Open:

```text
Subscription_Conversion_Prediction_ML_Project_Final.ipynb
```

You can run it using **Google Colab** or **Jupyter Notebook**.

### 3. Upload the dataset

Upload:

```text
subscription_conversion_100_users_dirty.csv
```

when prompted by the notebook.

### 4. Run the cells

Execute the notebook cells in sequence to perform data analysis, preprocessing, model training and evaluation.

---

## 💡 Key Project Output

The final system predicts the probability that a free user will convert into a paid subscriber.

```text
User Activity
     ↓
Machine Learning Model
     ↓
Conversion Probability
     ↓
Likely to Subscribe / Less Likely to Subscribe
```

---

## 📌 Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Cross-validation
* Larger real-world datasets
* Feature importance analysis
* Interactive dashboard using Power BI
* Deployment as a web application
* Real-time subscription conversion prediction
* Integration with customer marketing systems

---

## 👨‍💻 Project Author

**Arun Bhardwaj**


---

## ⭐ Project Objective

The main objective of this project is to demonstrate how **Machine Learning can be used to analyze user engagement behavior and predict subscription conversion**, supporting data-driven customer acquisition and marketing decisions.
