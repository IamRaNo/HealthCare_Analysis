# ❤️ Heart Disease Severity Analysis and Prediction

This project uses the **UCI Heart Disease Dataset** to analyze and predict the severity of heart disease. We cleaned the data, explored it using graphs and statistics, and built a machine learning model.

---

## 📁 Dataset Details

- Source: UCI Heart Disease Dataset
- 920 rows, 16 columns
- Target column: `Result` (shows heart disease severity from 0 to 4)

---

## 🎯 Project Objectives

- Find what factors are causing heart disease.
- Predict severity of heart disease using ML models.
- Visualize and understand the important patterns.

---

## 🔧 Tools Used

- Python
- Pandas and NumPy for data work
- Seaborn and Matplotlib for graphs
- Scikit-learn for machine learning
- Jupyter Notebook

---

## 🧹 Data Cleaning

- Removed unnecessary column `Id`
- Renamed confusing column names
- Fixed missing values using:
  - KNN for number columns
  - Mode for binary columns
  - 'Undefined' for categories like `thalassemia`
- Converted float columns back to integer

---

## 📊 Data Analysis

### Univariate (Single Column) Observations
- Average age = 53
- 80% of patients are male
- Most chest pain type = Asymptomatic

### Bivariate (Two Columns) Observations
- High `ST depression` and `exercise angina` → higher severity
- Lower `max heart rate` → higher severity

---

## 🤖 Machine Learning

- Used **Random Forest Classifier**
- Accuracy = 83%
- Train/test = 80% train, 20% test

---

## 📌 Results

- Important columns for prediction:
  - `ST Depression`
  - `Max Heart Rate`
  - `Exercise Angina`
  - `Affected Coronary Vessels`
- Older males have more risk
- Some countries (like Hungary) had more mild cases

---

---

## 🔮 Future Improvements

- Try other ML models
- Tune model parameters for better accuracy
- Deploy the model using Streamlit or Flask

---

## 🙏 Thanks

- Dataset from UCI ML Repository
- Tools from Scikit-learn, Pandas, Seaborn



