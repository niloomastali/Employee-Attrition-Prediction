# 👥 Employee Attrition Prediction
### HR Analytics · Deep Learning · Random Forest · Logistic Regression

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange?style=flat-square&logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Google_Colab-yellow?style=flat-square)

> **Coursera Project** · Niloofar Mastali · 2024

---

## 📌 Overview

This project predicts **employee attrition** (whether an employee will leave the company) using HR data. Three different ML/DL models are trained and compared to find the best approach for this classification task.

---

## 🎯 Key Features

- 📊 Full **Exploratory Data Analysis (EDA)** with visualizations
- 🔢 Feature engineering with **OneHotEncoder** and **MinMaxScaler**
- 🤖 Three models compared:
  - Logistic Regression
  - Random Forest Classifier
  - Deep Learning (TensorFlow/Keras)
- 📈 Evaluation with Confusion Matrix and Classification Report

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Main language |
| TensorFlow / Keras | Deep Learning model |
| Scikit-learn | ML models & preprocessing |
| Pandas / NumPy | Data processing |
| Seaborn / Matplotlib | Visualization |
| Google Colab | Cloud execution |

---

## 📁 Project Structure

```
employee-attrition-prediction/
│
├── Employee_Attrition.ipynb    # Main Jupyter Notebook
├── README.md                   # This file
└── LICENSE                     # MIT License
```

---

## 🔄 ML Pipeline

```
Data Loading → EDA → Preprocessing → Feature Engineering → Model Training → Evaluation
```

**Steps:**
1. **EDA** — Histograms, KDE plots, correlation heatmap
2. **Preprocessing** — Drop irrelevant columns, encode binary columns
3. **Feature Engineering** — OneHotEncoder for categorical, MinMaxScaler for numerical
4. **Model 1** — Logistic Regression
5. **Model 2** — Random Forest Classifier
6. **Model 3** — Deep Neural Network (3 hidden layers, 500 neurons each)
7. **Evaluation** — Confusion Matrix, Accuracy, Classification Report

---

## 📊 Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Samples:** 1,470 employees
- **Features:** 35 attributes (age, job role, salary, satisfaction, etc.)
- **Target:** Attrition (Yes/No)

---

## ⚠️ Disclaimer

This project is for **educational purposes only** as part of a Coursera course.

---

## 👩‍💻 Author

**Niloofar Mastali**
M.Sc. Computer Software Engineering (ML & AI)

📧 niloofar2020@gmail.com
🌍 Wien, Austria
🌐 [niloomastali.github.io](https://niloomastali.github.io)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

*⭐ If you found this helpful, please give it a star!*
