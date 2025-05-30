## Project Overview
Workforce360 offers data-driven insights into demographics, attrition patterns, and employee performance. The report, which was created using Power BI, assists HR teams in tracking important workforce metrics and determining the primary determinants of employee turnover, including job role, department, pay, frequency of travel, and satisfaction. It facilitates improved choices about strategic workforce planning, engagement, and retention.

## Project Objective & Goals
- Monitor and display important HR data, including headcount, the proportion of active versus inactive workers, departmental distribution, employee satisfaction, and performance evaluations.

- Recognize the elements that affect employee attrition, such as department, job role, education, pay, overtime, and business travel.

- Better workforce planning, engagement, and retention strategies are made possible by data-driven insights and interactive visuals that assist HR decision-making.

## Data Cleaning & Preparation
1. Imported HR data into Power BI
2. Built a star schema with appropriate relationships
4. Created DAX measures for KPIs such as Attrition Rate, Average Tenure, and Performance Trend

## Tools Used
-  Power BI  
-  DAX  
-  Power Query

  ## Insights 
- Attrition Trends: A significant percentage of the workforce is leaving the company, according to the overall attrition rate, with higher turnover seen in divisions like sales, human resources, and research and development. These regions might be dealing with a heavy workload, low job satisfaction, or slow career advancement.

- Business Travel and Overtime: Attrition rates are noticeably higher for workers who travel regularly or put in extra hours. This implies that poor work-life balance or burnout may be caused by long workdays and excessive travel.

- Tenure and Age Factors: A significant portion of departing employees were in the 20–30 age range and had shorter tenures (less than two years). This suggests that early-career workers are less likely to be retained, possibly as a result of inadequate onboarding or unfulfilled expectations.

- Performance and Environment Satisfaction: A large number of workers who scored poorly on environment satisfaction also received below-average performance evaluations and were more likely to quit. This implies a connection between retention, productivity, and job satisfaction.

- Impact of Education: Workers with less education had a marginally higher attrition rate, but this pattern also existed among highly educated employees in underperforming departments, demonstrating that education by itself cannot stop turnover.

- Job Role Patterns: Stress-intensive duties, a lack of opportunities for career advancement, or discontent with pay may be the causes of higher turnover rates in some roles, such as sales executives and HR assistants.

## Reccomendation
- Enhance Retention in High-Turnover Departments: Conduct exit interviews and pulse surveys in Sales and HR to understand root causes. Implement targeted retention strategies such as better workload management, clearer growth paths, and team-level engagement initiatives.

- Reduce Travel-Related and Overtime Burnout: Offer flexible work options or travel alternatives for employees in high-mobility roles. Monitor and manage overtime patterns more proactively using HR systems and team feedback.

- Improve Onboarding and Early Engagement: Since early-career employees are most likely to exit, strengthen onboarding processes, provide early mentorship, and schedule check-ins during the first 6–12 months to support new hires.

- Leverage Environment Satisfaction Data: Prioritize departments with lower environment satisfaction for leadership coaching, culture-building workshops, and psychological safety programs. Empower managers with feedback data to take action.

- Recognize and Retain High Performers: Create performance-based recognition and reward programs. Offer skill development plans and internal mobility for top performers, especially in high-risk job roles.

- Monitor Attrition by Demographic Groups: Regularly analyze attrition by age, education, gender, and job role to ensure inclusivity and equity. Where disparities exist, investigate underlying causes and introduce supportive interventions.

- Incorporate Predictive HR Analytics (Future Scope): Build on this report by developing a predictive model to proactively identify employees at risk of leaving using historical attrition trends, performance, and satisfaction data.

## Challenges Faced
Time Intelligence through Data Modeling: A date dimension table and the USERELATIONSHIP() function in DAX were needed to handle inactive relationships and guarantee accurate time-based analysis because the dataset included numerous date fields (such as Hire Date and Review Date).

Calculating the Attrition Rate: It was necessary to filter the appropriate population in each visual and clearly distinguish between active and inactive employees in order to define the attrition logic. It required more work to create a dynamic measure that changed with slicers and filters.

Creating Adaptable Age Groups: It was difficult to create unique age bins in Power Query that were consistent across visuals, readable, and sortable. Using M formulas and conditional columns required trial and error.

link to the full report(HR_Analytics) [https://app.powerbi.com/groups/11c67678-fd47-4222-b59d-0814a419a10d/reports/3e77e564-3ece-4750-badd-1ce0be7ddbda?ctid=6bd0734e-4fc4-4b1c-be23-6e5b6ed0d481&pbi_source=linkShare&bookmarkGuid=ec60f186-8522-4c01-8348-01466410dbcb] to explore the full report




