Social Media Data Analysis for Ola Cabs
Project Overview
This project focuses on analyzing social media posts related to Ola Cabs to extract actionable insights. The primary objectives are to:

Understand customer sentiment toward Ola Cabs services.
Analyze engagement metrics (likes, shares, views) to identify trends.
Categorize and visualize customer complaints for service improvement.
The analysis is based on a dataset containing social media posts, with fields such as:

Post Details: Content, datetime, hashtags, media links, mentions, and comments.
Engagement Metrics: Likes, shares, views, and comments.
User Details: Information about post authors and followers.
Deliverables
Cleaned Dataset:

final_cleaned_data.csv: The preprocessed dataset with added columns:
total_engagement: Sum of likes, shares, and comments.
sentiment_category: Sentiment classification (Positive, Neutral, Negative).
Jupyter Notebook:

social_media_analysis_ola_cabs.ipynb: Contains data cleaning, sentiment analysis, complaint categorization, and visualizations.
Report:

report_ola_cabs.pdf: A concise summary of findings and actionable recommendations.
Visualizations:

sentiment_distribution.png: Pie chart of sentiment distribution.
complaint_distribution.png: Bar chart of categorized complaints.
Key Findings
Sentiment Analysis:

Positive: 44.08%.
Negative: 32.40%.
Neutral: 23.52%.
Engagement Trends:

Twitter: Highest average engagement (1085.91 engagements per post).
Complaint Categories:

Driver Issues: 40%.
Cancellations: 35%.
Customer Service: 25%.
Recommendations
Address Customer Complaints:

Implement driver training programs to reduce complaints.
Streamline cancellation policies for better customer experience.
Leverage Twitter:

Focus marketing and engagement efforts on Twitter, as it shows the highest user activity.
Improve Brand Sentiment:

Respond to negative feedback proactively to build trust and improve the brand image.
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/social-media-analysis-ola-cabs.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
Copy code
jupyter notebook social_media_analysis_ola_cabs.ipynb
