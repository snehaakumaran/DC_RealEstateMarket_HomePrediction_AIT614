
# Predicting Home Prices in Washington D.C. Real Estate Market: A Machine Learning Approach 

## Authors - Team 5 

- [Nafisa Ahmed](nahmed27@gmu.edu)
- [Peter Bishay](pbishay@gmu.edu)
- [Charles Gilberston](cgilber@gmu.edu)
- [Sneha Kumaran](skumara2@gmu.edu)
- [Cora Sula](csula@gmu.edu)


## Working System Description

This system is ran on Databricks. This system will explore and analyze all persepctives how home prices tend to fluctuate and are impacted in D.C. Metropolitan area. Based on the trends and data exploration, our team was able to create a system that will predict the price of the homes by using various machine learning algorithms. We have created 2 notebooks that will display the analysis of various insights on how features or factors can impact the prices in D.C. real estate market. This will eventually lead us into creating models using multiple algorithms to predict the prices. 


##First Step - Import Data
## Dataset
A dataset file called DC_Properties.csv file is saved into the folder. Use that to run the notebook.

Also here is the link/source of the dataset
Dataset from Kaggle - DC_Properties.csv
- [D.C. Residential Properties.](https://www.kaggle.com/datasets/christophercorrea/dc-residential-properties/)

Make sure to ONLY download the DC_Properties.csv. This is the only file used to obtain all the results and analysis for this project.

##How to Import Dataset?
1. Click on file
2. Upload data to DBFS
3. Click on "Drop files to upload, or click to browse"
4. Add the file "DC_Properties.csv" into it and click "Next" after it loads
5. Click "Done"

#Notebook 1 - House Pricing Analysis

After importing the dataset, add inferSchema = "true"

In the first command line the variable housing_data should look like this:
- EX: housing_data = spark.read.format("csv").option("header", "true").load("dbfs:/FileStore/shared_uploads/nahmed27@gmu.edu/DC_Properties.csv", inferSchema = "true")

After all these criterias -> Run all cells

## System Run
The system will be able to run. It will go through Data Importing, Queries, Visualizations, Feature Preprocessings, and Machine Learning Algorithms. The algorithms are Random Forest and Linear Regression, Decision Trees. There are two types of linear regression models applied for analysis and cross comparison. Some of the commands may take a longer time than others. 


#Notebook 2 - Clustering Analysis

After importing the dataset -> Run all cells

##System Run
The system will be able to run. It will run the K-Means based algorithm. Some of the commands will take a longer time than others. 
