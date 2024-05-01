Report 
Based on the provided model description and the assumption that the data reflect the general population, our survival study using a Log-Normal AFT model offered considerable insights into factors influencing customer churn risk. The coefficients computed provide an approximation of each feature's influence on the time until a client churns. For example, characteristics with a positive coefficient, such as custcat_E-service, custcat_Plus service, and custcat_Total service, are related with a higher predicted tenure, meaning that consumers in these categories are more likely to continue with the service before leaving. On the other side, internet_Yes has a negative coefficient, implying that consumers who use internet services are more likely to churn, maybe owing to market competition or service quality issues.

The most valuable degments in terms of retention tend to be those classified as 'E-service', 'Plus service', and 'Total service'. These clients have a longer predicted duration and may generate more money, making them ideal candidates for retention initiatives.  To establish a yearly retention budget, we would include in the projected revenue loss from lost customers, which may be approximated by multiplying the forecasted churn probability by the CLV for each segment. For example, if we forecast a 10% turnover rate for the 'Total service' sector, with an average CLV of $1,000, and there are 1,000 customers in this segment, the potential revenue loss is $100,000 per year.

In accordance with results, the yearly retention budget should at minimum reflect the anticipated income loss while also accounting for the expenses of executing retention tactics. Given the high value and risk of churn among internet service customers, strategies should focus on improving service quality, delivering competitive pricing, and developing customer engagement programmes customised to their requirements. Furthermore, personalised retention incentives and loyalty awards for the 'Plus service' and 'Total service' groups may be useful in lowering turnover. These focused methods, along with a company-wide focus on customer satisfaction and continual service improvement, will be critical in keeping valuable clients and reducing churn risk.


Customer Lifetime Value and Survival Analysis

Project Overview
This project focuses on applying survival analysis to a telecommunications dataset to estimate the Customer Lifetime Value (CLV) and
assess factors influencing customer churn. Utilizing parametric Accelerated Failure Time (AFT) models, the analysis aims to uncover valuable
insights into customer retention and inform strategic decision-making.

 
Homework Context
Objective: To build, compare, and visualize survival models using the dataset provided, identify significant predictors of churn, and calculate the CLV of customers.
Goals:
Build AFT models with available distributions.
Compare the models and visualize survival curves.
Interpret model coefficients to understand churn factors.
Calculate CLV and explore its variation across different customer segments.
Write a report summarizing the findings, particularly focusing on customer segments that are valuable and at risk.
 
Dataset Description
The dataset includes the following fields:
ID: Unique subscriber identifier
Region: Subscriber's regional code
Tenure: Duration (in months) the subscriber has been with the company
Age: Subscriber's age
Marital Status: Whether the subscriber is married
Address: Number of years the subscriber has lived at the current address
Income: Annual income of the subscriber in thousand units
Education: Education level of the subscriber
Retirement Status: Whether the subscriber is retired
Gender: Gender of the subscriber
Service Usage: Subscription details for voice, internet, and call forwarding services
Customer Category: Category of the customer based on service type
Churn: Whether the subscriber has churned or not

Results
The analysis provides:
Model comparison results and visualizations of survival curves.
CLV calculations across various segments.
Strategic insights into which customer segments are more likely to churn.

Contributing
Contributions to this project are welcome. Follow standard GitHub fork and pull request procedures.
