# Airport Operations Performance & Delay Analytics — 2023
**📥 Download Dataset (2019-2023)** - https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023?utm_source=chatgpt.com

**📥 Download Cleaned Dataset (2023)** -   https://docs.google.com/spreadsheets/d/1wDTcA0UGI8enJXWJ2LN0g-KYsFqz-uBa/edit?usp=sharing&ouid=111996514773908040925&rtpof=true&sd=true

## Interactive Dashboards in Tableau & Power BI

This project analyzes U.S. domestic flight delays for January–August 2023 using **Tableau**, **Power BI**, and **Excel (Power Query)**.
It uncovers patterns in operational efficiency, airline performance, seasonal delays, and route reliability—presented through two fully-interactive dashboards.

## Project Overview

Commercial aviation delays have significant financial and operational impact.
This project provides an end-to-end analysis of flight performance using:

Time-series delay trends

Airline reliability comparisons

Route-level performance analytics

Root-cause delay breakdowns

Interactive slicers for month, airline, airport, and day

The outcome is two dashboards:

✔ Tableau Operational Delay Dashboard

Emphasizes geospatial mapping, time-of-day patterns, route delays, and airline ranking.

✔ Power BI Operational KPI Dashboard

Focuses on KPIs, airline performance, route tables, monthly delay causes, and interactive filters.

## Dataset Description

Raw data was obtained from the U.S. Bureau of Transportation Statistics (BTS) – On-Time Performance dataset (over 3M rows, 2019–2023).

**Cleaning & Preprocessing** --

Using Excel Power Query, only 2023 data was extracted. Cleaning involved:

Removing unused columns

Filtering by date range

Handling nulls

Deriving new fields

Adding airline lookup table

Calculating total monthly delay minutes


**Features in Cleaned Dataset**--

Flight Details

FL_DATE

AIRLINE_CODE, AIRLINE_NAME

ORIGIN, DEST

CRS_DEP_TIME, DEP_TIME

CRS_ARR_TIME, ARR_TIME

Delay Metrics

DEP_DELAY, ARR_DELAY

DELAY_DUE_CARRIER

DELAY_DUE_WEATHER

DELAY_DUE_NAS

DELAY_DUE_SECURITY

DELAY_DUE_LATE_AIRCRAFT

Status Flags

CANCELLED

DIVERTED

Derived Fields

Route (ORIGIN → DEST)

Month, Day of Week

Total Delay Minutes

On-Time %

Delayed Flights

Delay Hours (for tooltip)

Airline Code → Airline Name Mapping

## Dashboards
**1️⃣ Tableau Dashboard – Airport Delay Analytics**

Key Visuals-

**⭐ Heatmap: Delay by Hour × Day**

Shows delay concentration patterns (e.g., evenings & Fridays are worst).

**🗺 Airport Delay Map**

Highlights airports with the highest average delays via geospatial visualization.

**📉 Monthly Delay Trend**

Shows seasonal peaks and improvement patterns.

**🚫 Top 10 Worst Routes**

Routes contributing disproportionately to arrival delays.

**🛫 Airline Performance Chart**

Ranks airlines by on-time performance across 2023.

**2️⃣ Power BI Dashboard – Operational KPI & Root-Cause Analysis**

Key Components-

**⭐ KPI Cards**

On Time %

Average Arrival Delay (mins)

Cancellation Rate

Total Flights

Delayed Flights

Most Reliable Airline

Worst Month for Delays

**⭐ Trend: On-Time Arrival % by Month**

Shows performance volatility across January–August 2023.

**⭐ Airline Reliability Comparison**

Bar chart of airline on-time performance with full airline names.

**⭐ Route Performance Overview (Table)**

Includes:

Avg Arrival Delay

On-Time %

Total Flights

Delayed Flights

**⭐ Delay Causes by Month (Stacked Column)**

Breaks delays into:

Carrier

Late Aircraft

Security

Weather

Formatted in K (thousands) with tooltips showing minutes.

**⭐ Interactive Slicers**

Filter dashboard by:

Month

Airline

Day

Destination City

## Insights Summary


✔ July was the worst month for delays — highest total delay minutes
✔ Republic Airways was the most reliable airline with the highest on-time %
✔ Late Aircraft Delay + Carrier Delay accounted for the majority of delays
✔ On-time performance averaged ~77.4% across all flights
✔ Cancellation rate remained low (~1.7%), but delays were more common
✔ Routes such as ABQ-SFO, ABE-BNA, ACK-BOS contributed disproportionately to overall delays
✔ Delay spikes during evening hours indicate cascading delay effects

## Skills & Tools Used

Data Cleaning & Modeling

Excel Power Query

Power BI Data Model

DAX Calculations

Lookup table creation

KPI modeling

Data Visualization

Power BI

KPI Cards

Stacked Column Charts

Bar Charts

Table Visual

Custom Tooltips

Slicers / Filters

Tableau

Heatmaps

Maps

Trend Lines

Top N Rankings

KPI Cards

Analytics & Domain Knowledge

Airline operations analytics

Delay root-cause analysis

Time-series performance evaluation

Route-level diagnostics

Geospatial patterns

## How This Project Helps Aviation Stakeholders

-Airport Operators

Optimize staffing and runway scheduling based on peak delay periods.

-Airlines

Identify chronic delay-causing routes and improve turnaround consistency.

-Passengers

Understand seasonal and carrier-based reliability trends.
