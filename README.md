# DSA210-Project
# **My TikTok Usage Data Analysis**

## **Table of Contents**
- [**Description**](#description)
- [**Motivation**](#motivation)
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

## **Motivation**
Social media is an integral part of modern life, and TikTok is one of my most-used apps. By analyzing my TikTok usage patterns, I aim to:
- **Understand My Habits:** Gain insights into when and how I use TikTok.
- **Evaluate Consumer Behavior:** Explore how the app influences my preferences and content consumption.
- **Optimize Time Management:** Identify opportunities to reduce excessive screen time and improve productivity.

This project provides a data-driven exploration of my digital behavior, particularly during significant periods like exam seasons, and lays the groundwork for creating healthier habits.

---

## **Tools**
The following tools will be used for this project:
- **Jupyter Notebook**: For coding and documentation.
- **Pandas**: For data cleaning, structuring, and filtering.
- **Matplotlib & Seaborn**: For creating static visualizations.
- **Plotly**: For interactive visualizations.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For predictive modeling in future steps.
---

## **Data Source**
The data was directly exported from TikTok using their official **data export tool**.  
The dataset includes:
1. **Login History:** Information on login times and devices
2. **Activity Log:** Records of video-watching sessions, including timestamps and durations.

### **Data Collection**
1. Exported TikTok data in JSON format.
2. Converted the JSON to CSV for preprocessing and analysis.
3. Anonymized sensitive details to ensure privacy.

---

## **Data Processing**
To prepare the data for analysis, the following preprocessing steps will be applied:
- **Timestamps Conversion:** I will convert timestamps from UTC to local time and extract features like hour of the day and day of the week.
- **Usage Duration Aggregation:** I will sum usage durations for each day, week, and specific time intervals (morning, afternoon, evening, night).
- **Outlier Removal:** I will identify and exclude incomplete or anomalous entries.
- **Categorization:** I will group data into meaningful time-based intervals for better insights.

---

## **Data Visualizations**
The following visualizations will be created during the Exploratory Data Analysis (EDA) phase:
1. **Hourly Usage Patterns:** A line chart visualizing TikTok activity across each hour of the day.
2. **Weekly Usage Trends:** A bar chart comparing daily usage levels throughout the week.
3. **Daily Activity Heatmap:** A heatmap showcasing intensity of activity for each day and hour.

---

## **Data Analysis**

### **Hourly Usage Patterns**
- I will analyze hourly TikTok activity to identify peak usage times.
- I will compare weekday vs. weekend activity trends to detect differences.


### **Daily and Weekly Usage Trends**
- I will evaluate total TikTok usage for each day of the week.
- I will observe reduced usage on Sundays, likely due to social or family commitments.

---

## **Limitations**

### **Data Limitations**
- **Scope:** The dataset covers a limited time period, which may not reflect long-term trends.
- **Privacy Considerations:** Anonymizing data reduced the granularity of some insights.

### **Personal Limitations**
- **Technical Skills:** Advanced machine learning techniques were not fully utilized due to limited experience.
- **Visualization Constraints:** Interactive visualizations were not seamlessly integrated into the final report.

---

## **Future Work**
- **Longitudinal Analysis:** Collect additional data over an extended period to observe evolving trends.
- **Behavioral Insights:** Explore correlations between TikTok usage and metrics like productivity or mood.
- **Predictive Modeling:** Develop machine learning models to forecast usage patterns based on time or content type.
- **Content Analysis:** Examine the psychological or behavioral impact of frequently consumed content.

---







