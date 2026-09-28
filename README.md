<div align="center">

# 🫀 Medical Risk Prediction

### Cardiovascular disease risk stratification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![ROC-AUC](https://img.shields.io/badge/ROC--AUC-0.8117-success)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

## 📌 Overview

Cardiovascular disease is one of the leading causes of death worldwide, and early risk identification helps prioritize patient care. This project trains and compares multiple machine learning classifiers on the **UCI Heart Disease dataset**, selects the best-performing model, and converts its predicted probabilities into three easy-to-interpret risk tiers: **Low**, **Moderate**, and **Severe**.

## ✨ Highlights

- 📊 Trained on **920 patient records** from the UCI Heart Disease dataset
- 🤖 Compared **Random Forest, Gradient Boosting, and SVM**
- 🏆 Best model: **Gradient Boosting** with **ROC-AUC = 0.8117**
- 🚦 Reclassified predictions into **Low / Moderate / Severe** risk tiers

## 🗂️ Dataset

| Detail | Info |
|--------|------|
| **Source** | [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) |
| **Records** | 920 patients |
| **Features** | Age, sex, chest pain type, resting BP, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, ST depression |
| **Target** | Presence of heart disease |

## ⚙️ Methodology

```
Raw Data → Preprocessing → EDA → Model Training → Evaluation → Risk Stratification
```

1. **Preprocessing:** handle missing values, encode categorical variables, scale features
2. **Exploratory Analysis:** distributions, correlations, class balance
3. **Model Training:** Random Forest, Gradient Boosting, SVM
4. **Evaluation:** ROC-AUC, accuracy, precision, recall, F1-score
5. **Risk Stratification:** map predicted probabilities to risk tiers

## 📈 Results

| Model | ROC-AUC |
|-------|:-------:|
| Random Forest | `0.XXXX` |
| SVM | `0.XXXX` |
| **Gradient Boosting** ⭐ | **0.8117** |

### 🚦 Risk Tiers

| Tier | Probability Range | Meaning |
|------|:-----------------:|---------|
| 🟢 **Low** | `< 0.33` | Low likelihood of heart disease |
| 🟡 **Moderate** | `0.33 – 0.66` | Needs monitoring |
| 🔴 **Severe** | `> 0.66` | High likelihood, priority attention |

> Update the model scores and thresholds above to match your notebook.

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Data | pandas, NumPy |
| ML | scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |


```

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/gauravpathak50499/medical-risk-prediction.git
cd medical-risk-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook notebooks/risk_prediction.ipynb
```

## 🔮 Future Improvements

- [ ] Hyperparameter tuning with cross-validation
- [ ] SHAP-based explainability for individual predictions
- [ ] Deploy as a Streamlit / Flask web app
- [ ] Validate on external datasets

## ⚠️ Disclaimer

This project is for **educational purposes only** and is not a substitute for professional medical diagnosis or advice.

## 👨‍💻 Author

**Gaurav Pathak**
B.Tech CSBS, Techno India University, Kolkata


---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
