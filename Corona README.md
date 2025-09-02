COVID-19 Data Analysis using SQL

📌 Project Overview</u>

This project explores the COVID-19 dataset using SQL queries to extract insights on confirmed cases, deaths, and recoveries across countries and time periods.
The dataset contains 78,386 rows covering the period from 22-Jan-2020 to 13-Jun-2021 (18 months).

The analysis focuses on:

Data quality checks (nulls, missing values, duplicates)

Temporal trends (monthly/yearly cases)

Country-level comparisons

Statistical measures (mean, variance, standard deviation)

Key insights into the pandemic spread

🗂 Dataset Details

Key fields:

Province

Country_Region

Latitude, Longitude

Date

Confirmed, Deaths, Recovered

🔎 SQL Analysis & Insights

1. Data Quality Check

Null Values: Checked across all columns → No null values found.

Total Rows: 78,386 records.

2. Time Coverage

Start Date: 22-Jan-2020

End Date: 13-Jun-2021

Total Months Covered: 18

3. Aggregations & Trends

Monthly Averages: Calculated for Confirmed, Deaths, Recovered.

Frequent Values: Identified months in 2020 with the most recurring cases (Apr, Jun, Sep, Nov).

Min/Max per Year: Derived yearly minimum and maximum values for Confirmed, Deaths, and Recovered.

Total Monthly Cases: Summed Confirmed, Deaths, Recovered per month.

4. Statistical Measures

For Confirmed, Deaths, and Recovered cases, calculated:

Total

Average

Variance

Standard Deviation

5. Country-Level Insights

Highest Confirmed Cases: USA, followed by India, Brazil, France.

Lowest Death Cases: Identified countries with minimal reported deaths.

Top 5 Countries by Recoveries: Listed nations with the maximum recovery counts.

📊 Key Findings

No missing values in the dataset → clean and reliable.

USA leads in confirmed cases, followed by India and Brazil.

Some countries reported very low death counts despite active cases.

Recovered cases are highest in USA, India, and Brazil.

The pandemic showed seasonal patterns with spikes in certain months.

<u>🛠 Tools & Technologies</u>

SQL (BigQuery / MySQL)

Dataset: COVID-19 global cases data

Presentation: PowerPoint (insights summarized)

📌 Conclusion

This SQL-based analysis provides a comprehensive view of COVID-19 spread across the globe.
By leveraging aggregations, statistics, and country-level comparisons, the project highlights the impact of the pandemic, supporting further research and policy decision-making.
