
# 🎓 Student Exam Performance Prediction

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

## 📖 Overview

An end-to-end Machine Learning project that predicts a student's Mathematics Score based on demographic and academic information. The project implements the complete ML lifecycle including data ingestion, preprocessing, model training, hyperparameter tuning, model selection and deployment with Flask.

---

## ✨ Features

- End-to-End ML Pipeline
- Exploratory Data Analysis
- Data Ingestion & Transformation
- Feature Engineering
- Hyperparameter Tuning
- Automatic Best Model Selection
- Flask Web Application
- Prediction Pipeline
- Logging & Exception Handling

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- CatBoost
- XGBoost
- Matplotlib
- Seaborn
- Flask
- Dill
- Git & GitHub

---

## 🤖 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- XGBoost Regressor
- CatBoost Regressor

Hyperparameter tuning is performed and the best model is selected using R² Score.

---

## 📂 Project Structure

```text
UDEMY_ML_PROJECT/
├── notebook/
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
├── static/
├── templates/
├── app.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

Student Performance Dataset

**Features**

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Reading Score
- Writing Score

**Target**

- Math Score

> > **Dataset:** [Student Performance in Exams Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)

---

## 🚀 Installation

```bash
git clone https://github.com/sujithkuchipatla/udemy_ml_project.git

cd udemy_ml_project

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt
```

---

## ▶️ Run

```bash
python app.py
```

Visit:

```text
http://127.0.0.1:5000/
```

---

## 🌐 Web Application

The application predicts the Mathematics score based on user inputs collected through a Flask web interface.

---


## 🔮 Future Improvements

- Docker Support
- Cloud Deployment
- CI/CD
- Better UI
- Model Monitoring

---

## 👨‍💻 Author

**Sujith Kuchipatla**

GitHub:
https://github.com/sujithkuchipatla

---

⭐ If you like this project, don't forget to star the repository.
