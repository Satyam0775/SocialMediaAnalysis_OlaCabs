# **Social Media Data Analysis for Ola Cabs**

## **Project Overview**
This project analyzes social media data related to Ola Cabs to extract insights into:
- Customer sentiment.
- Engagement metrics.
- Key areas for service improvement.

The dataset includes:
- **Post Details**: Content, datetime, hashtags, media links, mentions, and comments.
- **Engagement Metrics**: Likes, shares, views, and comments.
- **User Details**: Information about post authors and followers.

The analysis is conducted using Python and includes steps for data cleaning, descriptive analysis, sentiment analysis, complaint categorization, and engagement analysis.

---

## **Deliverables**
1. **Cleaned Dataset**:
   - `final_cleaned_data.csv`: Preprocessed data with added columns:
     - `total_engagement`: Sum of likes, shares, and comments.
     - `sentiment_category`: Sentiment classification (Positive, Neutral, Negative).

2. **Analysis Notebook**:
   - `social_media_analysis_ola_cabs.ipynb`: Contains data cleaning, sentiment analysis, complaint categorization, and visualizations.

3. **Summary Report**:
   - `report_ola_cabs.pdf`: Key findings and actionable recommendations.

4. **Visualizations**:
   - `sentiment_distribution.png`: Pie chart of sentiment distribution.
   - `complaint_distribution.png`: Bar chart of categorized complaints.

---

## **Key Findings**
- **Sentiment Analysis**:
  - **Positive**: 44.08%.
  - **Negative**: 32.40%.
  - **Neutral**: 23.52%.

- **Engagement Trends**:
  - **Twitter**: Highest average engagement (1085.91 engagements per post).

- **Complaint Categories**:
  - Driver Issues: 40%.
  - Cancellations: 35%.
  - Customer Service: 25%.

---

## **Recommendations**
1. **Address Customer Complaints**:
   - Improve driver training to reduce complaints.
   - Simplify cancellation policies for a smoother customer experience.

2. **Leverage Twitter**:
   - Focus marketing and engagement campaigns on Twitter, as it shows the highest activity.

3. **Improve Brand Sentiment**:
   - Respond promptly to negative feedback to build trust and improve brand perception.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/Satyam0775/social-media-analysis-ola-cabs.git  
