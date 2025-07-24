#  Bank Marketing Campaign Prediction using Decision Tree Classifier

This project explores a **supervised machine learning approach** using a **Decision Tree Classifier** to predict whether a bank customer is likely to subscribe to a term deposit, based on the Bank Marketing dataset. The model helps understand key decision rules and patterns behind customer conversions, enabling smarter targeting for future marketing campaigns.

---

## 📂 Dataset

- **Source**: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Format**: CSV
- **Target Variable**: `deposit` (yes/no — whether the customer subscribed)

---

## 🔍 Objectives

- Predict the likelihood of a deposit using customer and campaign data
- Extract **human-readable decision rules**
- Evaluate model performance using accuracy, precision, recall, and F1-score
- Visualize the **decision tree** and other exploratory insights

---

## 📊 Visualizations Included

- Heatmap of feature correlations
- Value counts for target variable (`deposit`)
- Bar charts for categorical feature distributions
- Pie chart for deposit class ratio
- Decision Tree plot
- Text-based decision rules using `export_text()`
- Classification Report & Confusion Matrix

---

## 📌 Tools & Libraries

- Python
- Google Colab
- pandas, numpy, matplotlib, seaborn
- scikit-learn (for modeling & evaluation)

---

## 🧾 Project Highlights

- No paid APIs or third-party services required
- Beginner-friendly ML classification project
- Useful for portfolio, learning tree-based models, and campaign optimization

---

## 📁 Folder Structure

```bash
├── bank_marketing_decision_tree.ipynb   # Main notebook
├── bank_full.csv                             # Dataset 
├── README.md                            # Project overview
└── LICENSE                              # Open-source license (MIT)
