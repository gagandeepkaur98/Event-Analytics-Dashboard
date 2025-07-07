# 📊 Event Analytics Dashboard

This project presents an interactive Power BI dashboard designed to analyze and visualize performance metrics across multiple events. It enables data-driven insights into ticket revenue, sponsorship, social media engagement, volunteer contributions, and participant satisfaction.

The dashboard is supported by a cleaned dataset to ensure accuracy and consistency. This repository includes visuals from the dashboard, a record of data cleaning steps, and the original Power BI file for further exploration or reuse.

---

## 🧹 Dataset Cleaning Summary

### Issues in Original Dataset:

- **Missing Values**:
  - Columns such as `Sponsorship (INR)`, `Social Media Reach`, and `Volunteer Hours` had blank values.
  
- **Incorrect Entries**:
  - Fields like `Target Audience` had inconsistent formats (e.g., vague or overly broad terms).

### Fixes in Cleaned Dataset:

- **Filled missing values** using logical estimates or corrected records.
- **Standardized audience types** (e.g., “Students”, “Professionals”, “Tech Enthusiasts”) for better segmentation.
- **Corrected fields** such as `Duration`, `Event Type`, and `Venue` to ensure uniform structure.

The cleaned dataset forms the foundation of the Power BI visualizations.

---

## 📊 Dashboard Components Explained

### 1. 🟠 Donut Chart: Sum of Revenue from Tickets (INR) by Event Name

- **What it shows**: Percentage contribution of each event to the total ticket revenue.
- **Purpose**: Helps quickly identify top revenue-generating events.

---

### 2. 🔵 Line Chart: Revenue from Tickets (Descending Order)

- **What it shows**: Ticket revenue by event in descending order.
- **Purpose**: Highlights variance in event performance related to ticket sales.

---

### 3. 🔲 KPI Cards (Top Summary Metrics)

| Metric                      | Description                                                  |
|----------------------------|--------------------------------------------------------------|
| **Count of Event**         | Total number of events included in the analysis.             |
| **Social Media Reach**     | Cumulative reach across all platforms for all events.        |
| **Volunteer Hours**        | Sum of volunteer efforts contributed across events.          |
| **Sponsorship (INR)**      | Total monetary sponsorship received.                         |
| **Revenue (INR)**          | Total revenue from both ticket sales and sponsorships.       |

- **Purpose**: Offers a high-level snapshot of the events’ overall impact.

---

### 4. 🧵 Line Chart: Average Feedback Score (out of 5) by Event ID

- **What it shows**: Participant feedback score per event.
- **Purpose**: Measures satisfaction and perceived quality of each event.
- **Insight**: Aids in identifying successful formats and improvement areas.

---

### 5. 🟦 Bar Chart: Revenue vs Sponsorship by Event

- **What it shows**: Comparison between ticket revenue and sponsorship received per event.
- **Purpose**: Understand funding models – whether events relied more on attendees or sponsors.


---

## 🧰 Tools Used

- **Power BI Desktop** – Data visualization and dashboard design
- **Excel** – Dataset cleaning and pre-processing
- **DAX** – For calculated fields and KPIs

---


