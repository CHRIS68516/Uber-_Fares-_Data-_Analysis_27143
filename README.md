<p align="center">
 <h1>Uber Fares Data Analysis Project</h1>
  </p>
This project was carried out by a student analyst to examine Uber ride data and uncover meaningful patterns in fare amounts, ride durations, and travel locations. Using Python for data cleaning and preparation, and Power BI for building visualizations, I manually explored and transformed the dataset to gain a clear understanding of ride behavior across different times of day, days of the week, and distances traveled. Feature engineering was done to extract relevant time-based attributes and support deeper analysis.<br><br>


With the cleaned and enhanced data, I created interactive dashboards in Power BI to visualize fare distributions, detect peak hours, and analyze geographic patterns in ride activity. The findings from this human-led analysis aim to support smarter business decisions in areas like pricing strategy, driver allocation, and customer satisfaction. This project highlights how data science skills can be applied by individuals to solve real-world problems using structured data and visual storytellin


## How to Create a CSV File in Python Using Pandas

<img width="1395" height="754" alt="How to Create a CSV File in Python Using Pandas" src="https://github.com/user-attachments/assets/463a457c-d2ea-444f-91cc-a764ca528dd0" />

## Loading and Previewing Uber Ride Data Using Pandas in Python

<img width="1152" height="541" alt="Loading and Previewing Uber Ride Data Using Pandas in Python" src="https://github.com/user-attachments/assets/d0a69754-fa41-4478-b52b-5be323a2ea21" />


## Calculating Trip Distance Using Geopy and Coordinate Validation

<img width="1158" height="646" alt="Calculating Trip Distance Using Geopy and Coordinate Validation" src="https://github.com/user-attachments/assets/f88b6d7e-9708-4b68-8c41-d3951b18f122" />

## Visualizing the Relationship Between Fare Amount and Trip Distance

<img width="1173" height="765" alt="Visualizing the Relationship Between Fare Amount and Trip Distance" src="https://github.com/user-attachments/assets/e0a93f08-bcc5-44f6-952f-2af48a68f2b2" />

## Importing Statsmodels Library for Statistical Modeling

This line imports the statsmodels library (commonly used as sm), which provides classes and functions for estimating and analyzing many different statistical models (like linear regression, time series models, etc.).

<img width="1186" height="406" alt="importing" src="https://github.com/user-attachments/assets/ec1e0061-67bd-42fe-a865-7c66383d9269" />

## Summary Statistics and Data Ranges for Numeric Columns

This code performs descriptive analysis on a DataFrame df to understand the spread and scale of numeric data:

<img width="1183" height="685" alt="1" src="https://github.com/user-attachments/assets/60aabccc-38ec-4729-bccc-213718f8fb4d" />

## Outlier Detection Using the Interquartile Range (IQR) Method

<img width="1220" height="396" alt="2" src="https://github.com/user-attachments/assets/762809a3-2fd4-438c-aaf8-c01f91a7d94b" />

## Visualizing Outliers with Boxplots for Fare Amount and Distance

<img width="1171" height="726" alt="image" src="https://github.com/user-attachments/assets/3c78e05b-c41e-4837-bad1-bcee103a0060" />

## Histogram of Fare Amount Distribution

This code creates a histogram with a Kernel Density Estimate (KDE) to visualize how Uber fare amounts are distributed.

<img width="1170" height="712" alt="image" src="https://github.com/user-attachments/assets/24db89fc-8027-48d4-8b8e-5a8a91b48461" />

## Boxplot of Fare Amount by Hour of Day

This code visualizes how fare amounts vary across different hours of the day using a boxplot:

x='hour': Groups data by the hour (you must have a column hour extracted from datetime).

y='fare_amount': Shows the distribution of fares for each hour.

<img width="1184" height="662" alt="image" src="https://github.com/user-attachments/assets/2cb4fe6b-8d9a-413c-b7fa-9d1a68b62a21" />

## Violin Plot of Fare Amount by Hour of Day

This code creates a violin plot to show how Uber fare amounts vary by the hour of the day.

x='hour': Groups fares by each hour (0 to 23).

y='fare_amount': Displays fare amount distribution per hour.

inner='quartile': Adds lines for 25%, 50% (median), and 75% values inside each "violin."

palette='muted': Applies a soft color palette for readabilit

<img width="1207" height="739" alt="image" src="https://github.com/user-attachments/assets/68814f5b-c2fd-4637-a0f0-780a080fc279" />

## Scatter and Regression Plot of Fare Amount vs Distance Traveled

This visualization analyzes the relationship between trip distance and fare amount using two layers:

Scatterplot (sns.scatterplot):

Plots individual rides as points based on distance (x-axis) and fare_amount (y-axis).

alpha=0.5 makes the points semi-transparent, helping reduce clutter in dense areas.

Regression Line (sns.regplot):

A red line that models the linear relationship between distance and fare amount.

scatter=False prevents it from plotting another set of points.

<img width="1155" height="733" alt="image" src="https://github.com/user-attachments/assets/d5b27d75-e31d-43ac-a318-59cd56966b01" />

## Analysis of Fare Amount by Passenger Count

<img width="1220" height="668" alt="image" src="https://github.com/user-attachments/assets/08cee6b2-511f-4e2f-a1fd-694fb0a5f0eb" />

## Distance Traveled by Passenger Count with Correlation Analysis

This code performs visual and statistical analysis of how the number of passengers relates to the distance traveled in Uber rides.

<img width="1178" height="671" alt="image" src="https://github.com/user-attachments/assets/4e513165-6bbf-41da-a166-3965a9f43250" />

## Encoding Categorical Features Using Label Encoding

<img width="1162" height="533" alt="image" src="https://github.com/user-attachments/assets/7c70057e-886f-4b89-ae87-1701da9e9681" />

## Fetching Hourly Weather Data Using Meteostat API

This Python code fetches hourly weather data for a specific location and date range using the Meteostat library:

Location: Defined by latitude and longitude; in this example, New York City (40.7128, -74.0060).

Date Range: From January 1 to January 7, 2023.

Data: Hourly weather observations (temperature, humidity, wind, etc.) are retrieved.

Preview: Displays the first few rows of the weather dataset.

Export: Saves the data to a CSV file nyc_weather.csv for import into Power BI or further analysis.

<img width="1162" height="644" alt="image" src="https://github.com/user-attachments/assets/4b78903f-649a-4d70-9672-4c8c07157e75" />

## Adding Simulated Weather Data to Uber Fares Dataset

<img width="1228" height="825" alt="image" src="https://github.com/user-attachments/assets/5b757555-de49-475e-9e43-cc68e8980926" /><br><br>

### Uber Fares Data Analysis and Visualization Report


# Project Overview & Dataset Description

Introduces the dataset, project goal, and data sources.

<img width="1441" height="695" alt="bi1" src="https://github.com/user-attachments/assets/bdeb9a6d-d56f-4b5b-a57b-c9a6acca268c" />

# Data Cleaning and Preparation

Explains the methodology for removing missing/outlier data, datetime conversion, and distance calculation.

<img width="722" height="468" alt="image" src="https://github.com/user-attachments/assets/e48eaca8-59f4-4f6d-8b2d-56621a7d60f6" />

 # Feature Engineering

Describes new variables like hour, weekday, peak_time, and encoding techniques.

<img width="1309" height="645" alt="image" src="https://github.com/user-attachments/assets/8158eec4-6d2d-4a53-8709-9fe602b3019c" />

# Fare Distribution Analysis

Shows histogram, boxplot, and violin plot of fare amount distribution.

 <img width="885" height="468" alt="image" src="https://github.com/user-attachments/assets/c224d9fa-f2fc-4edf-95df-61d55ca7f0af" />

 <img width="566" height="403" alt="image" src="https://github.com/user-attachments/assets/4c850099-f92b-4ade-a631-f300ade22474" />


# Fare vs Distance

Displays scatterplot and regression line showing how distance affects fare.

<img width="656" height="468" alt="image" src="https://github.com/user-attachments/assets/24e4f5b6-7cd1-4870-bb27-adcbc3079ff5" />


# Temporal Analysis

Visualizes fare amount trends across hours, days, and weekdays.

<img width="1084" height="591" alt="image" src="https://github.com/user-attachments/assets/43b0a038-5484-4700-af3f-5d8e67ebe256" />


# Passenger Count Analysis

Boxplots showing relationship between passenger count, fare amount, and distance.

<img width="591" height="414" alt="image" src="https://github.com/user-attachments/assets/d75793e9-518b-4a0a-b99b-7bba220cfd0f" />


# Weather & Fare Trends (if included)

Analyzes how weather conditions or temperature affect fare (optional).

<img width="948" height="530" alt="image" src="https://github.com/user-attachments/assets/18495da8-a631-4155-9112-556d3a642446" />

# Key Insights & Summary

Summarizes main findings and correlations.

<img width="1028" height="607" alt="image" src="https://github.com/user-attachments/assets/8f08d4df-43e3-43fc-a9d3-8c0e9ccabeaa" />

# Final dashboard  Uber Fares Data Analysis and Visualization Report

<img width="1576" height="721" alt="dashboard" src="https://github.com/user-attachments/assets/e05e5548-416c-4bbf-86f3-186bca6e6b7f" />







