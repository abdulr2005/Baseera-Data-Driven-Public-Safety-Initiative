# 🛡️ Baseera | بصيرة — Data Analysis & Machine Learning

**Baseera** is a data-driven public-safety project that analyzes accidental drug-related mortality data and transforms the findings into accessible visual storytelling.

This repository contains the **data analysis and machine-learning side** of Baseera. The findings are presented to a broader audience through a separate bilingual interactive web report.

**[🌐 View the Interactive Report | عرض التقرير التفاعلي](https://abdulr2005.github.io/-Baseera-A-Vision-to-Save-Lives/)**  
**[💻 View the Web Report Repository](https://github.com/abdulr2005/-Baseera-A-Vision-to-Save-Lives)**

## 🎯 Project Overview

The analysis uses more than **9,200 records** of accidental drug-related deaths to explore:

- changes in mortality over time,
- demographic patterns,
- substances associated with recorded deaths,
- and patterns that can be explored through machine-learning models.

The overall workflow is:

**Raw Data → Cleaning & Analysis → Feature Engineering → Machine Learning → Insights → Interactive Web Report**

## 🛠️ Technical Stack

- **Data Analysis:** Python, Pandas, NumPy
- **Machine Learning:** Scikit-learn, XGBoost
- **Imbalanced Learning:** SMOTE / Imbalanced-Learn
- **Optimization:** GridSearchCV
- **Dimensionality Reduction:** PCA
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 🧠 Machine-Learning Workflow

### Data preparation
The project cleans and transforms the source data, engineers time-related information, and prepares features for modeling.

### Imbalanced data
**SMOTE** is used as part of the experimentation with class imbalance so minority cases are better represented during training.

### Dimensionality reduction
**PCA with 3 components** is explored as part of the modeling workflow.

### Model optimization
The project evaluates classification approaches and uses **GridSearchCV** for hyperparameter tuning. The strongest XGBoost experiment reached approximately **74% accuracy** while also considering recall during evaluation.

## 📊 Selected Findings

The dataset analysis highlighted several notable patterns:

- **Fentanyl** was linked to more than **5,670 recorded cases**.
- Approximately **74.2% of recorded victims were male**.
- Recorded deaths increased from **355 in 2012** to more than **1,500 in 2021**.

These are observations from the dataset analyzed in this project; they should be interpreted in the context of that dataset rather than as universal medical statistics.

## 📂 Repository Contents

- `Accidental_Drug_Related_Deaths.csv` — project dataset
- `Accidental_Drug_Related_Deaths.ipynb` — analysis and machine-learning workflow
- `README.md` — project documentation

## 🚀 Run the Analysis

```bash
git clone https://github.com/abdulr2005/Baseera-Data-Driven-Public-Safety-Initiative.git
cd Baseera-Data-Driven-Public-Safety-Initiative
```

Open `Accidental_Drug_Related_Deaths.ipynb` in Jupyter Notebook and run the analysis cells.

## 🌐 From Analysis to Data Storytelling

Instead of stopping at a notebook or static report, the project findings were transformed into a **bilingual Arabic/English interactive web experience** using HTML, CSS, JavaScript, and Chart.js.

That presentation layer is maintained separately in the [Baseera web-report repository](https://github.com/abdulr2005/-Baseera-A-Vision-to-Save-Lives).

---

> **Disclaimer:** This project is for educational, analytical, and awareness purposes. It is not medical advice or an emergency-response service.
