TikTok Data Analysis Project

Overview

This project analyzes TikTok video engagement trends based on claim status and author ban status. Using Python and Pandas, we examine factors influencing video engagement, including views, likes, comments, and shares.

Dataset

The dataset consists of various features such as:

claim_status: Indicates whether a video is a claim or an opinion.

author_ban_status: Specifies if the video's author is active, banned, or under review.

video_view_count, video_like_count, video_share_count, video_comment_count: Engagement metrics.

Key Insights

Claim videos account for ~40% of the dataset, while opinion videos make up ~60%.

Banned authors have significantly higher engagement rates, suggesting controversial or viral content.

Claim videos receive more likes, comments, and shares per view than opinion videos.

Engagement correlates strongly with claim status and author ban status.

Features Implemented

Data loading and cleaning with Pandas.

Boolean masking and filtering.

Grouping and aggregation using groupby() and agg().

Calculation of engagement ratios (likes_per_view, comments_per_view, shares_per_view).

Summary statistics and trend analysis.

Technologies Used

Python

Pandas

Jupyter Notebook


Install dependencies:

pip install pandas

Run the analysis in Jupyter Notebook or a Python script.

Future Enhancements

Data visualization using Matplotlib/Seaborn.

Sentiment analysis on video transcriptions.

Machine learning model to predict engagement trends.

Author

Ayodele Odugbile
