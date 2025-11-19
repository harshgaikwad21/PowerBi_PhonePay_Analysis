# PowerBi_PhonePay_Analysis

## Tool Used :

![power_bi](https://up.yimg.com/ib/th/id/OIP.qAwpaT7q385MhQTQi-9IagHaHa?pid=Api&rs=1&c=1&qlt=95&w=118&h=118)

![phone_pay](https://wallpapercave.com/wp/wp13954584.jpg)
## 🚀 PhonePe Payment Insights – Power BI Dashboard 

A comprehensive analytics dashboard built using Power BI, designed to visualize trends, patterns, and performance indicators related to PhonePe transactions across different metrics. This dashboard provides business-ready insights to support decision-making through interactive pages and drill-down visuals.

## 🔍 Project Overview

This Power BI project analyzes PhonePe’s digital payments ecosystem using interactive visuals and KPI cards.
The .pbit template includes predefined pages, theme colors, visuals, and structured data models to enable users to load their own dataset and instantly generate insights.

## 🧩 Key Features

## 📊 Multi-Page Dashboard

The template contains multiple report pages (as seen in the project structure), each focused on different analytical dimensions:


- Overview Page – High-level KPIs, growth trends, and summary cards

- Transactions Analysis – Volume, value, and categorical breakdown

- Geographical Insights – State-wise and district-wise performance

- Category Performance – Recharge, bill-payments, P2P, merchant payments

- User Demographics (if data is provided)

- Branding & Visual Identity Page – PhonePe themed colors and assets

## 📈 Analytics Covered
## KPIs Included

- Total Transactions

- Total Transaction Value

- Average Transaction Size

- YoY / MoM growth

- Category-wise contribution

- Trend deviation indicators

## Visual Types Used

- Line Charts for trends

- Donut & Pie charts for category contribution

- Map visuals for state/district analysis

- Cards with conditional formatting

- Bar charts with hierarchies

- Info-graphics supported by image URL bindings

## 🎨 Visual & Theme Customizations

The template uses a consistent visual theme aligned with PhonePe branding:

- Primary Color: #5F259F (PhonePe Purple)

- Accent colors for categories and regions

- Clean, minimal layout with focus on clarity

- Multiple pages include branded assets via image URLs

## 🧱 Data Model Overview

Although the template loads data dynamically, it is structured to support:

- Fact table for transactions

- Date table with hierarchy

- Lookup tables (Category, Geography)

- Relationship-based model optimized for cross-filtering

## Loans

<img width="1309" height="742" alt="loan" src="https://github.com/user-attachments/assets/f0f157af-7e7d-406d-b11b-7c5f1b0812f4" />

## 📌 Dashboard Insights (Loans)

- **Total Loan Amount**: ₹2.53 billion, with an **average loan size** of ₹50.65K and a **maximum loan** of ₹100K.

- **Loan Type Trend**:

     - **Auto Loan** has the highest loan amount (~644M).

     - Followed by **Mutual Fund (634M), Gold Loan (632M)**, and **Credit Score loans (622M)**.

     - Overall trend shows a **steady decline** across categories.

- **Payment Status**:

     - Majority of loan payments are **Successful**, with **Failed** payments making up only a small proportion.

- **Monthly Activity**:

     - Payment activity fluctuates between **4,000–4,400** counts per month.

     - **July and October** show noticeable peaks.

- **Filters Available**: Reasons such as Bank Denied, Server Error, Successful, and Wrong Info can be applied for deeper analysis.

## Insurance

<img width="1312" height="738" alt="insurance" src="https://github.com/user-attachments/assets/0b064b75-9c23-46cf-9e2e-87839f9f6a2a" />

## 📌 Dashboard Insights (Insurance)

- **Total Premium Collected**: ₹512.92M

- **Average Premium by Insurance Type**: ₹128.86M per category.

- **Insurance Type Performance**:

    - **Car Insurance** leads with ~₹129.3M.

    - **Term Life, Bike**, and **Health** follow closely, each contributing around ₹126M–₹128M.

    - All categories show a **balanced distribution**, with no major dominance.

- **Monthly Premium Trend**:

    - Premium collection remains **consistent across all months**, generally around **₹40M–₹45M** each month.

    - **July, August, and December** show slightly higher premium values.

- **Category Distribution**:

    - Insurance types contribute almost **equally**, indicating a **well-diversified premium portfolio**.
## Money Transfer

<img width="1310" height="737" alt="Money_transfer" src="https://github.com/user-attachments/assets/1fc8b477-8401-4465-b4cb-e2f09e27bb45" />

## 📌 Dashboard Insights (Money Transfer)

- **Total Transactions Amount:** ₹362.95M, indicating high digital payment activity.
 
- **Average Transaction Amount:** ₹2.52K, showing moderate-value transfers dominate usage.
 
- **Popular Transfer Types:** UPI ID and Mobile Number transfers show the highest share in both amount and transaction count.
 
- **Monthly Activity:** Transaction counts remain consistently high across all months, with no major seasonal dips.

- **Transfer Patterns:**
 
  - *To UPI ID* and *To Mobile Number* contribute significantly to overall transaction volume.
    
  - *To QR Code* and *To Self Account* have comparatively lower usage.

- **Overall Trend:** Steady payment flow across the year with balanced distribution among major transfer types.



## Recharge Bills

<img width="1309" height="736" alt="Recharge_bills" src="https://github.com/user-attachments/assets/79503ec0-958d-4472-9222-8a70a0f4177a" />

## 📌 Dashboard Insights (Recharge & Bills)

🔹 **Overall Transactions**

- **Total Amount Processed: ₹50.69M**

- **Earliest Transaction Date: 01 January 2024**

🔹 **Monthly Trend**

- Monthly totals range around **₹41M–₹43M**, showing **stable transaction volume**.

- **May** recorded the **highest amount (₹43.49M)**, indicating slight growth.

🔹 **Recharge Type & Reason**

- **Successful recharges dominate** with each success category contributing around **24%**.

- **Failure reasons** such as Wrong PIN, Insufficient amount, and Wrong details collectively form a very small percentage (<1%), indicating good transaction success rate.

🔹 **Recharge Type Distribution**

- Top recharge categories include:

    - **Electricity Bill**

    - **Cable TV**

    - **Mobile Recharge**

    - **DTH**

🔹 **Cumulative Monthly Growth**

- A steady **month-on-month increase** is visible, indicating consistent user activity and transaction frequency.

## 🛠️ How to Use This Template (.pbit)

1. Open the .pbit file in Power BI Desktop

2. When prompted, load your dataset (CSV, SQL, Excel, API, etc.)

3. Map fields based on:

    - Transaction Amount

    - Transaction Count

    - Category

    - State / District

    - Date

4. Refresh the dashboard to generate insights

5. Publish to Power BI Service (optional)

## 📌 Use Cases

- Digital payments trend analysis

- Business intelligence for fintech

- Geographic penetration insights for product teams

- Merchant/consumer behavior analysis

- Stakeholder reporting and presentations

## 🚧 Future Enhancements (Recommended)

- Add DAX-based anomaly detection

- Implement forecasting for transactions

- Integrate advanced tooltips for richer drilldowns

- Add RLS (Row Level Security) for enterprise sharing
