https://docs.google.com/spreadsheets/d/e/2PACX-1vTuekmJd59OJS6YR7HDrp9-vgugHrU5JcJJkz3S3T2sSl0UAXlVG_Mr1oPykqI7eD8mjsqMhAOeoZKj/pubhtml
# 🍕 Food Delivery Optimization Analysis

## 📌 Project Overview
**The "So What?":** I identified specific pickup bottlenecks that, if resolved, could reduce average delivery times by 15% and significantly boost customer retention.

---

## 📖 Table of Contents
* [Background](#-background)
* [Methodology](#-methodology)
* [Tools Used](#-tools-used)
* [Key Findings](#-key-findings)
* [Raw Data](#-raw-data)

---

## 🔍 Background
The food delivery industry operates on thin margins where every minute counts. This project analyzes the "order-to-door" pipeline to identify why certain deliveries exceed the promised time and how order volume fluctuates across different city zones.

## 🛠️ Methodology
1.  **Data Cleaning:** Processed raw CSV files using **SQL** to handle null values in delivery timestamps and normalize restaurant categories.
2.  **Exploratory Data Analysis (EDA):** Analyzed over 10,000+ rows of delivery data to find correlations between weather, traffic, and delivery speed.
3.  **Performance Metrics:** Defined KPIs including:
    *   **ADT:** Average Delivery Time.
    *   **OTD:** On-Time Delivery % per driver.
    *   **Churn Rate:** Correlation between late deliveries and customer re-order frequency.
4.  **Visualization:** Designed a multi-page **Tableau** dashboard for stakeholders to filter performance by region and time of day.

## 🛠️ Tools Used
*   **Excel:** Initial data auditing and quick pivot tables.

## 📈 Key Findings
*   **Pickup Bottlenecks:** 40% of delivery delays occurred during the "waiting for restaurant" stage, rather than actual transit time.
*   **Peak Demand:** Weekend dinner rushes (6 PM - 9 PM) account for 65% of revenue but show a 20% increase in customer complaints.
*   **Loyalty Factor:** Customers who experience an under-30-minute delivery are **3x more likely** to place a second order within 7 days.

## 📂 Raw Data
You can find the datasets used for this analysis in the `/data` folder of this repository. 
*   *Note: All personally identifiable information (PII) has been removed/anonymized.*

---

## 🛠️ How to Use This Repo
1. **SQL Scripts:** Check the `/scripts` folder to see how the data was joined and cleaned.
2. **Analysis:** Open the `/reports` folder for the full executive summary.
