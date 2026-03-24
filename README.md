# 💰 Insurance Charges Predictor

A Machine Learning project that predicts medical insurance charges based on individual attributes such as age, BMI, smoking status, and more. This project demonstrates regression techniques, data preprocessing, and feature engineering using real-world data.

---

## 🚀 Project Overview

The objective of this project is to build a predictive model that estimates a person's medical insurance cost based on their personal and health-related information. This is a **regression problem**, where the output is a continuous numerical value.

---

## 🧠 Key Concepts Applied

* Supervised Learning (Regression)
* Feature Engineering
* One-Hot Encoding (Categorical Variables)
* Train-Test Split
* Model Training & Evaluation

---

## 📊 Dataset Description

The dataset contains the following features:

* `age` → Age of the individual
* `sex` → Gender (male/female)
* `bmi` → Body Mass Index
* `children` → Number of dependents
* `smoker` → Smoking status (yes/no)
* `region` → Residential area

### 🎯 Target Variable

* `charges` → Medical insurance cost (continuous value)

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔍 Model Used

* Linear Regression *(primary model)*
* (Optional: Polynomial Regression / Ridge / Lasso if implemented)

---

## 📈 Workflow

1. Data Loading
2. Data Cleaning & Preprocessing
3. Encoding categorical variables (One-Hot Encoding)
4. Exploratory Data Analysis (EDA)
5. Train-Test Split
6. Model Training
7. Prediction & Evaluation

---

## 🧪 Example Prediction

```python id="0t9vdl"
model.predict([[25, 0, 28.5, 2, 1, 3]])
```

👉 Predicts insurance charges for a given individual profile.

---

## 📂 Project Structure

```id="7cs4d1"
insurance-charges-predictor/
│
├── insaurance_charge_predictor.ipynb   # Main notebook
├── README.md                          # Documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```bash id="r6fxjm"
git clone https://github.com/your-username/insurance-charges-predictor.git
```

2. Navigate to the project folder:

```bash id="bcndts"
cd insurance-charges-predictor
```

3. Install dependencies:

```bash id="0d0a3j"
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. Run the notebook:

```bash id="h3pt46"
jupyter notebook
```

---

## 📊 Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 🎯 Learning Outcomes

* Understanding regression problems
* Working with real-world datasets
* Handling categorical and numerical data
* Building predictive cost models

---

## 🚀 Future Improvements

* Feature scaling (Standardization)
* Hyperparameter tuning
* Model comparison (Random Forest, XGBoost)
* Deployment using Flask/React

---

## 👨‍💻 Author

**Mohit Mathangi**

---

## ⭐ Contributions

Feel free to fork, improve, or suggest enhancements!
