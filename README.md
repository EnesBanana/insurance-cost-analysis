# 🩺 Medical Insurance Cost Prediction Project

This project aims to predict annual medical insurance charges by analyzing a dataset of patient information. The scope of the project includes data cleaning, exploratory data analysis (EDA), and the development of various regression models to identify the key factors that influence insurance costs.

This work was completed as a project for the [IBM Data Science](https://www.coursera.org/professional-certificates/ibm-data-science) course on Coursera.

***

## 🎯 Objectives

In this project, the following objectives were achieved:

* Load the data as a `pandas` dataframe.
* Clean the data, handling blank entries to prepare it for analysis.
* Perform Exploratory Data Analysis (EDA) to identify the attributes that most affect the insurance `charges`.
* Develop single-variable and multi-variable Linear Regression models for predicting the `charges`.
* Use Ridge Regression to refine the performance of the Linear Regression models.

***

## 📋 Table of Contents

The analysis within the Jupyter Notebook is structured as follows:

1.  **Import the Dataset**: Loading the data using necessary libraries.
2.  **Data Wrangling**: Cleaning and preprocessing the dataset.
3.  **Exploratory Data Analysis (EDA)**: Understanding relationships and patterns within the data through visualization.
4.  **Model Development**: Building Linear and Ridge regression models for prediction.
5.  **Model Evaluation and Refinement**: Measuring the performance of the developed models.

***

## 📊 Dataset

The dataset used in this project is a modified version of the "Medical Insurance Price Prediction" dataset from Kaggle, which was filtered and prepared for the IBM course.

* **Dataset Used (IBM Version):** [medical_insurance_dataset.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-Coursera/medical_insurance_dataset.csv)
* **Original Dataset (Kaggle):** [Medical Insurance Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction)

### Data Dictionary

| Parameter | Description | Content Type |
|---|---|---|
| `age` | Age in years | integer |
| `gender` | Male or Female | integer (1 or 2) |
| `bmi` | Body Mass Index | float |
| `no_of_children`| Number of children | integer |
| `smoker` | Whether smoker or not | integer (0 or 1) |
| `region` | Which US region - NW, NE, SW, SE | integer (1,2,3 or 4) |
| `charges` | Annual Insurance charges in USD | float |

***

## 🛠️ Technologies & Libraries Used

* **Programming Language:** Python
* **Libraries:**
    * `pandas` (for data manipulation and analysis)
    * `numpy` (for numerical operations)
    * `matplotlib` & `seaborn` (for data visualization)
    * `scikit-learn` (for machine learning models and evaluation)
