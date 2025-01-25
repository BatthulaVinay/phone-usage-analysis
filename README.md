# phone-usage-analysis

## Overview
This project analyzes phone usage patterns in India and predicts the primary use of mobile devices based on various features. The notebook covers data preprocessing, exploratory data analysis (EDA), and model training using multiple classification algorithms.

## Features
The dataset contains the following features:
- **Categorical features:**
  - Gender
  - Location
  - Phone Brand
  - Operating System (OS)
  - Primary Use
- **Numerical features:**
  - Various usage metrics (unnamed in this draft)

## Workflow

### 1. Data Preprocessing
- Dropped irrelevant features (e.g., User ID).
- Label encoded categorical variables.
- Normalized numerical features using `MinMaxScaler`.
- Split data into training and testing sets (80/20 split).

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of categorical features.
- Explored relationships between usage patterns and the target variable (Primary Use).
- Analyzed numerical feature distributions and their relationships with categorical variables using violin plots.

### 3. Model Training and Evaluation
Implemented and evaluated the following classifiers:
- Random Forest
- AdaBoost
- Gradient Boosting
- Extra Trees
- Logistic Regression
- Support Vector Machine
- XGBoost
- LightGBM

#### Evaluation Metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 4. Visualization of Results
- Bar plots to compare model accuracy.
- Heatmaps for confusion matrices of each classifier.

## Setup Instructions

### Prerequisites
- Python 3.x
- Required libraries:
  - [`numpy`](https://numpy.org/)
  - [`pandas`](https://pandas.pydata.org/)
  - [`matplotlib`](https://matplotlib.org/)
  - [`seaborn`](https://seaborn.pydata.org/)
  - [`scikit-learn`](https://scikit-learn.org/)
  - [`imbalanced-learn`](https://imbalanced-learn.org/)
  - [`xgboost`](https://xgboost.readthedocs.io/)
  - [`lightgbm`](https://lightgbm.readthedocs.io/)

### Installation
1. Clone this repository.
2. Install the dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebook
1. Ensure the dataset (`phone_usage_india.csv`) is in the project directory.
2. Open and run the Jupyter Notebook using:
   ```bash
   jupyter notebook "Phone Usage in India .ipynb"
   ```

## Results
The notebook provides:
- Insights into the primary uses of phones in India.
- Performance comparison of multiple machine learning models for predicting primary phone usage.
- Visualizations for better interpretability of results.

## Acknowledgments
- Dataset: The data was sourced as part of a study on phone usage patterns.
- Libraries: Special thanks to contributors of Python libraries used in this project.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

