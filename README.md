# 🚖 Uber Trip Data Analysis – Power BI Project

This project provides a comprehensive Power BI dashboard analysis of Uber trip data, focusing on booking trends, revenue, trip efficiency, time-based demand, and detailed ride insights. Screenshots of the dashboards are included in the repository for visual reference.

---

## 📊 Dashboard 1: Overview Analysis

Gain high-level insights into booking trends, revenue, and trip metrics to support strategic decision-making.

### ✅ KPIs Tracked:
- **Total Bookings** – Number of trips over a selected period.
- **Total Booking Value** – Total revenue generated.
- **Average Booking Value** – Revenue per trip.
- **Total Trip Distance** – Distance covered across all trips.
- **Average Trip Distance** – Distance per trip.
- **Average Trip Time** – Duration per trip.

### 🎯 Expected Outcomes:
- Discover revenue and booking trends.
- Analyze trip distance and efficiency.
- Compare booking behavior over time.
- Support pricing and operational strategies.

### 📈 Visuals & Features:
- **Dynamic Measure Selector** using a disconnected table:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance
- **Breakdown by**:
  - Payment Type (Card, Cash, Wallet)
  - Trip Type (Day/Night)
- **Dynamic Chart Titles** that adjust based on selected measure.
- **Slicers** for Date, City, etc.
- **Tooltips** with contextual insights like Avg Booking Value.
- **Vehicle Type Analysis Grid**: Table showing KPIs by vehicle type.
- **Conditional Formatting** and **Sorting** for key metrics.
- **Total Bookings by Day**: Analyze fluctuations and peak booking days.

---

## 📍 Location-Based Insights

- **Top Pickup & Drop-off Locations** – Identify high-traffic areas.
- **Farthest Trip** – Find long-distance outlier trips.
- **Top 5 Locations by Bookings** – For demand forecasting.
- **Most Preferred Vehicle by Pickup Point** – Understand customer preference by location.

---

## 💡 Other Enhancements

- **📑 Bookmark Panel** – “Data Details” panel with metric definitions and data sources.
- **🔄 Clear Filters Button** – Resets all slicers in one click.
- **⬇️ Download Raw Data** – Export feature via Power Automate or Power BI's native export option.

---

## 🕒 Dashboard 2: Time Analysis

Analyze trip demand across various time intervals to optimize operations and resource planning.

### 🔄 Global Dynamic Measure
A single selector updates all visuals with:
- Total Bookings
- Total Booking Value
- Total Trip Distance

### 📊 Visuals:
- **Pickup Time (10-Min Intervals)** – Area chart for demand surges.
- **Day Name (Mon–Sun)** – Line chart for weekday/weekend analysis.
- **Hourly Heatmap** – Matrix showing trip intensity by hour and day.

---

## 🧾 Dashboard 3: Details Tab

A drill-through grid tab offering granular-level data visibility.

### 🧩 Features:
- **Grid Table** with essential trip fields.
- **Drill-Through** from other visuals (e.g., heatmaps, charts).
- **"View Full Data" Bookmark** – Toggle between filtered and full datasets.

---

## 📸 Screenshots

> Screenshots of all dashboards (Overview, Time Analysis, Details Tab) are available in the repository to visualize key insights.

---

## 🔍 Tools & Technologies Used

- **Power BI** – Dashboard development
- **DAX** – Measures and dynamic titles
- **Power Automate** – Optional export functionality
- **Bookmarks, Tooltips, Slicers** – Enhanced interactivity

---

## 📄 License

This project is for educational and portfolio purposes only. All data used is simulated or anonymized for demonstration.

---

## 🙌 Acknowledgements

- Inspired by real-world ride-hailing data use cases.
- Thanks to the Power BI community for techniques and design patterns.
