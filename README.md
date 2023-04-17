# Using Health Indicators to Predict Occurrence of Diabetes with AWS
This is the final project for the University of San Diego’s ADS 508 Data Science with Cloud Computing course.

## Description
Diabetes is an increasing issue in the United States. This project will examine diabetes health indicator data to predict which patients may be diagnosed with diabetes in the future or can be diagnosed with diabetes now. This project also has the objective of determining which diabetes health indicators are most predictive of a diabetes diagnosis

## Repository Contents
* [Notebook](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/analysisNotebook.ipynb)
* [diabetes_012_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_012_health_indicators_BRFSS2015.csv)
* [diabetes_binary_5050split_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_binary_5050split_health_indicators_BRFSS2015.csv)
* [diabetes_binary_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_binary_health_indicators_BRFSS2015.csv)

## Project Description
### Data Sources
The [diabetes datasets](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset) are obtained from Kaggle. The data will be stored on AWS S3 Bucket, which will establish a connection with AWS Sagemaker. The three files are uploaded to the S3 bucket.
* [diabetes_012_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_012_health_indicators_BRFSS2015.csv): The file contains 253,680 observations and the target variable (*Diabetes_012*) is imbalanced and has three classes (0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes).
* [diabetes_binary_5050split_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_binary_5050split_health_indicators_BRFSS2015.csv): The file contains 70,692 observations and the target variable (*Diabetes_binary*) has been balanced and has two classes (0 is for no diabetes and 1 is for prediabetes or diabetes).
* [diabetes_binary_health_indicators_BRFSS2015.csv](https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project/blob/main/data/diabetes_binary_health_indicators_BRFSS2015.csv): The file contains 253,680 observations and the target variable (*Diabetes_binary*) is imbalanced and has two classes (0 is for no diabetes and 1 is for prediabetes or diabetes).

The data can also be accessed directly through the public S3 bucket through this path: s3://diabetes-ads508
* diabetes_012_health_indicators_BRFSS2015.csv located here : s3://diabetes-ads508/folder-1/csv/
* diabetes_binary_5050split_health_indicators_BRFSS2015.csv located here : s3://diabetes-ads508/folder-2/csv/
* diabetes_binary_health_indicators_BRFSS2015.csv located here : s3://diabetes-ads508/folder-3/csv/




### Methods
* Data Preprocessing
* Data Visualization
* Exploratory Data Analysis
* Statistical Modeling

### Technologies
* AWS (SageMaker, Athena, S3, Data Wrangler)
* Python (AWS SageMaker)
* SQL

## Getting Started
### Installing
* Clone the repository using the following commands:
```
git init
```
```
git clone https://github.com/ChrisGarciaDS/ADS-508-Team-Final-Project.git
```

## Authors
* Christopher Garcia
* Claire Phibbs
* Christine Vu
