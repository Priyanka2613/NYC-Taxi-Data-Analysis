# NYC Taxi Data Analysis | Python & Pandas

## Project Overview

This project explores New York City taxi trip data as part of the **Google Advanced Data Analytics Professional Certificate – Automatidata Project** on Coursera.

The objective is to inspect the dataset, identify patterns in taxi trips, investigate unusual values, and prepare findings that could support future predictive modeling for the New York City Taxi and Limousine Commission (NYC TLC).

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Data Inspection and Filtering

## Dataset Information

The dataset contains **22,699 taxi trip records and 18 columns**.

Key variables include:

- `trip_distance` — Distance traveled in miles
- `fare_amount` — Base fare charged
- `total_amount` — Total trip charge
- `tip_amount` — Recorded tip amount
- `payment_type` — Customer payment method
- `passenger_count` — Number of passengers
- `VendorID` — Taxi service provider identifier

## Exploratory Data Analysis

The analysis includes:

1. Inspecting dataset structure, data types, and missing values.
2. Examining descriptive statistics and variable distributions.
3. Identifying unusual trip distances and fare amounts.
4. Comparing credit card and cash payment records.
5. Analyzing trip counts and average charges by vendor.
6. Calculating average recorded tips by passenger count.

## Key Findings

### 1. Trip Distance

- Average trip distance: **2.91 miles**
- Median trip distance: **1.61 miles**
- Maximum recorded distance: **33.96 miles**

The distribution is right-skewed, indicating that most trips are relatively short, while some trips cover considerably longer distances.

### 2. Fare and Total Amount

- Average fare amount: approximately **$13.03**
- Minimum recorded fare: **-$120.00**
- Minimum recorded total amount: **-$120.30**

Negative and zero charges require further investigation to distinguish legitimate adjustments from potential data quality issues.

### 3. Payment Methods

| Payment Method | Number of Trips |
|---|---:|
| Credit Card | 15,265 |
| Cash | 7,267 |
| No Charge | 121 |
| Dispute | 46 |

- Average recorded credit card tip: **$2.73**
- Average recorded cash tip: **$0.00**

Cash tips may not be captured in the dataset, so the recorded average should not be interpreted as proof that cash passengers never tip.

### 4. Vendor Comparison

| Vendor | Number of Trips | Average Total Amount |
|---|---:|---:|
| Vendor 1 | 10,073 | $16.30 |
| Vendor 2 | 12,626 | $16.32 |

Both vendors have similar average total trip charges.

### 5. Passenger Count and Tips

For credit card transactions, average recorded tip amounts vary slightly by passenger count, ranging from approximately **$2.61 to $2.83**.

## Recommendations

Before developing predictive models:

- Investigate negative and zero fare values.
- Examine unusually long taxi trips.
- Convert pickup and drop-off timestamps into datetime format.
- Evaluate potential outliers.
- Explore relationships between trip distance, duration, fare amount, and total charges.

## Conclusion

This project demonstrates foundational skills in Python-based exploratory data analysis, data inspection, filtering, grouping, and interpreting descriptive statistics.

Trip distance is a potentially useful predictor of taxi fares, while total amount could serve as the target variable for a fare prediction model, depending on the modeling objective.

## Project Notebook

The complete Jupyter Notebook containing the analysis, Python code, and results is available in this repository.

## Acknowledgment

Completed as part of the **Google Advanced Data Analytics Professional Certificate** on Coursera, using the Automatidata educational project scenario.

## Author

**Priyanka Rajangale**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

[LinkedIn](https://www.linkedin.com/in/priyanka-rajangale/)
