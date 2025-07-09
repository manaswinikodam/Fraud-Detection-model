# Credit Card Fraud Detection

A machine learning project focused on identifying fraudulent credit card transactions using real-world, imbalanced datasets. This project also emphasizes clarity in documentation to make complex models accessible to both technical and non-technical audiences.



##  Project Overview

This project leverages various machine learning algorithms to detect credit card fraud. It provides an end-to-end walkthrough of data exploration, model development, dimensionality reduction, and handling class imbalance, with an added layer of user-friendly documentation throughout the process.

The aim is to not only build a high-performing model but also to document it in a way that anyone can understand and replicate.



## Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains **284,807 transactions** with only **492 frauds** (high class imbalance).
- Includes anonymized features `V1` to `V28`, `Time`, `Amount`, and `Class`.



##  Technologies Used

- Languages: Python  
- Libraries: Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn  
- Techniques: PCA (dimensionality reduction), SMOTE (class balancing), Reinforcement Learning  
- Tools: Google Colab, Jupyter Notebook


#  Key Features

- **Exploratory Data Analysis** – with clearly explained visualizations and insights  
- **Multiple ML Models** – compared based on accuracy and F1-score  
- **Class Imbalance Handling** – using SMOTE  
- **Dimensionality Reduction** – using PCA for performance optimization  
- **Security Enhancement** – integrated a time-based CVV generator concept  
- **Beginner-Friendly Documentation** – step-by-step guidance in both code and explanations  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection.git
   cd fraud-detection
2.pip install -r requirements.txt


3.jupyter notebook CreditCardFraudDetection.ipynb

