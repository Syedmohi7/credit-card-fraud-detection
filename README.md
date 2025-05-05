# 💳 Credit Card Fraud Detection

### 🔍 A Machine Learning-Based Detection System Using Random Forest Classifier with GUI in Python

---

## 📌 Overview

Credit card fraud is a serious issue affecting millions of transactions worldwide. This project is a **GUI-based Python application** that helps detect fraudulent credit card transactions using a **Random Forest Classifier**. It is developed with **Tkinter** for the interface and **Scikit-learn** for machine learning operations.

---

## 🧠 Features

✅ Upload and read credit card transaction datasets (CSV)
✅ Split data into training and testing sets
✅ Train a Random Forest classifier model
✅ Predict and detect fraudulent transactions
✅ Display detailed results with transaction-wise predictions
✅ Visualize transaction statistics (fraud vs normal) using Matplotlib
✅ Interactive and user-friendly GUI

---

## 📂 Dataset

* The model uses a dataset with **31 columns**, including anonymized features (`V1` to `V28`), `Amount`, and `Class`.
* `Class`:

  * `0` → Legitimate transaction
  * `1` → Fraudulent transaction

You can use the public dataset available here:
📎 [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## ⚙️ Installation & Setup

### 🛠 Requirements

Make sure the following Python libraries are installed:

```bash
pip install numpy pandas matplotlib scikit-learn
```

### ▶️ Running the Application

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. **Run the main Python file**

```bash
python credit_card_fraud_gui.py
```

3. **Using the GUI Application**

* Click **Upload Credit Card Dataset** to load your dataset.
* Click **Generate Train & Test Model** to split the dataset.
* Click **Run Random Forest Algorithm** to train the model.
* Click **Detect Fraud From Test Data** to make predictions on a new test file.
* Click **Clean & Fraud Transaction Detection Graph** to visualize the results.

---

## 📊 Graph Output

The application displays a bar graph with:

* 🔵 Total Transactions
* 🟢 Legitimate Transactions
* 🔴 Fraudulent Transactions

This helps visually understand the fraud ratio in your test dataset.

---

## 🗂️ Project Structure

```
credit-card-fraud-detection/
│
├── credit_card_fraud_gui.py     # Main application file
├── dataset/                     # Folder to store your datasets
└── README.md                    # Project documentation
```

---

## 🧠 Model Used

**Random Forest Classifier**

* n\_estimators = 50
* max\_depth = 2
* class\_weight = 'balanced'

Why Random Forest?

* Handles imbalanced data better
* Provides high accuracy and robustness
* Reduces overfitting by aggregating multiple decision trees

---

## 👨‍💻 Developed By

**Syed Mohiuddin Jeelani Jaffri**
🎓 B.E in CSE with Data Science specialization
📍 Lords Institute of Engineering and Technology
📫 \[syedmohi143@gmail.com]

---

## 📄 License

This project is intended for **educational and academic purposes** only.

---
