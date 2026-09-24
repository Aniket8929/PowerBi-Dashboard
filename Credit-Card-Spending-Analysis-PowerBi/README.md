# 💳 Credit Card Spending Habits in India — Power BI Dashboard

An interactive Power BI dashboard analyzing credit card transaction patterns across India, exploring spending behavior by gender, card type, expense category, city, and time. Built to help identify who spends, where they spend, and how spending shifts across the year.

---

## 📌 Overview

This dashboard consolidates credit card transaction data into a single, interactive Power BI report. It enables users to slice and filter across multiple dimensions — gender, card type, expense category, and year — to uncover patterns in consumer behavior, seasonal spending cycles, and regional/city-level differences.

The report is designed for quick, at-a-glance analysis: every visual updates dynamically as filters are applied, so a viewer can go from a high-level overview to a specific segment (e.g., "Female Gold card holders' Travel spend in 2014") in a few clicks.

---

## 🎯 Objectives

- Understand how credit card spending varies by **gender** and **card type**.
- Identify which **expense categories** (Bills, Food, Fuel, Entertainment, Grocery, Travel) drive the most transaction volume.
- Track **seasonal/monthly trends** in spending behavior.
- Highlight the **top-spending cities** across India.
- Provide a single interactive view for exploratory, filter-driven analysis rather than static reporting.

---

## 🧩 Dashboard Components

| Visual | Type | Description |
|---|---|---|
| **Transaction Amount by Gender and Card Type** | Pie Chart | Breaks down total transaction value across each card type (Gold, Platinum, Signature, Silver), split by gender. Each slice is labeled with amount and percentage of total. |
| **Transaction Amount by Exp Type** | Treemap | Visualizes relative share of spending across expense categories — Bills, Fuel, Entertainment, Food, Grocery — sized and colored by proportion of total spend. |
| **Transaction Amount by Month and Gender** | Line Chart | Tracks monthly transaction totals across the year for Male vs. Female cardholders, revealing seasonal peaks and dips. |
| **Transaction Amount by Exp Type and Gender** | Stacked Horizontal Bar Chart | Compares transaction amounts per expense category, broken down by gender, with total values displayed alongside each bar. |
| **Top 5 Cities Analysis** | Ranked Bar/Segment Chart | Shows the five highest-spending cities (Greater Mumbai, Bengaluru, Ahmedabad, Delhi, Kolkata) with spend broken down by card type. |

---

## 🎛️ Interactivity & Filters

- **Gender Slicer** — Female / Male
- **Card Type Slicer** — Gold / Platinum / Signature / Silver
- **Expense Type Slicer** — Bills / Entertainment / Food / Fuel / Grocery / Travel
- **Year Slicer (buttons)** — 2013 / 2014 / 2015 / All
- **Field Selector** — Toggle the Top 5 Cities visual between "Card Type" and "Exp Type" breakdowns
- **Clear All Slicers** — One-click reset button in the top-right corner to remove all active filters
- Full **cross-filtering**: clicking any chart segment (e.g., a slice of the pie chart or a treemap category) filters all other visuals on the page accordingly

---

## 📊 Key Insights

- **Card type spend is fairly balanced** — Gold, Platinum, Signature, and Silver each account for roughly 11–15% of total transaction volume, indicating no single card tier dominates spending.
- **Bills and Food are the top expense categories**, together making up over 40% of total transaction value, followed by Fuel (~19%), Entertainment (~18%), and Grocery (~18%).
- **Seasonality is clear in monthly trends** — spending dips noticeably mid-year (around June–July) and rises toward the start and end of the calendar year, for both genders.
- **Female cardholders show marginally higher spend** than male cardholders in most months, though the gap narrows during low-spending periods.
- **Greater Mumbai leads city-wise spending**, followed closely by Bengaluru and Ahmedabad, with Delhi and Kolkata rounding out the top 5.
- Across expense categories split by gender, **Bills and Food remain the largest contributors for both genders**, while Travel shows the smallest and most balanced split.

---

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** — report design, data modeling, and DAX measures
- **DAX** — calculated measures for transaction totals, percentage-of-total breakdowns, and dynamic field switching (Card Type ↔ Exp Type)
- **Slicers & Bookmarks** — for interactive filtering and the "Clear all slicers" reset action
- **Custom color theme** — pink/magenta and purple/blue palette applied consistently across visuals for brand-style presentation

---

## 📁 Suggested Repository Structure

```
credit-card-spending-india/
│
├── data/
│   └── credit_card_transactions.csv     # Raw/source dataset
│
├── dashboard/
│   └── Credit_Card_Spending_India.pbix  # Power BI report file
│
├── images/
│   └── dashboard_preview.png            # Dashboard screenshot
│
└── README.md
```

*(Adjust file/folder names to match your actual project files.)*

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Credit_Card_Spending_India.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Use the slicers on the left panel (Gender, Card Type, Exp Type) and top-right panel (Year) to filter the data.
4. Toggle the **Select Field** buttons to switch the Top 5 Cities visual between Card Type and Exp Type views.
5. Hover over any chart element to view detailed tooltips with exact figures.
6. Click **Clear all slicers** to instantly reset every filter.

---

## 📷 Preview

<img width="889" height="496" alt="image" src="https://github.com/user-attachments/assets/c24e8d1e-aa30-4798-9e43-ec879922bed4" />


The dashboard is a single-page report combining a pie chart, treemap, line chart, stacked bar chart, and ranked city breakdown — giving a complete, at-a-glance picture of credit card spending behavior across India.

---

## 🔮 Future Improvements

- Add a **drill-through page** for individual city or card-type deep dives
- Incorporate **year-over-year growth** metrics
- Add **average transaction value** and **transaction count** alongside total amount
- Build a **mobile-optimized layout** for on-the-go viewing

---

## 📬 Contact

Feel free to reach out with questions, feedback, or collaboration ideas, or fork this project to adapt it for your own spending analysis.
