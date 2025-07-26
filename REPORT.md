# Uber Fares Data Analysis Report

## 1. Dataset Description and Sources
- Dataset downloaded from [Kaggle Uber Fares Dataset](https://www.kaggle.com/datasets)
- Contains ride data with columns such as `fare_amount`, `pickup_datetime`, `pickup_latitude`, `pickup_longitude`, and more.

# Introduction
This report presents an exploratory data analysis (EDA) of Uber fare data collected in New York City. The main goal is to uncover trends and patterns in ride fares, distances, ride durations, and their relationships with variables such as time of day, passenger count, and simulated weather conditions.

By cleaning, transforming, and visualizing the dataset, we aim to derive insights that could help understand pricing behavior, peak travel hours, and factors influencing fare variation. The results of this analysis can be useful for improving urban transportation services and informing ride pricing strategies.



## 3. Feature Engineering
Extracted time-based features such as hour, day, and weekday from the pickup timestamp.

Created new categorical features to classify peak vs. off-peak ride times.

Encoded categorical variables like weekday_name and peak_time for modeling and visualization.

## 4. Exploratory Data Analysis (EDA)
Visualized fare distribution using histograms and boxplots to detect skewness and outliers.

Explored the relationship between distance traveled and fare amount using scatter plots and regression lines.

Analyzed fare trends by hour of day, weekday, and passenger count to uncover demand patterns.

## 5. Key Insights
Fare amounts increase with distance, showing a strong positive correlation.

Higher fares are observed during peak hours, suggesting dynamic pricing or increased demand.

Passenger count shows minimal impact on both fare amount and trip distance.

## 6. Conclusion and Recommendations
Uber’s fare pricing appears to be strongly influenced by distance and time of day.

Incorporating real-time weather data could further enhance demand prediction models.

Future work could include clustering locations, predicting fare amounts, or building a fare recommendation system.
---

### Images and Visualizations
*(Include your images here by uploading them to the repo and linking)*

Example:

!<img width="1173" height="765" alt="Visualizing the Relationship Between Fare Amount and Trip Distance" src="https://github.com/user-attachments/assets/ae44dc4c-8697-4434-8965-fdde822aed9a" />

<img width="1171" height="726" alt="3" src="https://github.com/user-attachments/assets/81fa00a9-8935-4277-98ea-258771b2e821" />

<img width="1170" height="712" alt="4" src="https://github.com/user-attachments/assets/95fd8037-abef-446e-9e25-2f733916e04b" />



<img width="1184" height="662" alt="5" src="https://github.com/user-attachments/assets/04283324-3ffc-4f3e-a4db-01043a109aca" />


<img width="1207" height="739" alt="6" src="https://github.com/user-attachments/assets/d33c9c62-89b5-4941-be23-94c2602866e0" />

*Report prepared by [Your Name]*  
*Date: July 2025*
