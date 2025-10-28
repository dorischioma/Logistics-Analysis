# Logistics Performance Analysis
An in-depth analysis of shipment completion, delivery efficiency, customer satisfaction, and regional performance for a leading logistics company. This project uses five years of operational data to uncover insights, identify bottlenecks, and recommend improvements across transport modes and delivery regions.

## Project Overview
This report provides an in-depth analysis of logistics data, focusing on shipment completion rates, in-progress shipments, shipment values, and delivery times. It is designed to track the performance of completed shipments, the status of in-progress shipments, and insights into customer satisfaction, carrier performance, and delivery metrics across different regions.
The report is split into three key sections:
1.	Overview and Shipment Trends
2.	Shipment Forecasting by Shipping Mode (Jet, Bus, Lorry, Motorbike)
3.	Customer Experience and Delivery Metrics

## Problem Statement
Despite the growing demand for logistics services between 2020 and 2024, the company has experienced increasing difficulty in maintaining delivery efficiency, ensuring consistent customer satisfaction, and optimizing shipment performance across various transport modes and regions. Shipment completion rates have been inconsistent, particularly for high-priority deliveries. Transport types such as Motorbikes and Lorries frequently underperform, with recurring delays and customer complaints. Additionally, regions like Port Harcourt have shown prolonged delivery times and lower satisfaction scores compared to others.
These inefficiencies not only affect operational reliability but also hinder the company’s ability to deliver value to its customers and manage costs effectively. Without a clear understanding of the root causes, whether they stem from mode-specific bottlenecks, poor carrier performance, regional infrastructure gaps, or misaligned resource allocation, the company risks reduced customer retention, increased delivery costs, and missed revenue opportunities.
A data-driven diagnostic and prescriptive approach is needed to uncover performance gaps and empower executives with insights to optimize delivery routes, carrier selection, and service quality.

## Goal and Objective of the Analysis:
Goal:
The primary goal of this analysis is to provide insights into the logistics performance, identify any inefficiencies, and provide actionable recommendations to optimize shipment completion and in-progress shipments. The report aims to help stakeholders understand the trends, value, and customer satisfaction levels related to the delivery process, as well as the impact of different delivery modes, to determine whether shipments arrived as and when due or not.
Objectives:
1.	Measure the completed shipments by various transport modes and track their trends over months and years.
2.	Analyze the value of shipments, including any fluctuations in shipment value over time and by transport mode.
3.	Break down shipment performance by region, particularly tracking expected shipments in each city for each transport mode.
4.	Assess customer satisfaction based on shipment performance, delivery time, and feedback on different shipment types.
5.	Highlight areas where improvements can be made in logistics efficiency, such as reducing delivery time or improving customer satisfaction.

## Data Dictionary:
Shipment ID - Unique identifier for each shipment.  
Shipment Status	- Current status of the shipment (e.g., Completed, Ready for Pickup, In Transit, Not Completed).  
Order Date - The date when the shipment was ordered.  
Delivery Date	- The actual delivery date of the shipment.  
Shipping Mode	- Mode of transport used (Jets, Bus, Lorry, Motorbike).  
Carrier Name	- Name of the logistics carrier handling the shipment.  
Shipment Weight (lbs)	- Weight of the shipment in pounds.  
Delivery Time (Days)	- Number of days it took from order to delivery.  
Delivery Location	- The final destination of the shipment (city and country).  
Shipment Cost/Weight ($)	- Cost per unit weight of the shipment.  
Loading Time (hrs) - Time taken to load the shipment, in hours.  
Loading Weight (lbs) - Weight of shipment at loading, may vary slightly from shipment weight.  
Estimated Delivery Date	- Forecasted delivery date at the time of order.  
Tracking Number	- Unique tracking number assigned to the shipment.  
Shipment Type	- Classification such as Standard, Express, or Urgent.  
Customer Type	- Type of customer (Business, Retail, International).  
Payment Status	- Indicates whether the payment is Paid, Pending, or Overdue.  
Shipment Value ($)	- Monetary value of the shipment.  
Shipment Priority	- Priority level (High, Medium, Low).  
Carrier Performance Rating	- Carrier service rating (scale of 1–5).   
Delivery Window	- Preferred delivery window (e.g., 9 AM – 12 PM).  
Customer Satisfaction Score	- Satisfaction rating (scale of 1–10).  

## Data Cleaning 
The data was already clean, and required very little to no cleaning.  

## Tools Used  
- Power BI
- DAX (for Power BI)
- Power Query

## Data Analysis & Insights  
### Overview of Shipment Status  
Key Insights:  

Completed Shipments:    
-	Total completed shipments stand at 16.74K, with a 25% increase compared to the previous year.
-	The value of completed shipments is $11.32M, with a 25% increase from the previous year.
-	The average shipment time is 9.7 days, with Jets having the fastest delivery time at 10.1 days, and Motorbikes being the slowest at 9.9 days.

In Progress Shipments:    
-	47.46K shipments are still in progress, with a 25% increase compared to last year.
-	High priority shipments account for the highest proportion of in-progress deliveries.

Shipment Trend Analysis:    
-	The report also highlights trends over the months and years, giving insights into the growth and challenges in shipment deliveries.  
  ![Overview](https://github.com/dorischioma/Logistics-Analysis/blob/main/Overview%20Page.png)
    
### Shipment Forecasting by Shipping Mode
Key Insights:

Jet Shipments:  
•	11,775 shipments are expected to be delivered by Jet, with High priority shipments accounting for 4,002 of the deliveries.  

Bus Shipments:  
•	A total of 10,861 shipments are expected to be delivered by Bus, with Medium priority shipments accounting for 3,602 deliveries.  

Lorry Shipments:  
•	12,604 shipments are expected to be delivered by Lorry, with 4,430 being Low priority shipments.  

Motorbike Shipments:  
•	12,224 shipments are expected to be delivered by Motorbike, with Medium priority shipments accounting for 4,443 deliveries.  

Regional Breakdown:  
•	Each transportation mode has its shipments distributed across different regions, including Lagos, Abuja, Port Harcourt, and more. The analysis helps identify key regional shipment trends and delivery performance.   
 ![Overview](https://github.com/dorischioma/Logistics-Analysis/blob/main/Shipping%20Page.png)  
   
### Customer Experience and Delivery Metrics  
Key Insights:

Customer Type Breakdown:  
•	Business customers account for 35.99% of completed shipments, followed by Retail and International customers at 32.85% and 31.16% respectively.

Shipment Status:  
•	Shipment status metrics track various statuses such as In Transit, Ready for Pickup, Completed, etc. The priority levels help evaluate which shipments need immediate attention.  

Satisfaction Level:  
•	Customer satisfaction is tracked for each shipment, with metrics like Very Satisfied, Neutral, and Unsatisfied reflecting the service quality.
•	Shipment Value and Delivery Time are crucial factors in customer satisfaction, with high-value shipments and longer delivery times potentially impacting satisfaction levels.  

Payment and Rating:  
•	The payment status (paid or pending) and delivery rating are tracked to correlate how the payment status impacts customer satisfaction.    
 ![Overview](![Overview](https://github.com/dorischioma/Logistics-Analysis/blob/main/Overview%20Page.png)


## Conclusion:  
This analysis provided a comprehensive view of the company’s logistics operations from 2020 to 2024, highlighting strengths, inefficiencies, and actionable areas for improvement. By breaking down shipment volumes, transport mode performance, customer satisfaction, and regional delivery dynamics, the report revealed key trends affecting overall service quality and operational efficiency.

Key takeaways include:

- A strong upward trend in completed shipments and shipment value, indicating growing demand.  
- A concerning backlog of high-priority, in-progress shipments—especially tied to less reliable modes like Motorbikes.  
- Notable differences in delivery performance and customer satisfaction across regions, with Port Harcourt requiring focused attention.  
- Clear links between customer satisfaction and factors such as delivery time, shipment value, payment status, and carrier ratings.  

This project demonstrates how data can be used not just to monitor performance, but to drive strategic decisions. With the insights and recommendations provided, the company is better positioned to:

- Streamline delivery timelines,
- Optimize transport mode deployment,
- Improve customer experience,
- And ultimately, reduce operational costs.

This project reinforces the value of data analysis in transforming raw logistics data into meaningful improvements that directly impact business outcomes.


## Key Recommendations:
-	Focus on improving the delivery times for Motorbike and Lorry shipments.
-	Prioritize high-value and high-priority shipments to ensure they are delivered promptly.
-	Use the regional insights to optimize shipment routes and carrier performance.

