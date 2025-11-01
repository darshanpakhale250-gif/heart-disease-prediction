# Heart Disease Prediction

Predicts the presence of heart disease from clinical data using machine learning.  
This project includes exploratory data analysis, visualization (boxplots, heatmaps), preprocessing, and model training & comparison using Logistic Regression, Decision Tree, and Random Forest. It also exports and visualizes tree structures using Graphviz.

---

## 🚀 Project Overview
The dataset contains patient clinical features (age, chest pain type, blood pressure, cholesterol, etc.) and a target label `target` (0 = no disease, 1 = disease). The goal is to build models that classify whether a patient has heart disease, compare model performance, and visualize decision trees.

---

## 🔬 What this repo contains
- `heart_disease_project.py` — main script (analysis, visualizations, model training & evaluation).
- `requirements.txt` — Python dependencies.
- `.gitignore` — common files to ignore.
-  Notebook version for step-by-step exploration: `Heart_Disease_Project.ipynb`.
-  also .py file 

---

## 🧭 Key steps performed
1. Data loading and inspection (mean, min, max, quartiles, correlation)  
2. Visualization: boxplots, countplots, heatmap, bar plots  
3. Model training & evaluation:
   - Logistic Regression
   - Decision Tree (with depth tuning)
   - Random Forest (single-tree inspection + saving tree PDFs)
4. Model metrics: accuracy, confusion matrix, classification report (precision, recall, f1)
5. Export and visualize trees using Graphviz (saving PDFs)

---

## 📦 Requirements & Setup

1. Clone repo:
   ```bash
   git clone https://github.com/<your-username>/heart-disease-prediction.git
   cd heart-disease-prediction
