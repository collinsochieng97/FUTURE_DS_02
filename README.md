# FUTURE_DS_02
Customer Retention and Churn Analysis Using Python and Power BI
Project Overview
Customer retention is a critical factor in business success, as acquiring new customers is often more expensive than retaining existing ones. This project analyzes customer churn patterns to identify the key factors driving customer attrition and provide actionable recommendations to improve retention.
The analysis was conducted using Python, Pandas, Matplotlib, and Seaborn, focusing on customer demographics, subscription details, service usage, billing information, and churn status.
________________________________________
Business Problem
The company is experiencing customer churn and seeks to understand:
•	Why customers are leaving the platform.
•	Which customer segments are most likely to churn.
•	How long customers typically remain active.
•	What strategies can improve customer retention.
________________________________________
Project Objectives
1.	Analyze customer churn behavior.
2.	Identify high-risk customer segments.
3.	Measure customer retention and customer lifetime.
4.	Discover factors associated with customer attrition.
5.	Provide data-driven recommendations to improve retention.
________________________________________
Dataset Description
The dataset contains 7,043 customer records and 21 features, including:
Feature Category	Examples
Demographics	Gender, SeniorCitizen, Partner, Dependents
Subscription Information	Contract Type, Internet Service
Support Services	Tech Support, Online Security, Online Backup
Billing Information	Monthly Charges, Total Charges
Customer Lifetime	Tenure
Target Variable	Churn
________________________________________
Tools and Technologies
•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook
________________________________________
Data Cleaning
The following preprocessing steps were performed:
Missing Values Assessment
•	Checked for missing values using .isnull().sum().
•	No explicit missing values were identified.
Data Type Validation
•	Converted TotalCharges from object to numeric format.
Duplicate Check
•	Verified uniqueness of customer records.
•	Checked for duplicate customer IDs.
Categorical Data Validation
•	Reviewed categorical variables for inconsistencies.
•	Standardized values where necessary.
Outlier Detection
•	Used boxplots to assess distributions of:
o	Monthly Charges
o	Total Charges
o	Tenure
Class Balance Assessment
•	Evaluated distribution of churn classes.
•	Dataset exhibited moderate class imbalance suitable for analysis.
________________________________________
Exploratory Data Analysis (EDA)
Overall Churn Analysis
The dataset contains both retained and churned customers, allowing analysis of factors associated with customer attrition.
Contract Type and Churn
Contract Type	Churn Rate
Month-to-Month	42.71%
One Year	11.27%
Two Year	2.83%
Insight
Customers on month-to-month contracts are significantly more likely to churn compared to customers on long-term contracts.
________________________________________
Monthly Charges and Churn
Boxplot analysis revealed that churned customers generally have higher monthly charges than retained customers.
Insight
Higher monthly subscription costs appear to increase churn risk.
________________________________________
Technical Support and Churn
Tech Support	Churn Rate
No	41.64%
Yes	15.17%
Insight
Customers without technical support are substantially more likely to leave the platform.
________________________________________
Internet Service and Churn
Internet Service	Churn Rate
Fiber Optic	41.89%
DSL	18.96%
No Internet Service	7.40%
Insight
Fiber Optic customers exhibit the highest churn rates and represent a critical retention segment.
________________________________________
Customer Lifetime Analysis
Average Tenure
32.37 months
Median Tenure
29 months
Insight
Customers who churn tend to leave much earlier than customers who remain active.
This suggests that the first year of the customer journey is particularly important for retention.
________________________________________
Key Findings
Major Drivers of Churn
1.	Month-to-month contracts
2.	Lack of technical support
3.	Fiber Optic internet service
4.	Higher monthly charges
5.	Short customer tenure
High-Risk Customer Profile
Customers most likely to churn typically:
•	Use Fiber Optic internet service
•	Subscribe to month-to-month contracts
•	Lack technical support
•	Pay higher monthly charges
•	Have short tenure
________________________________________
Visualizations
The project includes:
•	Churn Distribution Analysis
•	Contract Type vs Churn
•	Monthly Charges vs Churn
•	Tech Support vs Churn
•	Internet Service vs Churn
•	Tenure vs Churn
•	Customer Lifetime Analysis
________________________________________
Business Recommendations
1. Encourage Long-Term Contracts
•	Offer discounts for annual subscriptions.
•	Introduce loyalty rewards.
•	Provide contract renewal incentives.
2. Improve Technical Support Adoption
•	Offer free onboarding assistance.
•	Provide support bundles.
•	Improve response times.
3. Improve Fiber Optic Customer Experience
•	Investigate service quality concerns.
•	Monitor customer complaints.
•	Improve network reliability.
4. Reduce Early Customer Churn
•	Strengthen onboarding programs.
•	Engage customers during their first year.
•	Implement customer success initiatives.
5. Review Pricing Strategy
•	Offer flexible pricing plans.
•	Provide loyalty discounts.
•	Introduce value-added service packages.
________________________________________
Conclusion
This analysis identified several significant factors influencing customer churn. Customers with month-to-month contracts, Fiber Optic internet service, higher monthly charges, and no technical support were found to have the highest churn rates. Additionally, customers who churn tend to leave early in their lifecycle.
The findings suggest that improving customer support, enhancing service quality, encouraging long-term commitments, and strengthening onboarding processes can significantly improve customer retention and reduce churn.
________________________________________
Author
Collins Ochieng Owino
BSc Mathematics & Computer Science
Data Analyst | Data Scientist | Software Developer
GitHub: [Your GitHub Profile]
LinkedIn: [Your LinkedIn Profile]

