# 🏥 County Health Tree Model

This project applies decision tree models to analyze county-level public health indicators in the U.S., aiming to identify key risk factors and predict overall health outcomes.

---

## 📌 Overview

- **Goal**: Predict county-level health outcomes and reveal interpretable drivers of public health disparities.
- **Method**: CART (Classification and Regression Trees) applied to structured health indicators.
- **Focus**: Smoking rates, obesity, uninsured percentage, education level, income inequality, etc.

---

## 📁 Files

| File | Description |
|------|-------------|
| `countyhealth_dataset.csv` | Cleaned dataset containing county-level health and demographic indicators |
| `countyhealth_treemodel_presentation.ipynb` | Jupyter Notebook including preprocessing, modeling, and visualization |
| `countyhealth_treemodel_report.html` | Rendered report with model output and key findings |

---

## 🧰 Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- CART (DecisionTreeRegressor / Classifier)

---

## 📊 Key Results

- Smoking and lack of insurance emerged as consistent top predictors of worse health scores.
- Decision trees provided clear visual interpretation of risk thresholds.
- The model demonstrated reasonable accuracy and high interpretability for policy support.

---

## 📎 Data Source

The dataset (`countyhealth_dataset.csv`) is adapted from the publicly available County Health Rankings data, compiled by the [University of Wisconsin Population Health Institute](https://www.countyhealthrankings.org/). Variables were selected and preprocessed for the purpose of this course project.


---

## ✍️ Author

**Xinyue Ha**  
MA in Statistics, Washington University in St. Louis  
🔗 [LinkedIn](www.linkedin.com/in/xinyue-ha-a0955b351) | 📧 xinyue.ha0236@gmail.com

