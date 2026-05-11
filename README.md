# Spotify Churn Analysis & Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on analyzing Spotify user behavior to understand the factors that may lead users to stop using the platform (Churn).

The analysis was performed using Python for data cleaning, exploration, visualization, and extracting business insights from user activity data.

The main goal was to identify behavioral patterns related to churn and understand how user engagement, listening habits, subscription types, and devices affect retention.

---

# Project Workflow

## 1. Data Understanding
At the beginning, the dataset structure was explored to understand:
- Data types
- Number of rows and columns
- Numerical vs categorical features
- Missing values
- Duplicate records

---

## 2. Data Cleaning & Preprocessing
The following preprocessing steps were performed:

- Checking missing values
- Detecting duplicates
- Understanding categorical variables
- Statistical summary of numerical columns
- Correlation analysis between numerical features

---

## 3. Exploratory Data Analysis (EDA)

Several analyses were performed to understand user behavior patterns.

### User Demographics Analysis
- Gender distribution
- Average user age
- User distribution across countries

### Subscription Analysis
- Comparing Premium, Free, Student, and Family subscriptions
- Analyzing churn rate for each subscription type

### Device Usage Analysis
- Comparing Mobile, Desktop, and Web usage
- Understanding engagement differences across devices

### Behavioral Analysis
- Average listening time
- Songs played per day
- Skip rate analysis
- Relationship between engagement and churn

### Correlation Analysis
Correlation between:
- Age & Listening Time
- Age & Skip Rate
- Numerical features related to churn behavior

---

# Key Insights

## 1. User engagement strongly affects churn
Users with lower listening activity and fewer songs played per day were more likely to churn.

## 2. Skip rate is an important indicator
Users with high skip rates showed weaker engagement and higher churn probability.

## 3. Subscription type alone is not enough
Premium users did not always have lower churn rates, which means user behavior matters more than subscription category.

## 4. Device usage patterns differ
Desktop users showed slightly higher activity levels compared to Mobile and Web users.

## 5. Demographics had weaker impact
Age and gender showed limited influence compared to behavioral metrics.

---

# Challenges Faced During the Analysis

## Understanding User Behavior
One of the biggest challenges was understanding which variables truly affect churn because some features showed weak correlations despite appearing important initially.

## Interpreting Correlations
Some numerical relationships were very small, so it was necessary to avoid misleading conclusions and focus more on behavioral patterns rather than only correlation values.

## Choosing Meaningful Visualizations
Selecting the right charts to clearly explain the data patterns was challenging, especially when comparing multiple subscription types and churn categories.

## Separating Useful Insights from Noise
The dataset contained many variables, but not all of them contributed equally to understanding churn behavior.

---

# What I Learned From This Project

Through this project, I improved my skills in:

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Data visualization
- Business insight extraction
- Correlation analysis
- Identifying churn patterns
- Translating raw data into actionable recommendations

I also learned how to connect technical analysis with real business problems like customer retention and user engagement.

---

# Recommendations

Based on the analysis results, Spotify could improve user retention by:

- Increasing engagement for low-activity users
- Monitoring users with high skip rates
- Creating personalized recommendations for inactive users
- Improving user experience across devices
- Offering targeted retention campaigns before users churn

---

# Future Improvements

Possible future improvements for this project:

- Build Machine Learning models for churn prediction
- Apply feature engineering techniques
- Use advanced visualization dashboards
- Perform segmentation analysis on user groups
- Compare multiple classification algorithms

---

# Conclusion

This project explored Spotify user behavior to better understand churn patterns and user engagement.

The analysis showed that behavioral metrics such as listening time, songs played, and skip rate are more influential than demographic factors.

The project demonstrates how data analysis can help businesses make better decisions to improve customer retention and user experience.

---

# Author
Rana Fayez
Aspiring Data Analyst | Python | Power BI | SQL
