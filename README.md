# PRODIGY_DS_03_Decision_Tree_Classifier
<br>
# Task-03: Decision Tree Classifier using Bank Marketing Dataset

## Internship

This project is completed as part of the **Prodigy Infotech Data Science Internship**.

## Objective

The objective of this task is to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a **term deposit** based on demographic and financial information.

## Dataset

The dataset used in this project is the **Bank Marketing Dataset (`bank-full.csv`)**.

This dataset contains information about bank customers who were contacted during a marketing campaign. The data includes details about the customer's background and previous interactions with the bank.

### Dataset Features

Some important features in the dataset include:

* **age** – Age of the customer
* **job** – Type of job
* **marital** – Marital status
* **education** – Education level
* **balance** – Average yearly balance
* **housing** – Whether the customer has a housing loan
* **loan** – Whether the customer has a personal loan
* **contact** – Communication type used during the campaign
* **duration** – Duration of the last contact
* **campaign** – Number of contacts during the campaign
* **poutcome** – Outcome of the previous marketing campaign
* **y** – Target variable indicating whether the customer subscribed to a term deposit (yes/no)

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Steps Performed

### 1. Data Loading

The dataset (`bank-full.csv`) was loaded into a Pandas DataFrame for analysis.

### 2. Data Exploration

Basic exploration techniques were used to understand the dataset:

* Viewing the first few rows
* Checking data types and structure
* Understanding dataset statistics

### 3. Data Preprocessing

Before building the model:

* Categorical variables were converted into numerical values.
* The dataset was prepared for machine learning.

### 4. Train-Test Split

The dataset was divided into:

* **Training Data (80%)**
* **Testing Data (20%)**

### 5. Model Building

A **Decision Tree Classifier** was implemented using Scikit-learn to predict whether a customer would subscribe to a term deposit.

### 6. Model Evaluation

The model performance was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

### 7. Decision Tree Visualization

The trained decision tree was visualized to understand how the model makes predictions based on different features.

## Outcome

This project demonstrates how machine learning models like **Decision Trees** can be used to analyze customer data and predict their responses to marketing campaigns.

## Project Files

* `Task03.ipynb` – Jupyter Notebook containing model implementation
* `bank-full.csv` – Dataset used for training the model

## Author

**Sudhanshu Yadav**
<br>
Master’s Student in **Survey Research and Data Analytics**

**Sudhanshu Yadav**
Master’s Student in **Survey Research and Data Analytics**
