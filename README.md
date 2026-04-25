# Machine-Learning-based-Late-Delivery-Risk-Prediction-in-APL-Logistics-Global-Supply-Chain-Operations

**Project Overview**

This project analyzes historical logistics and supply chain data of APL Logistics using Tableau to evaluate delivery performance and identify key factors contributing to shipment delays.
The objective is to examine delivery patterns, measure delay risks, and understand how different operational factors such as shipping mode, region, category, and order value impact delivery efficiency. The analysis also focuses on the business impact of delays on profitability and overall performance.

**Objective**

To analyze delivery performance and identify key factors contributing to shipment delays in APL Logistics using data-driven insights.

The objective includes:

•	Evaluating key business KPIs such as sales, orders, profit, and delivery metrics 

•	Analyzing shipping delays and deviations from planned timelines 

•	Examining the impact of shipping modes, regions, and markets 

•	Identifying high-risk product categories 

•	Understanding the relationship between delays and profitability 

•	Developing an interactive dashboard for monitoring performance 


**Problem Statement**

APL Logistics faces challenges related to frequent and unpredictable delivery delays, leading to SLA breaches, increased operational costs, and reduced customer satisfaction.
The organization lacks a proactive system to identify high-risk orders in advance, resulting in inefficient planning and reactive decision-making.
The task is to analyze historical logistics data to identify delay patterns and enable data-driven insights that improve delivery performance and operational efficiency.

**Dataset Information**
 
The dataset contains logistics and order-related data including:

•	Order ID – Unique identifier for each order 

•	Order Date – Date when order was placed 

•	Shipping Mode – Type of shipping (First Class, Second Class, etc.) 

•	Days for Shipping (Real) – Actual delivery time 

•	Days for Shipment (Scheduled) – Planned delivery time 

•	Late Delivery Risk – Indicator of delayed delivery (0/1) 

•	Order Region & Market – Geographic classification 

•	Category Name – Product category 

•	Sales – Total revenue per order 

•	Order Profit Per Order – Profit earned per order 

•	Order Item Quantity – Number of items per order 


**Tools & Technologies Used**

•	Tableau Public – Dashboard & data visualization

•	Microsoft Excel – Data preprocessing and cleaning 

•	CSV / Excel – Data source format 


**Data Preparation**
 
•	The dataset was imported into Tableau for analysis 

•	Missing values were handled using calculated fields where required 

•	Data types were verified and corrected 

•	New calculated fields were created for analysis: 

o	Shipping Delay = Actual Days – Scheduled Days 

o	Delay Category (Late / On Time) 

o	Order Value Category (High / Low) 

o	Profit Category (Profit / Loss) 

•	Data was structured for efficient visualization and analysis 


**Dashboard Features & Visualizations**
 
**KPI Cards (5 Key Metrics)**

<img width="392" height="236" alt="image" src="https://github.com/user-attachments/assets/8771c1ff-d095-4a6e-91fc-31d377ae5978" />



**Charts**

•	Delivery Distribution – Comparison of on-time vs late deliveries 

•	Shipping Delay Distribution – Histogram of delay deviations 

•	Shipping Mode vs Delay – Impact of shipping type on delays 

•	Regional-wise Delay Analysis – Delay comparison across regions 

•	Market-wise Analysis – Delay performance across markets 

•	Category-wise Delay Analysis – Top categories with highest delays 

•	Profit vs Delay Analysis – Impact of delay on profitability 

•	Order Value vs Delay Analysis – Effect of order value on delays 


**Key Insights**

•	 More than 50% of deliveries are delayed, indicating major inefficiencies 

•	 First Class shipping shows highest delay risk, contrary to expectations 

•	 Delay patterns are consistent across regions and markets, indicating systemic issues 

•	 Certain categories like Golf Bags & Carts have higher delay risk 

•	 On-time deliveries generate slightly higher profit, showing financial impact 

•	Order value does not significantly affect delay, indicating lack of prioritization 

 **Learning Outcomes**
 
•	Performed end-to-end logistics data analysis 

•	Developed calculated fields and KPIs in Tableau 

•	Built an interactive and professional dashboard 

•	Analyzed operational inefficiencies in supply chain 

•	Generated business-driven insights and recommendations 

•	Improved data storytelling and visualization skills 

**Dashboard**

<img width="1919" height="1028" alt="Dashboard APL Logistics" src="https://github.com/user-attachments/assets/69b08afe-580d-485c-bd88-0b7dedf22349" />

**Conclusion**

This study provides a comprehensive analysis of delivery performance within APL Logistics, highlighting key challenges related to shipment delays and operational inefficiencies. The findings indicate that delivery delays are frequent and widespread across shipping modes, regions, and product categories, reflecting systemic issues in logistics planning and execution. Although most delays are small in duration, their high occurrence significantly impacts overall performance and customer satisfaction.

The analysis also demonstrates that on-time deliveries contribute to better profitability, emphasizing the business importance of improving delivery reliability. Through the use of data-driven insights and interactive visualizations, this study identifies critical areas for improvement and supports informed decision-making.

By adopting a proactive and predictive approach to logistics management, APL Logistics can enhance its ability to identify high-risk shipments in advance, optimize resource allocation, and reduce operational costs. Overall, the implementation of these strategies will lead to improved delivery efficiency, stronger customer trust, and a more resilient and competitive supply chain system.



