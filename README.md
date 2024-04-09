# data_preprocessing
This repository contains Python code for data preprocessing tasks commonly performed in machine learning projects. The provided script covers the following preprocessing steps:

Importing necessary libraries.
Importing dataset from a CSV file.
Handling missing data.
Encoding categorical data.
Splitting the dataset into training and test sets.
Feature scaling.
Code Structure
The data_preprocessing.py script contains the code for performing the aforementioned preprocessing tasks. Below is a brief overview of each section of the code:

1. Importing the Libraries
Importing NumPy, Matplotlib, and Pandas libraries, which are commonly used for data manipulation and visualization in Python.
2. Importing the Dataset
Reading a CSV file named 'Data.csv' containing the dataset.
Separating independent variables (features) and dependent variable (target) from the dataset.
3. Handling Missing Data
Using SimpleImputer from scikit-learn to handle missing values by replacing them with the median of the respective column.
4. Encoding Categorical Data
Encoding categorical variables using one-hot encoding for independent variables and label encoding for the dependent variable.
5. Splitting the Dataset
Splitting the dataset into training and test sets using train_test_split from scikit-learn.
6. Feature Scaling
Scaling the features to have a mean of 0 and a standard deviation of 1 using StandardScaler from scikit-learn.
Usage
To use this script, follow these steps:

Ensure you have Python installed on your system.
Install the required libraries by running pip install -r requirements.txt.
Place your dataset in CSV format and update the filename in the script accordingly.
Run the script using Python.
bash
Copy code
python data_preprocessing.py
Requirements
Python 3.x
NumPy
Matplotlib
Pandas
scikit-learn
Contributors
Your Name - Creator
Feel free to contribute to this project by forking the repository and submitting pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.

