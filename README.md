# Smart House Pricing

## Description

This project explores a dataset from the Kaggle competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview). The objective is to build machine learning regression models to predict house prices based on various features related to the houses' attributes and conditions.

---

## Table of Contents

1. [Dataset](#dataset)
2. [Tools and Technologies](#tools-and-technologies)
3. [Approach](#approach)
4. [Prerequisites](#prerequisites)
5. [How to Run the Project](#how-to-run-the-project)

---

## Dataset

The dataset is sourced from the Kaggle competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data). It contains detailed information about houses in Ames, Iowa, including numerous features that influence house prices. The goal is to use this data to build predictive models.

---

## Tools and Technologies

This project uses:

- **Python** (3.x)
- **Jupyter Notebook**: For interactive code execution and visualization
- **Libraries**:
  - Pandas: For data manipulation and analysis
  - Matplotlib and Seaborn: For data visualization
  - Scikit-learn: For machine learning modeling and evaluation

---

## Approach

### 1. EDA and Data Pre-processing

#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.1 Data Overview 
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.2 Outliers Detection and Cleaning
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.3 Handling of Missing Values
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.4 Features Removal
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.5 Feature Engineering
#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1.6 Features Encoding

### 2. Modelling

- **Linear Regression**
- **Random Forest Regressor**
- **Ridge Regression**
- **Gradient Boosting Regressor**
- **Voting Regressor**

### 2. Feature importances
- **Visualization of the most important features**

---

## Prerequisites

- Python 3.8 or later
- A virtual Python environment is recommended (via `venv` or `conda`)
- The following libraries must be installed:
  - pandas
  - matplotlib
  - numpy
  - scikit-learn
  - seaborn
- Jupyter Notebook to run the `ames_house_prices_regression.ipynb` file

---

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone git@github.com:Dan-Popescu/Rahulmahala25/Smart-House-Pricing.git
   cd Rahulmahala25/Smart-House-Pricing
   ```

2. Activate the virtual environment:

   ```bash
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Download data from Kaggle ([House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)) and place it in the `data` folder.

5. Launch the notebook:

   ```bash
   jupyter notebook ames_houses_prices_regression.ipynb
   ```

6. Follow the steps in the notebook to execute the analysis and models.

