# 🛡️ Shield Insurance – Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analysis-blue?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-green?style=for-the-badge)

> 📊 An interactive Power BI dashboard developed to analyze Shield Insurance's revenue, customers, sales channels, policies, and business performance.

---

## 📊 Project Overview

This project is a **Power BI dashboard developed for Shield Insurance** as part of the **Codebasics Data Analytics Virtual Internship**.

The objective of this project was to transform insurance business data into meaningful insights and create an interactive dashboard that helps stakeholders understand business performance and identify areas for improvement.

### 🔍 The dashboard focuses on:

- 💰 Revenue performance
- 👥 Customer growth and distribution
- 📱 Sales channel performance
- 🎯 Customer demographics
- 📋 Policy trends
- 💼 Settlement analysis
- 📈 Daily and monthly growth
- 📊 Business performance KPIs

---

# 🎯 Business Problem

Shield Insurance needed better visibility into its business performance across multiple dimensions.

The dashboard was designed to help stakeholders analyze:

- Sales channels
- Customer segments
- Locations
- Policy types
- Revenue trends
- Customer behaviour
- Growth patterns
- Settlement performance

### 🎯 Objective

Build an interactive dashboard that allows business users to quickly understand:

> **What is happening in the business, where the business is performing well, and where improvement opportunities exist.**

---

# 📌 Dashboard Pages

## 1️⃣ Executive Overview

The Executive Overview provides a high-level view of the company's overall performance.

### 📊 Key Metrics

| KPI | Value |
|---|---:|
| 💰 Total Revenue | ₹989.3M |
| 👥 Total Customers | 26.8K |
| 📈 Revenue Growth | Tracked through DRG |
| 👥 Customer Growth | Tracked through DCG |
| 📅 MoM Analysis | Available |
| 🌍 Geographic Analysis | Available |

### Key Features

- Revenue KPI
- Customer KPI
- Daily Revenue Growth (DRG)
- Daily Customer Growth (DCG)
- Month-over-Month comparison
- Revenue trends
- Customer trends
- Geographic segmentation
- Demographic segmentation

### 📸 Screenshot

![Executive Overview](./Screenshot%202026-09-05%20164225.png)

---

## 2️⃣ Sales Mode Analysis

This page analyzes customer and revenue contribution across different sales channels.

### 📱 Sales Channels

- 👤 Agent
- 📱 App
- 🏢 Direct
- 🌐 Website

### 💡 Key Insights

- **Agent** is the largest contributor to customers and revenue.
- **App** shows strong growth and represents an important digital opportunity.
- Direct and Website channels provide additional opportunities for digital adoption.
- Channel-level analysis helps identify where resources and investments should be focused.

### 📸 Screenshot

![Sales Mode Analysis](./Screenshot%202026-09-13%20200327.png)

---

## 3️⃣ Customer & Revenue Analysis

This section focuses on understanding customer behaviour and revenue contribution.

### Analysis Includes

- Customer distribution
- Revenue contribution
- High-value customer segments
- Sales channel performance
- Customer growth
- Revenue trends

### 📸 Screenshot

![Customer and Revenue Analysis](./Screenshot%202026-09-13%20200353.png)

---

## 4️⃣ Age Group Analysis

The Age Group Analysis provides demographic insights into customer behaviour and business contribution.

### 🔎 Key Insight

The **31–40 age group** represents an important customer segment based on its combination of customer volume, revenue contribution, and policy behaviour.

This insight can help Shield Insurance develop more targeted customer engagement and product strategies.

### 📸 Screenshot

![Age Group Analysis](./Screenshot%202026-09-13%20200414.png)

---

# 💡 Key Business Insights

## 📈 1. Revenue Peak

**March 2023** recorded the highest revenue of approximately **₹264M**, indicating a strong period of business performance.

This creates an opportunity to investigate the factors behind the revenue peak and identify strategies that could be replicated in future campaigns.

---

## 📱 2. Digital Growth Opportunity

The **App channel shows strong growth**, indicating increasing customer adoption of digital channels.

Shield Insurance can focus on:

- Improving the digital customer experience
- Increasing app adoption
- Running targeted digital campaigns
- Encouraging customers to use self-service channels

---

## 👥 3. Core Customer Segment

The **31–40 age group** is an important customer segment with significant business contribution.

Potential strategies include:

- Personalized insurance products
- Targeted offers
- Digital engagement campaigns
- Customer retention programs
- Segment-specific marketing

---

## 🏢 4. Agent Channel Dominance

The **Agent channel** remains the strongest sales channel and represents an important foundation for the business.

At the same time, Shield Insurance can continue developing digital channels to improve scalability and reduce operational dependency.

---

# 🚀 Strategic Recommendations

### 1. 📱 Accelerate Digital Channels

Increase investment in the App, Website, and Direct channels to improve digital customer acquisition and engagement.

### 2. 🎯 Focus on Core Customer Segments

Develop targeted products and campaigns for the **31–40 age group** and other high-performing customer segments.

### 3. 📈 Replicate Successful Performance

Analyze the factors behind the **March 2023 revenue peak** and identify repeatable strategies.

### 4. 🏢 Optimize Sales Channels

Continue strengthening the Agent channel while gradually increasing adoption of digital channels.

---

# 🧮 Technical Implementation

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Visualization**

## 📚 Power BI Concepts Used

- Data cleaning
- Data transformation
- Data modeling
- Star schema
- Table relationships
- Calculated columns
- DAX measures
- Time intelligence
- KPI cards
- Line charts
- Bar charts
- Donut charts
- Slicers
- Interactive filters
- Drill-down analysis

---

# 📐 Key DAX Metrics

The dashboard includes several analytical measures such as:

- Total Revenue
- Total Customers
- Daily Revenue
- Daily Customer Growth
- Revenue Growth %
- Customer Growth %
- Previous Month Revenue
- Previous Month Customers
- Market Share %
- Customer Distribution %
- Revenue Contribution %

### Example DAX

```DAX
Previous Day Revenue =
CALCULATE(
    [Daily Revenue],
    DATEADD(
        dim_date[date],
        -1,
        DAY
    )
)
```

---

# 🗂️ Data Model

The project uses a structured data model consisting of dimension and fact tables.

### Dimension Tables

- `dim_customer`
- `dim_date`
- `dim_policies`

### Fact Tables

- `fact_premiums`
- `fact_settlements`

This structure enables efficient analysis across customers, policies, revenue, dates, and settlements.

---

# 📊 Dashboard Features

- ✅ Interactive Power BI dashboard
- ✅ Revenue KPI tracking
- ✅ Customer KPI tracking
- ✅ Daily growth analysis
- ✅ Month-over-Month analysis
- ✅ Sales channel analysis
- ✅ Customer demographic analysis
- ✅ Age group segmentation
- ✅ Revenue contribution analysis
- ✅ Interactive slicers and filters
- ✅ Time-based analysis
- ✅ Business-focused insights
- ✅ Executive-friendly visualization

---

# 🖼️ Dashboard Screenshots

## Executive Overview

![Executive Overview](./Screenshot%202026-09-05%20164225.png)

## Sales Mode Analysis

![Sales Mode Analysis](./Screenshot%202026-09-13%20200327.png)

## Customer & Revenue Analysis

![Customer and Revenue Analysis](./Screenshot%202026-09-13%20200353.png)

## Age Group Analysis

![Age Group Analysis](./Screenshot%202026-09-13%20200414.png)

---

# 📁 Project Files & Resources

## 📊 Power BI Dashboard File

The complete Power BI dashboard  is included in this repository.

👉 **[View Dashboard](https://lnkd.in/gHb4piR6)**

> ⚠️ **Note:** You need **Microsoft Power BI Desktop** to open the `.pbix` file.

---

## 🎥 Project Presentation

I created a complete walkthrough of the Shield Insurance Power BI project, covering the dashboard, analysis, key insights, and business recommendations.

👉 **[▶️ Watch the Project Presentation](https://drive.google.com/file/d/1Dj0v9QO8AckB1BQBkeSyTvztv-y6_G5Y/view?usp=drive_link)**

---

## 🔗 LinkedIn Project Post

I shared the Shield Insurance Power BI Capstone Project on LinkedIn, including the project walkthrough, dashboard insights, key findings, and recommendations.

👉 **[View the Project Post on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7505209362618101760/)**

---

# 🌐 Project Links

| Resource | Link |
|---|---|
| 📊 Power BI Dashboard | [View Dashboard](https://lnkd.in/gHb4piR6) |
| 🎥 Project Presentation | [Watch Video](https://drive.google.com/file/d/1Dj0v9QO8AckB1BQBkeSyTvztv-y6_G5Y/view?usp=drive_link) |
| 🔗 LinkedIn Project Post | [View LinkedIn Post](https://www.linkedin.com/feed/update/urn:li:activity:7505209362618101760/) |

---

# 📚 Learning Outcomes

Through this project, I strengthened my practical knowledge of:

- Power BI dashboard development
- DAX calculations
- Data modeling
- Power Query
- Business intelligence
- Data visualization
- KPI development
- Time-series analysis
- Customer segmentation
- Business storytelling
- Translating data into actionable insights

---

# 🙏 Acknowledgement

Special thanks to **Dhaval Patel Sir** and **Hemanand Vadivel Sir** for their valuable guidance and mentorship throughout the **Codebasics Data Analytics Virtual Internship**.

---

# 👨‍💻 Author

### Satish Gouni

**Data Analytics | Power BI | DAX | Data Visualization**

This project was developed as part of my learning journey in **Data Analytics and Business Intelligence**.

---

## ⭐ If you found this project useful

Feel free to ⭐ **Star this repository** and connect with me on LinkedIn.

---

### 🏷️ Tags

`Power BI` `DAX` `Data Analytics` `Business Intelligence` `Data Visualization` `Insurance Analytics` `Dashboard` `Codebasics` `Data Science`
