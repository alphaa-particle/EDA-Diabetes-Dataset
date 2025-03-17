# Diabetes Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a **Diabetes Dataset** to understand patterns, trends, and relationships between different health indicators. The analysis includes data cleaning, visualization, and statistical insights to help identify key factors associated with diabetes.

## 📂 Dataset
The dataset contains medical information such as:
- **Pregnancies**
- **Glucose Levels**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin Levels**
- **BMI (Body Mass Index)**
- **Diabetes Pedigree Function**
- **Age**
- **Outcome (Diabetes: 1, No Diabetes: 0)**

## 🚀 Analysis Performed
- **Data Cleaning:** Handling missing values, outlier detection, and feature engineering.
- **Descriptive Statistics:** Understanding central tendency, spread, and distributions.
- **Data Visualization:**
  - Histogram and boxplots for numerical features.
  - Correlation heatmaps.
  - Pairplots to observe feature interactions.
- **Feature Relationships:** Examining how glucose levels, BMI, and age influence diabetes risk.
- **Outlier Treatment:** Using IQR method (Winsorization) to cap extreme values.

## 📊 Key Insights
- Higher **glucose levels** and **BMI** are strongly associated with diabetes.
- Older individuals are more likely to have diabetes.
- Insulin levels vary significantly across diabetic and non-diabetic patients.
- Some features exhibit skewed distributions, requiring transformation.

## 🔧 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Diabetes-EDA.git
cd Diabetes-EDA
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook Diabities_EDA.ipynb
```

## 📌 Technologies Used
- **Python**
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Scikit-learn** for basic preprocessing

## 💡 Future Improvements
- Feature engineering for machine learning models.
- Predictive modeling using Logistic Regression, Decision Trees, etc.
- Handling class imbalance using SMOTE.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, raise issues, or submit pull requests.

## 📜 License
This project is licensed under the **MIT License**.

---
🚀 **Happy Coding!** 🎯

