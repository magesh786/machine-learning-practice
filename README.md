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


🧠 Day 04 — Breast Cancer Classification using KNN
📌 Project Overview

As part of my 30-Day Machine Learning Journey, I explored the K-Nearest Neighbors (KNN) algorithm and built a classification model using the Breast Cancer dataset.

The model learns patterns from medical measurement features and predicts whether a tumor belongs to the malignant or benign class.

Note: This is an educational machine learning project and is not intended for medical diagnosis or clinical use.

🎯 Objective

The main objective of this project is to understand how the K-Nearest Neighbors algorithm works for a binary classification problem.

The project also explores how different K values affect model performance.

🧠 Machine Learning Concept

Supervised Learning → Classification

KNN classifies a new data point based on the classes of its nearest neighboring data points.

🤖 Algorithm Used
K-Nearest Neighbors (KNN)

KNN predicts the class of a new observation by looking at the K closest training samples.

For example:

New Data Point
      ↓
Find nearest neighbors
      ↓
Check their classes
      ↓
Majority voting
      ↓
Predicted Class
📊 Dataset

This project uses the Breast Cancer Wisconsin dataset available through Scikit-learn.

The dataset contains 569 samples and 30 numerical features describing characteristics of cell nuclei.

Example Features
Mean Radius
Mean Texture
Mean Perimeter
Mean Area
Mean Smoothness
Mean Compactness
Mean Concavity
Mean Symmetry
Radius Error
Texture Error
Perimeter Error
Area Error

The target contains two classes:

0 → Malignant
1 → Benign
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
Breast Cancer Dataset
        ↓
Data Loading
        ↓
Data Exploration
        ↓
Data Cleaning
        ↓
Feature Selection
        ↓
Train/Test Split
        ↓
Feature Scaling
        ↓
KNN Model
        ↓
Model Training
        ↓
Prediction
        ↓
Model Evaluation
        ↓
K Value Comparison
        ↓
Final Model
⚙️ Important Steps
1. Data Loading

The dataset is loaded using Scikit-learn.

2. Train/Test Split

The dataset is divided into:

Training data — 80%
Testing data — 20%
3. Feature Scaling

KNN uses distances to find neighboring points, so feature scaling is important.

StandardScaler is used to standardize the features.

4. Model Training

A KNN classifier is trained using:

KNeighborsClassifier(n_neighbors=5)
5. K Value Testing

The project tests different K values from 1 to 15 and compares their accuracy.

This helps understand how the choice of K can influence model performance.

📈 Model Evaluation

The model is evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Classification Report
Confusion Matrix

The project also generates a graph showing:

K Value vs Accuracy

This helps identify a suitable K value for the model.

📊 Visualizations

The project includes:

Target Distribution

Shows the distribution of malignant and benign samples.

Confusion Matrix

Shows:

Actual Class
     ↓
Predicted Class

and helps understand correct and incorrect predictions.

K Value vs Accuracy

Shows how model accuracy changes with different K values.

🔮 Example Prediction

The trained model can predict the class of a new sample based on its feature values.

Example output:

Predicted Class: Benign
📚 What I Learned

Through this project, I learned:

What KNN is
How KNN performs classification
The importance of feature scaling
How distance-based algorithms work
How to select a suitable K value
Train/test splitting
Model evaluation
Confusion matrix
Classification metrics
Comparing model performance for different K values



🍷 Day 05 — Wine Classification using Random Forest
📌 Project Overview

As part of my 30-Day Machine Learning Journey, Day 5 focuses on Supervised Learning – Classification.

In this project, I built a Wine Classification model using the Random Forest Classifier from Scikit-learn.

The model learns from chemical properties of wine samples and predicts which wine class a sample belongs to.

🎯 Objective

The main objectives of this project are:

Understand the Random Forest Classification algorithm
Load and explore a real-world dataset
Perform data preprocessing
Split data into training and testing sets
Apply feature scaling
Train a Random Forest model
Evaluate classification performance
Analyze feature importance
Predict the class of a new wine sample
🤖 Machine Learning Concept
Supervised Learning

Supervised Learning uses labeled data to learn the relationship between input features and output classes.

Classification

Classification predicts a categorical output.

For this project:

Input: Chemical properties of wine
Output: Wine class

🌳 Algorithm — Random Forest

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees.

Instead of relying on a single decision tree, Random Forest creates many trees and combines their predictions to produce a more robust result.

Advantages
Good classification performance
Reduces overfitting compared with a single decision tree
Handles multiple features
Provides feature importance
Works well on many structured datasets
📊 Dataset

The project uses the built-in Wine Dataset available in Scikit-learn.

Dataset Information
Samples: 178
Features: 13
Classes: 3
Problem Type: Multi-class Classification
Wine Classes

The dataset contains three different wine classes:

Class 0
Class 1
Class 2

The dataset features represent chemical properties such as:

Alcohol
Malic acid
Ash
Alcalinity of ash
Magnesium
Total phenols
Flavanoids
Nonflavanoid phenols
Proanthocyanins
Color intensity
Hue
OD280/OD315 of diluted wines
Proline
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab / Jupyter Notebook
🔄 Project Workflow
Load Wine Dataset
       ↓
Explore Dataset
       ↓
Check Missing Values
       ↓
Data Visualization
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Random Forest Model
       ↓
Model Training
       ↓
Prediction
       ↓
Model Evaluation
       ↓
Feature Importance
       ↓
New Wine Prediction
📈 Data Exploration

The project performs:

Dataset shape analysis
Dataset information
Missing-value checking
Statistical analysis
Target class distribution
Feature correlation analysis
⚙️ Data Preprocessing

The dataset is divided into:

80% Training Data
20% Testing Data

The data is split using:

train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42,
    stratify=y
)

Feature scaling is performed using:

StandardScaler()
🌲 Random Forest Model

The model is created using:

RandomForestClassifier(
    n_estimators=100,
    random_state=42
)

The model contains 100 decision trees whose predictions are combined to classify the wine samples.

📊 Model Evaluation

The model is evaluated using:

Accuracy

Measures the percentage of correctly classified samples.

Classification Report

Provides:

Precision
Recall
F1-score
Support
Confusion Matrix

Shows the relationship between:

Actual classes
Predicted classes
🔍 Feature Importance

Random Forest provides an important advantage: it can estimate the importance of each feature.

The project visualizes feature importance to understand which chemical properties contribute most to the classification decision.

📊 Visualizations

The project includes:

Wine Class Distribution
Feature Correlation Heatmap
Confusion Matrix
Random Forest Feature Importance

These visualizations make it easier to understand the dataset and model performance.

🔮 New Wine Prediction

A wine sample from the dataset is passed to the trained model to demonstrate prediction.

The model predicts:

Predicted Wine Class: ...

Prediction probabilities are also calculated for each wine class.

📁 Project Structure
Day-05-Random-Forest-Wine/
│
├── Random_Forest_Wine_Classification.ipynb
├── random_forest_wine_predictions.csv
└── README.md
▶️ How to Run
1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/machine-learning-daily-series.git
2. Open the Day 5 Folder
cd machine-learning-daily-series/Day-05-Random-Forest-Wine
3. Install Required Libraries
pip install numpy pandas matplotlib seaborn scikit-learn
4. Run the Notebook

Open:

Random_Forest_Wine_Classification.ipynb

You can run it using:

Google Colab
Jupyter Notebook
VS Code
📌 Key Learning Outcomes

Through this project, I learned:

How Random Forest works
How ensemble learning improves classification
How to preprocess a dataset
How to split data into training and testing sets
How feature scaling works
How to evaluate a classification model
How to interpret a confusion matrix
How to analyze feature importance
How to generate prediction probabilities

🧠 Day 06 — Breast Cancer Classification using SVM
📌 Project Overview

Welcome to Day 6 of my 30-Day Machine Learning Journey.

In this project, I explored Support Vector Machine (SVM), a powerful supervised machine learning algorithm used for classification.

I used the Breast Cancer dataset available in Scikit-learn to build a classification model that predicts whether a sample belongs to the malignant or benign class.

⚠️ This project is for educational purposes only and should not be used for medical diagnosis.

🎯 Objective

The objectives of this project are:

Understand Support Vector Machine
Perform binary classification
Preprocess the dataset
Apply feature scaling
Train an SVM model
Evaluate model performance
Compare different SVM kernels
Generate predictions
Analyze the confusion matrix
🤖 Machine Learning Concept
Supervised Learning

Supervised learning uses labeled data to train a machine learning model.

In this project:

Input: Measurements of cell nuclei
Output: Cancer classification

Classification

The model performs binary classification.

The two target classes are:

Malignant
Benign
📐 Algorithm — Support Vector Machine

Support Vector Machine (SVM) is a supervised learning algorithm that finds an optimal decision boundary between different classes.

SVM attempts to maximize the margin between classes while correctly classifying the training samples.

Important SVM Parameters
SVC(
    kernel="rbf",
    C=1.0,
    gamma="scale"
)
Kernel Types Tested

The project compares:

Linear
Polynomial
RBF
Sigmoid
📊 Dataset

The project uses the Breast Cancer Wisconsin Diagnostic dataset available through Scikit-learn.

Dataset Information
Samples: 569
Features: 30
Classes: 2
Problem Type: Binary Classification
Classes
Malignant
Benign

The features describe characteristics of cell nuclei extracted from digitized images.

🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab
Jupyter Notebook
🔄 Project Workflow
Load Dataset
     ↓
Explore Dataset
     ↓
Check Missing Values
     ↓
Visualize Target Distribution
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Create SVM Model
     ↓
Train Model
     ↓
Make Predictions
     ↓
Evaluate Model
     ↓
Compare Kernels
     ↓
New Sample Prediction
⚙️ Data Preprocessing

The dataset is divided into:

80% Training Data
20% Testing Data

The split uses:

train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42,
    stratify=y
)

Because SVM is sensitive to feature scale, StandardScaler is applied before training.

scaler = StandardScaler()

X_train_scaled = scaler.fit_transform(X_train)
X_test_scaled = scaler.transform(X_test)
🧠 SVM Model

The primary model uses the RBF kernel:

SVC(
    kernel="rbf",
    C=1.0,
    gamma="scale",
    probability=True
)

The model is trained using the scaled training data.

📊 Model Evaluation

The model is evaluated using:

Accuracy

Measures the percentage of correctly classified samples.

Precision

Measures how many predicted positive samples were actually positive.

Recall

Measures how many actual positive samples were correctly identified.

F1-Score

Combines precision and recall into a single metric.

Confusion Matrix

Shows:

Actual class
Predicted class
Correct predictions
Incorrect predictions
🔬 Kernel Comparison

One important part of this project is comparing different SVM kernels.

The following kernels are tested:

Kernel	Description
Linear	Uses a linear decision boundary
Polynomial	Uses polynomial transformation
RBF	Captures non-linear relationships
Sigmoid	Uses a sigmoid-based transformation

The accuracy of each kernel is displayed using a bar chart.

📈 Visualizations

The project includes:

Class Distribution
SVM Confusion Matrix
Kernel Accuracy Comparison

These visualizations help understand the dataset and model performance.

🔮 New Sample Prediction

A sample is passed through the trained SVM model.

The model returns the predicted class and prediction probabilities.

Example:

Predicted Class: benign

The prediction is only an educational demonstration using the dataset.

📁 Project Structure
Day-06-SVM-Breast-Cancer/
│
├── SVM_Breast_Cancer_Classification.ipynb
├── svm_breast_cancer_predictions.csv
└── README.md
▶️ How to Run
1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/machine-learning-daily-series.git
2. Open the Project
cd machine-learning-daily-series/Day-06-SVM-Breast-Cancer
3. Install Libraries
pip install numpy pandas matplotlib seaborn scikit-learn
4. Run the Notebook

Open:

SVM_Breast_Cancer_Classification.ipynb

You can run the notebook using:

Google Colab
Jupyter Notebook
VS Code
📌 Key Learning Outcomes

From this project, I learned:

What Support Vector Machine is
How SVM performs classification
Why feature scaling is important
What kernels are
Difference between linear and non-linear kernels
How to evaluate classification models
How to use confusion matrices
How to compare different model configurations
🚀 Future Improvements

Future improvements could include:

Hyperparameter tuning
GridSearchCV
Cross-validation
ROC-AUC analysis
Precision-Recall analysis
Feature selection
Comparing SVM with Random Forest, KNN and Logistic Regression
Building a Streamlit interface
