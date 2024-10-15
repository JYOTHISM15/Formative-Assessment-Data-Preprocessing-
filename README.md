# Formative-Assessment-Data-Preprocessing-# Data Preprocessing System

## Objective
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning applications.

## Dataset
The dataset used in this project can be found [here](https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing).

## Key Components

### 1. Data Exploration 
- Explore the data to list unique values in each feature and determine their lengths.
- Perform statistical analysis and rename columns for clarity.

### 2. Data Cleaning 
- Identify and address missing and inappropriate values.
- Remove duplicate rows from the dataset.
- Detect and handle outliers.
- Replace the value `0` in the age column with `NaN`.
- Treat null values in all columns using appropriate methods (removal or replacement with mean/median/mode).

### 3. Data Analysis 

- Filter the dataset for records where age > 40 and salary < 5000.
- Plot a chart to visualize the relationship between age and salary.
- Count the number of individuals from each location and represent this data visually.

### 4. Data Encoding 
- Convert categorical variables into numerical representations using techniques such as one-hot encoding and label encoding, making them suitable for analysis by machine learning algorithms.

### 5. Feature Scaling 
- After encoding, perform feature scaling using `StandardScaler` and `MinMaxScaler` to normalize the data.
