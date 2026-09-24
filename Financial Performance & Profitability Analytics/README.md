# 💰 Finance Power BI Dashboard

An interactive, multi-page Power BI dashboard built to analyze company-wide financial performance — revenue, profitability, customer behavior, and product performance — in a single, clean, dark-themed report.

---

## 📌 Overview

This dashboard consolidates financial and business data into four focused pages, allowing stakeholders to move from a high-level executive view down to customer- and product-level detail without leaving the report.

| Page | Purpose |
|---|---|
| 🏠 Home | Landing/navigation page |
| 📊 Executive Summary | High-level revenue, profit & department performance |
| 👥 Customer Insights | Customer segments, types & acquisition channels |
| 📦 Product Performance | Revenue by product, category & pricing analysis |

---

## 🏠 Page 1: Home

The landing page of the report, providing simple navigation buttons to move between the **Executive Summary**, **Customer Insights**, and **Product Performance** pages.

<img width="642" height="362" alt="image" src="https://github.com/user-attachments/assets/9a04393e-cd71-47ba-8a42-09ff12d44cde" />


**Highlights:**
- Clean branded landing screen
- One-click navigation to every report page
- Sets the visual theme (dark background, green accent palette) used throughout the report

---

## 📊 Page 2: Executive Summary

A high-level financial overview designed for leadership, summarizing revenue, profit, margins, and department-wise performance.

<img width="638" height="356" alt="image" src="https://github.com/user-attachments/assets/2d2b3fb5-66b0-4a81-9886-8c18ca97870a" />

**Key Metrics (KPI cards):**
- **Total Revenue:** 125.89M
- **Gross Profit:** 52.76M
- **Gross Margin %:** 41.91%
- **Net Profit:** 20.17M
- **Net Margin %:** 16.03%

**Visuals included:**
- Revenue vs Expense vs Net Profit — by Quarter (clustered column chart)
- Total Revenue by Category (Electronics, Hardware, Software, Services)
- Gross Profit & Net Profit Trend (monthly area/line chart, Jan–Dec)
- Department-wise performance table — Gross Profit, Net Profit, Total Budget, Total Expense, Gross Margin %, and Net Margin % across Marketing, Sales, Customer Support, HR, Finance, Procurement, IT, Legal, Operations, and R&D

---

## 👥 Page 3: Customer Insights

A closer look at the customer base — who they are, how they're segmented, and where they come from.

<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/fb9bfdff-378c-4839-9425-f4adba8c43d6" />


**Key Metrics (KPI cards):**
- **Total Customers:** 183
- **Revenue per Customer:** 687.95K
- **Total Transactions:** 500
- **Transactions per Customer:** 2.73

**Visuals included:**
- Customers by Segment — Premium, Basic, VIP, Standard
- Customers by Type — Startup, SMB, Mid-Market, Enterprise
- Revenue by Segment — VIP, Premium, Basic, Standard
- Customer Acquisition Channel breakdown (donut chart) — Social Media, Website, Cold Outreach, Advertisement, Partner, Direct Sales, Referral, Trade Show

---

## 📦 Page 4: Product Performance

A breakdown of product- and category-level revenue, along with pricing analysis against standard cost.

<img width="636" height="358" alt="image" src="https://github.com/user-attachments/assets/5d6809be-edf9-4923-a608-767349037606" />

**Key Metrics (KPI cards):**
- **Total Revenue:** 125.89M
- **Total Products:** 40
- **Total Quantity:** 50K
- **Avg Discount:** 12.60K

**Visuals included:**
- Revenue by Category (Electronics, Hardware, Software, Services)
- Top 5 Products by Revenue (table — Elite Connect, Elite Engine, Pro Analytics, Smart Manager, Ultra Analytics)
- Revenue by Sub-Category (treemap — Accessories, SaaS, Networking, Support, Audio, Productivity, Wearables, Security, Storage, Peripherals, etc.)
- Price vs Standard Cost comparison across brands (BrightEdge, Nimbus, NovaByte, Verlexa, Quanfix, CoreLogic, TechCore, Ironforge, Streamline, PulseWorks)

---

## 🎨 Design

- **Theme:** Dark background (`#1F1F1F` / `#343434`) with green accent tones for a clean, corporate finance look
- **Consistent layout:** KPI cards at the top of every analysis page, supporting charts/tables below
- **Navigation:** Button-based navigation from the Home page to all report pages

---

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query** — data cleaning & transformation

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Finance-Dashboard.pbix` in **Power BI Desktop**
3. Refresh the data source(s) if connected to live data
4. Use the navigation buttons on the **Home** page to explore the report

---

