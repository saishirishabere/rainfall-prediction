# rainfall-prediction
In this project, I will be implementing a predictive model on Rain Dataset to predict whether or not it will rain tomorrow in Australia.The Dataset contains about 10 years of daily weather observations of different locations in Australia. By the end of this project, you will be able to build a predictive model.

# Objectives:
Design a predictive model with the use of machine learning algorithms to forecast whether or not it will rain tomorrow in Australia.
# Data Source:
The dataset is taken from Kaggle and contains about 10 years of daily weather observations from many locations across Australia.

# Dataset Description:
Number of columns: 23

Number of rows: 145460

Number of Independent Columns: 22

Number of Dependent Column: 1

# Problem Statement:

Build an efficient Classification Model that should predict whether it Rains Tomorrow or not, using the dataset Rain in Australia.

# Exploratory Data Analysis

In this EDA part I have to do the following steps.

# Feature Engineering

Data Preprocessing
Missing Data We can use seaborn to create a simple heatmap

![image](https://user-images.githubusercontent.com/100595913/156792691-44f7fb05-f69c-45e4-a4c2-56b92748d766.png)



# Bar Graph

![image](https://user-images.githubusercontent.com/100595913/156792739-e71709ed-b7ef-4360-9c01-965b0082570b.png)

# Data Cleaning

Correlation
To check the Correlation using Heatmap

![image](https://user-images.githubusercontent.com/100595913/156792830-68c415ea-1beb-4eae-bb13-274a994d5dbe.png)

Finding categorical and Numerical features in Dataset

Replace the Missing Values & Replace the Null values

To Detect and Handle the Outliers

# To find the Outliers in the dataset Using Box plot

![image](https://user-images.githubusercontent.com/100595913/156792969-54b4ee63-e702-4aa2-871a-4a433f9ae9e0.png)

To Remove the Outliers & verifying in the dataset Using Box plot

![image](https://user-images.githubusercontent.com/100595913/156793059-de18b2e9-9290-4ea0-b212-8c343da052d6.png)

One Hot Encoding Method

Encoding Categorical Features using replace function

# Classification models
To apply the Machine Learning Algorithm

# Feature Selection
Finding the Correlation
![image](https://user-images.githubusercontent.com/100595913/156793308-d44e102d-118a-4c05-b874-c0a02f3cc077.png)

# Model Building

Model Training

Model Testing

Evaluating Model Performance using Accuracy, Confusion Matrix, 
Classification Report, RUC-AUC curve

# Confusion Martix (Decision Tree Classifier)

![image](https://user-images.githubusercontent.com/100595913/156794056-062cfac8-d938-4a82-ad4a-dc097bebaf6e.png)

# Visualize the Performance of the Decision Tree Classifier Model
![image](https://user-images.githubusercontent.com/100595913/156794137-94e48002-a9f7-41d4-b325-6e039013043b.png)

# Confusion Martix (Decision Tree Classifier (Entropy))

![image](https://user-images.githubusercontent.com/100595913/156794285-35818596-d815-4590-867c-769300268954.png)

# Visualize the Performance of the (Decision Tree Classifier (Entropy)) Model

![image](https://user-images.githubusercontent.com/100595913/156794382-76042954-4168-4056-931b-290f17de0616.png)

# Confusion Martix (Decision Tree Classifier (Gini))
![image](https://user-images.githubusercontent.com/100595913/156794503-e289518f-4430-4188-a72a-00a61985a116.png)

# Visualize the Performance of the (Decision Tree Classifier (Gini)) Model

![image](https://user-images.githubusercontent.com/100595913/156794572-5fecaa1c-08ea-4dcb-8fcf-95eed91fb249.png)

# Confusion Martix (Random Forest Classifier)
![image](https://user-images.githubusercontent.com/100595913/156794684-1e4b5c3b-3c67-4bf4-8146-7458a3e35330.png)

# Visualize the Performance of the (Random Forest Classifier) Model

![image](https://user-images.githubusercontent.com/100595913/156794751-aa43842e-1c09-4a72-ac22-342e23c28c43.png)

# Confusion Martix (Logistic Regression)

![image](https://user-images.githubusercontent.com/100595913/156794980-83fb448b-8b0e-4561-b239-e54417f15ad9.png)

# Visualize the Performance of the (Logistic Regression) Model

![image](https://user-images.githubusercontent.com/100595913/156795048-6ff96744-7aba-4f4d-a09d-7287cf76a2de.png)

# Confusion Martix (XGBoost Classifier)
![image](https://user-images.githubusercontent.com/100595913/156795123-a9c60ea4-079a-4fa5-8762-d9c296ef442e.png)

# Visualize the Performance of the (XGBoost Classifier) Model
![image](https://user-images.githubusercontent.com/100595913/156795174-2ce28782-7fac-4e22-966b-278301c76012.png)

# Confusion Martix (Naive Byes)

![image](https://user-images.githubusercontent.com/100595913/156795232-a3938f43-959e-452a-af3a-1e2270abbac9.png)

# Visualize the Performance of the (Naive Byes) Model
![image](https://user-images.githubusercontent.com/100595913/156795285-ced31c2d-0cc1-4f88-b93a-0259e28b1a02.png)

# Comparative Analysis & Model Evaluation Evaluation

![image](https://user-images.githubusercontent.com/100595913/156795406-fae367a3-3275-490e-8b24-2b94183da2eb.png)
# Here, We applied Five Machine learning algorithms, We can conclude that Random Forest classifier performs the best with 85.40% accuracy

# Libraries used

Data Cleaning: Numpy, Pandas

Visualisation: Seaborn, Matplotlib

Feature scaling: StandardScaler

Splitting to train and test: train_test_split

Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score

Algorithms: DecisionTreeClassifier, RandomForestClassifier, 
LogisticRegression, GaussianNB, XGBClassifier



