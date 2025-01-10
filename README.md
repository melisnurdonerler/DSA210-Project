**Table of Contents**
- [**Description**](#description)
- [**Links**](#links)
- [**Motivation**](#motivation)
- [**Hypothesis**](#hypothesis)
- [**Tools**](#tools)
- [**Data Source**](#data-source)
  - [**Data Collection**](#data-collection)
- [**Data Processing**](#data-processing)
- [**Data Visualizations**](#data-visualizations)
- [**Data Analysis**](#data-analysis)
  - [**Hourly Usage Patterns**](#hourly-usage-patterns)
  - [**Daily and Weekly Usage Trends**](#daily-and-weekly-usage-trends)
- [**Limitations**](#limitations)
  - [**Data Limitations**](#data-limitations)
  - [**Personal Limitations**](#personal-limitations)
- [**Future Work**](#future-work)




---
## **Description**
This project is part of the **Sabancı University DSA210 Introduction to Data Science** course for the Fall 2024-2025 term.  
It focuses on analyzing my TikTok usage data to uncover patterns in my activity, explore consumer behavior, and evaluate the impact of social media on time management.
---
## **Links**
- Code related to my project can be found in [main.ipynb](https://github.com/melisnurdonerler/DSA210-Project/tree/main).
- The presentation website is on https://tiktok-usage-insights-clzb9j2.gamma.site/.
- The presentation file can be found https://github.com/melisnurdonerler/DSA210-Project/blob/main/Melisnur-Donerler-31145.pptx
- My findings can be found **Table of Contents**
- [**Description**](#description)
- [**Links**](#links)
- [**Motivation**](#motivation)
- [**Hypothesis**](#hypothesis)
- [**Tools**](#tools)
- [**Data Source**](#data-source)
  - [**Data Collection**](#data-collection)
- [**Data Processing**](#data-processing)
- [**Data Visualizations**](#data-visualizations)
- [**Data Analysis**](#data-analysis)
  - [**Hourly Usage Patterns**](#hourly-usage-patterns)
  - [**Daily and Weekly Usage Trends**](#daily-and-weekly-usage-trends)
- [**Limitations**](#limitations)
  - [**Data Limitations**](#data-limitations)
  - [**Personal Limitations**](#personal-limitations)
- [**Future Work**](#future-work)




---
## **Description**
This project is part of the **Sabancı University DSA210 Introduction to Data Science** course for the Fall 2024-2025 term.  
It focuses on analyzing my TikTok usage data to uncover patterns in my activity, explore consumer behavior, and evaluate the impact of social media on time management.
---
## **Links**
- Code related to my project can be found in [main.ipynb](https://github.com/melisnurdonerler/DSA210-Project/tree/main).
- The presentation website is on https://tiktok-usage-insights-clzb9j2.gamma.site/.
- The presentation file can be found https://github.com/melisnurdonerler/DSA210-Project/blob/main/Melisnur-Donerler-31145.pptx
- Ny findings can be found https://github.com/melisnurdonerler/DSA210-Project/blob/main/Dsa210-Findings.docx

---

## **Motivation**
Social media is an integral part of modern life, and TikTok is one of my most-used apps. By analyzing my TikTok usage patterns, I aim to:
- **Understand My Habits:** Gain insights into when and how I use TikTok.
- **Evaluate Consumer Behavior:** Explore how the app influences my preferences and content consumption.
- **Optimize Time Management:** Identify opportunities to reduce excessive screen time and improve productivity.

This project provides a data-driven exploration of my digital behavior, particularly during significant periods like exam seasons, and lays the groundwork for creating healthier habits.

---

## **Hypothesis**
My hypothesis is that TikTok usage is higher during non-exam periods compared to exam periods, and the highest engagement occurs in the evenings and on weekends.

**Conclusion**: Based on the data analysis and visualizations, this hypothesis was **partially supported**. The usage was indeed higher during non-exam periods, confirming a reduction in activity during exams. However, while peak engagement times were mostly in the evenings, weekends did not always show the highest activity compared to certain weekdays.

---

## **Tools**
The following tools were used for this project:
- **Python (Jupyter Notebook & Script Format)**: For coding and documentation.
- **Pandas**: For data cleaning, structuring, and filtering.
- **Matplotlib & Seaborn**: For creating static visualizations.
- **Plotly**: Considered for interactive visualizations (not fully integrated).
- **NumPy**: For numerical operations.

---

## **Data Source**
The data was directly exported from TikTok using their official **data export tool**.

### **Data Collection**
1. Initially exported TikTok data in JSON format.
2. Switched to text format for easier processing.
3. Anonymized sensitive details to ensure privacy.

---

## **Data Processing**
To prepare the data for analysis, the following preprocessing steps were applied:
- **Text Parsing:** Extracted dates and links from text files.
- **Timestamps Conversion:** Converted timestamps from UTC to local time and extracted hour of the day and day of the week.
- **Usage Duration Aggregation:** Summed usage durations for specific time intervals (morning, afternoon, evening, night).
- **Categorization:** Grouped data into meaningful time-based intervals for better insights.

---

## **Data Visualizations**
The following visualizations and outputs were created:
1. **Hourly Usage Patterns** (`hourly_usage.png`): A bar chart showing TikTok activity across each hour of the day.
2. **Daily Usage Trends** (`daily_usage.png`): A bar chart comparing daily usage levels.
3. **Daily Distribution of Favorite Videos** (`favorite_videos_daily.png`): Bar chart showing favoriting patterns across days.
4. **Exam Period vs. Non-Exam Period** (`period_usage_comparison.png`): A bar chart comparing usage during exams and other periods.
5. **Correlation Heatmap** (`hourly_browsing_favorites_correlation.png`): A heatmap showing the relationship between browsing and favoriting activities.
6. **Top Liked Videos** (`top_liked_videos.csv`): CSV file listing the most frequently liked content.
7. **Monthly Usage Patterns** (`monthly_usage.png`): Usage trends over different months.
8. **Hourly Browsing and Favorite Correlation** (`browsing_favorite_pattern.png`): Comparison of browsing vs. favoriting by hour.
9. **Favorite Hourly Pattern** (`favorite_hourly_pattern.png`): Distribution of favorited videos by hour.
10. **Daily Activity Heatmap** (`daily_activity_analysis.png`): A visualization of activity intensity by day and hour.

---

## **Data Analysis**

### **Hourly Usage Patterns**
- The analysis identified peak usage times in the late evening hours.
- Differences between weekday and weekend activity were observed, with Saturdays showing higher engagement than midweek days.

### **Daily and Weekly Usage Trends**
- Usage patterns showed higher engagement on weekends overall.
- The analysis supported reduced usage during exam periods, confirming part of the hypothesis.

---

## **Limitations**

### **Data Limitations**
- **Scope:** The dataset covers a limited time period, which may not reflect long-term trends.
- **Privacy Considerations:** Anonymizing data reduced the granularity of some insights.

### **Personal Limitations**
- **Technical Skills:** Advanced machine learning techniques were not fully utilized.
- **Visualization Constraints:** Interactive visualizations were planned but not seamlessly integrated.

---

## **Future Work**
- **Longitudinal Analysis:** Collect additional data over an extended period to observe evolving trends.
- **Behavioral Insights:** Explore correlations between TikTok usage and productivity or mood.
- **Predictive Modeling:** Develop models to forecast usage patterns based on time or content type.
- **Content Analysis:** Investigate the psychological or behavioral impact of frequently consumed content.

