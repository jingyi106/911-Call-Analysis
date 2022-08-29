# 911-Calls-Analysis

## Background

For this project we will be analyzing some 911 call data from Kaggle:https://www.kaggle.com/datasets/mchirico/montcoalert. The data contains the following fields:

lat : String variable, Latitude

lng: String variable, Longitude

desc: String variable, Description of the Emergency Call

zip: String variable, Zipcode

title: String variable, Title

timeStamp: String variable, YYYY-MM-DD HH:MM:SS

twp: String variable, Township

addr: String variable, Address

e: String variable, Dummy variable (always 1)

## Analytics Pipeline

### Basic Analysis: 

1. Top 5 zipcodes for 911 calls

2. Top 5 townships for 911 calls

3. Number of unique title codes


### 911 Calls Reason Analysis

1. Most Common Reason for 911 calls

2. Data Visualization: Number of 911 calls of each reason based on time factors (Hour, Day of Week, Month)

### Time Analysis
1. Time Series visualization 
2.  Create heatmap and cluster map to see during which time there are relatively more 911 calls (At which hour; on which day; in which month)

## Packages Used
Numpy, Pandas, Plotly and Cufflinks (Interactive Data Visualization), Matplotlib, Seaborn
