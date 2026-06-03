# Salary Prediction Using Simple Linear Regression

A beginner-friendly Machine Learning project that predicts employee salary based on years of experience using **Simple Linear Regression**.
This project includes a dataset, Jupyter Notebook implementation, and a Streamlit web app for salary prediction.

---

## 📌 Project Overview

This project demonstrates how Simple Linear Regression can be used to predict salary from experience.
The model learns the relationship between **Years of Experience** and **Salary**, then predicts salary for new input values.

---

## 🚀 Features

* Load and analyze salary dataset
* Visualize relationship between experience and salary
* Train a Simple Linear Regression model
* Plot regression line
* Predict salary based on user input
* Streamlit web app interface

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Streamlit
* Jupyter Notebook

---

## 📂 Repository Structure

```text
salary-prediction-linear-regression/
│
├── Salary_Data.csv
├── SimpleLinearRegression.ipynb
├── app.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The dataset contains two columns:

| Column          | Description                         |
| --------------- | ----------------------------------- |
| YearsExperience | Employee's years of work experience |
| Salary          | Salary based on experience          |

---

## 🧠 Machine Learning Model

The project uses **Simple Linear Regression**, where:

```text
Salary = m × YearsExperience + c
```

Here:

* `m` = slope/coefficient
* `c` = intercept
* `YearsExperience` = input feature
* `Salary` = predicted output

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/SriValli-28/salary-prediction-linear-regression.git
```

### 2. Open the project folder

```bash
cd salary-prediction-linear-regression
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📌 How the App Works

1. Upload the salary dataset CSV file.
2. The app displays the dataset.
3. It visualizes salary vs years of experience.
4. It trains a Linear Regression model.
5. It displays the regression line.
6. User enters years of experience.
7. The app predicts the expected salary.

---

## 📈 Output

The model predicts salary based on the number of years of experience entered by the user.

Example:

```text
Input: 3.5 years of experience
Output: Predicted salary based on trained model
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

* How to load and process CSV data
* How to visualize data using Matplotlib
* How Simple Linear Regression works
* How to train a model using Scikit-learn
* How to build a basic ML web app using Streamlit

---

## 🔮 Future Improvements

* Add model accuracy score
* Add Mean Squared Error and R² Score
* Improve UI design
* Deploy the app using Streamlit Cloud
* Save and load trained model using Pickle

---

## 👩‍💻 Author

**Srivalli**
B.Tech CSE Student | Software Development | AI/ML Enthusiast

* GitHub: [SriValli-28](https://github.com/SriValli-28)
* LinkedIn: [Thota Sri Valli](https://www.linkedin.com/in/thota-sri-valli-280177283/)
