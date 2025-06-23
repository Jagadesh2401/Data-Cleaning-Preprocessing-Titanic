# Welcome to GitHub Desktop!

This is READMEs are # 🚢 Task 1: Titanic Data Cleaning & Preprocessing

🎓 **Internship**: AI & ML  
📁 **Task**: Data Preprocessing using Titanic Dataset  
📊 **Format**: Jupyter Notebook (`.ipynb`)
tr
---

## 📌 Objective

To understand and implement **data cleaning and preprocessing** techniques, including:
- Handling missing values
- Encoding categorical features
- Scaling numerical values
- Detecting and removing outliers

This task prepares the data for machine learning models by ensuring it's clean, consistent, and structured.

---

## 📂 Dataset

- **Name**: Titanic - Machine Learning from Disaster
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File Used**: `train.csv` (renamed to `titanic.csv`)

---

## 🧰 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🧠 What I Did

### ✅ 1. Data Loading & Exploration
- Loaded the CSV using `pandas`
- Inspected data types, null values, and statistics

### ✅ 2. Missing Value Treatment
- `Age`: Filled using **median**
- `Embarked`: Filled using **mode**
- `Cabin`: Dropped (too many nulls)
- `Fare`: Dropped rows with missing values

### ✅ 3. Categorical Encoding
- `Sex`: Converted to numerical (0 for male, 1 for female)
- `Embarked`: One-hot encoded (`Embarked_Q`, `Embarked_S`)

### ✅ 4. Feature Scaling
- Applied **StandardScaler** to `Age` and `Fare`

### ✅ 5. Outlier Detection & Removal
- Used **boxplots** for visualization
- Applied **IQR method** to remove outliers in `Age` and `Fare`

---

## 📈 Output

- Final cleaned dataset: `cleaned_titanic.csv`
- Cleaned and ready for machine learning modeling

---
