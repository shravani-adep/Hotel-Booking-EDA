# Hotel Booking Demand Analysis (EDA)

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on a hotel booking dataset to uncover customer behavior, booking patterns, cancellation trends, revenue insights, and factors influencing hotel performance.

The analysis focuses on transforming raw booking data into meaningful business insights through data cleaning, feature engineering, statistical exploration, and visual storytelling using Python.

---

## Dataset Information

The dataset contains booking information for hotel reservations, including:

* Hotel type
* Lead time
* Arrival dates
* Customer demographics
* Market segments
* Booking status
* Average Daily Rate (ADR)
* Stay duration
* Reservation information

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Data Preparation

The following preprocessing steps were performed:

### Data Type Analysis

* Inspected column data types
* Converted date columns into datetime format
* Corrected inappropriate numeric data types

### Missing Value Analysis

* Identified missing values
* Investigated missing patterns in agent, company, and children columns

### Duplicate Analysis

* Checked duplicate records
* Documented duplicate observations before proceeding with analysis

### Outlier Analysis

* Investigated extreme values using box plots
* Examined ADR distribution and booking-related numerical variables

---

## Exploratory Data Analysis

### Booking Behavior Analysis

* Lead Time Distribution
* Hotel Type Distribution
* Market Segment Share

### Customer Insights

* Top Booking Countries
* Average Group Size by Country
* Total Guests by Country

### Cancellation Analysis

* Overall Cancellation Percentage
* Hotel Type vs Cancellation
* Lead Time vs Cancellation

### Revenue Analysis

* Revenue by Hotel Type
* Monthly Revenue Trend
* Monthly Revenue Trend by Hotel

### Correlation Analysis

* Correlation Heatmap
* ADR vs Group Size by Hotel

### Reservation Analysis

* Reservation Status Distribution

---

## Conclusion

This project demonstrates the use of Exploratory Data Analysis to transform hotel booking data into actionable business insights. Through statistical analysis and visualization, key drivers of customer behavior, cancellations, revenue generation, and booking patterns were identified, providing valuable information for hotel management and decision-making.
