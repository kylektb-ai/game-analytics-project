# Game Analytics Project (BigQuery + SQL)

## Overview
This project analyses player behaviour in a simulated game dataset using SQL in BigQuery.  
The goal is to understand user engagement, revenue patterns, and retention over time.

---

## Dataset
The dataset contains user-level game events including:
- user_id
- signup_date
- event_date
- event_type (session, level_up, purchase)
- revenue
- level

---

## Key Analyses

### 1. Daily Active Users (DAU)
Tracked the number of unique users active per day to measure engagement trends.

### 2. Revenue Analysis
Aggregated daily in-game purchases to understand monetisation patterns over time.

### 3. Retention Analysis
Built cohort-based retention using signup date vs event activity to measure user return behaviour.

---

## Key Insights
- Strong drop-off in user engagement shortly after signup  
- Retention decreases significantly over time  
- Revenue is concentrated in early user lifecycle stages  
- Early engagement is the strongest predictor of long-term retention  

---

## Tools Used
- BigQuery (SQL)
- Google Cloud Platform
- Data aggregation and cohort analysis

---

## Files
- `queries.sql` → all SQL used for analysis  
- `game_analytics_dashboard.jpg` → Looker Studio visual dashboard  

---

## Dashboard
![Game Analytics Dashboard](game_analytics_dashboard.jpg)
