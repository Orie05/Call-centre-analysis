# Call Centre Analysis

## Introduction:

This project delves into a dataset provided by Claire, the Call Centre Manager at PhoneNow, aiming to provide transparency and insights into call centre operations. Through data analysis and visualization, we seek to identify key metrics such as overall customer satisfaction, calls answered/abandoned, speed of answer, and agent performance.

## Data Overview:
The dataset covers call centre data spanning a period, including metrics like Call Id, Agent, Date, Time, Topic, Answered (Y/N), Resolved (Y/N), speed of answer (secs), average talk duration and satisfaction rating. Using Power BI, we visualize this dataset to uncover insights that inform strategic discussions and improvements in call centre operations.

## Business Objective:
Our goal is to derive actionable insights from call centre data to optimize operations, enhance decision-making and improve overall performance. Key questions addressed include:

- What is the overall customer satisfaction level?
- How many calls were answered and abandoned?
- What is the average speed of answer?
- How do different agents perform in terms of call handling and customer satisfaction?

## Data Transformation and Preprocessing:
We preprocess the data using Power Query Editor, transforming columns and detecting data types. Steps include handling headers, splitting datetime, and converting data types as needed. New measures were also created using DAX 

## Sample dataset
![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/3140d09a-ffc5-439e-a346-a26fc7e14d8b)


## Analysis and Insights:

Upon exploration, we discovered the following:

### Overall Metrics:

- A total of 5000 calls were recorded during the period analyzed, showcasing the substantial volume of customer inquiries.
- The average speed of answer stood at 67.52 seconds, indicating the efficiency of the call center in addressing incoming calls promptly.
- Out of these calls, 4054 were successfully answered by agents, while 946 calls were abandoned by customers, suggesting potential challenges in call routing or wait time management.
- Among the customers, 2023 expressed satisfaction with the service provided, while 1759 were unsatisfied, including those who abandoned their calls.
- Customer satisfaction levels varied, with 1218 customers being neutral, 1180 satisfied, 843 very satisfied, 417 very unsatisfied, and 396 unsatisfied.

**KPIs**
![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/c292a39d-9cf4-4931-a223-606ef8c05826)

![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/43423497-6290-42a2-959e-899d0f008b42)


**Agents' Performance**

![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/58e62e12-5708-49db-9f02-48a9ba1692dd)



### Call Topics:

- Technical support and payment-related issues emerged as the most common topics of discussion, with significant numbers of both abandoned and answered calls.
- Other prevalent topics included contract-related queries, admin support, and streaming concerns, each contributing to the overall call volume.
  
![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/90c1f36b-31fe-4003-beb8-842ef0d71925)

![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/1862d532-3dd8-470c-8da8-61de82e4bf33)


### Resolution Status:

- While efforts were made to resolve customer issues, only 73% of cases were successfully resolved, leaving 27% unresolved. This indicates potential challenges in effectively addressing customer concerns.

![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/f332de07-4d17-452b-ad46-0fb821f9e5f8)


## Insights and Possible Reasons:

- High Abandonment Rate: The significant number of abandoned calls suggests potential issues with call routing, long wait times, or ineffective IVR systems. Strategies to reduce wait times and improve call routing efficiency could help mitigate abandonment rates.
- Customer Satisfaction Trends: While a majority of customers express neutrality or satisfaction, the sizable number of unsatisfied customers indicates potential issues with service quality or communication. Improving agent training, service quality, and feedback mechanisms could address these concerns.
- Call Topic Analysis: Technical support and payment-related issues account for a significant portion of calls, indicating potential product/service issues or billing discrepancies. Streamlining support processes and enhancing payment systems could address these challenges.
- Resolution Status: Despite efforts to resolve issues, a considerable portion remains unresolved. This could stem from complex issues, agent expertise gaps, or resource limitations. Investing in training and knowledge management systems could improve issue resolution rates.

## Recommendations:

- Implement strategies to reduce wait times and improve call routing efficiency to reduce abandonment rates.
- Provide additional training and support to underperforming agents to improve overall performance.
- Enhance product documentation and payment systems to address technical and billing-related issues.
- Invest in agent training and knowledge management systems to improve issue resolution rates and overall customer satisfaction.
- Leverage customer satisfaction data to enhance overall service quality.
- Continuously monitor and adjust call centre operations based on data-driven insights.

  # Dashboard
  ![image](https://github.com/Orie05/Call-centre-analysis/assets/149834782/388a4af6-83b6-4d9f-8ff0-5becec955d98)

  To interact with dashboard -  [Click here](https://drive.google.com/file/d/1pQJ4vw0C-S0bhHHA8i2T02oRX3ie1dHs/view?usp=drive_link)


