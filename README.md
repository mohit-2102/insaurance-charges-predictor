# 🎓 Student Marks Predictor

A Machine Learning project that predicts student marks based on study hours using **Linear Regression**. This project demonstrates the fundamentals of supervised learning, data preprocessing, model training, and prediction.

---

## 🚀 Project Overview

The goal of this project is to build a simple predictive model that estimates a student's marks based on the number of hours they study. It serves as an introduction to core Machine Learning concepts and workflows.

---

## 🧠 Concepts Covered

* Supervised Learning
* Regression (Linear Regression)
* Train-Test Split
* Model Training using Scikit-learn
* Prediction & Evaluation

---

## 📊 Dataset

The dataset used in this project is a small sample containing:

* **Hours Studied** (Input Feature)
* **Marks Obtained** (Target Variable)

Example:

| Hours | Marks |
| ----- | ----- |
| 1     | 35    |
| 2     | 50    |
| 3     | 65    |
| 4     | 70    |
| 5     | 90    |

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn

---

## 🔍 Model Used

* **Linear Regression**

The model learns the relationship between study hours and marks, and predicts marks for new input values.

---

## 📈 How It Works

1. Load and prepare the dataset
2. Split data into training and testing sets
3. Train the Linear Regression model
4. Make predictions
5. Evaluate the results

---

## 🧪 Example Prediction

```python
model.predict([[6]])
```

👉 Predicts marks for a student who studies 6 hours.

---

## 📂 Project Structure

```
student-marks-predictor/
│
├── SupervisedLearning.ipynb   # Main notebook
├── README.md                 # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-marks-predictor.git
```

2. Navigate to the project folder:

```bash
cd student-marks-predictor
```

3. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Learning Outcome

This project helped in understanding:

* How Machine Learning models are trained
* Difference between input features and target variables
* How predictions are made using real data

---

## 🚀 Future Improvements

* Add more features (sleep, practice, etc.)
* Use advanced models
* Deploy as a web app using Flask/React
* Integrate with a frontend UI

---

## 👨‍💻 Author

**Mohit Mathangi**

---

## ⭐ Contribute / Feedback

Feel free to fork this repo, suggest improvements, or connect with me for collaboration.
