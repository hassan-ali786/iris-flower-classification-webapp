Iris Flower Classification Web App

This project is a Machine Learning powered web application built using Flask that predicts the species of an Iris flower based on user input measurements. The application uses a trained classification model and provides results through an interactive and user-friendly web interface.

Project Overview

The Iris Web App allows users to input four flower measurements:

Sepal Length

Sepal Width

Petal Length

Petal Width

Based on these inputs, the trained machine learning model predicts the Iris species. The application then displays the predicted species along with the corresponding flower image.

Features

Machine Learning model integration

Real-time prediction using Flask

Modern and responsive user interface

Image display based on predicted species

Predict Again functionality

Clean and professional design

Ready for deployment

Technologies Used

Python

Flask

Scikit-learn

NumPy

HTML

CSS

Jinja2

Pickle

Project Structure
iris-webapp/
│
├── app.py
├── model.pkl
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── style.css
│   └── images/
│       ├── setosa.jfif
│       ├── versicolor.jfif
│       └── virginica.jfif
│
└── README.md

How to Run the Project Locally

Step 1: Clone the repository

git clone https://github.com/yourusername/iris-webapp.git


Step 2: Navigate to project folder

cd iris-webapp


Step 3: Install required libraries

pip install flask numpy scikit-learn


Step 4: Run the Flask application

python app.py


Step 5: Open in browser

http://127.0.0.1:5000

Machine Learning Model

The model was trained using the Iris dataset and saved as a pickle file. It predicts one of the following species:

Setosa

Versicolor

Virginica

Use Cases

Machine Learning deployment practice

Flask web development learning

Portfolio project for students and beginners

Demonstration of ML model integration

Future Improvements

Add probability scores

Add charts and visualization

Deploy on cloud platform

Improve UI with dashboard features

Author

Hassan Ali

Aspiring Data Scientist 