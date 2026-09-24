# 📊 Payment Insights Dashboard

A Power BI dashboard that visualizes transaction activity, user behavior, and revenue breakdown for a digital payments platform — built for clarity, speed, and at-a-glance decision-making.

<img width="893" height="488" alt="image" src="https://github.com/user-attachments/assets/437f65ce-ff1c-4db9-9d7d-2ee3d75e3064" />

## 🔍 Overview

This dashboard delivers a single-pane view of platform health: transaction volume, transaction value, active users, and success rate, alongside deeper cuts by time, age segment, service type, and top users.

## ✨ Features

- **KPI Summary Cards** — Total Transactions, Total Value, Unique Users, and Success Rate, each with month-over-month change
- **Transactions Over Time** — dual-axis trend line comparing transaction count vs. transaction value across the year
- **Age Segment Contribution** — donut breakdown of transaction share by generation (Gen X, Gen Z, Millennials, Boomers)
- **Service Transaction Value Analysis** — horizontal bar comparison across service categories (Loans, Insurance, Money Transfer, Recharge & Bills)
- **Top 5 Users** — ranked bar chart by transaction value
- **Weekday vs. Weekend Usage** — donut split of transaction activity by day type
- **Insights Panel** — auto-surfaced highlights (e.g. top-contributing segment, top-performing service)
- **Filters** — Month selector and Payment Status filter (Failed / Pending / Successful)

## 🛠️ Tech Stack

- Power BI Desktop
- DAX for calculated measures (MoM %, success rate, segment share)
- Power Query for data shaping and transformation

## 📈 Key Insights

- Gen X users contributed the highest transaction volume among all age segments
- Loans generated the highest transaction value of any service category
- Weekday transactions significantly outpace weekend activity

## 🚀 Getting Started

1. Clone this repository
2. Open `dashboard.pbix` in Power BI Desktop
3. Connect the data source under **Transform Data → Data Source Settings**
4. Refresh to load the latest data


