FEATURE ENGINEERING ON FLIGHT DATA
This project focuses on transforming and preparing raw flight dataset features for improved machine learning performance. The notebook includes multiple preprocessing and feature engineering operations to better capture flight delay patterns and prediction opportunities.

**PROJECT GOALS**
Clean and preprocess the flight dataset
Handle missing or inconsistent values
Convert string columns into usable numerical formats
Extract meaningful features from timestamps and categories
Reduce feature noise and improve ML model readiness

**DATASET INFORMATION**
The dataset consists of flight-related attributes such as:
Airline name
Source airport
Destination airport
Date of journey
Departure and arrival times
Flight duration
Total stops count
Ticket price

**FEATURE ENGINEERING TASKS PERFORMED**
Converted date columns into Day, Month, and Year
Split duration string into hours and minutes
Converted categorical airline and airport columns into numerical form
Extracted departure and arrival features like hour and minute
Handled missing values using imputation techniques
Standardized or normalized selected numerical columns
Prepared final dataset for ML model training

**TOOLS AND LIBRARIES USED**
Python
Pandas for data processing
NumPy for numerical operations
Scikit-learn for encoding and transformations
Matplotlib/Seaborn for optional visual exploration

**OUTPUT SUMMARY**
A cleaned and enhanced dataset suitable for ML modeling
Additional engineered features capturing useful flight patterns
Improved dataset shape and consistency
