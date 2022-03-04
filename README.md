Rainfall-Prediction
In this project, I will be implementing a predictive model on Rain Dataset to predict whether or not it will rain tomorrow in Australia.The Dataset contains about 10 years of daily weather observations of different locations in Australia. By the end of this project, you will be able to build a predictive model.

Objectives:
Design a predictive model with the use of machine learning algorithms to forecast whether or not it will rain tomorrow in Australia.

Data Source:
The dataset is taken from Kaggle and contains about 10 years of daily weather observations from many locations across Australia.

Dataset Description:
Number of columns: 23
Number of rows: 145460
Number of Independent Columns: 22
Number of Dependent Column: 1
Problem Statement:
Build an efficient Classification Model that should predict whether it Rains Tomorrow or not, using the dataset Rain in Australia.

Exploratory Data Analysis
In this EDA part I have to do the following steps.

Feature Engineering
Data Preprocessing
Missing Data We can use seaborn to create a simple heatmap

image

Bar Graph

image

Data Cleaning
Correlation
To check the Correlation using Heatmap

image

Finding categorical and Numerical features in Dataset
Replace the Missing Values & Replace the Null values
To Detect and Handle the Outliers
To find the Outliers in the dataset Using Box plot
image

To Remove the Outliers & verifying in the dataset Using Box plot

image

One Hot Encoding Method
Encoding Categorical Features using replace function

Classification models
To apply the Machine Learning Algorithm

Feature Selection
Finding the Correlation

image

Model Building
Model Training
Model Testing
Evaluating Model Performance using Accuracy, Confusion Matrix, Classification Report, RUC-AUC curve
Confusion Martix (Decision Tree Classifier)
image

Visualize the Performance of the Decision Tree Classifier Model
image

Confusion Martix (Decision Tree Classifier (Entropy))
image

Visualize the Performance of the (Decision Tree Classifier (Entropy)) Model
image

Confusion Martix (Decision Tree Classifier (Gini))
image

Visualize the Performance of the (Decision Tree Classifier (Gini)) Model
image

Confusion Martix (Random Forest Classifier)
image

Visualize the Performance of the (Random Forest Classifier) Model
image

Confusion Martix (Logistic Regression)
image

Visualize the Performance of the (Logistic Regression) Model
image

Confusion Martix (XGBoost Classifier)
image

Visualize the Performance of the (XGBoost Classifier) Model
image

Confusion Martix (Naive Byes)
image

Visualize the Performance of the (Naive Byes) Model
image

Comparative Analysis & Model Evaluation
image

Here, We applied Five Machine learning algorithms, We can conclude that Random Forest classifier performs the best with 85.40% accuracy
Libraries used
Data Cleaning: Numpy, Pandas
Visualisation: Seaborn, Matplotlib
Feature scaling: StandardScaler
Splitting to train and test: train_test_split
Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score
Algorithms: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression, GaussianNB, XGBClassifier
d
