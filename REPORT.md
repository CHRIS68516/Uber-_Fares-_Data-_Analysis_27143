# Uber Fares Data Analysis Report

## 1. Dataset Description and Sources
- Dataset downloaded from [Kaggle Uber Fares Dataset](https://www.kaggle.com/datasets)
- Contains ride data with columns such as `fare_amount`, `pickup_datetime`, `pickup_latitude`, `pickup_longitude`, and more.

## 2. Data Cleaning Methodology
- Removed rows with missing or invalid values
- Converted pickup datetime strings to datetime objects
- Calculated trip distance using pickup and dropoff coordinates
- Detected and handled outliers using the IQR method

## 3. Feature Engineering
- Extracted hour, day, and weekday from pickup datetime
- Created peak and off-peak time indicators
- Encoded categorical variables like weekday and peak time

## 4. Exploratory Data Analysis (EDA)
- Visualized fare distribution with histograms and boxplots
- Analyzed relationship between fare amount and distance traveled
- Examined fare patterns by hour of day and passenger count

## 5. Key Insights
- Fares generally increase with distance traveled
- Peak hours show higher fare amounts, possibly due to surge pricing
- Passenger count has little correlation with fare amount or distance

## 6. Conclusion and Recommendations
- Pricing strategies should consider time-of-day and distance trends
- Further analysis with real weather data could improve understanding of demand fluctuations

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
