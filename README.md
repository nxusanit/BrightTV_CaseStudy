# BrightTV_CaseStudy
BrightTV’s CEO has set a strategic objective to grow the company’s subscription base for the current financial year. This project focuses on leveraging customer data and viewing behaviour to generate actionable insights that support the Customer Value Management (CVM) team in achieving this goal.

The analysis uses two datasets:

User Profiles (demographics: age, gender, race, province, etc.)
Viewership Data (session-level viewing behaviour)

Each record in the dataset represents one viewing session per user.
The primary objective of this analysis is to:

Understand user behaviour and engagement patterns
Identify drivers of content consumption
Highlight low engagement periods and opportunities
Provide data-driven recommendations to:
Increase engagement
Improve retention
Grow the subscription base

Data Preparation
1. Time Conversion
All timestamps were originally in UTC
Converted to South Africa Standard Time (SAST = UTC +2) for accurate analysis
2. Data Integration
Joined viewership data with user profile data using userID
Enabled segmentation across:
Demographics (age, gender, race, province)
Behaviour (channels, viewing time, frequency)
3. Feature Engineering

Key derived variables:

Date (from timestamp)
Time Buckets:
Morning (06:00–11:59)
Afternoon (12:00–17:59)
Evening (18:00–23:59)
Late Night (00:00–05:59)
Age Groups:
Under 18, 18–24, 25–34, 35–44, 45–54, 55–64, 65+
📊 Key Analysis Areas
1. User & Usage Trends
Viewership trends over time (daily/monthly)
Peak vs low consumption periods
Sessions per user (engagement levels)
2. Customer Segmentation
Viewership by:
Age group
Gender
Province
Identification of high-value segments
3. Content Performance
Most watched channels/content
Engagement by time and segment
Identification of high-performing vs underperforming content
🔍 Key Insights
📈 Viewing Behaviour
Evening (18:00–23:00) is the peak consumption period
Weekends show highest engagement
Monday–Tuesday are lowest consumption days
👥 Customer Segments
25–44 age group drives the majority of engagement
Urban provinces (e.g., Gauteng, Western Cape) dominate usage
📺 Content Trends
A small number of channels drive the majority of viewership
Long-tail content is underutilised
🧠 Drivers of Consumption

Consumption is influenced by:

Time availability (evenings & weekends)
Content relevance and quality
User engagement maturity
Ease of access and personalised recommendations
Content Recommendations

To increase consumption during low-engagement periods:

1. Short-Form Content
20–30 minute episodes for weekday viewing
2. Mid-Week Content Releases
Drop new episodes on Monday/Tuesday to boost engagement
3. Live / Event-Based Content
Sports or live shows to create urgency
4. Personalised Content
“Recommended for you”
“Continue watching” features
 Growth Initiatives

 Acquisition
Partnerships (telcos, ISPs, device manufacturers)
Referral programmes
Free trial campaigns
   Retention (CVM Focus)
Behaviour-based segmentation:
High-value users
At-risk users
New users
Targeted engagement campaigns
   Upsell & Cross-Sell
Premium content tiers
Add-on subscriptions (e.g., sports, movies)
Key Metrics to Track
Daily Active Users (DAU)
Monthly Active Users (MAU)
Churn rate
Average session duration
Revenue per user
Engagement rate

Conclusion

BrightTV can significantly grow its subscription base by:

Targeting low-engagement periods
Leveraging customer segmentation
Optimising content strategy
Driving personalised engagement initiatives
💬 Final Statement

By combining data-driven insights with customer-centric strategies, BrightTV can transform user behaviour into sustained subscription growth and long-term customer value.
