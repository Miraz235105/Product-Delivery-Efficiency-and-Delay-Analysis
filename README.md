# Product Delivery Efficiency and Delay Analysis: A Case Study on "Deliver on Time"
In today's fast-paced e-commerce world, timely delivery isn't just a convenience; it's a major driver of customer satisfaction and business success. This case study explores how Deliver manages its shipments and what factors influence whether packages arrive on time.

<img width="1342" height="597" alt="Dashboard of Product Delivery Efficiency and Delay Analysis" src="https://github.com/user-attachments/assets/c3e0336d-701a-48bd-ba42-967c4de096cd" />

### Introduction
This project analyzes factors affecting on-time deliveries at Deliver, using Excel to explore shipment modes, warehouses, product characteristics, and customer interactions, with the goal of identifying patterns and insights to improve logistics and reduce delays.
### Story of Data
The dataset, inspired by Kaggle, contains e-commerce shipment records collected via automated logging systems, capturing transactions, customer interactions, and delivery outcomes. Each row represents a shipment, with columns including shipment ID, warehouse, mode, customer care calls, ratings, cost, prior purchases, product importance, high-value indicator, gender, discount, weight, weight category, and on-time delivery. Key features like shipment mode, warehouse, customer interactions, product characteristics, and discounts help evaluate efficiency and service quality, while engineered variables such as High-Value Shipment and Weight Category enrich the analysis. No limitations were identified.
### Data Splitting and Preprocessing
The dataset was reviewed to ensure no duplicates, inconsistencies, or missing values were present. Two new variables were created: "Weight Category" (Light, Medium, Heavy) and "High-Value Shipment" (based on cost and product importance). Independent variables include warehouse, shipment mode, customer care calls, ratings, cost, prior purchases, product importance, high-value indicator, gender, discount, weight, and weight category, while the dependent variable is on-time delivery. Belonging to the e-commerce and logistics industry, the analysis is relevant for improving operational efficiency, customer satisfaction, and resource allocation. Key stakeholders include logistics, customer service, management, and marketing teams, with insights helping optimize routing, warehouse allocation, prioritization, and overall service reliability.
### Pre-Analysis
In the pre-analysis phase, initial exploration highlighted key trends affecting delivery outcomes. Shipment mode and warehouse block influence on-time performance, with certain modes and locations performing better. Multiple customer care calls often correlate with delays, while heavier or high-priority products tend to arrive on time. Early observations suggest possible links between customer rating, discount offered, and prior purchases with delivery efficiency. Overall, shipment mode, warehouse, product weight, and customer interactions appear to be the most influential factors, guiding deeper analysis of delays and operational patterns.
### In-Analysis
**Key Patterns Observed:**
-Flight shipments have slightly higher on-time delivery rates than Ship and Road modes.
-Heavier or high-value products tend to be delivered on time more consistently, likely due to priority handling.
-Shipments with multiple customer care calls experience higher delays, indicating unresolved issues.
-High-volume discount periods may cause operational strain and delays.
**Preliminary Recommendations:**
-Prioritize Flight shipments for time-sensitive or high-priority deliveries.
-Optimize Ship and Road operations by reviewing bottlenecks, routes, and staffing.
-Monitor customer queries proactively, resolving issues faster to prevent escalation.
-Allocate additional resources during high-volume discount periods to reduce delays.
### Post-Analysis and Insights
**Key Findings:** Based on the completed analysis, several significant insights emerged:
-Although Ship mode handles the largest number of on-time deliveries, Flight has the highest on-time delivery rate.
-While most deliveries are on time, delays among Very Satisfied, Dissatisfied, and Neutral customers highlight service gaps that require targeted improvements to maintain satisfaction.
-Warehouse F has the highest number of on-time deliveries but also the highest number of delays, likely because it handles the largest volume overall.
-Heavy shipments dominate delays, making this group the biggest contributor to delays.
-Most Delayed Deliveries Come from Customers Who Called 3–4 Times.
-Although most shipments are Standard products, High-value shipments receive slightly better prioritization, resulting in fewer delays proportionally.
-All delayed orders occur in the 1–10% discount range, and the same discount range has the highest on-time delivery rate.
-Customers with 3 prior purchases had more on-time deliveries than delayed deliveries.
### Data Visualizations & Charts
Visual representations were created in Microsoft Excel to simplify complex data relationships and highlight key patterns related to the delivery status. The Clustered Column Chart showed Delivery Timeliness by Transport Mode, Delivery Performance by Discount Range, Delivery Performance Across Warehouses, the Pie Chart showed Overall Delivery Performance, the Bar Chart showed Frequency of Complaints among Delayed Orders, and the Stacked Column Chart showed Top Prior Purchases by Delivery Performance.
A consolidated dashboard provides an at-a-glance view of how shipment, customer, and product variables interact with on-time delivery, helping stakeholders quickly identify high-risk segments and factors contributing to delays.
### Recommendations
**Actionable Insights:**
-Prioritize operational improvements in Ship and Road deliveries.
-Optimize handling, routing, or consider staggered scheduling.
-Implement targeted monitoring or priority handling.
-Review resource allocation during high-volume standard discount periods.
-Establish faster issue resolution for multiple complaints.
-Focus on process improvements, staffing, or equipment upgrades.
**Optimizations / Business Decisions:**
-Prioritize high-risk segments (heavy shipments, high-volume warehouses, standard products) for resources.
-Consider predictive scheduling to match shipment mode and product type with delivery reliability.
-Use dashboards to monitor real-time performance and intervene promptly in delayed shipments.
### Conclusion
The analysis shows Ship mode and heavy shipments contribute most to delays, while Flight and medium-weight shipments are more reliable. Repeat customers and low-discount orders face higher delays, with Warehouse F being critical due to its volume. Limitations include a lack of external and granular operational data. Future research should explore real-time tracking, customer segmentation, and strategies to optimize high-volume and heavy shipments.
Explore the full technical report and dataset on GitHub: 
### References
Dataset Source: [E-Commerce Shipping Data]([url](https://www.kaggle.com/datasets/prachi13/customer-analytics?)).
Tools Used: Microsoft Excel (Pivot Tables, Charts, Dashboard).
External Resources: Literature on delivery logistics and operational efficiency, research on customer satisfaction and shipment prioritization strategies, online tutorials, and documentation for Excel analytical functions.

**Appendices:** Additional charts, tables, and raw data snapshots
