📊 Social Media Advertising Analysis Dashboard
📌 Project Overview

This project analyzes 3,000+ social media advertising campaigns across multiple platforms (Facebook, Instagram, Twitter, Pinterest) to understand campaign performance, ROI, engagement, and profitability.
The goal is to help marketing teams identify what works best, where to invest, and which campaigns generate the highest returns.

The analysis is presented through an interactive Power BI dashboard that allows users to filter and explore campaign data in real time.

📁 Dataset Description

Rows: ~3,000
Granularity: One row = One advertising campaign

Main Columns
Column	Description
Campaign_ID	Unique campaign identifier
Company	Brand running the campaign
Channel_Used	Platform (Facebook, Instagram, Twitter, Pinterest)
Target_Audience	Age and gender segment
Location	City
Clicks	Number of ad clicks
Impressions	Number of times ad was shown
Conversion_Rate	% of users who converted
Engagement_Score	Engagement level (1–10)
Acquisition_Cost	Cost of running the campaign
ROI	Return on investment
Date	Campaign date
🎯 Key Metrics Created

Several calculated measures were built in Power BI:

Total Spend

Revenue (Clicks × Conversion Rate)

Profit = Revenue – Total Spend

Avg ROI

Avg Engagement

Avg Conversion Rate

Total Clicks

Total Impressions

These metrics power all visualizations.

📊 Dashboard Features
1️⃣ Overview of Campaign KPIs

At the top of the dashboard:

Total Spend

Total Clicks

Total Impressions

Avg ROI

Avg Engagement

Avg Conversion Rate

This gives a quick snapshot of overall campaign performance.

2️⃣ Top-Performing Posts

A bar chart shows:

Top 10 Campaigns by Profit

This identifies the most successful ad campaigns based on actual money generated, not just clicks or impressions.

3️⃣ ROI Summary

A pie chart shows:

Top 5 Companies by ROI

This highlights which brands deliver the highest return on ad spend.

4️⃣ Interactive Filters

Users can filter the entire dashboard by:

Platform (Facebook, Instagram, etc.)

Company

Location

Target Audience

This allows:

“Show me only Instagram campaigns in Austin for Men 25–34.”

5️⃣ Platform Icons

Facebook, Instagram, Twitter, and Pinterest logos are displayed using Image URL columns, making the dashboard more intuitive and visually appealing.

📌 Key Business Insights

High traffic does not always mean high ROI.

Some campaigns generate large impressions but low profit.

Certain platforms and audiences consistently outperform others.

Profit-based ranking provides better decision-making than clicks alone.

💡 Actionable Recommendations

Increase budget for campaigns with high Profit and high ROI.

Focus marketing spend on top-performing platforms.

Target audience groups that show consistently high conversion.

Reduce spend on high-impression but low-ROI campaigns.

🛠 Tools Used

Power BI Desktop

DAX (for measures & rankings)

Interactive visuals & slicers
