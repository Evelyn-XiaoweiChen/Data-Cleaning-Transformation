# Data-Cleaning-Transformation

# Goal

The goal of this project is to clwan and tranform the data in a dataset named fifa-21-messy-raw-dataset-for-cleaning-exploring. The specific tasks include:

1. make the Height and Weight columns have the appropriate data type
2. separate the Joined column into Year, Month, Day three columns
3. clean and transform the columns Values, Wage, and Release Clause into columns of integers
4. remove the newline characters from Hits column
5. separate the Team & Contract column 

# Dataset

The dataset used in this project is sourced from Kaggle and contains information about football
players. The dataset was obtained using the Kaggle API by executing the following command:

    !kaggle datasets download -d yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring 

# Format

The dataset is provided in zip format and consists of two files named 'fifa21_raw_data.csv' and 
'fifa21 raw data v2.csv'. The CSV files contain rows of data, each representing a football player,
and columns representing various attributes such as player name,height, weight,tam,contract,etc.

# Unzip the dataset file

    with zipfile.ZipFile
    
    ('fifa-21-messy-raw-dataset-for-cleaning-exploring.zip', 'r') as zip_ref:
  
    zip_ref.extractall('.')


# Data Summary

The dataset has 18978 rows and 77 columns:
![alt text](<dataStructure.png>)

 The goal of this project is to clean and transform the data in this dataset 
 to make it suitable for analysis and further processing.

 # Requirements

 * Python 3
 * pandas
 * numpy
 * zipfile

 # Tools 

 VSCode, Git

 # Usage

 1. Install kaggle & download dataset with Kaggle API

        %pip install kaggle

 ## download files with kaggle API
     !kaggle datasets download -d yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring


2. Import libraries

       import pandas as pd

       import numpy as np

       import zipfile


3. Extract zip file and read CSV file


       with zipfile.ZipFile

       ('fifa-21-messy-raw-dataset-for-cleaning-exploring.zip', 'r') as zip_ref:

       zip_ref.extractall('.')

 ### load datasets

    df = pd.read_csv('fifa21_raw_data.csv')



# Run data cleaning and transformation tasks:


Task 1: Making the Height and Weight columns have the appropriate data type

Solution: Refer to the Jupyter Notebook for the code to convert data types.

Task 2: Separating the Joined column into Year, Month, Day three columns

Solution: Refer to the Jupyter Notebook for the code to separate the column.

Task 3: Cleaning and transforming the columns Values, Wage, and Release Clause into columns of integers

Solution: Refer to the Jupyter Notebook or for the code to clean and transform the columns.

Task 4: Removing the newline characters from the Hits column

Solution: Refer to the Jupyter Notebook for the code to remove newline characters.

Task 5: Separating the Team & Contract column

Solution: Refer to the Jupyter Notebook for the code to separate the column.