# 🚢 Titanic Survival Prediction – CodSoft Internship Task 1

## 📌 Internship: CodSoft (Data Science)
**Task 1: Titanic Survival Prediction**  
Batch: **July B37**

---

## 🎯 Objective
Build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, and fare.

---

## 📁 Dataset
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Columns used:
  - `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Logistic Regression, Random Forest)

---

## 📊 Workflow

### 1. Data Cleaning
- Handled missing values (Age, Embarked)
- Encoded `Sex` and `Embarked` using LabelEncoder

### 2. Exploratory Data Analysis (EDA)
- Survival rate by gender, class
- Age and fare distributions
- Visualized using Seaborn

### 3. Model Building
- Logistic Regression: baseline model
- Random Forest Classifier: best performer
- Compared accuracy, precision, recall

### 4. Prediction Interface
- Took live user input through terminal
- Predicted survival using Random Forest
- Used DataFrame for proper feature naming

---

## ✅ Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 81.01%   |
| Random Forest       | **83.24%** ✅

✔️ Final model: **Random Forest Classifier**

---

## 🔮 Live Input Demo

Example prediction using user input:

```text
Pclass: 3
Sex: female
Age: 22
SibSp: 0
Parch: 0
Fare: 7.25
Embarked: S
→ ✅ Survived
