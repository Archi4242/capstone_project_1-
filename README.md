# capstone_project_1-
Nike invests millions every year in influencer marketing and creator-led short-form content on YouTube Shorts and TikTok. Your role is to analyze the 2025 short-form video trends dataset and provide actionable insights into:

How Nike’s campaigns perform across countries and platforms
What type of content drives completion and engagement
Which creators and hashtags provide the most ROI
How to predict viral trends for upcoming product launches

Phase 1 – SQL Analysis 

1.Platform Comparison: Total views and average engagement_rate across YouTube Shorts vs TikTok.

2.Regional Hotspots: Top 5 countries with the highest views for Nike campaigns on each platform.

3.Category Performance: Average completion_rate and avg_watch_time_sec for categories like sports, lifestyle, fashion.

4.Creator Impact: Top 10 author_handle by average views and their creator_tier.

5.Hashtag ROI: Top 20 hashtags by total views and their median engagement_rate.

6.Emoji Effect: Compare median engagement_per_1k between videos with and without has_emoji in titles.

7.Upload Timing: Average views and completion_rate by publish_dayofweek and upload_hour.

8.Trend Momentum: Median engagement_velocity and trend_duration_days by trend_type.

9.Device Analysis: Completion rates by device_type (e.g., mobile vs tablet) and device_brand.

10.Traffic Sources: Breakdown of traffic_source (e.g., For You Page, search, direct) with median completion_rate

11.Seasonal Insights: Compare views and engagement_rate across event_season (e.g., Olympics, Christmas, Summer sales)

12.Data Quality Check: Validate if engagement_total = likes + comments + shares + saves. Return mismatched rows.
 

Phase 2 – Power BI Report
1. Executive Overview

KPIs: Total views, total videos, average engagement_rate, average completion_rate.
Filters: platform, region, country, category.
 

2. Content Insights

Category performance (views, completion rate).
Hashtag performance & emoji impact.
Duration vs watch-time analysis.
 

3. Creator Insights

Top creators by views and tier.
Upload timing trends (hour/day).
Engagement breakdown (like_rate, share_rate, save_rate).
 

4. Market & Device Analysis

Country-wise and region-wise views.
Device type/brand completion rates.
Traffic source comparison.
 

5. Trend & Seasonality (optional 5th page)

Engagement velocity vs trend type.
Seasonal performance patterns.
