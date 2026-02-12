# 🛡️ Baseera | بصيرة 
### **Empowering Communities through Data-Driven Insights**

**[🔗 View Live Report | عرض التقرير المباشر]( https://github.com/abdulr2005/-Baseera-A-Vision-to-Save-Lives.git )**

**Baseera** (Arabic for "Insight") is a data science initiative and public safety platform designed to combat the drug overdose crisis. This project transforms complex medical datasets and machine learning outcomes into clear, life-saving awareness tools for the general public.

---

## 🚀 Project Overview
This project analyzes over **9,200 records** of accidental drug-related deaths to identify trends, high-risk demographics, and lethal substance patterns.

### **Key Features:**
* **Live Interactive Dashboard:** **[Explore the Report](YOUR_URL_HERE)**
* **Visual Analytics:** Interactive trends showing the 300%+ surge in cases over the last decade.
* **ML-Driven Insights:** Substance risk profiling using advanced classification models.* **ML-Driven Insights:** Substance risk profiling using advanced classification models.
* **Bilingual Dashboard:** Fully responsive UI supporting both **Arabic and English**.
* **Emergency Guide:** A practical "First Responder" guide for overdose situations (Narcan/Naloxone).

---

## 🛠️ Technical Stack
* **Data Science:** Python (Pandas, NumPy)
* **Machine Learning:** Scikit-Learn, XGBoost, Imbalanced-Learn (SMOTE)
* **Frontend:** HTML5, CSS3 (Sticky UI Architecture), JavaScript (ES6+, Intersection Observer API)
* **Visualization:** Chart.js, Matplotlib, Seaborn

---

## 🧠 Machine Learning Pipeline
I implemented a robust engineering-first approach to handle real-world medical data:

### **1. Data Engineering & Preprocessing**
* **Feature Engineering:** Converted temporal data into Unix Timestamps to capture time-based growth.
* **Handling Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to ensure the model learns from critical minority cases.
* **Dimensionality Reduction:** Used **PCA (Principal Component Analysis)** with `n_components=3` to optimize model focus and reduce noise.

### **2. Model Selection & Optimization**
* **XGBoost (Champion Model):** Achieved an accuracy of **~74%** with high recall, optimized via **GridSearchCV** to prioritize public safety sensitivity.

---

## 🎨 Frontend Highlights
* **Lazy Loading Charts:** Graphs animate only when scrolled into view using the **Intersection Observer API**.
* **Storytelling UI:** A sticky-section layout that guides the user from data facts to medical reality and finally to action steps.
* **Localization Engine:** A custom JS-based translation system for seamless language switching.

---

## 📊 Key Insights
* **The Fentanyl Crisis:** Linked to over **5,670 cases**, making it the primary target for awareness.
* **Gender Gap:** Statistics revealed that **74.2% of victims were male**, guiding targeted intervention strategies.
* **Temporal Surge:** Deaths increased from **355 in 2012** to over **1,500 in 2021**.

---

## 📂 Installation & Usage
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/abdulr2005/baseera.git](https://github.com/abdulr2005/baseera.git)
    ```
2.  **Run Analysis:** Open the Jupyter Notebook `Accidental_Drug_Related_Deaths.ipynb`.
3.  **View Dashboard:** Launch `index.html` in any modern web browser.

---

## 👨‍💻 Developed By
**Abdulrahman El-Essawi**
* *Data Science & Robotics Enthusiast*
* [LinkedIn](https://www.linkedin.com/in/abdulrahmn-essawi-785543358/) | [GitHub](https://github.com/abdulr2005)

---
*Disclaimer: This project is intended for educational and awareness purposes only. In case of emergency, always contact local medical services immediately.*
