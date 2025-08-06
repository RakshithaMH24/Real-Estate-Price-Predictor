<div align="center">

# 🏡 Real Estate Price Predictor

### 📈 A Machine Learning project to forecast housing prices using the Boston Housing Dataset  
**Built with Python • Jupyter Notebook • Scikit-learn**

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

</div>

---

## 📌 Overview

This project demonstrates how **machine learning models** can predict real estate prices based on key features such as crime rate, average rooms, distance to employment centers, and more.

The goal is to provide a data-driven approach for:
- 🏢 Real estate developers
- 🏠 Home buyers
- 💰 Investors

To make **informed decisions** using historical housing data.

---

## 🎯 Objective

Build a regression model that accurately predicts house prices based on the following key attributes:
- Number of rooms
- Local crime rates
- Proximity to highways and rivers
- Pollution levels (NOx)
- Tax rate and more

---

## 📊 Dataset: Boston Housing

- 📁 506 entries, 13 features + 1 target (MEDV)
- 📌 Source: UCI Machine Learning Repository

| Feature | Description |
|--------|-------------|
| CRIM | Crime rate |
| ZN | Land zoned for large lots |
| INDUS | Non-retail business area |
| CHAS | Bounded by river |
| NOX | Pollution |
| RM | Rooms per dwelling |
| AGE | Older units % |
| DIS | Distance to jobs |
| RAD | Highway access |
| TAX | Property tax |
| PTRATIO | Student-teacher ratio |
| B | Black population proportion |
| LSTAT | % lower-status |
| MEDV | 🏷️ Target price |

---

## ⚙️ Tech Stack

- **Languages & Tools**: Python, Jupyter Notebook
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn
- **Model**: Linear Regression + Evaluation Metrics

---

## 🚀 Features

✨ Cleaned and processed real-world housing data  
📊 EDA with beautiful and insightful visualizations  
🧠 Trained Linear Regression model  
📈 Performance evaluated using RMSE, MAE  
📤 Predict prices using new feature input  

---

## 📈 Model Performance

- ✅ **Root Mean Squared Error (RMSE)** – Main metric
- 📉 MAE (Mean Absolute Error)
- 📍 L1 Norm (Manhattan Distance)

> RMSE is chosen as it penalizes large prediction errors — ideal for real estate applications.

---

## 📂 Project Structure

```
├── Real Estate-Prediction.ipynb      # Main notebook
├── data.csv                          # Cleaned dataset
├── housing.data, housing.names       # Raw dataset
├── Dragon.joblib                     # Saved ML model
├── Outputs from different models.txt # Evaluation results
```

---

## ▶️ Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/RakshithaMH24/Real-Estate-Price-Predictor.git
cd Real-Estate-Price-Predictor
```

### 2. Launch Notebook
```bash
jupyter notebook Real\ Estate-Prediction.ipynb
```

---

## 🛠️ Future Improvements

- 🔧 Add Streamlit/Flask UI
- 🎯 Hyperparameter tuning
- 📦 Add more regression models (e.g., XGBoost)
- 🌐 Deploy on web

---

## 👩‍💻 Author

**Rakshitha M H**  
🔗 [GitHub](https://github.com/RakshithaMH24)  
🔗 [LinkedIn](https://www.linkedin.com/in/your-link) <!-- Replace with your actual link -->

---

<div align="center">

⭐ *If you found this useful, give it a star!*  
📬 *Feedback is always welcome!*

</div>
