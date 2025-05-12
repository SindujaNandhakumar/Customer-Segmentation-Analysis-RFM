# 🏍️ Customer Segmentation & Revenue Analysis for an Automobile Bike Company

## 📊 Overview

This project focuses on Customer Segmentation for an automobile bike company using the RFM (Recency, Frequency, Monetary) model — a behavior-based technique that segments customers based on how recently, how often, and how much they purchase (RFM-RECENCY,FREQUENCY,MONETARY). Customers were grouped into 11 distinct segments to better understand their buying behavior.

The goal of this analysis is to identify key customer segments that can be targeted to boost sales and improve marketing strategies. The project includes data cleaning and analysis using Python, and the insights are visualized through an interactive Tableau sales dashboard.

## 📁 Datasets Used

The analysis was performed using the following datasets:

* **`Raw_data.xlsx`**: A consolidated file containing multiple sheets of customer-related data.
* **`Transactions_data.xlsx`**: Records of all customer transactions across various states in Australia.
* **`NewCustomerList.xlsx`**: Details of recently acquired customers.
* **`CustomerDemographic.xlsx`**: Demographic data including gender, age, wealth segment, and industry.
* **`CustomerAddress.xlsx`**: Location and address information of customers.

---

## 🧼 Analysis Approach

### 1. Data Quality Assessment & Cleaning

* Checked for missing values, duplicates, and inconsistencies.
* Performed transformations and standardizations to ensure data readiness for analysis.

### 2. Exploratory Data Analysis (EDA)

* **Age Distribution**: New customers are primarily aged 50–59, while older customers peak at 40–49.
* **Gender**: Female customers show slightly higher engagement.
* **Industry**: Finance, Manufacturing, and Health dominate customer base.
* **Wealth Segment**: Majority of customers belong to the Mass Market segment.

---

## 📈 RFM Analysis & Customer Segmentation

Customer segmentation was performed using **RFM (Recency, Frequency, Monetary)** modeling — a behavioral technique based on past purchase activity. Customers were grouped into the following 11 segments:

* Platinum Customers
* Very Loyal Customers
* Recent Customers
* Potential Customers
* Lost Customers
* Losing Customers
* Late Bloomers
* High Risk Customers
* Evasive Customers
* Becoming Loyal
* Almost Lost Customers

### Key Visual Insights:

* **Recency vs. Monetary**: Customers with recent purchases (within 0–50 days) generate the highest revenue. Those with purchase gaps of 250+ days contribute the least.
* **Frequency vs. Monetary**: A positive correlation observed — frequent buyers significantly boost revenue.

---

## 💡 Insights from Revenue by Segment

* **Top Revenue Contributors**: Platinum, Very Loyal, Recent, and Potential Customers — due to their consistent engagement.
* **Unexpected Finding**: **Losing Customers** (at risk of churn) generate more revenue than even the Platinum segment — signaling urgency for re-engagement.
* **Almost Lost Segment**: Though currently inactive, these customers display high past value and can be reactivated with targeted efforts.

---

## ✅ Strategic Recommendations

* Prioritize **retention strategies** for **Losing** and **Almost Lost** customer segments to prevent revenue loss.
* Maintain strong engagement with **Platinum** and **Very Loyal** customers to reinforce loyalty and sustained value.
* Use personalized communication, targeted promotions, and loyalty programs to move customers up the value chain.

---

## 📌 Tools Used

* Microsoft Excel
* Python (Data Cleaning ,Analysis & Visualization)
* Tableau (Visual Analysis)

## Tableau

![image](https://github.com/user-attachments/assets/4a01a8d8-f884-45d9-a966-d27085c40911)


  

