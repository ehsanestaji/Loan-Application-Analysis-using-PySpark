# 📊 Loan Application Analysis using PySpark

## 📌 Description

This repository contains an end-to-end analysis of loan applications using PySpark. It includes data manipulation, feature engineering, and binary classification models. 

## 📚 Table of Contents

1. [📋 Data Overview](#data-overview)
2. [📁 Project Structure](#project-structure)
3. [🔨 Usage](#usage)


## 📋 Data Overview

The data for this project is sourced from the Kaggle competition [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data). The goal of the competition is to predict the capability of each applicant in repaying a loan.

### application_train.csv

- **Number of Entries**: `307,511`
- **Number of Columns**: `122`
- **Column Types**: `Float64(65), Int64(41), Object(16)`

#### 📄 Sample Data

| SK_ID_CURR | TARGET | NAME_CONTRACT_TYPE | CODE_GENDER | FLAG_OWN_CAR | ... |
|------------|--------|--------------------|-------------|--------------|-----|
| 100002     | 1      | Cash loans         | M           | N            | ... |
| 100003     | 0      | Cash loans         | F           | N            | ... |
| 100004     | 0      | Revolving loans    | M           | Y            | ... |
| 100006     | 0      | Cash loans         | F           | N            | ... |
| 100007     | 0      | Cash loans         | M           | N            | ... |

## 📁 Project Structure

### 📓 Notebooks

- `Income-Spark.ipynb`: Main Jupyter Notebook for the project.

#### 📝 Sections in Notebook

1. **Import Essential Libraries**: Libraries like `os` and `pandas` are imported.
2. **Initialize PySpark Configuration**: The Spark Configuration and Context are initialized.
3. **Import PySpark and Initialize**: PySpark library is imported and Spark Session is initialized.

#### 💻 Code Snippets

- Importing essential libraries
  ```python
  import os
  import pandas as pd
  ```

- Initializing PySpark Configuration
  ```python
  from pyspark import SparkConf, SparkContext
  ```

- Initializing Spark Session
  ```python
  import pyspark
  from pyspark.sql import SparkSession
  ```

## 🔨 Usage

To run the Jupyter Notebook, execute:

```bash
jupyter notebook Loan-Application-PySpark.ipynb
```
