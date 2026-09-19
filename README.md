# FUTURE_DS_02
Customer Retention &amp; Churn Analysis using Excel | Future Interns Data Science &amp; Analytics Internship

## Project Overview

This project was completed as part of the **Future Interns Data Science & Analytics Internship**.

The project focuses on analyzing customer churn and retention patterns for a subscription-based business using **Microsoft Excel**. The analysis examines customer characteristics, subscription details, tenure, service usage, payment methods, and monthly charges to identify observable churn patterns and support data-driven retention recommendations.

The project includes data cleaning, PivotTable analysis, data visualization, and a comprehensive Excel dashboard.

---

## Objectives

The main objectives of this project are to:

- Calculate the overall customer churn rate.
- Identify important customer churn patterns.
- Analyze churn by contract type.
- Analyze customer tenure and lifetime patterns.
- Compare churn across internet service types.
- Analyze churn across payment methods.
- Examine monthly charge segments and churn.
- Compare churn between senior-citizen and non-senior customer segments.
- Identify customer segments with different observed churn levels.
- Provide practical recommendations to support customer retention.

---

## Tools Used

- **Microsoft Excel**
- Excel Tables
- PivotTables
- Data Cleaning
- Data Segmentation
- Data Visualization
- Dashboard Design

---

## Dataset

The project uses a **Telco Customer Churn** dataset containing customer, subscription, service, billing, tenure, and churn information.

- **Total customer records:** 7,043

---

## Data Cleaning & Preparation

The following data preparation steps were performed:

- Converted the dataset into an Excel Table named `CustomerData`.
- Checked `customerID` for duplicate records.
- No duplicate customer IDs were found.
- Identified 11 blank values in the `TotalCharges` column.
- Replaced the blank `TotalCharges` values with 0.
- Created `TenureGroup` categories for customer lifetime analysis.
- Organized the cleaned data for further PivotTable and dashboard analysis.

---

## Analysis Performed

### 1. Overall Churn Analysis

The overall customer churn rate was calculated using the customer-level data.

| Metric | Result |
|---|---:|
| Total Customers | 7,043 |
| Churned Customers | 1,869 |
| Overall Churn Rate | 26.54% |

---

### 2. Churn Rate by Contract Type

Churn was analyzed across different contract types.

| Contract Type | Churn Rate |
|---|---:|
| Month-to-month | 42.71% |
| One year | 11.27% |
| Two year | 2.83% |

The analysis shows different observed churn levels across contract types, with month-to-month customers recording the highest churn rate in this dataset.

---

### 3. Customer Tenure & Lifetime Analysis

Customers were grouped into tenure ranges to examine customer lifetime patterns and churn.

The analysis uses tenure groups because the dataset does not contain a customer signup date or signup month. Therefore, artificial signup-month cohorts were not created.

---

### 4. Churn Rate by Internet Service

Customer churn was compared across different internet service categories to identify differences in observed churn patterns between service segments.

---

### 5. Churn Rate by Payment Method

Customer churn was analyzed across different payment methods to identify variations in churn rates between payment segments.

---

### 6. Churn Rate by Monthly Charges

Customers were grouped into monthly charge ranges to examine differences in observed churn levels.

The **80–100 monthly-charge range** recorded the highest observed churn rate at **36.91%**.

---

### 7. Churn Rate by Senior Citizen Status

Churn was compared between:

- Senior-citizen customers
- Non-senior customers

This provides an additional customer segmentation perspective for retention analysis.

---

## Key Insights

- The overall customer churn rate is **26.54%**, with **1,869 out of 7,043 customers** having churned.
- Month-to-month customers recorded a **42.71% churn rate**, compared with **11.27%** for one-year contracts and **2.83%** for two-year contracts.
- Churn varies across monthly-charge ranges, with the **80–100 range** recording the highest observed churn rate at **36.91%**.
- Customer tenure shows different churn patterns, highlighting the importance of monitoring retention throughout the customer lifecycle.
- Churn rates vary across internet service types and payment methods.
- Senior-citizen and non-senior customer segments show different observed churn patterns.

---

## Practical Recommendations

Based on the observed patterns in the analysis, the following retention actions can be considered:

1. **Encourage suitable month-to-month customers to consider longer-term contracts** through relevant offers and benefits.

2. **Provide early-stage engagement and support** for newer customers to strengthen retention during the early customer lifecycle.

3. **Review higher monthly-charge segments** to better understand pricing, service value, and customer support needs.

4. **Use customer segmentation** to identify higher-churn groups and provide targeted retention support.

5. **Monitor churn patterns regularly** across contract type, tenure, service type, payment method, and customer segments.

---

## Dashboard

The completed Excel dashboard contains:

- Total Customers KPI
- Churned Customers KPI
- Overall Churn Rate KPI
- Churn Rate by Contract Type
- Churn Rate by Customer Tenure
- Churn Rate by Internet Service
- Churn Rate by Payment Method
- Churn Rate by Monthly Charges
- Churn Rate by Senior Citizen Status
- Key Insights
- Practical Recommendations

### Dashboard Preview

![Customer Retention & Churn Dashboard](Customer_Retention_Churn_Dashboard.png)

---

## Project Files

| File | Description |
|---|---|
| `Customer_Retention_Churn_Analysis.xlsx` | Complete Excel analysis, PivotTables, charts, and dashboard |
| `Customer_Retention_Churn_Dashboard.png` | Preview of the completed customer retention and churn dashboard |
| `README.md` | Project documentation |

---

## Data Limitation

The dataset contains a `Churn` field but does not contain a dedicated field describing specific reasons for customer churn.

Therefore, this project focuses on **observed churn patterns and customer segments** rather than assigning specific causes to customer churn.

Similarly, because signup dates are not available, **tenure-based groups** were used for customer lifetime analysis instead of creating artificial signup-month cohorts.

---

## Conclusion

This analysis provides a structured view of customer churn patterns using Excel. The dashboard brings together key churn metrics, customer segmentation analysis, visualizations, and practical retention recommendations to support data-driven decision-making.
