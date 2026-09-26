# Day 01 — Supervised Learning: Student Performance Prediction

## 📌 Project Overview

This is my first project in my **Daily Machine Learning Series**.

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

👥 Day 07 — Customer Segmentation using K-Means
📌 Project Overview

Welcome to Day 7 of my 30-Day Machine Learning Journey.

For Day 7, I moved from Supervised Learning to Unsupervised Learning.

In this project, I built a Customer Segmentation system using K-Means Clustering.

Instead of predicting a predefined target, the model groups customers based on similarities in their characteristics.

🎯 Objective

The main objectives are:

Understand Unsupervised Learning
Learn K-Means Clustering
Group similar customers
Apply feature scaling
Find a suitable number of clusters
Use the Elbow Method
Use Silhouette Score
Visualize customer clusters
Analyze cluster characteristics
Export clustering results
🧠 Machine Learning Concept
Unsupervised Learning

Unlike supervised learning, unsupervised learning works with data where a target label is not provided.

The model attempts to discover patterns, structures, or groups within the data.

Clustering

Clustering is an unsupervised learning technique that groups similar observations together.

K-Means is one of the commonly used clustering algorithms. It assigns samples to clusters around centroids and attempts to minimize within-cluster variation.

🤖 Algorithm — K-Means Clustering

K-Means works by:

Selecting the number of clusters K
Initializing cluster centroids
Assigning each sample to its nearest centroid
Updating the centroids
Repeating the process until the centroids stabilize

The number of clusters must be specified when creating the K-Means model.

📊 Project Dataset

For this educational project, a customer dataset was created containing:

Customer ID
Age
Annual Income
Spending Score
Features
Feature	Description
Age	Customer age
Annual Income	Approximate annual income
Spending Score	Customer spending behavior

The dataset contains 200 customer records.

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
Create Customer Dataset
        ↓
Explore Data
        ↓
Check Missing Values
        ↓
Select Features
        ↓
Feature Scaling
        ↓
Elbow Method
        ↓
Silhouette Score
        ↓
Select K
        ↓
Train K-Means
        ↓
Assign Clusters
        ↓
Visualize Clusters
        ↓
Analyze Cluster Centers
        ↓
Export Results
⚙️ Feature Scaling

K-Means uses distances between data points, so differences in feature scales can influence clustering.

Therefore, the project uses StandardScaler before applying K-Means.

scaler = StandardScaler()

X_scaled = scaler.fit_transform(X)
📐 Finding the Number of Clusters
Elbow Method

The Elbow Method calculates the model's inertia for different values of K.

The resulting curve can help identify a point where adding additional clusters gives diminishing improvement.

Scikit-learn describes inertia as the within-cluster sum-of-squares criterion.

Silhouette Score

The project also calculates the Silhouette Score.

The score measures how well samples fit within their assigned clusters compared with neighboring clusters. Values closer to 1 generally indicate better separation.

📊 Visualizations

The project generates:

Elbow Curve
Silhouette Score Comparison
Annual Income vs Spending Score
Age vs Spending Score
Cluster Size Distribution
👥 Customer Segmentation

After applying K-Means, every customer receives a cluster label.

Example:

Customer 1 → Cluster 0
Customer 2 → Cluster 1
Customer 3 → Cluster 2

The actual interpretation of each cluster depends on the characteristics of its members.

For example, a cluster may represent customers with:

Higher income and higher spending
Lower income and lower spending
Moderate income and moderate spending
📍 Cluster Centers

K-Means calculates a centroid for every cluster.

The project converts the scaled cluster centers back to the original feature scale to make them easier to interpret.


👥 Day 08 — Customer Segmentation using DBSCAN
📌 Project Overview

Welcome to Day 8 of my 30-Day Machine Learning Journey.

In Day 7, I explored K-Means Clustering.

For Day 8, I continued with Unsupervised Learning by exploring DBSCAN — Density-Based Spatial Clustering of Applications with Noise.

DBSCAN groups points based on density and can identify points that do not belong to any cluster as noise.

🎯 Objective

The main objectives of this project are:

Understand DBSCAN
Learn density-based clustering
Perform customer segmentation
Apply feature scaling
Understand eps
Understand min_samples
Detect noise and outliers
Calculate Silhouette Score
Visualize customer clusters
Analyze cluster characteristics
🧠 Machine Learning Concept
Unsupervised Learning

Unsupervised Learning discovers patterns or structures in data without predefined target labels.

Density-Based Clustering

DBSCAN identifies dense regions of data and separates them from sparse regions.

Unlike K-Means, DBSCAN does not require the number of clusters to be specified beforehand.

🤖 Algorithm — DBSCAN

DBSCAN uses two important parameters:

eps

Defines the maximum distance for two points to be considered neighbors.

min_samples

Defines the minimum number of points required to form a dense region.

The model used in this project is:

DBSCAN(
    eps=0.45,
    min_samples=8
)
⭐ Important DBSCAN Feature — Noise Detection

One of the major advantages of DBSCAN is its ability to identify noise or outlier points.

DBSCAN represents noise using:

Cluster = -1

Therefore, points labeled -1 in this project are treated as detected outliers.

📊 Dataset

This educational project uses a generated customer dataset containing:

Customer ID
Age
Annual Income
Spending Score

Additional unusual customer records are included to demonstrate DBSCAN's ability to identify potential outliers.

Features Used
Feature	Description
Age	Customer age
Annual Income	Annual income
Spending Score	Customer spending behavior

Customer_ID is used only as an identifier and is not used for clustering.

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
Create Customer Dataset
        ↓
Explore Data
        ↓
Check Missing Values
        ↓
Select Features
        ↓
Feature Scaling
        ↓
Create DBSCAN Model
        ↓
Perform Clustering
        ↓
Identify Noise
        ↓
Calculate Silhouette Score
        ↓
Visualize Clusters
        ↓
Analyze Clusters
        ↓
Export Results
⚙️ Feature Scaling

DBSCAN is distance-based, so feature scaling is important.

The project uses StandardScaler:

scaler = StandardScaler()

X_scaled = scaler.fit_transform(X)

This places the features on a comparable scale before clustering.

🔍 DBSCAN Parameters
eps

Controls the neighborhood radius around each data point.

min_samples

Controls the minimum number of nearby samples required to form a dense region.

Changing these parameters can significantly affect:

Number of clusters
Number of noise points
Cluster structure
📈 Visualizations

The project generates:

1. Original Customer Data

Shows the customer distribution before clustering.

2. DBSCAN Customer Segmentation

Shows customers grouped into DBSCAN clusters.

3. Age vs Spending Score

Shows how age and spending behavior relate to discovered clusters.

4. Cluster Distribution

Shows the number of customers in each cluster.

📊 Silhouette Score

The project calculates the Silhouette Score for non-noise points when at least two clusters are available.

A higher Silhouette Score generally indicates better separation between clusters.

🚨 Outlier Detection

DBSCAN identifies noise points using the cluster label:

-1

The project extracts these customers separately:

outlier_customers = df[
    df["Cluster"] == -1
]

The detected outliers are saved as:

dbscan_outliers.csv

Day 9 - PCA Wine Dataset Dimensionality Reduction
📌 Project Overview

This project demonstrates Principal Component Analysis (PCA) using the Wine dataset from Scikit-learn.

PCA is a dimensionality-reduction technique that transforms a dataset with many features into a smaller number of principal components while preserving as much important information as possible.

In this project, the original Wine dataset contains 13 features, which are transformed into 2 principal components for visualization and analysis.

🎯 Objectives
Understand Principal Component Analysis
Perform feature scaling
Reduce dimensionality using PCA
Analyze explained variance
Visualize high-dimensional data in 2D
Understand PCA component loadings
Compare original and reduced datasets
Save PCA results for further analysis
🧠 What is PCA?

Principal Component Analysis (PCA) is an unsupervised dimensionality-reduction technique.

Instead of working with every original feature, PCA creates new variables called Principal Components.

The first principal component captures the maximum possible variance in the data.

The second principal component captures the maximum remaining variance while being independent of the first component.

PCA Flow
Original Dataset
       ↓
Feature Scaling
       ↓
Calculate Principal Components
       ↓
Rank Components by Variance
       ↓
Select Important Components
       ↓
Reduced Dataset
       ↓
2D Visualization
📊 Dataset

The project uses the built-in Wine dataset from Scikit-learn.

Dataset characteristics
Number of samples: 178
Original features: 13
Classes: 3
Target: Wine class
Example features
Alcohol
Malic acid
Ash
Magnesium
Total phenols
Flavanoids
Color intensity
Hue
Proline
⚙️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Google Colab / Jupyter Notebook
🔬 Project Workflow
Step 1 — Load Dataset

The Wine dataset is loaded using:

from sklearn.datasets import load_wine
Step 2 — Feature Selection

The 13 numerical features are selected for PCA.

Step 3 — Feature Scaling

StandardScaler is used because PCA is sensitive to differences in feature scales.

StandardScaler()
Step 4 — Apply PCA

PCA is first applied using all components to understand the explained variance.

Then PCA is performed with:

PCA(n_components=2)
Step 5 — Explained Variance

The explained variance ratio tells us how much information is captured by each principal component.

Step 6 — Visualization

The 13-dimensional dataset is transformed into two dimensions and visualized using a scatter plot.

Step 7 — Feature Loadings

PCA loadings are analyzed to understand which original features contribute strongly to each principal component.

📈 Important Concepts
Explained Variance

Explained variance represents how much of the dataset's information is captured by each principal component.

Cumulative Explained Variance

Cumulative variance shows the total information retained when multiple components are combined.

Principal Components

Principal components are new transformed features created from combinations of the original features.

Feature Loadings

Loadings indicate the contribution of original features to each principal component.

📊 Visualizations

This project generates:

Cumulative explained variance plot
PCA 2D scatter plot
Principal Component 1 feature contribution plot
📁 Project Structure
Day-09-PCA-Wine-Dimensionality-Reduction/
│
├── PCA_Wine_Dimensionality_Reduction.ipynb
├── wine_pca_results.csv
├── pca_feature_loadings.csv
├── pca_explained_variance.csv
└── README.md
💾 Output Files
wine_pca_results.csv

Contains:

Principal Component 1
Principal Component 2
Wine Target Class
pca_feature_loadings.csv

Contains the contribution of each original feature to the two principal components.

pca_explained_variance.csv

Contains:

Principal component number
Explained variance
Cumulative variance
🔄 Original vs Reduced Dataset
Dataset	Features
Original Wine Dataset	13
PCA Reduced Dataset	2

PCA allows the 13-dimensional data to be represented in a 2-dimensional space, making visualization and further analysis easier.

💡 Real-World Applications

PCA is commonly used in:

Data visualization
Image processing
Face recognition
Genomics
Financial analysis
Anomaly detection
Machine learning preprocessing
Feature engineering
High-dimensional data analysis
🆚 PCA vs K-Means vs DBSCAN
Technique	Main Purpose
K-Means	Cluster data into groups
DBSCAN	Density-based clustering and noise detection
PCA	Reduce the number of dimensions


# Day 10 - Gradient Boosting Classification

## 📌 Project Overview

This project demonstrates **Gradient Boosting Classification** using the Breast Cancer dataset from Scikit-learn.

Gradient Boosting is an ensemble machine learning technique that builds multiple decision trees sequentially. Each new tree attempts to improve the errors made by the previous trees.

The model is trained to classify samples into two classes: **malignant** and **benign**.

---

## 🎯 Objectives

* Understand Gradient Boosting
* Learn ensemble learning
* Perform binary classification
* Split data into training and testing sets
* Apply feature scaling
* Train a Gradient Boosting classifier
* Evaluate model accuracy
* Analyze the confusion matrix
* Study feature importance
* Generate prediction probabilities

---

## 🧠 What is Gradient Boosting?

Gradient Boosting is an **ensemble learning algorithm**.

Instead of depending on one decision tree, Gradient Boosting creates multiple trees sequentially.

Each new tree focuses on correcting the errors made by previous trees.

### Basic Workflow

```text
Dataset
   ↓
Train First Decision Tree
   ↓
Calculate Errors
   ↓
Train Next Tree
   ↓
Correct Previous Errors
   ↓
Repeat Process
   ↓
Combine Weak Learners
   ↓
Final Prediction
```

---

## 📊 Dataset

The project uses the built-in Breast Cancer dataset from Scikit-learn.

### Dataset Characteristics

* Samples: 569
* Features: 30
* Classes: 2
* Classification Type: Binary Classification

### Classes

```text
0 → Malignant
1 → Benign
```

The dataset contains numerical measurements related to cell characteristics.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 🔬 Machine Learning Workflow

### 1. Load Dataset

The Breast Cancer dataset is loaded using:

```python
from sklearn.datasets import load_breast_cancer
```

### 2. Data Exploration

The project checks:

* Dataset shape
* Data types
* Missing values
* Statistical summary
* Target distribution

### 3. Train-Test Split

The dataset is divided into:

* 80% training data
* 20% testing data

### 4. Feature Scaling

StandardScaler is used to standardize the feature values.

### 5. Model Training

GradientBoostingClassifier is used:

```python
GradientBoostingClassifier(
    n_estimators=100,
    learning_rate=0.1,
    max_depth=3,
    random_state=42
)
```

### 6. Prediction

The trained model predicts the class of unseen test samples.

### 7. Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### 8. Feature Importance

Gradient Boosting provides feature importance values that help identify which features contributed most to the predictions.

---

## 📈 Model Parameters

| Parameter     |             Value |
| ------------- | ----------------: |
| Algorithm     | Gradient Boosting |
| n_estimators  |               100 |
| learning_rate |               0.1 |
| max_depth     |                 3 |
| random_state  |                42 |
| Test Size     |               20% |

---

## 📊 Visualizations

The project generates:

1. Target distribution
2. Confusion matrix
3. Top 15 feature importance chart

---

## 📁 Project Structure

```text
Day-10-Gradient-Boosting-Breast-Cancer/
│
├── Gradient_Boosting_Breast_Cancer.ipynb
├── gradient_boosting_breast_cancer_predictions.csv
├── gradient_boosting_feature_importance.csv
├── gradient_boosting_model_summary.csv
└── README.md
```

---

## 💾 Output Files

### `gradient_boosting_breast_cancer_predictions.csv`

Contains:

* Actual class
* Predicted class
* Malignant probability
* Benign probability

### `gradient_boosting_feature_importance.csv`

Contains the importance score of each feature.

### `gradient_boosting_model_summary.csv`

Contains the main model configuration and evaluation information.

---

## 🧠 Important Concepts Learned

### Ensemble Learning

Combining multiple models to create a stronger predictive model.

### Weak Learners

Simple models, such as shallow decision trees, that are combined to build a stronger model.

### Sequential Learning

Gradient Boosting builds trees one after another rather than independently.

### Learning Rate

Controls how much each new tree contributes to the final model.

### Number of Estimators

Controls the number of boosting stages or trees.

### Feature Importance

Shows the relative contribution of features to the model.

---

## 🆚 Gradient Boosting vs Random Forest

| Feature         | Random Forest      | Gradient Boosting             |
| --------------- | ------------------ | ----------------------------- |
| Tree Training   | Parallel           | Sequential                    |
| Main Idea       | Reduce variance    | Correct errors                |
| Learning        | Independent trees  | Dependent trees               |
| Ensemble        | Bagging            | Boosting                      |
| Common Strength | Robust performance | Strong predictive performance |

---

## 🌍 Real-World Applications

Gradient Boosting is commonly used for:

* Fraud detection
* Customer churn prediction
* Credit risk analysis
* Medical classification
* Recommendation systems
* Sales prediction
* Customer behavior prediction
* Financial prediction
* Ranking problems

---

## 🚀 Future Improvements

* Tune hyperparameters using GridSearchCV
* Compare Gradient Boosting with Random Forest
* Try XGBoost
* Try LightGBM
* Try CatBoost
* Perform cross-validation
* Optimize precision and recall
* Build a web application for predictions

---

## 📚 Learning Outcome

After completing Day 10, I learned:

* What ensemble learning means
* How Gradient Boosting works
* Sequential decision-tree learning
* Learning rate
* Number of estimators
* Model evaluation
* Confusion matrix
* Feature importance
* Prediction probabilities

---

## 🏁 Conclusion

Day 10 introduced **Gradient Boosting**, an important ensemble learning algorithm for classification.

The project demonstrated how multiple decision trees can be combined sequentially to build a powerful predictive model.

**Learn → Build → Analyze → Improve → Share**


# Day 11 - AdaBoost Classification

## 📌 Project Overview

This project demonstrates **AdaBoost Classification** using the Breast Cancer dataset from Scikit-learn.

AdaBoost, short for **Adaptive Boosting**, is an ensemble machine learning algorithm that combines multiple weak learners to create a stronger classifier.

In this project, small Decision Trees are used as weak learners and combined sequentially to classify breast cancer samples.

---

## 🎯 Objectives

* Understand AdaBoost
* Learn ensemble learning
* Understand weak learners
* Perform binary classification
* Train an AdaBoost classifier
* Evaluate classification performance
* Analyze feature importance
* Generate prediction probabilities
* Study the effect of the number of estimators

---

## 🧠 What is AdaBoost?

**AdaBoost (Adaptive Boosting)** is an ensemble learning technique.

It starts with a simple model and gives more attention to incorrectly classified samples during subsequent boosting stages.

The process continues by adding weak learners that focus on improving previous mistakes.

### AdaBoost Workflow

```text
Dataset
   ↓
Create Initial Weak Learner
   ↓
Make Predictions
   ↓
Identify Incorrect Predictions
   ↓
Increase Focus on Difficult Samples
   ↓
Train Next Weak Learner
   ↓
Repeat
   ↓
Combine Weak Learners
   ↓
Final Prediction
```

---

## 📊 Dataset

The project uses the built-in **Breast Cancer Wisconsin dataset** available through Scikit-learn.

### Dataset Characteristics

* Samples: 569
* Features: 30
* Classes: 2
* Problem Type: Binary Classification

### Target Classes

```text
0 → Malignant
1 → Benign
```

The dataset contains numerical measurements describing characteristics of cell nuclei.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 🔬 Machine Learning Workflow

### 1. Load Dataset

The dataset is loaded using:

```python
from sklearn.datasets import load_breast_cancer
```

### 2. Explore Data

The project examines:

* Dataset shape
* Data types
* Missing values
* Statistical summary
* Target distribution

### 3. Train-Test Split

The dataset is divided into:

* 80% training data
* 20% testing data

### 4. Feature Scaling

StandardScaler is used to standardize the numerical features.

### 5. Create Base Learner

A shallow Decision Tree is used as the weak learner.

```python
DecisionTreeClassifier(
    max_depth=1,
    random_state=42
)
```

### 6. Create AdaBoost Model

```python
AdaBoostClassifier(
    estimator=base_model,
    n_estimators=100,
    learning_rate=0.5,
    random_state=42
)
```

### 7. Train Model

The AdaBoost model learns from the training dataset.

### 8. Make Predictions

The trained model predicts the classes of the test samples.

### 9. Evaluate Model

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### 10. Feature Importance

Feature importance is analyzed to understand which features contribute more to the model.

---

## 📈 Model Parameters

| Parameter      |               Value |
| -------------- | ------------------: |
| Algorithm      | AdaBoost Classifier |
| Base Estimator |       Decision Tree |
| Tree Depth     |                   1 |
| n_estimators   |                 100 |
| learning_rate  |                 0.5 |
| Test Size      |                 20% |
| random_state   |                  42 |

---

## 🔍 Important AdaBoost Concepts

### Weak Learner

A weak learner is a relatively simple model that performs better than random guessing.

In this project, a shallow Decision Tree is used.

### Boosting

Boosting combines multiple weak learners to create a stronger model.

### Adaptive Learning

AdaBoost gives more attention to samples that previous learners classified incorrectly.

### n_estimators

Controls the number of weak learners used by the AdaBoost model.

### learning_rate

Controls the contribution of each weak learner to the final model.

---

## 📊 Visualizations

This project generates:

1. Target class distribution
2. Confusion matrix
3. Feature importance chart
4. Number of estimators vs accuracy graph

---

## 📁 Project Structure

```text
Day-11-AdaBoost-Breast-Cancer/
│
├── AdaBoost_Breast_Cancer.ipynb
├── adaboost_breast_cancer_predictions.csv
├── adaboost_feature_importance.csv
├── adaboost_estimator_experiment.csv
├── adaboost_model_summary.csv
└── README.md
```

---

## 💾 Output Files

### `adaboost_breast_cancer_predictions.csv`

Contains:

* Actual class
* Predicted class
* Malignant probability
* Benign probability
* Actual label
* Predicted label

### `adaboost_feature_importance.csv`

Contains feature importance values for all 30 features.

### `adaboost_estimator_experiment.csv`

Contains accuracy results for different numbers of estimators.

### `adaboost_model_summary.csv`

Contains the main model configuration and accuracy.

---

## 🆚 AdaBoost vs Gradient Boosting

| Feature          | AdaBoost                       | Gradient Boosting          |
| ---------------- | ------------------------------ | -------------------------- |
| Technique        | Boosting                       | Boosting                   |
| Main Idea        | Focus on misclassified samples | Minimize prediction errors |
| Weak Learners    | Usually shallow trees          | Usually decision trees     |
| Learning         | Sequential                     | Sequential                 |
| Common Parameter | n_estimators                   | n_estimators               |
| Learning Rate    | Yes                            | Yes                        |

---

## 🌍 Real-World Applications

AdaBoost can be applied to:

* Fraud detection
* Classification systems
* Customer analysis
* Medical classification
* Face detection
* Spam detection
* Risk assessment
* Anomaly detection

---

## 🚀 Future Improvements

* Perform hyperparameter tuning
* Compare AdaBoost with Gradient Boosting
* Compare AdaBoost with Random Forest
* Experiment with different weak learners
* Apply cross-validation
* Test different learning rates
* Build a prediction web application

---

## 📚 Learning Outcomes

After completing Day 11, I learned:

* What AdaBoost means
* What boosting is
* What weak learners are
* How AdaBoost learns sequentially
* How incorrectly classified samples receive more attention
* The role of `n_estimators`
* The role of `learning_rate`
* Feature importance
* Classification evaluation
* Confusion matrix
* Prediction probabilities

---

## 📅 Machine Learning Journey

```text
Day 1  → Logistic Regression
Day 2  → Linear Regression
Day 3  → Decision Tree
Day 4  → KNN
Day 5  → Random Forest
Day 6  → SVM
Day 7  → K-Means
Day 8  → DBSCAN
Day 9  → PCA
Day 10 → Gradient Boosting
Day 11 → AdaBoost
```

---

## 🏁 Conclusion

Day 11 introduced **AdaBoost**, an important ensemble learning algorithm.

The project demonstrated how multiple weak Decision Tree learners can be combined sequentially to create a stronger classification model.

This project also helped me understand the relationship between **weak learners, boosting, learning rate, estimators, feature importance, and classification performance**.

**Learn → Build → Analyze → Improve → Share**

# Day 12 - XGBoost Classification

## 📌 Project Overview

This project demonstrates **XGBoost Classification** using the Breast Cancer dataset from Scikit-learn.

**XGBoost (Extreme Gradient Boosting)** is an optimized gradient boosting algorithm based on decision trees. It builds trees sequentially and combines them to create a strong predictive model.

In this project, XGBoost is used to classify breast cancer samples into **malignant** and **benign** classes.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand XGBoost
* Learn advanced gradient boosting
* Understand ensemble learning
* Perform binary classification
* Train an XGBoost classifier
* Evaluate classification performance
* Analyze feature importance
* Generate prediction probabilities
* Experiment with different numbers of estimators
* Compare XGBoost with other ensemble methods

---

## 🧠 What is XGBoost?

**XGBoost stands for Extreme Gradient Boosting.**

It is a powerful implementation of gradient-boosted decision trees designed for speed, performance, and regularization.

XGBoost builds trees sequentially. Each new tree attempts to improve the predictions made by the existing ensemble.

### Basic Workflow

```text
Dataset
   ↓
Initial Prediction
   ↓
Calculate Prediction Errors
   ↓
Build Decision Tree
   ↓
Improve Previous Prediction
   ↓
Add New Tree
   ↓
Repeat
   ↓
Combine Trees
   ↓
Final Prediction
```

---

## 🔬 Why XGBoost?

XGBoost is popular because it provides:

* Strong predictive performance
* Regularization
* Efficient tree boosting
* Handling of complex relationships
* Feature importance
* Parallel processing capabilities
* Support for classification and regression

---

## 📊 Dataset

This project uses the **Breast Cancer Wisconsin dataset** available through Scikit-learn.

### Dataset characteristics

* Samples: 569
* Features: 30
* Classes: 2
* Problem: Binary Classification

### Target Classes

```text
0 → Malignant
1 → Benign
```

The features represent numerical measurements describing characteristics of cell nuclei.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Google Colab
* Jupyter Notebook

---

## 📦 Installation

If XGBoost is not already installed:

```bash
pip install xgboost
```

For Google Colab:

```python
!pip install xgboost -q
```

---

## 🔬 Machine Learning Workflow

### Step 1 — Load Dataset

```python
from sklearn.datasets import load_breast_cancer
```

The built-in Breast Cancer dataset is loaded into a Pandas DataFrame.

### Step 2 — Explore Dataset

The project checks:

* Dataset shape
* Feature names
* Missing values
* Statistical summary
* Target distribution

### Step 3 — Train-Test Split

The dataset is divided into:

* 80% training data
* 20% testing data

### Step 4 — Feature Scaling

StandardScaler is applied to standardize the numerical features.

### Step 5 — Create XGBoost Model

The model uses:

```python
XGBClassifier(
    n_estimators=100,
    learning_rate=0.1,
    max_depth=3,
    subsample=0.8,
    colsample_bytree=0.8
)
```

### Step 6 — Train Model

The XGBoost classifier is trained using the training dataset.

### Step 7 — Make Predictions

The trained model predicts the classes of the test samples.

### Step 8 — Evaluate Performance

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Step 9 — Feature Importance

XGBoost feature importance is analyzed to determine which features contributed most to the predictions.

### Step 10 — Parameter Experiment

Different values of `n_estimators` are tested to observe their effect on accuracy.

---

## ⚙️ XGBoost Parameters

| Parameter          |           Value | Purpose                                    |
| ------------------ | --------------: | ------------------------------------------ |
| `n_estimators`     |             100 | Number of boosting rounds                  |
| `learning_rate`    |             0.1 | Contribution of each tree                  |
| `max_depth`        |               3 | Maximum tree depth                         |
| `subsample`        |             0.8 | Fraction of training samples used per tree |
| `colsample_bytree` |             0.8 | Fraction of features used per tree         |
| `objective`        | binary:logistic | Binary classification                      |
| `eval_metric`      |         logloss | Training evaluation metric                 |
| `random_state`     |              42 | Reproducibility                            |

---

## 🧠 Important Concepts Learned

### 1. Gradient Boosting

A sequential ensemble technique where new models improve previous predictions.

### 2. Boosting

Multiple weak learners are combined to form a stronger model.

### 3. Learning Rate

Controls how strongly each new tree contributes to the final model.

### 4. n_estimators

Controls the number of boosting rounds.

### 5. max_depth

Controls the maximum depth of each decision tree.

### 6. Subsampling

`subsample` controls the fraction of training samples used for each tree.

### 7. Feature Subsampling

`colsample_bytree` controls the fraction of features considered for each tree.

### 8. Feature Importance

Shows the relative importance of input features in the trained model.

---

## 📊 Visualizations

The project generates:

1. Target distribution
2. Confusion matrix
3. Top 15 feature importance chart
4. Number of estimators vs accuracy graph

---

## 📁 Project Structure

```text
Day-12-XGBoost-Breast-Cancer/
│
├── XGBoost_Breast_Cancer.ipynb
├── xgboost_breast_cancer_predictions.csv
├── xgboost_feature_importance.csv
├── xgboost_estimator_experiment.csv
├── xgboost_model_summary.csv
└── README.md
```

---

## 💾 Output Files

### `xgboost_breast_cancer_predictions.csv`

Contains:

* Actual class
* Predicted class
* Prediction probability
* Actual label
* Predicted label

### `xgboost_feature_importance.csv`

Contains the importance value of each feature.

### `xgboost_estimator_experiment.csv`

Contains accuracy results for different values of `n_estimators`.

### `xgboost_model_summary.csv`

Contains the model configuration and final accuracy.

---

## 🆚 XGBoost vs Gradient Boosting vs AdaBoost

| Feature            | AdaBoost       | Gradient Boosting         | XGBoost                   |
| ------------------ | -------------- | ------------------------- | ------------------------- |
| Learning Type      | Boosting       | Boosting                  | Boosting                  |
| Training           | Sequential     | Sequential                | Sequential                |
| Base Models        | Weak learners  | Decision trees            | Decision trees            |
| Regularization     | Limited        | Available                 | Strong                    |
| Speed Optimization | Basic          | Moderate                  | Highly optimized          |
| Feature Importance | Yes            | Yes                       | Yes                       |
| Common Use         | Classification | Classification/Regression | Classification/Regression |

---

## 🌍 Real-World Applications

XGBoost is widely used for:

* Fraud detection
* Credit risk prediction
* Customer churn prediction
* Medical classification
* Sales prediction
* Customer behavior analysis
* Ranking systems
* Financial modeling
* Recommendation systems
* Tabular machine learning problems

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* RandomizedSearchCV
* Cross-validation
* Early stopping
* Compare XGBoost with LightGBM
* Compare XGBoost with CatBoost
* ROC-AUC analysis
* Precision-Recall analysis
* SHAP-based model explainability
* Deploy the model as a web application

---

## 📅 Machine Learning Journey

```text
Day 1  → Logistic Regression
Day 2  → Linear Regression
Day 3  → Decision Tree
Day 4  → KNN
Day 5  → Random Forest
Day 6  → SVM
Day 7  → K-Means
Day 8  → DBSCAN
Day 9  → PCA
Day 10 → Gradient Boosting
Day 11 → AdaBoost
Day 12 → XGBoost
```

---

## 📚 Learning Outcome

After completing Day 12, I learned:

* What XGBoost is
* How gradient boosting works
* Ensemble learning
* Sequential tree building
* Learning rate
* Boosting rounds
* Tree depth
* Subsampling
* Feature importance
* Classification evaluation
* Model parameter experimentation

---

## 🏁 Conclusion

Day 12 introduced **XGBoost**, one of the most important gradient boosting techniques for tabular machine learning.

The project demonstrated how sequential decision trees can be combined to create a powerful classifier while also exploring important parameters such as `n_estimators`, `learning_rate`, `max_depth`, `subsample`, and `colsample_bytree`.

This project builds on the concepts learned in **Gradient Boosting and AdaBoost** and takes the ensemble-learning section of the 30-day journey one step further.

**Learn → Build → Analyze → Improve → Share**
# Day 13 - Naive Bayes Spam Detection

## 📌 Project Overview

This project demonstrates **Text Classification using Multinomial Naive Bayes**.

The goal is to classify messages into two categories:

* **Spam**
* **Ham (Not Spam)**

The project combines **TF-IDF text vectorization** with the **Multinomial Naive Bayes** algorithm.

This introduces Natural Language Processing (NLP) concepts into the 30-day Machine Learning journey.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand Naive Bayes
* Learn text classification
* Understand NLP preprocessing
* Convert text into numerical features
* Use TF-IDF vectorization
* Train a Multinomial Naive Bayes classifier
* Evaluate classification performance
* Analyze important spam-related words
* Predict custom messages

---

## 🧠 What is Naive Bayes?

Naive Bayes is a probabilistic machine learning algorithm based on **Bayes' theorem**.

It assumes that features contribute independently to the outcome given the class.

Despite this simplifying assumption, Naive Bayes performs very well for many text-classification problems.

### Basic Workflow

```text
Text Dataset
     ↓
Text Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Numerical Feature Matrix
     ↓
Naive Bayes Model
     ↓
Training
     ↓
Prediction
     ↓
Spam / Ham
```

---

## 📱 Project Problem

Spam messages can contain words such as:

```text
free
prize
winner
cash
reward
claim
offer
```

Normal messages may contain words such as:

```text
project
meeting
assignment
class
report
exam
```

The model learns patterns from these words and predicts whether a new message is likely to be spam or normal.

---

## 📊 Dataset

For this learning project, a small text-message dataset was created containing examples of:

* Spam messages
* Normal messages

### Classes

```text
0 → Ham
1 → Spam
```

The dataset is intended for educational demonstration of the complete NLP + machine-learning workflow.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TF-IDF
* Multinomial Naive Bayes
* Google Colab
* Jupyter Notebook

---

## 🔬 Machine Learning Workflow

### 1. Create Dataset

Text messages and their corresponding labels are stored in a Pandas DataFrame.

### 2. Encode Labels

The labels are converted into numerical values:

```python
ham  → 0
spam → 1
```

### 3. Train-Test Split

The dataset is divided into:

* 80% training data
* 20% testing data

### 4. TF-IDF Vectorization

Text cannot be directly provided to most machine-learning algorithms.

TF-IDF converts text into numerical feature vectors.

```python
TfidfVectorizer()
```

### 5. Train Naive Bayes

The Multinomial Naive Bayes classifier is trained using the TF-IDF features.

```python
MultinomialNB()
```

### 6. Prediction

The model predicts whether unseen messages are:

* Spam
* Ham

### 7. Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### 8. Custom Predictions

New messages are provided to the trained model to demonstrate real-time classification.

---

## 🔤 What is TF-IDF?

**TF-IDF** stands for:

> Term Frequency — Inverse Document Frequency

It converts text into numerical values based on the importance of words within documents.

Words that are important to a particular message receive higher weights.

### TF-IDF Process

```text
Text
 ↓
Tokenization
 ↓
Calculate Term Frequency
 ↓
Calculate Inverse Document Frequency
 ↓
Generate Numerical Vectors
```

---

## 🧠 Why Multinomial Naive Bayes?

Multinomial Naive Bayes is particularly useful for text classification because it works well with word-frequency or TF-IDF based features.

Common applications include:

* Spam detection
* Sentiment analysis
* News classification
* Document classification
* Email filtering

---

## 📊 Model Evaluation

The project evaluates the model using:

### Accuracy

Measures the percentage of correctly classified messages.

### Precision

Measures how many predicted spam messages were actually spam.

### Recall

Measures how many actual spam messages were correctly detected.

### F1-Score

Provides a balance between precision and recall.

### Confusion Matrix

Shows:

```text
True Negative
False Positive
False Negative
True Positive
```

---

## 🔍 Important Spam Words

The project also calculates word scores to identify words that are strongly associated with spam messages.

Examples may include:

```text
free
prize
claim
reward
cash
winner
offer
```

---

## 📈 Visualizations

The project generates:

1. Spam vs Ham distribution
2. Confusion matrix
3. Important spam-word visualization

---

## 📁 Project Structure

```text
Day-13-Naive-Bayes-Spam-Detection/
│
├── Naive_Bayes_Spam_Detection.ipynb
├── naive_bayes_spam_predictions.csv
├── naive_bayes_custom_predictions.csv
├── naive_bayes_word_importance.csv
├── naive_bayes_model_summary.csv
└── README.md
```

---

## 💾 Output Files

### `naive_bayes_spam_predictions.csv`

Contains:

* Original message
* Actual class
* Predicted class
* Ham probability
* Spam probability
* Actual label
* Predicted label

### `naive_bayes_custom_predictions.csv`

Contains predictions for manually entered messages.

### `naive_bayes_word_importance.csv`

Contains words ranked according to their association with spam.

### `naive_bayes_model_summary.csv`

Contains the main model information and accuracy.

---

## 🆚 Naive Bayes vs Previous Algorithms

| Algorithm           | Main Application                   |
| ------------------- | ---------------------------------- |
| Logistic Regression | Classification                     |
| Decision Tree       | Classification                     |
| KNN                 | Classification                     |
| Random Forest       | Ensemble Classification            |
| SVM                 | Classification                     |
| Gradient Boosting   | Ensemble Learning                  |
| AdaBoost            | Boosting                           |
| XGBoost             | Advanced Boosting                  |
| Naive Bayes         | Probabilistic Classification / NLP |

---

## 🌍 Real-World Applications

Naive Bayes is commonly used for:

* Email spam filtering
* SMS spam detection
* Sentiment analysis
* News categorization
* Document classification
* Text filtering
* Customer feedback classification

---

## 🚀 Future Improvements

* Use a larger real-world SMS spam dataset
* Add text preprocessing
* Remove punctuation
* Apply stemming
* Apply lemmatization
* Compare CountVectorizer with TF-IDF
* Compare Naive Bayes with Logistic Regression
* Use n-grams
* Perform hyperparameter tuning
* Build a web-based spam detector

---

## 📅 Machine Learning Journey

```text
Day 1  → Logistic Regression
Day 2  → Linear Regression
Day 3  → Decision Tree
Day 4  → KNN
Day 5  → Random Forest
Day 6  → SVM
Day 7  → K-Means
Day 8  → DBSCAN
Day 9  → PCA
Day 10 → Gradient Boosting
Day 11 → AdaBoost
Day 12 → XGBoost
Day 13 → Naive Bayes
```

---

## 📚 Learning Outcomes

After completing Day 13, I learned:

* What Naive Bayes is
* Probabilistic classification
* Multinomial Naive Bayes
* Text classification
* NLP fundamentals
* TF-IDF
* Vocabulary generation
* Classification metrics
* Confusion matrix
* Prediction probabilities
* Spam detection

---

## 🏁 Conclusion

Day 13 introduced **Naive Bayes** and the fundamentals of text classification.

Unlike the tree-based ensemble algorithms explored in the previous days, this project focuses on **Natural Language Processing and probabilistic machine learning**.

By combining **TF-IDF and Multinomial Naive Bayes**, text messages can be converted into numerical representations and classified as spam or normal messages.

**Learn → Build → Analyze → Improve → Share**
# Day 14 - Sentiment Analysis using Logistic Regression and TF-IDF

## 📌 Project Overview

This project performs **Sentiment Analysis** on text reviews using **TF-IDF Vectorization** and **Logistic Regression**.

The model classifies text into two categories:

* Positive
* Negative

This project is part of my **30-Day Machine Learning Learning Series**.

---

## 🎯 Objectives

* Understand basic Natural Language Processing (NLP)
* Convert text into numerical features using TF-IDF
* Apply Logistic Regression to text classification
* Evaluate classification performance
* Predict sentiment for new/custom messages
* Identify important words/features influencing predictions

---

## 🧠 Machine Learning Concepts

### 1. Natural Language Processing

NLP allows computers to process and understand human language.

### 2. TF-IDF

TF-IDF stands for:

**Term Frequency - Inverse Document Frequency**

It converts text into numerical values based on the importance of words within documents.

### 3. Logistic Regression

Logistic Regression is a supervised machine learning algorithm commonly used for classification.

In this project:

```text
Text → TF-IDF → Logistic Regression → Sentiment
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TF-IDF
* Logistic Regression
* Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```text
Day-14-Sentiment-Analysis/
│
├── Sentiment_Analysis.ipynb
├── sentiment_predictions.csv
├── sentiment_custom_predictions.csv
├── sentiment_feature_importance.csv
├── sentiment_model_summary.csv
└── README.md
```

---

## 🔄 Workflow

```text
Dataset
   ↓
Train-Test Split
   ↓
TF-IDF Vectorization
   ↓
Logistic Regression
   ↓
Model Prediction
   ↓
Accuracy & Classification Report
   ↓
Confusion Matrix
   ↓
Custom Sentiment Prediction
```

---

## 📊 Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The notebook also generates prediction probabilities for each test message.

---

## 🔍 Feature Importance

Logistic Regression coefficients are used to identify words/features that contribute toward positive or negative sentiment.

Positive coefficient:

```text
Positive sentiment influence
```

Negative coefficient:

```text
Negative sentiment influence
```

---

## 💾 Generated Files

### `sentiment_predictions.csv`

Contains test-set predictions and sentiment probabilities.

### `sentiment_custom_predictions.csv`

Contains predictions for manually entered messages.

### `sentiment_feature_importance.csv`

Contains TF-IDF features and their Logistic Regression coefficients.

### `sentiment_model_summary.csv`

Contains model configuration and performance information.

---

## 🚀 Future Improvements

* Use a larger real-world review dataset
* Add neutral sentiment
* Perform advanced text preprocessing
* Compare Logistic Regression with Naive Bayes and SVM
* Use Word2Vec or embeddings
* Experiment with transformer-based NLP models
* Build a web application for real-time sentiment prediction

---

## 📚 Key Learning

Day 14 helped me understand how **machine learning can work with human language**.

The key pipeline learned today was:

```text
Text
 ↓
TF-IDF
 ↓
Machine Learning Model
 ↓
Classification
```

This provides a foundation for applications such as:

* Product review analysis
* Customer feedback analysis
* Social media sentiment analysis
* Opinion mining
* Customer support analytics

---

## 👨‍💻 Author

**Magesh L**

B.E. Computer Science and Engineering

Karpaga Vinayaga College of Engineering and Technology

---

## ⭐ 30-Day ML Series

**Day 14 / 30 Completed**

Continuing to learn, build, document, and share one machine learning concept every day.

# Day 15 - Neural Network Classification using MLP

## 📌 Project Overview

This project demonstrates **Neural Network Classification** using the `MLPClassifier` from Scikit-learn.

The **Breast Cancer Wisconsin dataset** is used to classify tumors into:

* Malignant
* Benign

This project is part of my **30-Day Machine Learning Learning Series**.

---

## 🎯 Objectives

* Understand the fundamentals of Artificial Neural Networks
* Learn how an MLP classifier works
* Understand input, hidden, and output layers
* Apply feature scaling before neural network training
* Learn about the ReLU activation function
* Understand the Adam optimizer
* Evaluate a neural network using classification metrics
* Visualize the training loss curve

---

## 🧠 Machine Learning Concept

### Multi-Layer Perceptron (MLP)

An MLP is a type of feed-forward artificial neural network.

The network used in this project contains:

```text
Input Layer
    ↓
64 Neurons
    ↓
32 Neurons
    ↓
Output Layer
```

### Architecture

```text
30 Input Features
       ↓
Hidden Layer 1
64 Neurons
ReLU
       ↓
Hidden Layer 2
32 Neurons
ReLU
       ↓
Output
Malignant / Benign
```

---

## 🔄 Workflow

```text
Breast Cancer Dataset
        ↓
Train-Test Split
        ↓
StandardScaler
        ↓
MLP Neural Network
        ↓
Model Training
        ↓
Prediction
        ↓
Accuracy
        ↓
Classification Report
        ↓
Confusion Matrix
        ↓
Loss Curve
```

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* MLPClassifier
* StandardScaler
* Google Colab / Jupyter Notebook

---

## 📊 Dataset

The project uses the built-in **Breast Cancer Wisconsin dataset** available through Scikit-learn.

The dataset contains:

* 569 samples
* 30 numerical features
* 2 target classes

Target classes:

```text
0 → Malignant
1 → Benign
```

---

## ⚙️ Model Configuration

```python
MLPClassifier(
    hidden_layer_sizes=(64, 32),
    activation="relu",
    solver="adam",
    alpha=0.0001,
    learning_rate_init=0.001,
    max_iter=1000,
    early_stopping=True
)
```

### Important Parameters

| Parameter            | Purpose                                                    |
| -------------------- | ---------------------------------------------------------- |
| `hidden_layer_sizes` | Defines neural network hidden layers                       |
| `activation`         | Activation function                                        |
| `solver`             | Optimization algorithm                                     |
| `learning_rate_init` | Initial learning rate                                      |
| `max_iter`           | Maximum training iterations                                |
| `early_stopping`     | Stops training when validation performance stops improving |

---

## 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Training Loss

The project also generates prediction probabilities.

---

## 📉 Loss Curve

The training loss curve helps visualize how the neural network's loss changes during training.

```text
Higher Loss
     │\
     │ \
     │  \
     │   \
     │    \____
     │
     └──────────────
       Iterations
```

A decreasing loss generally indicates that the model is learning from the training data.

---

## 📂 Project Structure

```text
Day-15-Neural-Network-Classification/
│
├── Neural_Network_Classification.ipynb
├── neural_network_predictions.csv
├── neural_network_model_summary.csv
├── neural_network_loss_curve.csv
└── README.md
```

---

## 💾 Generated Files

### `neural_network_predictions.csv`

Contains actual labels, predicted labels, and prediction probabilities.

### `neural_network_model_summary.csv`

Contains model configuration and performance information.

### `neural_network_loss_curve.csv`

Contains training iteration and loss values.

---

## 🚀 Future Improvements

* Experiment with different neural network architectures
* Tune learning rate
* Tune hidden-layer sizes
* Compare different activation functions
* Use cross-validation
* Compare MLP with XGBoost, SVM, and Random Forest
* Experiment with deep learning frameworks such as TensorFlow and PyTorch
* Apply neural networks to image and NLP datasets

---

## 💡 Key Learning

Day 15 introduced me to **Artificial Neural Networks**.

The main learning pipeline was:

```text
Features
   ↓
Scaling
   ↓
Neural Network
   ↓
Hidden Layers
   ↓
Activation Function
   ↓
Prediction
```

This project helped me understand the foundation behind more advanced **Deep Learning and AI systems**.

---

## 👨‍💻 Author

**Magesh L**

B.E. Computer Science and Engineering

Karpaga Vinayaga College of Engineering and Technology

---

## 📌 30-Day ML Series

**Day 15 / 30 Completed ✅**

Learning → Building → Documenting → Sharing 🚀

# Day 16 - Support Vector Regression for House Price Prediction

## 📌 Project Overview

This project demonstrates **Support Vector Regression (SVR)** for predicting house values.

The project uses the **California Housing dataset** available through Scikit-learn.

SVR is a regression technique based on the Support Vector Machine algorithm.

This project is part of my **30-Day Machine Learning Learning Series**.

---

## 🎯 Objectives

* Understand Support Vector Regression
* Learn how SVR can be used for regression problems
* Understand the importance of feature scaling
* Learn about the RBF kernel
* Understand important SVR parameters
* Evaluate regression performance
* Analyze prediction errors

---

## 🧠 Machine Learning Concept

### Support Vector Regression

Support Vector Regression extends the Support Vector Machine concept to continuous-value prediction.

Instead of predicting classes, SVR predicts a numerical value.

In this project:

```text
Housing Features
       ↓
Feature Scaling
       ↓
SVR
       ↓
House Value Prediction
```

---

## 🔑 Important SVR Parameters

### Kernel

The project uses:

```python
kernel="rbf"
```

RBF stands for **Radial Basis Function**.

### C

```python
C=100
```

Controls the trade-off between model complexity and training errors.

### Gamma

```python
gamma="scale"
```

Controls how strongly individual training samples influence the model.

### Epsilon

```python
epsilon=0.1
```

Defines the epsilon-tube within which errors are not penalized.

---

## 📊 Dataset

The project uses the **California Housing dataset**.

Features include:

* MedInc
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

Target:

```text
HouseValue
```

The target represents median house value in units of $100,000.

---

## 🔄 Workflow

```text
California Housing Dataset
          ↓
Data Exploration
          ↓
Train-Test Split
          ↓
StandardScaler
          ↓
Support Vector Regression
          ↓
RBF Kernel
          ↓
Prediction
          ↓
Evaluation
          ↓
Error Analysis
```

---

## 📈 Evaluation Metrics

The following metrics are used:

### MAE

Mean Absolute Error measures the average absolute difference between actual and predicted values.

### MSE

Mean Squared Error gives more weight to larger errors.

### RMSE

Root Mean Squared Error is the square root of MSE.

### R² Score

R² measures how much of the variation in the target is explained by the model.

---

## 📉 Visualizations

The project generates:

* Correlation matrix
* Actual vs predicted scatter plot
* Prediction error distribution

---

## 📂 Project Structure

```text
Day-16-Support-Vector-Regression/
│
├── SVR_House_Price_Prediction.ipynb
├── svr_house_predictions.csv
├── svr_model_summary.csv
├── svr_error_analysis.csv
└── README.md
```

---

## 💾 Generated Files

### `svr_house_predictions.csv`

Contains actual and predicted house values.

### `svr_model_summary.csv`

Contains model configuration and evaluation metrics.

### `svr_error_analysis.csv`

Contains prediction errors and absolute errors.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Support Vector Regression
* StandardScaler
* Google Colab / Jupyter Notebook

---

## 🚀 Future Improvements

* Perform GridSearchCV for hyperparameter tuning
* Compare RBF, linear, and polynomial kernels
* Experiment with different C values
* Experiment with different gamma values
* Compare SVR with Linear Regression
* Compare SVR with Random Forest Regression
* Build a house-price prediction web application

---

## 💡 Key Learning

Day 16 helped me understand that **Support Vector Machines are not limited to classification**.

SVR can also be used to predict continuous numerical values.

The major pipeline learned today was:

```text
Features
   ↓
Scaling
   ↓
Kernel Transformation
   ↓
SVR
   ↓
Continuous Prediction
```

# Day 17 - KNN Regression for House Price Prediction

## 📌 Project Overview

This project demonstrates **K-Nearest Neighbors (KNN) Regression** for predicting house values.

The **California Housing dataset** from Scikit-learn is used for this project.

Unlike traditional regression algorithms that learn an explicit equation, KNN Regression predicts a target value using the values of nearby training samples.

This project is part of my **30-Day Machine Learning Learning Series**.

---

## 🎯 Objectives

* Understand KNN Regression
* Learn distance-based machine learning
* Understand the importance of feature scaling
* Experiment with different K values
* Find a suitable K based on RMSE
* Evaluate regression performance
* Analyze prediction errors

---

## 🧠 What is KNN Regression?

KNN stands for **K-Nearest Neighbors**.

For regression, the algorithm looks at the nearest training examples and uses their target values to generate a prediction.

Simplified workflow:

```text
New Data Point
      ↓
Calculate Distances
      ↓
Find K Nearest Neighbors
      ↓
Use Neighbor Target Values
      ↓
Generate Prediction
```

---

## 🔍 KNN Parameters

The model uses:

```python
KNeighborsRegressor(
    n_neighbors=5,
    weights="distance",
    metric="minkowski",
    p=2
)
```

### `n_neighbors`

Defines how many nearby samples are considered.

### `weights="distance"`

Closer samples receive greater influence on the prediction.

### `metric="minkowski"`

Defines the distance calculation.

### `p=2`

With `p=2`, Minkowski distance corresponds to Euclidean distance.

---

## 📊 Dataset

The project uses the **California Housing dataset**.

Features include:

* MedInc
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

Target:

```text
HouseValue
```

The target represents median house value in units of $100,000.

---

## 🔄 Machine Learning Workflow

```text
California Housing Dataset
          ↓
Data Exploration
          ↓
Train-Test Split
          ↓
Feature Scaling
          ↓
KNN Regression
          ↓
Test Different K Values
          ↓
Select K Based on RMSE
          ↓
Final Prediction
          ↓
Error Analysis
```

---

## 📈 Evaluation Metrics

The project uses:

### MAE

Mean Absolute Error measures the average absolute prediction error.

### MSE

Mean Squared Error gives greater weight to larger errors.

### RMSE

Root Mean Squared Error measures prediction error in the same general scale as the target.

### R² Score

R² measures the proportion of target variation explained by the model.

---

## 🧪 K Value Experiment

The project tests multiple K values:

```text
K = 1
K = 3
K = 5
K = 7
K = 10
K = 15
K = 20
```

The RMSE values are compared to select a K value for the final model.

---

## 📂 Project Structure

```text
Day-17-KNN-Regression/
│
├── KNN_Regression_House_Price.ipynb
├── knn_house_predictions.csv
├── knn_k_experiment.csv
├── knn_model_summary.csv
└── README.md
```

---

## 💾 Generated Files

### `knn_house_predictions.csv`

Contains:

* Actual house values
* Predicted house values
* Prediction errors
* Absolute errors

### `knn_k_experiment.csv`

Contains the performance of different K values.

### `knn_model_summary.csv`

Contains the final model configuration and evaluation metrics.

---

## 📊 Visualizations

The project generates:

* Correlation matrix
* Actual vs predicted plot
* Prediction error distribution
* K vs RMSE experiment plot

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* KNeighborsRegressor
* StandardScaler
* Google Colab / Jupyter Notebook

---

## 🚀 Future Improvements

* Use GridSearchCV for systematic hyperparameter tuning
* Compare different distance metrics
* Compare uniform and distance-based weights
* Test larger datasets
* Compare KNN with SVR
* Compare KNN with tree-based regression
* Build a real-time house price prediction application

---

## 💡 Key Learning

Day 17 helped me understand **distance-based regression**.

The main concept was:

```text
Training Data
     ↓
Calculate Distance
     ↓
Find Nearest Neighbors
     ↓
Use Neighbor Information
     ↓
Predict Continuous Value
```

I also learned why **feature scaling is important for KNN**, because the algorithm depends on distances between data points.

# Day 18 — Isolation Forest for Anomaly Detection

## 📌 Project Overview

Welcome to **Day 18** of my 30-Day Machine Learning Daily Series.

In this project, I implemented **Isolation Forest**, an unsupervised machine learning algorithm used to identify unusual or anomalous observations.

The project simulates financial transactions and detects potentially unusual transactions based on:

* Transaction Amount
* Transaction Frequency
* Transaction Hour
* Distance From Home

---

## 🎯 Objective

The main objectives are:

* Understand anomaly detection
* Learn how Isolation Forest works
* Detect unusual transactions
* Perform feature scaling
* Analyze anomaly scores
* Experiment with contamination levels
* Create a custom anomaly detection function

---

## 🧠 What is Isolation Forest?

**Isolation Forest** is an unsupervised learning algorithm designed specifically for anomaly detection.

The basic idea is that anomalies are usually:

* Rare
* Different from normal observations
* Easier to isolate from the rest of the data

The algorithm creates random decision trees and measures how quickly observations can be isolated.

An observation requiring fewer splits to isolate is more likely to be an anomaly.

---

## 🔍 Isolation Forest Output

The model produces two important outputs.

### Prediction

```text
1  → Normal
-1 → Anomaly
```

### Anomaly Score

The anomaly score indicates how unusual an observation is.

Lower scores generally indicate observations that are more likely to be anomalous.

---

## 📊 Dataset

This project uses a **synthetically generated financial transaction dataset**.

The dataset contains:

| Feature               | Description                           |
| --------------------- | ------------------------------------- |
| Amount                | Transaction amount                    |
| Transaction_Frequency | Number of transactions                |
| Transaction_Hour      | Time of transaction                   |
| Distance_From_Home    | Distance between transaction and home |

The dataset contains normal transactions and intentionally generated unusual transactions for demonstration.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```text
Generate Transaction Data
          ↓
Data Exploration
          ↓
Feature Selection
          ↓
Feature Scaling
          ↓
Isolation Forest
          ↓
Anomaly Prediction
          ↓
Anomaly Score Analysis
          ↓
Visualization
          ↓
Contamination Experiment
          ↓
Save Results
```

---

## ⚙️ Model Configuration

```python
IsolationForest(
    n_estimators=200,
    contamination=0.03,
    random_state=42,
    n_jobs=-1
)
```

### Parameters

**n_estimators**

Number of isolation trees used by the model.

**contamination**

Expected proportion of anomalies in the dataset.

**random_state**

Ensures reproducible results.

**n_jobs**

Allows the model to use multiple CPU cores.

---

## 📈 Experiments

The project experiments with different contamination values:

```text
0.01
0.02
0.03
0.05
0.08
```

This helps understand how the expected anomaly percentage affects the number of detected anomalies.

---

## 📊 Visualizations

The project generates:

1. Transaction Amount vs Transaction Frequency
2. Transaction Hour vs Distance From Home
3. Anomaly Score Distribution
4. Contamination vs Detected Anomalies

---

## 📁 Generated Files

### `isolation_forest_transactions.csv`

Contains all transactions along with:

* Anomaly Prediction
* Anomaly Label
* Anomaly Score

### `detected_anomalies.csv`

Contains only transactions classified as anomalies.

### `isolation_forest_experiment.csv`

Contains results from different contamination values.

### `isolation_forest_model_summary.csv`

Contains the main model configuration and summary statistics.

---

## 🌍 Real-World Applications

Isolation Forest can be used in areas such as:

* Fraud detection
* Network intrusion detection
* Cybersecurity
* Manufacturing defect detection
* Sensor anomaly detection
* Financial transaction monitoring
* Healthcare monitoring
* IoT monitoring
* System failure detection

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* What anomaly detection means
* How Isolation Forest works
* Difference between supervised and unsupervised learning
* Feature scaling
* Anomaly scores
* Contamination parameter
* Outlier visualization
* Practical anomaly detection workflow

---

## 🚀 Future Improvements

Possible improvements include:

* Use a real financial transaction dataset
* Compare Isolation Forest with DBSCAN
* Compare with Local Outlier Factor
* Build a real-time fraud detection dashboard
* Deploy the model using Streamlit
* Integrate the model with an API

---

# Day 19 — Hierarchical Clustering for Customer Segmentation

## 📌 Project Overview

Welcome to **Day 19** of my 30-Day Machine Learning Daily Series.

In this project, I implemented **Hierarchical Clustering** using **Agglomerative Clustering** to segment customers based on their purchasing characteristics.

The project analyzes:

* Annual Income
* Spending Score
* Age
* Purchase Frequency

The objective is to discover natural groups of customers without using predefined labels.

---

## 🎯 Objective

The main objectives of this project are:

* Understand hierarchical clustering
* Learn Agglomerative Clustering
* Understand dendrograms
* Perform customer segmentation
* Use feature scaling
* Evaluate clusters using Silhouette Score
* Experiment with different numbers of clusters
* Analyze customer groups

---

## 🧠 What is Hierarchical Clustering?

Hierarchical Clustering is an **unsupervised machine learning algorithm** that creates a hierarchy of clusters.

There are two major approaches:

### 1. Agglomerative Clustering

Starts with each data point as an individual cluster and progressively merges similar clusters.

```text
Individual Points
       ↓
Small Clusters
       ↓
Larger Clusters
       ↓
Final Clusters
```

### 2. Divisive Clustering

Starts with one large cluster and progressively divides it into smaller clusters.

This project uses **Agglomerative Clustering**.

---

## 🌳 What is a Dendrogram?

A **dendrogram** is a tree-like visualization that shows how clusters are progressively merged.

It helps understand the hierarchical structure of the data and can assist in selecting an appropriate number of clusters.

---

## 📊 Dataset

This project uses a synthetically generated customer dataset.

| Feature            | Description                |
| ------------------ | -------------------------- |
| Customer_ID        | Unique customer identifier |
| Annual_Income      | Customer annual income     |
| Spending_Score     | Customer spending score    |
| Age                | Customer age               |
| Purchase_Frequency | Number of purchases        |

---

## ⚙️ Algorithm

The project uses:

```python
AgglomerativeClustering(
    n_clusters=4,
    metric="euclidean",
    linkage="ward"
)
```

### Important Parameters

**n_clusters**

Number of customer groups to create.

**metric**

Distance measurement between observations.

**linkage**

Method used to determine how clusters are merged.

The project uses:

```text
Ward Linkage
```

---

## 📐 Silhouette Score

The **Silhouette Score** measures how well-separated the generated clusters are.

Its value generally ranges from:

```text
-1 to +1
```

A higher score generally indicates better-defined clustering structure.

The project tests multiple cluster counts and selects the configuration with the highest Silhouette Score for the experiment.

---

## 🔄 Machine Learning Workflow

```text
Generate Customer Dataset
          ↓
Data Exploration
          ↓
Feature Selection
          ↓
Feature Scaling
          ↓
Create Dendrogram
          ↓
Agglomerative Clustering
          ↓
Cluster Evaluation
          ↓
Silhouette Score
          ↓
Cluster Experiment
          ↓
Customer Segmentation
          ↓
Save Results
```

---

## 📈 Visualizations

The project generates:

1. Hierarchical Clustering Dendrogram
2. Annual Income vs Spending Score
3. Age vs Spending Score
4. Number of Clusters vs Silhouette Score

---

## 📁 Generated Files

### `hierarchical_customer_segmentation.csv`

Contains customer information along with:

* Cluster assignment
* Best cluster assignment
* Customer segment

### `hierarchical_cluster_summary.csv`

Contains average statistics for each cluster.

### `hierarchical_cluster_experiment.csv`

Contains Silhouette Scores for different numbers of clusters.

### `hierarchical_model_summary.csv`

Contains the main model configuration and evaluation information.

---

## 💼 Real-World Applications

Hierarchical Clustering can be applied to:

* Customer segmentation
* Market research
* Document clustering
* Social network analysis
* Biological data analysis
* Image segmentation
* Recommendation systems
* Product grouping

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* Unsupervised learning
* Hierarchical clustering
* Agglomerative clustering
* Dendrogram interpretation
* Ward linkage
* Euclidean distance
* Feature scaling
* Silhouette Score
* Customer segmentation

---

## 🚀 Future Improvements

Possible improvements include:

* Use a real customer dataset
* Compare Hierarchical Clustering with K-Means
* Compare different linkage methods
* Build an interactive Streamlit dashboard
* Add customer purchasing history
* Build a recommendation system based on customer clusters

---
# Day 20 — Naive Bayes for SMS Spam Detection

## 📌 Project Overview

Welcome to **Day 20** of my Machine Learning Daily Series.

For Day 20, I explored **Naive Bayes Classification** and built a simple **SMS Spam Detection** system.

The project classifies messages into two categories:

* **Ham** — Normal message
* **Spam** — Unwanted/promotional message

The project combines **TF-IDF text vectorization** with **Multinomial Naive Bayes**.

---

## 🎯 Objective

The main objectives of this project are:

* Understand Naive Bayes classification
* Work with text data
* Convert text into numerical features
* Use TF-IDF vectorization
* Train a Multinomial Naive Bayes model
* Detect spam messages
* Evaluate classification performance
* Experiment with the `alpha` parameter
* Test custom messages

---

## 🧠 What is Naive Bayes?

Naive Bayes is a probabilistic machine learning algorithm based on **Bayes' theorem**.

It assumes that features are conditionally independent given the class.

For text classification, Naive Bayes is widely used because it is:

* Simple
* Fast
* Efficient with high-dimensional text data
* Suitable for classification problems

---

## 🔢 Bayes' Theorem

The basic idea can be represented as:

```text
P(Class | Features)
```

The model calculates the probability that a message belongs to a particular class based on the words/features present in that message.

---

## 📱 Project Use Case

The project simulates an SMS filtering system.

Example:

```text
"Congratulations you won a free prize claim now"
```

Possible prediction:

```text
SPAM
```

Another example:

```text
"Can you send me the assignment?"
```

Possible prediction:

```text
HAM
```

---

## 📊 Dataset

The notebook uses a small SMS message dataset containing two classes:

| Label | Meaning                      |
| ----- | ---------------------------- |
| Ham   | Normal message               |
| Spam  | Unwanted/promotional message |

The dataset is created directly in the notebook so the project can run in Google Colab without requiring an external dataset download.

---

## 🔄 Machine Learning Workflow

```text
SMS Messages
     ↓
Data Cleaning
     ↓
Train-Test Split
     ↓
TF-IDF Vectorization
     ↓
Multinomial Naive Bayes
     ↓
Prediction
     ↓
Model Evaluation
     ↓
Custom Message Testing
```

---

## 🔤 TF-IDF Vectorization

Machine learning models cannot directly process raw text.

Therefore, the project uses **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert messages into numerical vectors.

```python
TfidfVectorizer(
    lowercase=True,
    stop_words="english",
    ngram_range=(1, 2)
)
```

The project uses both:

* Unigrams
* Bigrams

---

## 🤖 Model Used

```python
MultinomialNB()
```

**Multinomial Naive Bayes** is particularly useful for text classification problems.

---

## 📈 Evaluation Metrics

The model is evaluated using:

### Accuracy

Overall percentage of correctly classified messages.

### Precision

Measures how many messages predicted as spam are actually spam.

### Recall

Measures how many actual spam messages were successfully detected.

### F1 Score

Combines precision and recall into a single metric.

### Confusion Matrix

Shows:

```text
True Positive
True Negative
False Positive
False Negative
```

---

## 🧪 Hyperparameter Experiment

The project experiments with different values of:

```text
Alpha
```

Values tested:

```text
0.01
0.1
0.5
1.0
2.0
```

This demonstrates how smoothing can affect Naive Bayes performance.

---

## 📊 Visualizations

The project generates:

1. Ham vs Spam Distribution
2. Confusion Matrix
3. Alpha vs Accuracy

---

## 📁 Generated Files

### `naive_bayes_sms_predictions.csv`

Contains test messages with:

* Actual label
* Predicted label
* Spam probability

### `naive_bayes_alpha_experiment.csv`

Contains model performance for different alpha values.

### `naive_bayes_model_summary.csv`

Contains the main model metrics.

---

## 🌍 Real-World Applications

Naive Bayes can be used for:

* Spam detection
* Email classification
* Sentiment analysis
* News classification
* Document classification
* Text categorization
* Support ticket classification

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* Text classification
* Bayes theorem
* Multinomial Naive Bayes
* TF-IDF
* Unigrams and bigrams
* Classification metrics
* Confusion matrices
* Hyperparameter experimentation

---

## 🚀 Future Improvements

Future versions of this project could include:

* A larger real-world SMS dataset
* Text preprocessing and lemmatization
* Comparing Naive Bayes with Logistic Regression
* Comparing Naive Bayes with SVM
* Building a Streamlit spam detection application
* Deploying the model as an API

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

# 🚀 Day 21 — Advanced Random Forest Regression

## 🏠 California Housing Price Prediction

As part of my **30-Day Machine Learning Daily Series**, Day 21 focuses on an advanced implementation of **Random Forest Regression** for predicting California housing values.

Instead of using a basic Random Forest model, this project demonstrates a more realistic end-to-end machine learning workflow including **feature engineering, pipelines, cross-validation, hyperparameter optimization, model interpretation, residual analysis, learning curves, and model persistence**.

---

## 📌 Project Overview

The objective of this project is to predict the median house value using demographic, geographic, and household-related features from the **California Housing dataset**.

The project goes beyond simply training a model by implementing several advanced machine learning techniques.

### Main workflow

```text
California Housing Dataset
          ↓
Exploratory Data Analysis
          ↓
Feature Engineering
          ↓
Train / Validation / Test Split
          ↓
Preprocessing Pipeline
          ↓
Random Forest Regression
          ↓
5-Fold Cross-Validation
          ↓
Randomized Hyperparameter Search
          ↓
Best Model Selection
          ↓
Model Evaluation
          ↓
Feature & Permutation Importance
          ↓
Residual Analysis
          ↓
Learning Curve
          ↓
Model Saving
          ↓
Custom House Prediction
```

---

## 🎯 Objectives

* Predict California housing values using Random Forest Regression.
* Build a complete machine learning pipeline.
* Perform feature engineering.
* Handle missing values using preprocessing pipelines.
* Apply 5-fold cross-validation.
* Optimize Random Forest hyperparameters.
* Evaluate the model using multiple regression metrics.
* Analyze feature importance.
* Perform permutation importance analysis.
* Study model residuals.
* Generate empirical prediction intervals.
* Save the trained model for future use.
* Perform predictions on new house data.

---

## 📊 Dataset

The project uses the **California Housing dataset** available through `scikit-learn`.

### Original features

| Feature    | Description                 |
| ---------- | --------------------------- |
| MedInc     | Median income               |
| HouseAge   | Median house age            |
| AveRooms   | Average number of rooms     |
| AveBedrms  | Average number of bedrooms  |
| Population | Block population            |
| AveOccup   | Average household occupancy |
| Latitude   | Geographic latitude         |
| Longitude  | Geographic longitude        |

### Target

```text
MedHouseVal
```

The target represents the median house value in units of hundreds of thousands of dollars.

---

## 🧠 Feature Engineering

Five additional features are created to provide the model with more meaningful relationships.

### 1. Rooms Per Household

```text
Rooms_Per_Household =
AveRooms / AveOccup
```

### 2. Bedrooms Per Room

```text
Bedrooms_Per_Room =
AveBedrms / AveRooms
```

### 3. Population Per Household

```text
Population_Per_Household =
Population / AveOccup
```

### 4. Income × Age Interaction

```text
Income_Age_Interaction =
MedInc × HouseAge
```

### 5. Income × Rooms Interaction

```text
Income_Room_Interaction =
MedInc × AveRooms
```

These engineered features allow the model to capture additional relationships between the original variables.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib
* Random Forest
* RandomizedSearchCV
* K-Fold Cross-Validation
* Pipeline
* Feature Engineering
* Permutation Importance

---

## 🤖 Machine Learning Algorithm

### Random Forest Regression

Random Forest is an ensemble learning algorithm that combines multiple decision trees.

For regression, the predictions from individual trees are aggregated to produce the final prediction.

Conceptually:

```text
                 Training Data
                       │
          ┌────────────┼────────────┐
          ↓            ↓            ↓
       Tree 1       Tree 2       Tree 3
          ↓            ↓            ↓
      Prediction    Prediction    Prediction
          └────────────┼────────────┘
                       ↓
              Final Prediction
```

---

## 🔧 Advanced Hyperparameter Optimization

Instead of manually selecting model parameters, `RandomizedSearchCV` is used.

The search explores parameters such as:

```python
n_estimators
max_depth
min_samples_split
min_samples_leaf
max_features
bootstrap
```

Example search space:

```python
param_distributions = {
    "model__n_estimators": [100, 200, 300, 500],
    "model__max_depth": [None, 10, 20, 30, 40],
    "model__min_samples_split": [2, 5, 10],
    "model__min_samples_leaf": [1, 2, 4],
    "model__max_features": [0.5, 0.7, 1.0],
    "model__bootstrap": [True, False]
}
```

The optimization uses **5-fold cross-validation** and minimizes RMSE.

---

## 📈 Evaluation Metrics

The model is evaluated using:

### MAE — Mean Absolute Error

Measures the average absolute difference between actual and predicted values.

### MSE — Mean Squared Error

Penalizes larger errors more heavily.

### RMSE — Root Mean Squared Error

Provides the square root of MSE and is easier to interpret in the target's units.

### R² Score

Measures how much of the variance in the target variable is explained by the model.

---

## 🔍 Model Interpretability

Two feature-importance approaches are used.

### 1. Random Forest Feature Importance

Uses the importance calculated from the trained decision trees.

### 2. Permutation Importance

Features are randomly shuffled and the change in model performance is measured.

This provides another perspective on which features contribute most to predictions.

---

## 📉 Residual Analysis

Residuals are calculated as:

```text
Residual = Actual Value - Predicted Value
```

The project analyzes:

* Residual vs predicted values
* Residual distribution
* Largest prediction errors
* Absolute prediction errors

This helps identify patterns that may indicate model limitations.

# 🚀 Day 23 — Advanced Elastic Net Regression

## 🏠 California Housing Price Prediction

As part of my **Machine Learning Daily Series**, Day 23 focuses on **Elastic Net Regression**, a regularized linear regression technique that combines the ideas of **Lasso and Ridge Regression**.

After exploring Lasso Regression on Day 22, this project goes one step further by combining **L1 and L2 regularization** in a single model.

---

## 🎯 Project Objective

The objective is to predict California housing values while studying:

* L1 regularization
* L2 regularization
* Feature selection
* Coefficient shrinkage
* Hyperparameter optimization
* Cross-validation
* Model comparison
* Regression error analysis

The project implements a complete machine learning workflow rather than simply training a single model.

---

## 🧠 What is Elastic Net?

Elastic Net is a regularized regression technique that combines **L1 and L2 penalties**.

Conceptually:

```text
Elastic Net
     │
     ├── L1 Regularization
     │      ↓
     │   Feature Selection
     │
     └── L2 Regularization
            ↓
       Coefficient Stability
```

The model is controlled mainly by two parameters:

### Alpha

Controls the overall regularization strength.

### L1 Ratio

Controls the balance between L1 and L2 regularization.

```text
l1_ratio = 1.0
      ↓
Lasso-like behavior

l1_ratio = 0.0
      ↓
Ridge-like behavior

0 < l1_ratio < 1
      ↓
Elastic Net combination
```

---

## 🔬 Why Elastic Net?

Lasso can perform feature selection by shrinking coefficients to zero, while Ridge helps stabilize coefficients through L2 regularization.

Elastic Net combines these two behaviors.

This makes it useful when:

* Features may be correlated
* Feature selection is desirable
* Model complexity needs to be controlled
* A balance between L1 and L2 regularization is required

---

## 📊 Dataset

The project uses the **California Housing dataset** from Scikit-learn.

### Original Features

| Feature    | Description                 |
| ---------- | --------------------------- |
| MedInc     | Median income               |
| HouseAge   | Median house age            |
| AveRooms   | Average number of rooms     |
| AveBedrms  | Average number of bedrooms  |
| Population | Population                  |
| AveOccup   | Average household occupancy |
| Latitude   | Geographic latitude         |
| Longitude  | Geographic longitude        |

### Target

```text
MedHouseVal
```

The target represents median house value in units of hundreds of thousands of dollars.

---

## 🛠️ Feature Engineering

The project creates additional features:

### Rooms Per Household

```text
AveRooms / AveOccup
```

### Bedrooms Per Room

```text
AveBedrms / AveRooms
```

### Population Per Household

```text
Population / AveOccup
```

### Income × Age

```text
MedInc × HouseAge
```

### Income × Rooms

```text
MedInc × AveRooms
```

### Income × Occupancy

```text
MedInc × AveOccup
```

### Latitude × Longitude

```text
Latitude × Longitude
```

These engineered variables provide additional information for the regression model.

---

## ⚙️ Machine Learning Pipeline

The project uses a Scikit-learn pipeline:

```text
Raw Dataset
     ↓
Feature Engineering
     ↓
Missing Value Imputation
     ↓
StandardScaler
     ↓
Elastic Net Regression
     ↓
Prediction
     ↓
Evaluation
```

Feature scaling is important because regularization is sensitive to the scale of the input variables.

---

## 🔧 Hyperparameter Optimization

Two important Elastic Net parameters are optimized:

```text
alpha
l1_ratio
```

The project uses:

```python
GridSearchCV
```

with **5-fold cross-validation**.

The search selects the configuration with the lowest cross-validated RMSE.

---

## 📈 Model Evaluation

The following metrics are calculated:

### MAE

Mean Absolute Error.

### MSE

Mean Squared Error.

### RMSE

Root Mean Squared Error.

### R²

Coefficient of determination.

---

## 🔍 Feature Selection

Elastic Net can shrink coefficients toward zero.

The project analyzes:

* Total features
* Selected features
* Zero-coefficient features
* Coefficient magnitude
* Positive and negative coefficients

This provides an interpretable view of the linear model.

---

## 🧪 Alpha Experiment

Different values of `alpha` are tested to understand how regularization strength affects:

* RMSE
* R²
* Number of non-zero coefficients

The results are visualized using:

```text
Alpha vs RMSE
```

---

## 🧪 L1 Ratio Experiment

Different `l1_ratio` values are also evaluated.

This helps study the balance between:

```text
L1 regularization
        ↕
L2 regularization
```

The project analyzes how this balance affects:

* Prediction error
* R²
* Number of selected features

---

## 🔄 Model Comparison

The project compares:

* Linear Regression
* Lasso Regression
* Elastic Net
* Ridge Regression

This helps demonstrate the differences between regularized and non-regularized linear models.

---

## 📉 Residual Analysis

Residuals are calculated as:

```text
Residual =
Actual Value - Predicted Value
```

The project generates:

* Residual vs predicted plot
* Residual distribution
* Largest prediction errors

---

## 📚 Learning Curve

A learning curve compares training and validation RMSE across different training-set sizes.

This provides insight into:

* Model learning behavior
* Potential underfitting
* Potential overfitting
* Effect of additional training data

---

## 💾 Model Persistence

The final trained pipeline is saved as:

```text
elastic_net_house_model.pkl
```

This allows the trained model to be loaded and reused later without retraining.

---

## 📂 Project Structure

```text
Day-23-Advanced-Elastic-Net-Regression/
│
├── Day_23_Elastic_Net_Regression.ipynb
│
├── day23_outputs/
│   ├── elastic_net_predictions.csv
│   ├── elastic_net_coefficients.csv
│   ├── elastic_net_alpha_experiment.csv
│   ├── elastic_net_l1_ratio_experiment.csv
│   ├── elastic_net_cross_validation.csv
│   ├── elastic_net_grid_search.csv
│   ├── elastic_net_model_summary.csv
│   ├── best_parameters.csv
│   ├── model_comparison.csv
│   ├── elastic_net_house_model.pkl
│   ├── elastic_net_coefficients.png
│   ├── actual_vs_predicted.png
│   ├── residual_analysis.png
│   ├── residual_distribution.png
│   ├── alpha_vs_rmse.png
│   ├── l1_ratio_vs_rmse.png
│   ├── l1_ratio_vs_features.png
│   └── learning_curve.png
│
└── README.md
```

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Joblib
* Elastic Net Regression
* Lasso Regression
* Ridge Regression
* GridSearchCV
* K-Fold Cross-Validation
* Feature Engineering
* Model Evaluation

---

## ▶️ Installation

```bash
pip install numpy pandas matplotlib scikit-learn joblib
```

---

## ▶️ Run the Project

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/machine-learning-daily-series.git
```

Navigate to the project:

```bash
cd machine-learning-daily-series/Day-23-Advanced-Elastic-Net-Regression
```

Open the notebook:

```bash
jupyter notebook
```

Then run:

```text
Day_23_Elastic_Net_Regression.ipynb
```

The project can also be executed in Google Colab.

---

## 📌 Key Learning Outcomes

Through this project, I learned:

* How Elastic Net combines L1 and L2 regularization
* The purpose of the `alpha` parameter
* The purpose of the `l1_ratio` parameter
* How regularization affects coefficients
* How feature selection works
* How to optimize multiple hyperparameters
* How to use GridSearchCV
* How to perform K-Fold cross-validation
* How to compare Linear, Ridge, Lasso and Elastic Net models
* How to analyze regression errors
* How to save and reuse trained models

---

## 🚀 Future Improvements

Possible extensions include:

* Bayesian Ridge Regression
* Huber Regression
* Quantile Regression
* Robust regression
* SHAP-based model interpretation
* Optuna hyperparameter optimization
* XGBoost comparison
* LightGBM comparison
* Streamlit deployment
* REST API deployment
* Docker deployment

---
# Day 24 — Advanced Time Series Forecasting

## Electricity Demand Forecasting Using Machine Learning

This project is part of my **30-Day Machine Learning Daily Series**.

For Day 24, I moved from traditional regression and regularization techniques into **Time Series Forecasting**.

The objective is to forecast hourly electricity demand using historical demand patterns, time-based features, temperature, lag features, and rolling statistics.

---

## Project Objective

Build a machine learning forecasting system that can learn temporal patterns in electricity consumption and predict future electricity demand.

The project uses:

* Time-based feature engineering
* Lag variables
* Rolling statistics
* Cyclic time encoding
* Random Forest Regression
* TimeSeriesSplit
* RandomizedSearchCV
* Walk-forward validation
* Residual analysis
* Feature importance

---

## Dataset

A synthetic hourly electricity-demand dataset is generated directly inside the notebook.

The dataset contains approximately two years of hourly observations.

### Main columns

| Feature     | Description           |
| ----------- | --------------------- |
| timestamp   | Date and time         |
| hour        | Hour of the day       |
| day_of_week | Day of the week       |
| day_of_year | Day number            |
| month       | Month                 |
| is_weekend  | Weekend indicator     |
| temperature | Simulated temperature |
| demand      | Electricity demand    |

---

## Time Series Feature Engineering

Instead of using only the current timestamp, historical demand information is converted into machine learning features.

### Lag Features

The model uses:

* Lag 1 hour
* Lag 2 hours
* Lag 3 hours
* Lag 24 hours
* Lag 48 hours
* Lag 168 hours

For example:

`lag_24` represents the electricity demand 24 hours earlier.

This helps the model learn daily and weekly demand patterns.

---

## Rolling Features

The project calculates:

* 24-hour rolling mean
* 24-hour rolling standard deviation
* 168-hour rolling mean
* 168-hour rolling standard deviation

The rolling statistics are shifted before calculation to avoid using future target information.

---

## Cyclic Time Encoding

Time is cyclical.

For example, 23:00 and 00:00 are close to each other even though their numerical values are far apart.

Therefore, sine and cosine transformations are used:

* `hour_sin`
* `hour_cos`
* `day_sin`
* `day_cos`
* `month_sin`
* `month_cos`

---

## Machine Learning Model

The main model is:

**Random Forest Regressor**

Random Forest combines multiple decision trees to learn nonlinear relationships between historical demand, time features, temperature, and other variables.

---

## Train/Test Strategy

A random train-test split is avoided because time series data has a temporal order.

Instead:

```text
Past data → Training
Future data → Testing
```

Approximately:

* 80% → Training
* 20% → Testing

This provides a more realistic forecasting evaluation.

---

## Hyperparameter Optimization

`RandomizedSearchCV` is used to search for better Random Forest parameters.

Parameters explored include:

* `n_estimators`
* `max_depth`
* `min_samples_split`
* `min_samples_leaf`
* `max_features`

The search uses `TimeSeriesSplit` rather than ordinary random cross-validation.

---

## Evaluation Metrics

The forecasting model is evaluated using:

### MAE

Mean Absolute Error measures the average absolute prediction error.

### MSE

Mean Squared Error penalizes larger errors more strongly.

### RMSE

Root Mean Squared Error represents prediction error in the same unit as electricity demand.

### R²

R² measures how much variation in the target is explained by the model.

---

## Walk-Forward Validation

Time series models should be evaluated while respecting chronological order.

This project uses `TimeSeriesSplit` to simulate multiple historical forecasting scenarios.

This provides a more appropriate validation strategy than randomly shuffling observations.

---

## Visualizations

The project generates:

* Original demand time series
* Actual vs predicted demand
* Last 7 days forecast
* Residual analysis
* Residual distribution
* Feature importance

---

## Feature Importance

Feature importance is extracted from the trained Random Forest model.

This helps identify which temporal and environmental variables contributed most to the predictions.

Typical important features can include:

* Recent demand
* 24-hour lag
* 168-hour lag
* Rolling demand statistics
* Temperature
* Hour of day

---

## Model Persistence

The trained model is saved using Joblib:

```text
electricity_demand_forecasting_model.pkl
```

It can later be loaded for prediction without retraining the model.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Joblib
* Google Colab

---

## Installation

```bash
pip install numpy pandas matplotlib scikit-learn joblib
```

The notebook can also be executed directly in Google Colab.

---

## Project Structure

```text
Day-24-Advanced-Time-Series-Forecasting/
│
├── Day_24_Advanced_Time_Series_Forecasting.ipynb
│
├── day24_outputs/
│   ├── original_demand.png
│   ├── actual_vs_predicted.png
│   ├── last_7_days_forecast.png
│   ├── residual_analysis.png
│   ├── residual_distribution.png
│   ├── feature_importance.png
│   ├── forecast_predictions.csv
│   ├── feature_importance.csv
│   ├── model_metrics.csv
│   ├── model_comparison.csv
│   ├── walk_forward_validation.csv
│   ├── hyperparameter_search.csv
│   ├── best_parameters.csv
│   ├── largest_forecast_errors.csv
│   └── electricity_demand_forecasting_model.pkl
│
└── README.md
```

---

## Key Learning Outcomes

Through this project, I learned how to:

1. Work with time-dependent datasets.
2. Engineer lag features.
3. Create rolling statistics.
4. Encode cyclical time variables.
5. Perform chronological train-test splitting.
6. Apply Random Forest to forecasting.
7. Perform time-series cross-validation.
8. Optimize model hyperparameters.
9. Analyze forecasting residuals.
10. Identify important forecasting features.
11. Save and reload a trained ML model.

---

## Future Improvements

Possible improvements include:

* LSTM forecasting
* GRU networks
* XGBoost forecasting
* Prophet
* ARIMA/SARIMA
* Real electricity consumption datasets
* Weather API integration
* Real-time demand forecasting
* Multi-step forecasting
* Forecasting dashboards using Streamlit

---

## Conclusion









