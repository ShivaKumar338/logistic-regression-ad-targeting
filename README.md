# 🧠 Predictive Modeling for Click-Through Rate Optimization at ConnectSphere Digital

## 📘 Project Overview
This project focuses on improving the efficiency of online advertising campaigns through **predictive modeling**.  
ConnectSphere Digital aims to identify users who are **most likely to click on ads**, thereby reducing wasted ad spend and maximizing campaign performance.

Using **Logistic Regression**, the model predicts whether a user will click on an advertisement based on **demographic** and **behavioral data**.

---

## 🎯 Objective
The main goal of this project is to build and evaluate a **Logistic Regression** model that predicts the likelihood of a user clicking on an online advertisement.

**The model classifies users as:**
- `1 → Likely to Click`
- `0 → Unlikely to Click`

### 🧩 Key Features Used
- `Age`
- `Area Income`
- `Daily Time Spent on Site`
- `Daily Internet Usage`
- `Male` (Gender)

---

## 💼 Business Objective
By integrating this predictive model into its ad strategy, **ConnectSphere Digital** can:
- Optimize ad targeting and reduce wasteful impressions.
- Improve **Click-Through Rate (CTR)** and **Return on Ad Spend (ROAS)**.
- Enhance **client satisfaction** through data-driven decisions.

---

## ⚙️ Technical Approach

1. **Data Loading & Preprocessing**
   - Load dataset, check for null values, and encode categorical variables.
   - Normalize numeric features using `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships between features and target variable using Seaborn.
   - Identify trends affecting ad clicks.

3. **Model Development**
   - Build a **Logistic Regression** classifier using Scikit-learn.
   - Train and test split: 70% training, 30% testing.

4. **Model Evaluation**
   - Metrics used: **Accuracy**, **Precision**, **Recall**, **F1-Score**.
   - Visualize results using a confusion matrix.

5. **Prediction**
   - Predict ad click likelihood for new users.

---

## 🧮 Technologies Used
- **Python 3**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Project Files in This Repository
| File Name | Description |
|------------|-------------|
| `ctr_prediction.ipynb` | Main Jupyter Notebook containing full implementation (data analysis, model training, and evaluation). |
| `project_report.pdf` | Final report summarizing the project overview, results, and business impact. |
| `README.md` | Project documentation and description (this file). |
| `requirements.txt` | List of Python dependencies for running the project. |

*(Add or rename files in this table if your filenames differ.)*

---

## 📊 Dataset
**Source:** [Advertising Dataset (Google Drive)](https://drive.google.com/file/d/1J5yqeokVKRrBZXrNxxnwXN_jGG4pUybL/view)

**Target Variable:**  
`Clicked on Ad` → (1 = Clicked, 0 = Not Clicked)

---

## 📈 Results
- The Logistic Regression model achieved high accuracy in predicting user click behavior.
- Key metrics (example output):

