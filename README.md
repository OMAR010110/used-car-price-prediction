# 🚗 Used Car Price Prediction

## 📌 Project Overview

This project focuses on predicting used car prices using **Linear Regression**, a supervised machine learning algorithm.

The model uses vehicle characteristics to estimate prices and demonstrates the complete regression workflow, from data preparation and exploratory analysis to model training and evaluation.

## 🎯 Project Objectives

* Explore and understand the dataset.
* Clean the data and handle missing values and duplicate records.
* Perform Exploratory Data Analysis (EDA).
* Visualize relationships between vehicle features and prices.
* Encode categorical variables for machine learning.
* Train a Linear Regression model.
* Evaluate predictions using regression metrics.

## 📂 Dataset

The dataset contains used car information, including:

| Feature               | Description                                      |
| --------------------- | ------------------------------------------------ |
| `year`                | Manufacturing year                               |
| `mileage_km`          | Distance driven in kilometers                    |
| `engine_size_L`       | Engine displacement in liters                    |
| `fuel_type`           | Vehicle fuel type                                |
| `num_previous_owners` | Number of previous owners                        |
| `price_usd`           | Target variable: car price in USD                |
| `car_id`              | Vehicle identifier; excluded from model features |

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Exploration

* Inspected dataset dimensions and data types.
* Generated descriptive statistics.
* Checked for missing values and duplicates.

### 2. Data Cleaning

* Standardized categorical text values.
* Converted numerical columns to appropriate data types.
* Checked for invalid values and potential outliers.
* Handled missing values.

### 3. Exploratory Data Analysis

* Visualized the distribution of car prices.
* Analyzed relationships between price and numerical features.
* Compared prices across fuel types.
* Examined correlations between numerical variables.

### 4. Data Preprocessing

* Separated features from the target variable.
* Split the dataset into training and testing sets.
* Applied One-Hot Encoding to the categorical feature.
* Used a preprocessing pipeline to prepare the data.

### 5. Model Training

* Trained a Linear Regression model on the training set.

### 6. Model Evaluation

Model performance was evaluated using:

* **MAE:** Mean Absolute Error
* **RMSE:** Root Mean Squared Error
* **R²:** Coefficient of Determination

An actual-versus-predicted plot was also created to visualize prediction performance.

## 📊 Results

The notebook reports the evaluation metrics calculated on the held-out test set.

Add the final MAE, RMSE, and R² values here after running the notebook.

## 🚀 How to Run

1. Clone or download this repository.

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Place the dataset in the appropriate location.

4. Open the notebook:

   ```bash
   jupyter notebook
   ```

5. Run the notebook cells from top to bottom.

## ⚠️ Limitations

Linear Regression assumes a linear relationship between the numerical features and the target. Used car prices can also depend on factors that are not included in this dataset, such as brand, vehicle condition, accident history, and service records.

The dataset is also relatively small, so the model's performance should be interpreted with caution.

## 👨‍💻 Author

**Omar Refaat**

Computer Science Graduate | Data Analysis & Machine Learning Enthusiast
