# Decision trees and random forest analysis

This is a laboratory made for practicing machine learning techniques in the context of the [Master of Artificial Intelligence at UNIR](https://www.unir.net/ingenieria/master-inteligencia-artificial/).

## Objective:
Use Decision Trees and Random Forest for a regression and classification problem:

* *Predicting the selling price and price range of the property.*


### Dataset:
- [https://www.kaggle.com/datasets/gpandi007/usa-housing-dataset](https://www.kaggle.com/datasets/gpandi007/usa-housing-dataset)


## Project Summary

This project consists of the following steps:

### 1. Descriptive Data Analysis

- **Numerical Variables**: Generate descriptive statistics (mean, median, standard deviation, etc.) for all numerical columns in the dataset.
- **Categorical Variables**: List all unique categories and compute their frequency distributions.

### 2. Correlation Matrix

- Create a correlation matrix for all numerical variables.
- Analyze the relationships between variables and identify those with strong correlations that may impact the model.

### 3. Handling Missing Values

- Identify columns with missing data.
- Decide whether to drop records, or impute missing values using measures such as the mean, median, or mode.

### 4. Regression Models: Decision Trees and Random Forest

- Apply Decision Tree and Random Forest models to the regression task using `SalePrice` as the target variable.
- Compare the predictive performance of both models using appropriate evaluation metrics, such as RMSE (Root Mean Squared Error).

### 5. Model Comparison

- Highlight the advantages and disadvantages of each model.
- Evaluate whether the developed models are effective and useful for the dataset based on the results.

### 6. Classification Task

- For classification, create three groups based on `SalePrice`:
  - **Group 1**: SalePrice ≤ 100,000
  - **Group 2**: SalePrice between 100,001 and 500,000
  - **Group 3**: SalePrice ≥ 500,001
- Apply both Decision Tree and Random Forest classifiers.
- Compare the performance of the models using confusion matrices and accuracy by class.
- Comment on any challenges with group imbalance or classification difficulty, especially for Group 3.

### 7. Additional Comments

- Provide any further observations, insights, or recommendations discovered during the analysis process.


## Setup and Run Jupyter Notebook Locally

Follow these steps to install the required dependencies and run the Jupyter notebook on your local machine:

1. **Clone the repository** (if you haven’t already):

   ```bash
   git clone git@github.com:pyjavo/lab_decision_trees_random_forest.git
   cd lab_decision_trees_random_forest
   ```
2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows use: venv\Scripts\activate
   ```
3. **Install the dependencies:**

```
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook:**
```
jupyter notebook
```

5. **Open the notebook for Exploratory Data Analysis (EDA):**

In your browser, navigate to the notebook file (e.g., `lab_1.ipynb`) to begin the exploratory data analysis. You can inspect the dataset, generate summary statistics, visualize distributions, and uncover patterns within the data.
