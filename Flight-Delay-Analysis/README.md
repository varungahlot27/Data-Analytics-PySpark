# Flight Delay Analysis

This project analyzes a large dataset of domestic flight records using **PySpark**.

The objective is to explore flight delays, departure patterns, airtime, and arrival performance using PySpark filtering, aggregation, counting, averaging, and maximum-value operations.

## Project Overview

The dataset contains domestic flight records with information including:

- Flight date
- Departure delay
- Arrival delay
- Air time
- Flight distance
- Departure time
- Arrival time

The analysis answers five business-oriented questions related to flight operations and delays.

## Key Analysis

### 1. Early Arrivals
Identified the number of flights that arrived earlier than expected.

**Result:** 534,655 flights

### 2. Typical Departure Time for Long-Distance Flights
Calculated the average departure time for flights traveling more than 2,000 miles.

**Result:** Approximately 1:58 PM

### 3. Arrival Delays Longer Than 60 Minutes
Calculated the proportion of flights experiencing an arrival delay of more than 60 minutes.

**Result:** Approximately 5.31%

### 4. Average Airtime Before 9:00 AM
Calculated the average airtime for flights departing before 9:00 AM.

**Result:** Approximately 111.36 minutes

### 5. Maximum Arrival Delay With No Departure Delay
Found the maximum arrival delay among flights that had no departure delay.

**Result:** 232 minutes

## Technologies Used

- Python
- PySpark
- Apache Spark
- Google Colab

## Skills Demonstrated

- Data loading
- Data exploration
- Data filtering
- Aggregation
- Statistical calculations
- Reusable PySpark functions
- Working with large datasets
- Analytical problem solving

## Project Files

- [Flight Delay Analysis Notebook](./Flight_Delay_Analysis.ipynb)

## Key Takeaway

This project demonstrates the practical use of PySpark to process and analyze a large flight dataset and convert operational questions into reproducible analytical functions and measurable results.
