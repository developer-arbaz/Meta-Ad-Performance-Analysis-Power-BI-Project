# 📊 Meta Ad Performance Analysis Dashboard (Power BI)

## 🧾 Project Overview
The **Meta Ad Performance Dashboard** is a data-driven Power BI project that analyzes advertising campaigns running on **Facebook and Instagram**.  
It provides complete visibility into campaign reach, engagement, conversion performance, and budget utilization — enabling better marketing decisions and ROI optimization.

---

## 🎯 Business Objective
The goal of this project is to help the marketing team:
- Identify which **platform (Facebook or Instagram)** performs better.
- Track **funnel performance** from impressions → clicks → purchases.
- Analyze **audience engagement patterns** by gender, age, country, and time.
- Optimize **budget allocation** for high-performing ads and ad types.

---

## 📂 Dataset Information
This dataset simulates real-world Meta advertising data with four key tables:

| Table Name | Description |
|-------------|--------------|
| **ad_events** | Fact table – stores all user interactions like impressions, clicks, comments, and purchases. |
| **ads** | Contains ad details such as platform, ad type, target age, gender, and interests. |
| **campaigns** | Holds campaign-level information like name, duration, and total budget. |
| **users** | Includes demographic and location data of users interacting with ads. |

---

## 🧮 KPIs & Metrics
| KPI | Definition | Formula |
|-----|-------------|----------|
| **Impressions** | Number of times ads were displayed | Count of event_type = Impression |
| **Clicks** | Number of times users clicked ads | Count of event_type = Click |
| **Engagements** | Clicks + Shares + Comments | (Clicks + Shares + Comments) |
| **CTR (Click-Through Rate)** | % of impressions that led to clicks | (Clicks ÷ Impressions) × 100 |
| **Engagement Rate** | % of impressions that resulted in engagement | (Engagements ÷ Impressions) × 100 |
| **Conversion Rate** | % of clicks that led to purchases | (Purchases ÷ Clicks) × 100 |
| **Total Budget** | Total allocated spend | SUM(campaigns.total_budget) |

---

## 📈 Dashboard Features
The Power BI dashboard includes multiple interactive visuals:

1. 🧍 **Target Gender – Donut Chart**  
   Compare engagement by male vs female audiences.
2. 👶 **Age Group – Bar Chart**  
   Track engagement and conversions by age group.
3. 🌍 **Country – Map Visualization**  
   Identify top-performing regions by metric.
4. 📅 **Calendar Month – Heat Map**  
   Detect seasonal trends and peak campaign months.
5. 📊 **Weekly Trend – Stacked Column Chart**  
   Compare ad type performance over weeks.
6. ⏰ **Hourly Trend – Area Chart**  
   Discover peak hours for user activity.
7. 🎥 **Ad Type – Matrix View**  
   Compare performance across ad formats and platforms.

---

## 🔍 Key Insights
- **High CTR (11.7%)** indicates strong creative engagement.  
- **Engagement Rate (13.5%)** is excellent, but **conversion efficiency (5%)** suggests a drop-off post-click.  
- **Females (43%) and users aged 18–30** show the strongest engagement.  
- **Video and Story ads** outperform other formats.  
- **Evening hours** drive maximum engagement.

---

## 🧰 Tools & Technologies Used
- **Power BI** – Data cleaning, modeling, DAX calculations, visualization  
- **Excel / CSV files** – Data source  
- **DAX Measures** – For dynamic KPI calculations  
- **Data Modeling** – Star schema design (Fact + Dimensions)

---

## 📘 Learnings & Takeaways
- Building an end-to-end marketing analytics dashboard from raw data  
- Creating calculated columns and measures using DAX  
- Using filters, slicers, and parameters for interactivity  
- Presenting business insights using clear data storytelling

---

## 📸 Dashboard Preview
> *(Insert your Power BI Dashboard screenshot here)*  
> Example:  
> ![Meta Ad Dashboard]([./Meta Ad Performance Dashboard.png)

---

## 🧑‍💻 Developed by
**Arbaz Khan**  
📍 Data Analyst | SQL | Power BI | Excel | Python  
🔗 [LinkedIn](https://www.linkedin.com/in/arbaz-data-analyst/) | [GitHub](https://github.com/developer-arbaz) | [Portfolio](https://developer-arbaz.github.io/developerarbaz.github.io/)

---

⭐ *If you found this project insightful, don’t forget to star this repo!*
