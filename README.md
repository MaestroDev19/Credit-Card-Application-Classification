# Credit Card Application Classification

## Overview
This project implements a machine learning model to classify credit card applications as either approved or not approved based on various features. The model uses a Random Forest classifier and includes data preprocessing, feature selection, model training, evaluation, and hyperparameter tuning.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Features
- Data loading and preprocessing
- Correlation analysis and visualization
- Feature selection based on correlation
- Model training using Random Forest
- Model evaluation with confusion matrix, accuracy score, and classification report
- Hyperparameter tuning using GridSearchCV

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The dataset used in this project is available on Kaggle. You can download it from the following link:

[Credit Card Applications Dataset](https://www.kaggle.com/datasets/nazishjaveed/credit-card-application/data)

This dataset contains various features related to credit card applications, with the target variable indicating whether the application was approved (1) or not approved (0).

## Installation
To run this project, you need to have Python installed on your machine. You can install the required libraries using pip:

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-application-classification.git
   cd credit-card-application-classification
   ```

2. Place the `Credit_Card_Applications.csv` file in the project directory.

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook credit.ipynb
   ```

4. Follow the instructions in the notebook to execute the code cells and analyze the results.

## Results
The model's performance can be evaluated using the confusion matrix, accuracy score, and classification report generated during the evaluation phase. The confusion matrix provides insights into the model's predictions compared to the actual outcomes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html) - For providing tools and libraries for machine learning.
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html) - For visualization capabilities.
- [Seaborn Documentation](https://seaborn.pydata.org/) - For enhanced statistical data visualization.
- [Kaggle](https://www.kaggle.com/datasets/nazishjaveed/credit-card-application/data) - For the Credit Card Applications dataset used in this project.
