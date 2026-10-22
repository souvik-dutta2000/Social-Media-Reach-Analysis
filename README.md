# Social Media Reach Analysis | Instagram + LinkedIn
An end-to-end data analytics project that analyses 10,000 social media posts (5,000 Instagram + 5,000 LinkedIn) to answer one question: what actually drives reach and engagement, and where should the next content and ad budget go?

Dataset note: the data is simulated (synthetic) for learning and portfolio practice. It is modelled on typical Instagram and LinkedIn post metrics for one brand account in 2025. It is not real account data. The monthly reach targets used in the dashboard are also assumed examples.

Table of contents
Business problem
Dataset
Architecture
Workflow
Key findings
Recommendations
Dashboard
Repository structure
How to run
Skills demonstrated
Limitations
Future improvements
Author
1. Business problem

A brand posts on Instagram and LinkedIn. The marketing team wants to know:

Which platform performs better on reach and engagement?
Which post types and content categories work best on each platform?
When should we post (day and hour)?
How many hashtags should we use?
Is paid promotion worth it?
Are we on track against our reach targets?
2. Dataset
Item	Detail
Source	Simulated for practice (one brand account, 2025)
Size	5,000 Instagram posts + 5,000 LinkedIn posts after cleaning (5,025 raw rows each)
Columns	19 (Post_ID, Platform, Post_Date, Post_Time, Post_Type, Content_Category, Followers_At_Post, Hashtag_Count, Caption_Length, Impressions, Reach, Likes, Comments, Shares, Saves, Link_Clicks, Profile_Visits, Followers_Gained, Paid_Promotion)
Instagram post types	Reel, Carousel, Image, Story
LinkedIn post types	Text, Image, Document, Video, Poll, Article
Extra tables (Excel)	Dim_Platform (platform pictures), Targets (assumed monthly reach targets), AI_Recommendations
