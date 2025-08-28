# US Logistics Performance Data Analysis: Shipment Trends, Costs, and Carrier Efficiency

## **Project Objective**

This project analyzes **US logistics shipment data** to identify trends in **delivery performance, carrier efficiency, and cost optimization**.
The goal is to provide insights that help stakeholders **reduce delays, lower costs, and improve supply chain reliability**.

## **Dataset Used**

- <a href="https://github.com/aagomu1/US-Logistics-Performance-Data-Analysis/blob/main/logistics_shipments_dataset.xlsx">Us Logistics Performance Data</a>

## **Questions(KPIs)**

- What is the **distribution of shipments across delivery statuses**(Delivered, Delayed, In Transit, Lost, Returned)?
- Which **carriers handle the highest shipment volumes**, and how do their performance outcomes differ?
- How have **shipment volumes and delivery performance trended over time**(spikes,delays,recoveries)?
- Which **destinations incur the highest total shipping costs**, and where are resources most concentrated?
- How does **shipment weight relate to cost**,and what role does distance play in this relationship?
- What is the **correlation between shipment distance and transit days**, and how do delays impact this?
- Which are the **Top 5 destinations with the highest number of delayed shipments**?
- How do **shipping costs and delays vary geographically** across destinations?
- How does each **carrier balance cost and transit efficiency**, and which carriers perform best overall?

## **Process**

- **Verified and cleaned shipment records** to remove missing values, standardize data types, and ensure consistency.
- Processed and validated **1,968 shipment records** across multiple destinations and carriers.
- Engineered new fields such as **Transit Days** and categorized delivery outcomes (Delivered, Delayed, In Transit, Lost, Returned).
- Conducted **exploratory and trend analysis** to uncover cost drivers, delay patterns, and carrier performance.
- Built an **interactive Power BI dashboard** with KPIs, dynamic filters, and visualizations for **carrier efficiency, cost trends, and delivery reliability**.

## **Dashboard**

- <a href="https://github.com/aagomu1/US-Logistics-Performance-Data-Analysis/blob/main/US_Logistics_Performance_Data_Analysis_Dashboard.pdf">US Logistics Performance Data Analysis Dashboard</a>

## **Project Insights**

- The majority of shipments were **Delivered(~1,600)**, while **Delayed shipments (~200)** were the second most common, highlighting reliability but with some carrier inefficiencies.
- **Lasership** managed the **highest shipment volumes**, while **DHL** showed the highest delays and **USPS** had the most shipments in transit and lost shipments.
- **Shipment volumes spiked periodically**, with delays and recoveries visible in time-trend analysis.
- **Detroit, San Fransisco, Chicago, Portland, and Minneapolis** accounted for the **highest shipping costs**, concentrating resource demand in key destinations.
- **Shipment weight and distance strongly correlate with cost**-heavier and longer-distance shipments drive higher expenses.
- **Transit days increase with distance**, but delays break this relationship, creating unpredictability in delivery times.
- **Top 5 delayed destinations** were Phoenix, New York, Portland, Seattle, and San Fransisco, making them critical risk areas.
- **Geographic analysis** revealed uneven distribution of costs and delays, with certian cities consistently underperforming.
- **UPS emerged as the most efficient carrier overall**, balancing cost and transit speed better than competitors like DHL, FedEx, and USPS.

## **Final Conclusion**

This project demonstrates how **logistics and supply chain data** can be transformed into **actionable insights for cost optimization and delivery reliability**.
By monitoring these KPIs, logistics managers and analysts can:

- **Prioritize carriers** with proven reliability to reduce risks of delays and losses.
- **Allocate resources strategically** to high-cost destinations like Detroit and San Fransisco.
- **Mitigate risk in delay-prone cities**(Pheonix, New York, Portland, Seattle, San Fransisco) through better plannning and contingency routing.
- **control costs** by analyzing weight, distance, and carrier performance to improve pricing strategies.
