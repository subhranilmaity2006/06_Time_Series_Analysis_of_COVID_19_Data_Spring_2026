# 06_Time_Series_Analysis_of_COVID_19_Data_Spring_2026

Project Report Summary
This project involved a two-part analysis:

Part 1: Time-Series Analysis of COVID-19 Data

Data Loading & Preprocessing: The WHO-COVID-19-global-daily-data.csv dataset was loaded, subsetted to key columns (Date_reported, Country, WHO_region, New_cases, New_deaths), converted the Date_reported column to datetime format, and trimmed to the period from '2020-03-01' to '2023-08-31'.
Analysis: We identified the top 5 most affected countries by cumulative cases, calculated daily global new cases, aggregated data by quarter for new cases and deaths, determined total cases by WHO region, and found the date with the highest global new cases. A pivot table was also created to show monthly cases by region.

Part 2: MNIST Clustering Analysis

Data Loading: The MNIST handwritten digits dataset was loaded, separating features (X) and target labels (y).
K-Means Clustering: A K-Means model with 10 clusters was applied to the MNIST features.
Evaluation: The clustering performance was evaluated using the macro-averaged F1 score, after mapping the arbitrary cluster labels to the most frequent true labels within each cluster. The F1 score achieved was approximately 0.786.
Overall, the project demonstrated comprehensive data handling, time-series analysis, and unsupervised machine learning techniques.
