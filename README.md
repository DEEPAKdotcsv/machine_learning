# machine_learning

# Titanic Data Preprocessing and Exploration

This project involves cleaning, preprocessing, and visualizing the Titanic dataset to prepare it for further analysis or modeling.

## Description

- Loaded the Titanic dataset from an Excel file.
- Explored basic information about the dataset: shape, columns, missing values.
- Handled missing data:
  - Imputed missing Age values with the mean.
  - Imputed missing Embarked values with the most frequent category.
  - Dropped the Cabin column due to excessive missing data.
- Converted categorical variables (Sex and Embarked) to numeric using one-hot encoding.
- Visualized distributions of Age and Fare.
- Scaled numerical features:
  - StandardScaler for Age.
  - MinMaxScaler for Fare.
- Detected and removed outliers from Age and Fare using the IQR method.

## Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/titanic-preprocessing.git
cd titanic-preprocessing
pip install numpy pandas seaborn matplotlib scikit-learn openpyxl
