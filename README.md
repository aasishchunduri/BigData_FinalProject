# BigData_FinalProject_Group12
# Team Members
* Aasish Chunduri
* Sumanth Reddy Alluri
* Siva Naga Rutwik Reddy Chintha
* Varshith Reddy Gopu
* Aditya Shiva Sai Agganoor
# Communication Plan
We are communicating with the teammates through email, slack and decided to connect every weekend through zoom calls.
# Business Problem or Opportunity:
The dataset under consideration here is from the CDC's yearly poll of individuals regarding their health status. The dataset originated from the CDC and is a significant component of the Behavioural Risk Factor Surveillance System (BRFSS), which conducts annual telephone surveys to collect information on Americans' health conditions. Heart disease, one of the major causes of death for people of most races in the US, is caused by high blood pressure, high cholesterol, and smoking, according to the CDC (Centers for Disease Control and Prevention). Other significant indicators are the presence of diabetes, obesity (high BMI), a lack of physical activity, and excessive alcohol consumption. Data from 2020 is included in the most recent dataset (as of February 15, 2022). The dataset we selected will undergo data pre-processing so that we can apply a spectrum of machine learning models to derive and identify "patterns" from the data that can predict a patient's condition because identifying and preventing the factors that have the greatest impact on heart disease is very important in healthcare.

Link: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease
# Research Objectives:
We pre-process the dataset and use the data to make predictions and derive insights. Using multiple factors like high blood pressure, high cholesterol, smoking, and BMI we can train a machine learning model on this dataset to predict a person's risk of developing heart disease considering the various factors present in the dataset.

# Deliverable 2
## Data Understanding
We have one csv file named heartdisease.csv where HeartDisease column is the dependent variable and remaining columns are the independent variables. We have 319795 entries and 18 columns.<br>

We performed the exploratory data analysis on our dataset.

## Exploratory Data Analysis:
We used AWS QuickSight for the exploratory data analysis.

<img src="images/quicksight_1.png">
The above visualization represents the number of people having heart disease and those of not have it.<br>

<img src="images/quicksight_2.png">
The above visualization represents the relation between age category and heart disease. It gives an analysis of how many people belonging to a particular age have
been exposed to heart disease or not.<br>

<img src="images/quicksight_3.png">
The above visualization is for Sex,Race against heart disease. It gives us an analysis of which race people and gender people are more effected by heart disease.<br>

<img src="images/quicksight_4.png">
The above chart explains the relationship between BMI, sleep time, and heart disease.<br>

## Data Preparation
We used Sagemaker for the data preparation and the data cleaning process. We have imported the necessary libraries to perform these actions.
<img src="images/sagemaker_1.png"><br>
There are no missing values in the dataset in any column.
<img src="images/dataprep_1.png"><br>
We have multiple categorical values in each column. We need to convert all of them into numerical values to train the model.
<img src="images/dataprep_2.png"><br><br>
These are the steps taken in the Data preparation phase which makes the data ready to train using the machine learning model.

# Deliverable 3
## Analytics,Machine learning





