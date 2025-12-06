# Airport Operations Delay Analytics (2023)

# 📌 Project Overview

This project analyzes U.S. domestic flight performance for the year 2023 using Tableau.
The goal is to identify:

- Delay patterns across airports, airlines, weekdays, and time of day

- Worst-performing routes and operational hotspots

- Seasonal and temporal behaviors in flight delays

- Airlines with the best and worst on-time performance

- Actionable insights for improving airport efficiency

The final output is a fully interactive Tableau Operational Dashboard with KPI cards, heatmaps, geospatial maps, and comparative analysis visuals.

# 📂 Dataset Description

The dataset comes from the U.S. Bureau of Transportation Statistics (BTS) On-Time Performance records.
From the original multi-million row dataset (2019–2023), only 2023 data was extracted and cleaned using Excel Power Query.

After preprocessing, the dataset includes fields such as:

✈️ Flight Details

FL_DATE (Flight Date)

AIRLINE_CODE

ORIGIN, DEST

CRS_DEP_TIME, DEP_TIME

CRS_ARR_TIME, ARR_TIME

⏱ Delay Metrics

DEP_DELAY, ARR_DELAY

DELAY_DUE_CARRIER

DELAY_DUE_WEATHER

DELAY_DUE_NAS

DELAY_DUE_SECURITY

DELAY_DUE_LATE_AIRCRAFT

🛑 Status Flags

CANCELLED

DIVERTED

🧮 Derived Fields 

Is Delayed (binary flag for ≥15 min delay)

Time of Day (Morning/Afternoon/Evening/Night)

Route (ORIGIN → DEST)

Day of Week, Month

On-Time Performance(%)

On_Time_Percent_Display (converted to 0–100 scale)

This cleaned dataset is used for all visualizations.

# 📌 Overall Dashboard

📊 Heatmap – Delay by Day & Hour

🗺️ Airport Delay Map

📉 Monthly Delay Trend

🛫 Top 10 Worst Routes (Avg Arrival Delay)

🏢 Airline On-Time Performance Ranking

# 📈 Dashboard Explanation

The Tableau dashboard consists of six key components:

 **1️⃣ KPI Cards**

- Average Arrival Delay

- On-Time Performance (%)

- Cancellation Rate

These provide a quick snapshot of overall flight performance in 2023.

**2️⃣ Heatmap: Delay Patterns (Day × Hour)**

- Reveals operational bottlenecks:

- Which hours experience the worst delays

- Weekday vs weekend delay patterns

- Insights for airport/airline scheduling optimizations

**3️⃣ Geospatial Airport Delay Map**

Identifies:

- Airports with highest average delays

- Distribution of air traffic delays across the country

- Volume vs performance relationship

**4️⃣ Monthly Delay Trend**

Shows:

- Seasonal peaks

- Weather-related patterns

- Holiday travel impact

- Improving or worsening trends

**5️⃣ Top 10 Worst Routes**

- A bar chart ranking routes by highest average arrival delay.

- Highlights long-haul or congestion-prone sectors that contribute most to network inefficiency.

**6️⃣ Airline On-Time Performance Ranking**

Ranked comparison of major U.S. carriers:

- Best vs worst airlines

- Service reliability

- Insights into operational consistency

**🔍 Insights Summary**

Here are key findings from the analysis (update these with your actual results after reviewing the dashboard):

- Certain time windows (e.g., late evening) show highest delays, suggesting congestion or cascading delays.

- Weather-related delays spike during winter months.

- A handful of routes contribute disproportionately to total delay minutes.

- Some carriers consistently outperform others in on-time performance metrics.

- Airports in high-traffic regions show greater susceptibility to NAS (National Airspace System) delays.

- These insights help stakeholders optimize staffing, scheduling, and route planning.

## 🛠️ Skills & Tools Used

**Data Cleaning & Preparation**

Excel Power Query

Data filtering (year-based extraction)

Derived metrics creation

Missing value handling

**Data Visualization**

Tableau Desktop

Heatmap

Filled maps

KPI cards

Trend analysis

Top N analysis

Interactive filters & dashboard actions

**Analytics & Domain Skills**

Aviation operations analytics

Delay root-cause analysis

Time-series interpretation

Route-level performance evaluation

Geospatial visualization
