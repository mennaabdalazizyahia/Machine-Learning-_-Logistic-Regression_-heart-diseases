# ❤️ Heart Disease Classification (Logistic Regression)

## 📖 Project Overview
This project applies **Logistic Regression** to predict the likelihood of a person having a **heart attack** based on health indicators.  
The dataset includes lifestyle and medical attributes such as sex, sleep hours, BMI, smoking habits, physical activity, and general health.

---

## 📂 Dataset
- **Source**: [Kaggle - Personal Key Indicators of Heart Disease](https://www.kaggle.com/datasets/cdc/heart-disease-indicators-dataset)  
- **File Used**: `heart_2022_no_nans.csv`  
- **Target Variable**: `HadHeartAttack` (Yes/No → encoded to 1/0)

---

## 🛠️ Tools & Libraries
- **Python** 🐍  
- **Pandas & NumPy** → Data handling & preprocessing  
- **Matplotlib & Seaborn** → Visualizations (scatter plots, pair plots, bar charts)  
- **Scikit-learn** → Machine Learning (Logistic Regression, train/test split, metrics)

---

## ⚙️ Steps Performed
1. **Data Loading & Inspection**:
   - Loaded dataset and checked for missing values.
   - Explored categorical and numerical variables.  
2. **Exploratory Analysis**:
   - Scatter plots between `Sex`, `SleepHours` and `HadHeartAttack`.  
   - Pairplot of all features for visual correlation.  
   - Bar chart of heart attack occurrences.  
3. **Preprocessing**:
   - Converted `HadHeartAttack` from categorical (`Yes/No`) to numeric (1/0).  
   - Applied one-hot encoding to categorical features.  
4. **Model Training**:
   - Split dataset into training (70%) and testing (30%) using `train_test_split`.  
   - Trained a **Logistic Regression** classifier.  
5. **Model Evaluation**:
   - **Accuracy Score:** 95 %  

---

## 📊 Key Insights
- Logistic Regression is effective for binary classification tasks such as predicting heart attack risk.  
- Class imbalance can affect recall/precision (further tuning or resampling may improve performance).  
- Sleep hours and sex show visual correlations with heart attack occurrence.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/mennaabdalazizyahia/heart-disease-logistic-regression.git
   cd heart-disease-logistic-regression
