# 06_Time_Series_Analysis_of_COVID_19_Data_Spring_2026

# Project Report: Time Series Analysis of COVID-19 Data and Clustering of MNIST Dataset

## 1. Abstract

This project focuses on the analysis of global COVID-19 data using time series techniques and the application of machine learning clustering methods on the MNIST handwritten digit dataset. The COVID-19 dataset obtained from the World Health Organization (WHO) was processed to study trends in reported cases, deaths, regional distributions, and temporal patterns. Data preprocessing included filtering relevant columns, converting date formats, aggregating data by day and quarter, and generating summary statistics. Additionally, the MNIST dataset was analyzed using the K-Means clustering algorithm to group handwritten digit images into clusters. The performance of the clustering model was evaluated using the F1 Score. The project demonstrates the use of data analytics, time series analysis, and unsupervised machine learning techniques for extracting meaningful insights from large datasets.

## 2. Introduction

The COVID-19 pandemic generated an enormous amount of global health data, making it an ideal case for time series analysis. Understanding the spread of infections across countries and regions helps researchers and policymakers make informed decisions. Time series analysis enables the study of trends, patterns, and variations over time.

In addition to pandemic data analysis, machine learning techniques are increasingly used to discover hidden patterns in data. Clustering is one such unsupervised learning technique. The MNIST dataset, containing handwritten digit images, is widely used for testing machine learning algorithms. In this project, K-Means clustering was applied to group similar digit images, and clustering performance was evaluated using the F1 Score.

## 3. Project Objectives

The main objectives of this project are:

1. To load and preprocess WHO COVID-19 global daily data.
2. To perform data cleaning and datetime conversion for time series analysis.
3. To analyze COVID-19 trends within a specified date range.
4. To identify the most affected countries based on cumulative cases.
5. To calculate daily global COVID-19 cases.
6. To aggregate cases and deaths on a quarterly basis.
7. To examine the distribution of cases across WHO regions.
8. To identify the day with the highest number of new reported cases.
9. To create monthly regional summaries using pivot tables.
10. To apply K-Means clustering on the MNIST dataset.
11. To evaluate clustering performance using the F1 Score.

## 4. Methodology

### 4.1 COVID-19 Data Analysis

The following steps were performed:

* Imported required Python libraries such as Pandas.
* Loaded the WHO COVID-19 global daily dataset.
* Selected relevant columns:

  * Date_reported
  * Country
  * WHO_region
  * New_cases
  * New_deaths
  * Cumulative_cases
* Converted the Date_reported column into datetime format.
* Filtered records between March 2020 and August 2023.
* Grouped data by country to determine the most affected countries.
* Aggregated daily global cases using group-by operations.
* Calculated quarterly totals for new cases and deaths.
* Computed total cases by WHO region.
* Identified the date with the highest number of new cases.
* Created pivot tables for monthly case analysis across regions.

### 4.2 MNIST Clustering Analysis

The following machine learning steps were performed:

* Loaded the MNIST handwritten digit dataset.
* Prepared image data for clustering.
* Applied the K-Means clustering algorithm.
* Assigned data points to clusters based on feature similarity.
* Compared cluster assignments with actual digit labels.
* Evaluated clustering quality using the F1 Score metric.

## 5. Data Analysis and Results

### COVID-19 Analysis Results

* The dataset was successfully cleaned and transformed into a time-series format.
* Analysis identified the countries with the highest cumulative COVID-19 case counts.
* Daily global case trends revealed periods of rapid infection growth and pandemic waves.
* Quarterly aggregation highlighted variations in infection and mortality rates over time.
* WHO regional analysis showed unequal distribution of cases across different regions.
* The day with the highest number of new reported cases was identified through daily aggregation.
* Monthly regional summaries provided a clear comparison of case trends among WHO regions.

### MNIST Clustering Results

* K-Means clustering successfully grouped handwritten digit images into clusters.
* Similar digit patterns were placed within the same clusters.
* The clustering quality was evaluated using the F1 Score.
* Results demonstrated the effectiveness of unsupervised learning in discovering patterns within image datasets.

## 6. Conclusion

This project successfully demonstrated the application of data analysis and machine learning techniques on two different datasets. The COVID-19 time series analysis provided valuable insights into global infection trends, regional distributions, and temporal variations in reported cases and deaths. The MNIST clustering task illustrated how K-Means can be used to group similar data points without labeled training data. Overall, the project highlights the importance of data preprocessing, exploratory analysis, aggregation techniques, and machine learning methods for extracting meaningful information from large real-world datasets.

