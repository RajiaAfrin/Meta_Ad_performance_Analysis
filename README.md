# Meta Ad Performance Analysis

## Project Background

Digital advertising plays a critical role in customer acquisition, brand awareness, and revenue growth. Businesses invest heavily in social media advertising platforms such as Facebook and Instagram to reach targeted audiences and drive conversions.

This project analyzes advertising performance data from Meta platforms (Facebook and Instagram) to evaluate campaign effectiveness, audience engagement, conversion performance, and budget utilization. The goal is to measure key marketing KPIs, identify high-performing audiences and ad formats, and provide actionable recommendations for improving return on investment (ROI).

# Dataset Used
- <a href="https://github.com/RajiaAfrin/Meta_Ad_performance_Analysis/tree/main/Meta%20Ad%20Analysis">Dataset<a/>

Insights and recommendations are provided on the following key areas:

- Campaign Performance Overview
- Audience Engagement Analysis
- Geographic Performance Analysis
- Ad Format Performance
- Time-Based Engagement Trends
- Conversion Funnel Analysis

This project was created using **Power BI, Power Query, Data Modeling, and DAX**.

## Data Structure & Initial Checks

The dashboard is built using four connected tables:

### ad_events (Fact Table)

Stores user interactions with advertisements.

Important fields include:

- event_id
- ad_id
- user_id
- timestamp
- day_of_week
- time_of_day
- event_type

### ads

Contains ad-level metadata and targeting information.

Important fields include:

- ad_id
- campaign_id
- ad_platform
- ad_type
- target_gender
- target_age_group
- target_interests

### campaigns

Contains campaign budget and duration information.

Important fields include:

- campaign_id
- name
- start_date
- end_date
- duration_days
- total_budget

### users

Contains user demographic information.

Important fields include:

- user_id
- user_gender
- user_age
- age_group
- country
- location
- interests

### Data Model

The project follows a star schema:

- Fact Table: ad_events
- Dimension Tables:
  - ads
  - campaigns
  - users

# Dashboard Interaction 
- <a href="https://github.com/RajiaAfrin/Meta_Ad_performance_Analysis/blob/main/Meta%20Ad%20Analysis.pbix">Dashboard<a/>

## Executive Summary

### Overview of Findings

The advertising campaigns generated strong reach and engagement across Facebook and Instagram, producing **216K impressions**, **25.4K clicks**, and **29K engagements**.

The campaigns achieved a **CTR of 11.76%** and an **Engagement Rate of 13.56%**, significantly outperforming typical social media advertising benchmarks.

Although awareness and engagement performance were strong, conversion efficiency was weaker. Only **1.3K purchases** were generated, resulting in a **Purchase Rate of 0.61%**.

Audience analysis revealed that **female users** and **young adults aged 18–30** generated the highest engagement levels. Video and Story advertisements consistently outperformed Image and Carousel ads across multiple performance metrics.

## Insights Deep Dive

## 1. Campaign Performance Overview

The dashboard highlights the following key marketing KPIs:

- Impressions: **216K**
- Clicks: **25.4K**
- Shares: **1.3K**
- Comments: **2.6K**
- Purchases: **1.3K**
- Engagements: **29K**
- CTR: **11.76%**
- Engagement Rate: **13.56%**
- Conversion Rate: **5.21%**
- Purchase Rate: **0.61%**
- Total Budget: **2.5M**
- Average Budget per Campaign: **50.7K**

These metrics indicate strong campaign visibility and audience engagement.

## 2. Audience Engagement Analysis

### Gender Analysis

Audience engagement was distributed as follows:

- Female: **13K (43%)**
- Male: **6K (22%)**
- Other / Not Specified: **10K (35%)**

Female audiences generated the highest engagement levels, indicating stronger interaction with campaign content.

### Age Group Analysis

The highest engagement levels were observed among:

- Ages **18–30**
- Early 20s audience segment

Engagement declines noticeably among audiences aged 35 and above.

This suggests that younger audiences are more responsive to campaign messaging and creative content.

## 3. Geographic Performance Analysis

The highest levels of engagement were generated from:

- United States
- India
- Brazil
- Germany
- United Kingdom

These countries represent the strongest-performing audience markets within the campaign portfolio.

## 4. Ad Format Performance

Performance varied across ad formats.

| Ad Type | Impressions | Clicks | CTR | Purchase Rate | Conversion Rate | Engagement Rate |
|----------|-----------:|-------:|------:|------:|------:|------:|
| Carousel | 48K | 6K | 11.7% | 0.59% | 5.1% | 13.4% |
| Image | 51K | 6K | 11.7% | 0.57% | 4.9% | 13.5% |
| Stories | 72K | 8K | 11.8% | 0.65% | 5.2% | 13.6% |
| Video | 46K | 5K | 11.9% | 0.62% | 5.2% | 13.7% |

### Key Findings

- Video ads achieved the highest CTR, Conversion Rate, and Engagement Rate.
- Story ads generated the highest impression volume.
- Image and Carousel ads delivered solid engagement but lower conversion performance.

## 5. Time-Based Engagement Trends

### Weekly Trend Analysis

Weekly engagement remained relatively stable throughout the reporting period, indicating consistent audience interest and campaign performance.

### Hourly Trend Analysis

Audience engagement peaks during:

- Afternoon hours
- Evening hours

The lowest engagement levels occur during:

- Early morning hours (approximately 00:00–05:00)

These findings highlight the importance of ad scheduling for maximizing campaign performance.

## 6. Conversion Funnel Analysis

The campaign funnel demonstrates strong upper-funnel performance:

- High impressions
- High CTR
- Strong engagement

However, conversion efficiency declines at the purchase stage.

Key funnel metrics:

- CTR: **11.76%**
- Conversion Rate: **5.21%**
- Purchase Rate: **0.61%**

This indicates that users are interested in the ads but fewer complete the final purchase action.

# Dashboard
<img width="1166" height="670" alt="image" src="https://github.com/user-attachments/assets/51f29d63-de16-40fb-a41c-44f8c118f769" />

<img width="1163" height="673" alt="image" src="https://github.com/user-attachments/assets/ed82ebf0-9fbe-43fd-8720-d7f5273b875f" />


## Recommendations

Based on the findings, I would recommend the following:

### 1. Improve Conversion Optimization

The gap between engagement and purchases suggests opportunities to improve landing pages, offers, checkout experiences, and retargeting strategies.

### 2. Prioritize High-Performing Audiences

Female users and young adults aged 18–30 generate the strongest engagement and should remain primary target segments.

### 3. Allocate More Budget to Video and Story Ads

Video and Story formats consistently outperform other ad types and should receive increased budget allocation.

### 4. Optimize Campaign Scheduling

Campaign delivery should be concentrated during afternoon and evening hours when engagement is highest.

### 5. Expand Focus on High-Performing Countries

India, the United States, Brazil, Germany, and the United Kingdom represent valuable markets for future campaign investment.

### 6. Strengthen Retargeting Campaigns

Users who engage but do not purchase should be targeted through remarketing and conversion-focused campaigns.

## Assumptions and Caveats

- The analysis includes only paid Meta advertising campaigns.
- Organic engagement is excluded from the analysis.
- Campaign performance is based on historical advertising activity.
- User behavior may change over time due to seasonality, competition, and campaign strategy changes.
- Geographic and demographic findings are limited to the available dataset.

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Business Intelligence
- Marketing Analytics
