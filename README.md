# 🍷 Red Wine Quality Prediction

This repository contains a Machine Learning project that predicts the quality of red wine based on its physicochemical properties using classification algorithms.

---

## 📌 Project Overview
The quality of wine is traditionally evaluated by human sensory tests. This project leverages Machine Learning to automate and objectively predict whether a red wine is of **Good** or **Bad** quality based on chemical feature analysis.

---

## 📊 Dataset Description
- **Source:** UCI Machine Learning Repository (Red Wine Quality Dataset)
- **Features:** 11 chemical attributes including `alcohol`, `volatile acidity`, `sulphates`, `pH`, `density`, etc.
- **Target Variable (`quality_label`):**
  - **1 (Good):** Wine quality score $\ge 6$
  - **0 (Bad):** Wine quality score $< 6$

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:**
  - `pandas`, `numpy` (Data Manipulation & Cleaning)
  - `scikit-learn` (Model Building & Scaling)
  - `matplotlib`, `seaborn` (Data Visualization)

---

## 📈 Model Performance & Results

| Model | Accuracy | Precision (Good) | Recall (Good) | F1-Score (Good) |
| :--- | :---: | :---: | :---: | :---: |
| **Logistic Regression** | 73.53% | 0.76 | 0.73 | 0.74 |
| **Decision Tree** | 62.50% | 0.64 | 0.66 | 0.65 |
| **Random Forest** ⭐ | **76.84%** | **0.80** | **0.75** | **0.77** |

> 🏆 **Best Model:** **Random Forest Classifier** achieved the highest accuracy of **76.84%**.

---

## 💡 Key Insights
1. **Alcohol Content:** The most critical chemical factor influencing high-quality red wine.
2. **Sulphates & Volatile Acidity:** Secondary important attributes that impact wine quality classification.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/fa-elma/Wine_Quality_prediction.git](https://github.com/fa-elma/Wine_Quality_prediction.git)
