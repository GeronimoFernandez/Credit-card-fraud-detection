# Credit Card Fraud Detection

End-to-end Machine Learning project focused on detecting fraudulent credit card transactions using highly imbalanced financial datasets and classification models optimized through threshold tuning.

---

# 🎯 Business Problem

Credit card fraud generates billions of dollars in financial losses every year.  
The objective of this project is to build a fraud detection system capable of identifying fraudulent transactions with high recall while minimizing false positives.

---

# 📊 Key Results

- **ROC-AUC:** 0.996
- **Recall:** 82%
- **Precision:** 63%
- **Cross Validation ROC-AUC:** 0.9948 ± 0.0014

The final XGBoost model was optimized using threshold tuning techniques to achieve a better balance between fraud detection and alert precision.

---

# 🧠 Models Evaluated

| Model | ROC-AUC | Recall | Precision | F1-Score |
|--------|---------|--------|-----------|----------|
| Logistic Regression | 0.913 | 0.76 | 0.04 | 0.07 |
| Random Forest | 0.939 | 0.77 | 0.12 | 0.21 |
| XGBoost (threshold 0.5) | 0.996 | 0.97 | 0.19 | 0.32 |
| **XGBoost (threshold 0.9)** | **0.996** | **0.82** | **0.63** | **0.71** |

---

# ⚙️ Machine Learning Pipeline

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Handling Class Imbalance  
5. Model Training  
6. Threshold Optimization  
7. Model Evaluation  

---

# 🛠️ Technologies Used

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

---

# 📁 Project Structure

```txt
Credit_Card_Fraud_Project/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│
├── notebooks/
│
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 How to Run

```bash
git clone https://github.com/GeronimoFernandez/Credit-card-fraud-detection.git

cd Credit_Card_Fraud_Project

pip install -r requirements.txt
```

---

# 📂 Dataset

The original datasets are not included in this repository due to GitHub file size limitations.

This project uses the Credit Card Fraud Detection dataset available on Kaggle:

https://www.kaggle.com/datasets/kartik2112/fraud-detection

After downloading the datasets, place the files inside:

```txt
data/raw/
```

---

# 🔮 Future Improvements

- FastAPI deployment
- Streamlit dashboard
- Real-time fraud prediction
- MLflow experiment tracking
- Docker containerization

---

# 👤 Author

**Geronimo Fernandez**  
Data Scientist | Machine Learning Enthusiast
---

# 📄 License

This project is licensed under the MIT License.
