# Data-Cleaning-Transformation

Goal

The goal of this project is to clwan and tranform the data in a dataset named fifa-21-messy-raw-dataset-for-cleaning-exploring. The specific tasks include:

1. make the Height and Weight columns have the appropriate data type
2. separate the Joined column into Year, Month, Day three columns
3. clean and transform the columns Values, Wage, and Release Clause into columns of integers
4. remove the newline characters from Hits column
5. separate the Team & Contract column 

Dataset

The dataset used in this project is sourced from Kaggle and contains information about football
players. The dataset was obtained using the Kaggle API by executing the following command:

!kaggle datasets download -d yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring 

Format
The dataset is provided in zip format and consists of two files named 'fifa21_raw_data.csv' and 
'fifa21 raw data v2.csv'. The CSV files contain rows of data, each representing a football player,
and columns representing various attributes such as player name,height, weight,tam,contract,etc.

Structure
The dataset has 77 columns:
#   Column            Non-Null Count  Dtype 
---  ------            --------------  ----- 
 0   photoUrl          18979 non-null  object
 1   LongName          18979 non-null  object
 2   playerUrl         18979 non-null  object
 3   Nationality       18979 non-null  object
 4   Positions         18979 non-null  object
 5   Name              18979 non-null  object
 6   Age               18979 non-null  int64 
 7   ↓OVA              18979 non-null  int64 
 8   POT               18979 non-null  int64 
 9   Team & Contract   18979 non-null  object
 10  ID                18979 non-null  int64 
 11  Height            18979 non-null  object
 12  Weight            18979 non-null  object
 13  foot              18979 non-null  object
 14  BOV               18979 non-null  int64 
 15  BP                18979 non-null  object
 16  Growth            18979 non-null  int64 
 17  Joined            18979 non-null  object
 18  Loan Date End     1013 non-null   object
 19  Value             18979 non-null  object
...
 75  PHY               18979 non-null  int64 
 76  Hits              18979 non-null  object

 The goal of this project is to clean and transform the data in this dataset 
 to make it suitable for analysis and further processing.

 