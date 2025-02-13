# predicting_graduate_admission
# Predicting Graduate Admission Probability

This project develops a machine learning model to predict the probability of graduate admissions. It leverages two machine learning techniques—**Linear Regression** and **Random Forest**—to process and analyze historical admission data sourced from Kaggle, ultimately building accurate prediction models.

## Project Overview

- **Data Source:** Historical graduate admission data from Kaggle.
- **Techniques Used:**
  - **Linear Regression:** Establishes a linear relationship between input features and the target variable.
  - **Random Forest:** Utilizes an ensemble of decision trees to improve prediction accuracy and reduce overfitting.
- **Objective:** To accurately predict the likelihood of a candidate's admission based on various academic and demographic features.

## Features

- Data preprocessing and cleaning to handle missing values and outliers.
- Feature selection and engineering to identify key predictors.
- Model training using both Linear Regression and Random Forest.
- Evaluation of model performance using metrics such as RMSE, MAE, and R-squared.
- Visualization of prediction results and model comparisons.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/monikaNowdu/Predicting-graduate-admission-probability.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Predicting-graduate-admission-probability
    ```
3. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows: venv\Scripts\activate
    ```
4. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the main script to train and evaluate the models:
```bash
python main.py
