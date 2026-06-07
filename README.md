# Marketing Dashboard - Multi Channel Advertising Analysis
Overview

This project focuses on unifying and analyzing advertising data from multiple marketing platforms including Facebook, Google Ads, and TikTok. The objective was to create a unified dataset and build an interactive dashboard for cross-channel marketing performance analysis.

# Project Goals
Combine advertising data from multiple platforms into one unified table
Standardize different column structures across platforms
Create a dashboard for performance tracking and insights
Analyze key marketing metrics across channels and campaigns
Data Sources

The project uses advertising data from:

facebook_ads.csv
google_ads.csv
tiktok_ads.csv
Data Transformation

The raw datasets were uploaded into PostgreSQL and transformed using SQL.

# Key transformation steps:

Standardized different column names across platforms
Mapped:
ad_set_id → ad_id
ad_set_name → ad_name
ad_group_id → ad_id
ad_group_name → ad_name
Added a platform column for source identification
Combined datasets using UNION ALL to preserve all records
Dashboard Features

# The Power BI dashboard includes:

KPI Metrics
Total Impressions
Total Clicks
CTR (Click Through Rate)
CPC (Cost Per Click)
Conversion Rate
Video Views
Total Spend
Visualizations
Spend Trend by Date
Channel Performance Comparison
Campaign Performance Analysis
Interactive Filters for:
Date
Platform
Campaign Name
Channel
Tools Used
PostgreSQL for data transformation
SQL for data unification
Power BI for dashboard creation
Key Insight


PREVIEW OF A dashboard:  https://github.com/atharvsankpal26/Marketing-Dashboard/blob/main/Marketing%20Dashboard.png

# The dashboard enables comparison of marketing performance across channels, helping identify trends, campaign effectiveness, and optimization opportunities.




