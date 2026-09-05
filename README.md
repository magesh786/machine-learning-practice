# Day 01 — Supervised Learning: Student Performance Prediction

## 📌 Project Overview

This is my first project in my **Daily Machine Learning Learning Series**.

The goal of this project is to understand the fundamentals of **Supervised Learning** by predicting whether a student will pass or fail based on:

* Study Hours
* Attendance
* Assignments Completed

## 🧠 Machine Learning Concept

**Supervised Learning — Classification**

The model learns from labeled training data where:

* `0` = Fail
* `1` = Pass

## 🤖 Algorithm Used

**Logistic Regression**

## 🛠️ Technologies

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## 🔄 Workflow

1. Create/load dataset
2. Explore the data
3. Check missing values
4. Visualize the data
5. Select features and target
6. Split data into training and testing sets
7. Scale the features
8. Train Logistic Regression model
9. Make predictions
10. Evaluate the model
11. Test the model with a new student

## 📊 Features

| Feature               | Description                     |
| --------------------- | ------------------------------- |
| Study Hours           | Number of hours studied         |
| Attendance            | Student attendance percentage   |
| Assignments Completed | Number of completed assignments |
| Pass                  | Target variable                 |

## 🎯 Objective

The main objective is not just to build a model, but to understand the complete **Machine Learning workflow from data to prediction**.

## 🚀 Future Improvements

* Use a real-world dataset
* Compare multiple classification algorithms
* Perform hyperparameter tuning
* Improve feature engineering
* Deploy the model as a web application

## 📚 Learning Outcome

Through this project, I learned the basic workflow of a supervised machine learning classification problem and how to train, predict, and evaluate a Logistic Regression model.


# Day 02 — House Price Prediction using Linear Regression

## 📌 Project Overview

For Day 2 of my Machine Learning journey, I built a **House Price Prediction** model using **Linear Regression**.

The model predicts house prices based on:

* Area in square feet
* Number of bedrooms
* Age of the house

## 🧠 Concept

**Supervised Learning → Regression**

## 🤖 Algorithm

**Linear Regression**

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## 🔄 Machine Learning Workflow

Dataset → Data Exploration → Visualization → Feature Selection → Train/Test Split → Model Training → Prediction → Evaluation

## 📊 Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## 🎯 Learning Outcome

This project helped me understand how regression models learn relationships between input features and a continuous target value.

I also learned how to evaluate predictions using different regression metrics.

## 🚀 Next Step

Continue building and learning a new Machine Learning concept every day.

**Day 2/30 — Learning by Building.**


🌸 Day 03 — Iris Flower Classification using Decision Tree
📌 Project Overview

As part of my 30-Day Machine Learning Journey, I built an Iris Flower Classification model using a Decision Tree Classifier.

The model learns from flower measurements and predicts the species of an Iris flower.

🎯 Objective

To build a supervised machine learning classification model that can identify the species of an Iris flower based on its physical measurements.

🧠 Machine Learning Concept

Supervised Learning → Classification

The model learns from labeled data and predicts one of three Iris species:

🌸 Iris Setosa
🌸 Iris Versicolor
🌸 Iris Virginica
🤖 Algorithm Used

Decision Tree Classifier

A Decision Tree makes predictions by creating a series of decision rules based on the input features.

📊 Dataset

The project uses the Iris Dataset, containing 150 flower samples.

Features
Feature	Description
Sepal Length	Length of the sepal
Sepal Width	Width of the sepal
Petal Length	Length of the petal
Petal Width	Width of the petal
Target

The target variable represents the Iris species:

0 → Setosa
1 → Versicolor
2 → Virginica
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab
Jupyter Notebook
🔄 Machine Learning Workflow
Iris Dataset
     ↓
Data Loading
     ↓
Data Exploration
     ↓
Data Visualization
     ↓
Train/Test Split
     ↓
Decision Tree Model
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
     ↓
New Flower Prediction
📈 Model Evaluation

The model is evaluated using:

Accuracy Score
Classification Report
Confusion Matrix

The confusion matrix helps understand how correctly the model classified each Iris species.

🌳 Decision Tree Visualization

The project also visualizes the trained Decision Tree to understand how the model makes classification decisions.

🔮 Example Prediction

The model can predict the species of a new flower using its:

Sepal Length
Sepal Width
Petal Length
Petal Width

Example:

Input:
Sepal Length = 5.1
Sepal Width  = 3.5
Petal Length = 1.4
Petal Width  = 0.2

Prediction:
Iris Setosa
📚 What I Learned

Through this project, I learned:

Basics of classification
How Decision Trees work
Loading datasets using Scikit-learn
Train/test splitting
Model training
Making predictions
Accuracy evaluation
Confusion matrix
Classification reports
Decision Tree visualization
🚀 Future Improvements
Compare Decision Tree with Random Forest
Try K-Nearest Neighbors
Compare multiple classification algorithms
Perform hyperparameter tuning
Deploy the model as a web application using Streamlit

