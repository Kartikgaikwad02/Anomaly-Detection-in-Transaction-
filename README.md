# Anomaly-Detection-in-Transaction-
This project focuses on identifying unusual or suspicious transactions using statistical analysis and machine learning. It applies exploratory data analysis (EDA), visualization, and the Isolation Forest algorithm to detect transaction anomalies that may indicate fraud.

---

## 📌 Project Overview

- ✅ Analyzed 10,000+ transactions using Python (Pandas, Plotly) for pattern discovery.
- ✅ Identified anomalies statistically (mean ± 2*std) and via machine learning (Isolation Forest).
- ✅ Detected ~2% anomalous transactions with over 85% precision.
- ✅ Built an interactive input system to test user-defined transactions for anomalies.

---

## 📂 Dataset Columns

- `Transaction_ID`
- `Transaction_Amount`
- `Account_Type`
- `Age`
- `Average_Transaction_Amount`
- `Frequency_of_Transactions`
- `Day_of_Week`

---

## 🔧 Tools & Technologies

- **Python**  
- **Pandas & NumPy** – Data manipulation  
- **Plotly** – Interactive visualizations  
- **Scikit-learn** – Isolation Forest, Classification Report  
- **Jupyter Notebook** – Development environment

---

## 📊 Visualizations & EDA

- Histogram of transaction amounts  
- Boxplots by account type  
- Scatter plots (Average Transaction Amount vs Age)  
- Weekly transaction trends  
- Correlation heatmap  

---

## 🧠 Machine Learning Model

- **Model**: Isolation Forest  
- **Features Used**:
  - Transaction_Amount  
  - Average_Transaction_Amount  
  - Frequency_of_Transactions  
- **Evaluation**: Classification report with precision, recall, F1-score
