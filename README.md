# Student Performance Predictor Web Application

An end-to-end Machine Learning web application that predicts whether a student will **pass or fail** based on demographic and educational factors.  
The system leverages supervised learning techniques and provides real-time predictions through a professional web interface.

---

## Project Overview

This application analyzes student data and predicts pass/fail outcomes.  
It follows a complete ML lifecycle:

- Data preprocessing and feature encoding  
- Model training using Random Forest, Gradient Boosting, and Logistic Regression  
- Model evaluation using Accuracy scores  
- Automatic best model selection  
- Deployment using Flask  
- Professional frontend integration for real-time predictions

---

## Machine Learning Models

**Algorithms:** Logistic Regression, Random Forest, Gradient Boosting  

**Best Performing Model:** Random Forest  

**Why Random Forest:**  

- High accuracy on tabular datasets  
- Resistant to overfitting  
- Strong generalization capability  
- Stable performance for small datasets  

---

## Dataset Information

**Dataset:** Students Performance in Exams Dataset  

**Features:**  

- Gender  
- Race / Ethnicity  
- Parental Level of Education  
- Lunch Type  
- Test Preparation Course  

**Target:** Pass / Fail  

---

## Model Performance Metrics

| Model | Accuracy |
|-------|---------|
| Logistic Regression | 0.84 |
| Random Forest | 0.91 |
| Gradient Boosting | 0.89 |

**Metric Explanation:**  

- **Accuracy:** Overall correct predictions  
- **Best Model Selection:** Automatically selects Random Forest for predictions  

---

## Project Structure

```bash
student-performance-predictor/
├── data/
│   └── students.csv
├── model/
│   └── best_model.pkl
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── css/style.css
├── train_model.py
├── app.py
├── requirements.txt
├── README.md
└── assets/
    └── homepage.png
```

---

## Installation Guide

1. Clone the repository:

```bash
git clone https://github.com/Hassan-Ali786/student-performance-predictor.git
cd student-performance-predictor
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Train the models:

```bash
python train_model.py
```

4. Run the web application:

```bash
python app.py
```

Open a browser at `http://127.0.0.1:5000`, enter student details, and click **Predict**.

---

## Key Features

- Real-time pass/fail prediction  
- Professional and user-friendly interface  
- Multiple machine learning models with automatic best model selection  
- Evaluation using Accuracy scores  
- Modular and production-ready architecture  

---

## Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)  
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)  
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)  
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)  

---

## Real-World Applications

- Academic institutions and schools  
- Student performance analytics  
- Education dashboards and reporting tools  
- Data-driven decision making in education  

---

## Future Improvements

- Add more student features for better prediction  
- Create analytics dashboard for student insights  
- Deploy the application on cloud platforms  
- Store prediction history in a database  
- Add visualization for model comparison  
- Multi-class prediction (grades A, B, C, Fail)  

---

## Author

Hassan Ali  
Aspiring Data Scientist and Machine Learning Engineer  

---

## Application Screenshot

![Student Performance Web App](assets/homepage.png)
