Traffic Accident Data Analysis
This project analyzes traffic accident data to uncover patterns and trends related to road conditions, weather, and time of day. The insights gained from this analysis aim to develop targeted strategies to improve road safety.

Dataset
The dataset used in this project is the US Accidents dataset, which can be found here.

Code Overview
The analysis is performed using Python and involves the following steps:

Data Loading and Initial Exploration

Load the dataset using pandas
Display the first 10 rows of the dataset
Check the number of columns and rows
Display the columns of the dataset
Data Cleaning and Preprocessing

Check for missing and null values
Drop rows with missing values in crucial columns
Fill missing values in other columns with appropriate values
Convert date-time columns to the correct format
Exploratory Data Analysis (EDA)

Plot the percentage of missing data per column
Analyze the number of accidents in each city
Visualize the distribution of accidents by hour of the day, day of the week, and month of the year
Examine the distribution of accidents by severity and state
Plot the latitudes and longitudes of accidents
Inferences and Visualizations

Analyze the impact of weather conditions, visibility, and temperature on accident severity
Create various plots to visualize the findings
Key Findings
Cities with the highest number of accidents
Time periods with the highest accident frequency
States with the highest accident severity
Weather conditions that contribute to higher accident rates
Requirements
pandas
seaborn
matplotlib
Usage
To run the analysis, follow these steps:

Clone the repository
Install the required packages using pip install pandas seaborn matplotlib
Run the analysis script
