# Decision Trees and Random Forest: A Practical Guide to Regression and Classification

This project serves as a hands-on application of core machine learning concepts, with a focus on tree-based models. It was developed as part of the coursework for the [Master's in Artificial Intelligence at UNIR](https://www.unir.net/ingenieria/master-inteligencia-artificial/), and aims to demonstrate a complete pipeline from exploratory data analysis (EDA) to model evaluation.

## Objective

Build and evaluate machine learning models using Decision Trees and Random Forests to address both **regression** and **classification** tasks:

- **Goal**: Predict the **selling price** and **price category** of residential properties.

---

## Dataset

- Source: [USA Housing Dataset - Kaggle](https://www.kaggle.com/datasets/gpandi007/usa-housing-dataset)

---

## Project Workflow

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

- Assess model strengths and limitations.
- Evaluate whether the developed models are effective and useful for the dataset based on the results.

### 6. Classification Task

- Categorize `SalePrice` into three price ranges:
  - **Group 1**: SalePrice ≤ 100,000
  - **Group 2**: SalePrice between 100,001 and 500,000
  - **Group 3**: SalePrice ≥ 500,001
- Train classifiers (`DecisionTreeClassifier` and `RandomForestClassifier`) and evaluate with:
  - Confusion matrices
  - Classification reports
  - Class-wise accuracy
- Analyze performance challenges due to class imbalance

### 7. Final Observations

- Provide any further observations, insights, or recommendations discovered during the analysis process.

---

## Local Setup and Notebook Execution

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

5. **Run the analysis notebook:**

Open the notebook file (e.g., `eda_and_tree_based_models.ipynb`) in your browser. The notebook walks through data exploration, model training, and evaluation with clear, reproducible steps and visualizations.

---

This project not only demonstrates applied knowledge in supervised learning with tree-based models but also emphasizes good practices in data preprocessing, model evaluation, and interpretability — key competencies for a Machine Learning Engineer role.
