📊 Meta Ad Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

> Comprehensive analysis of **44 campaigns** across Facebook & Instagram platforms | Campaign Period: **May – August 2025**

---

🧾 Project Overview

This Power BI dashboard transforms raw Meta advertising data into actionable business intelligence. It delivers a modern, interactive analytics experience inspired by Meta's design language — enabling marketers and analysts to track performance, compare platforms, and optimise campaign strategy at a glance.

A total budget of **$2.5M** was analysed across **339,812 impressions**, **25,400 clicks**, and **1,300 purchases**, with an overall CTR of **11.76%** and a conversion rate of **5.21%**.

---

📸 Dashboard Preview

| Facebook View | Instagram View |
|---|---|
| ![Facebook](./screenshots/facebook.png) | ![Instagram](./screenshots/instagram.png) |

| Campaign & Ad Performance | Executive Summary |
|---|---|
| ![Campaign](./screenshots/campaign.png) | ![Summary](./screenshots/summary.png) |

---

✨ Key Features

🔢 KPI Tracking
- Real-time KPI cards: Impressions, Clicks, Shares, Comments, Purchases, Engagements
- Derived metrics: CTR, Conversion Rate, Engagement Rate, Purchase Rate
- Platform-level budget breakdown (Facebook vs Instagram)

### 📈 Performance Visualisations
- Weekly & hourly impression trend charts
- Purchases by ad type (Carousel, Stories, Video, Image) with monthly trend lines
- Conversion funnel from Impression → Click → Like → Comment → Purchase → Share
- Budget vs Purchases scatter plot for ROI analysis

### 🌍 Geographic & Demographic Breakdown
- Impressions by country (interactive Bing Maps)
- Gender and age-group segmentation for both platforms
- Monthly calendar heatmap for day-level performance

### 🎛️ Dynamic Filtering
- Platform slicer: Facebook / Instagram
- Campaign Name filter
- Target Interest filter
- Ad Type filter
- Dynamic measure selector (switch chart metric on the fly)

---

## 🛠️ Technical Highlights

### DAX Measures
- Custom CTR, Conversion Rate, Engagement Rate, Purchase Rate calculations
- Budget per campaign and average budget per click
- Platform-specific aggregations with CALCULATE + FILTER patterns
- Dynamic measure switching using SWITCH(SELECTEDVALUE(...))

### Power Query (ETL)
- Multi-source data consolidation
- Data type standardisation and null handling
- Date table generation for time-intelligence functions
- Column renaming and conditional column transformations

### Data Modelling
- Star schema design with fact and dimension tables
- Relationships across campaigns, ad types, platforms, and time dimensions
- Bidirectional filtering where appropriate

---

## 📊 Key Findings

| Metric | Facebook | Instagram |
|---|---|---|
| Impressions | 215,972 | 123,840 |
| Clicks | 25,389 | 14,690 |
| CTR | 11.76% | 11.86% |
| Purchases | 1,323 | 708 |
| Conversion Rate | 5.21% | 4.82% |
| Total Budget | $2.19M | $2.01M |

- 🏆 **Best ROI campaign**: Campaign_42_Summer — 67 purchases on a $7,918 budget ($118/purchase)
- 📉 **Worst ROI campaign**: Campaign_20_Winter — 73 purchases on a $98,905 budget
- 🥇 **Top ad type**: Stories — highest purchase rate (5.34%) across all months
- 📅 **Peak purchases**: July 2025 (696 purchases), followed by a sharp drop in August

---

## 📁 Project Structure

```
meta-ad-dashboard/
├── MetaAdDashboard.pbix       # Main Power BI file
├── data/
│   └── meta_ads_raw.xlsx      # Source dataset
├── screenshots/
│   ├── facebook.png
│   ├── instagram.png
│   ├── campaign.png
│   └── summary.png
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/meta-ad-dashboard.git
   ```
2. Open `MetaAdDashboard.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `data/meta_ads_raw.xlsx`
4. Click **Refresh** to load the data
5. Explore using the slicers on the right panel

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development & publishing |
| DAX | Custom measures & calculated columns |
| Power Query (M) | Data transformation & ETL |
| Microsoft Excel | Source data preparation |
| Bing Maps | Geographic visualisation |

---

## 🤝 Connect

If you found this project useful or have questions, feel free to connect on [LinkedIn] (https://www.linkedin.com/in/ayesha-sana-3908a130b?utm_source=share_via&utm_content=profile&utm_medium=member_android)or open an issue.

---

*Built with 💙 using Power BI | Data period: May–August 2025*# dashboard
