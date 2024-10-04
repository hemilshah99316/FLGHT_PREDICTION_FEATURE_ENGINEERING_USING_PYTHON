# ✈️ Airline Data Feature Engineering Project


## 📊 Overview

This project involves feature engineering on airline data to prepare it for machine learning applications. The dataset contains flight details, including airlines, journey dates, sources, destinations, and prices.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Libraries:** 
  - Pandas
  - NumPy
  - Matplotlib
  - Scikit-Learn
  - Seaborn
## 📈 Data Transformation

The initial dataset was transformed to create a machine learning-friendly format. Below are the details of the transformed dataset:

| Column           | Dtype   |
|------------------|---------|
| Airline          | int32   |
| Source           | int32   |
| Destination      | int32   |
| Total_Stops      | float64 |
| Additional_Info  | int32   |
| Price            | float64 |
| Date             | int32   |
| Month            | int32   |
| Year             | int32   |
| Arrival_hour     | int32   |
| Arrival_min      | int32   |
| Dept_hour        | int32   |
| Dept_min         | int32   |
| duration_hour    | int32   |


## 🔍 Features Engineered

- **Airline:** Encoded as integers.
- **Source and Destination:** Converted to numerical format for better processing.
- **Total Stops:** Managed missing values and encoded accordingly.
- **Date, Month, Year:** Extracted from the date of journey.
- **Arrival and Departure Times:** Split into hours and minutes.
- **Flight Duration:** Parsed into hours for better usability.

## 🚀 Next Steps

The transformed dataset is now ready for machine learning modeling. Future enhancements could include:

- Implementing predictive models for flight prices.
- Conducting exploratory data analysis (EDA) for deeper insights.
