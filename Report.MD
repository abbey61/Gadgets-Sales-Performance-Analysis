# Introduction
As part of TS Academy **2026** Data Analytics training, I undertook a simulated project analyzing AdeTech, a fast-growing online gadget retailer. 
The company had been collecting large volumes of sales, customer, and product data, but struggled to extract actionable insights. My role was to act as the lead Data Analyst, responsible for cleaning, modeling, and visualizing the data to uncover trends and provide recommendations. 
This project allowed me to apply end-to-end analytics skills — from data preparation to dashboard design, using Power BI as the primary tool.

# Business Challenge
AdeTech was data-rich but insight-poor. Management lacked clarity on key performance drivers and needed answers to critical questions:

- Which products is the most profitable?

- Which product colors sold the most?

- How much revenue do the company generated in the first 3 month of 2023?

- Which month is the worst performing?

- Which customer income level ordered most? 

The challenge was to transform raw, fragmented data into structured insights that could guide executive decision-making and improve overall business performance.

# Data Overview & Preparation
**Datasets Used:**

- **Sales & Transactions:** Sales ID, product ID, customer ID, quantity, sales amount, unit cost, sales dates

- **Customers:** Customer ID, name, age, region, gender, income level, signup date

- **Product:** Product ID, product name, category, brand, color, weight

# Preparation Steps:

- Removed duplicates and standardized formats

- Validated data types and segmented numerical values

- Created calculated columns (e.g., Revenue, COGS, Profit)

- Built a clean, structured dataset ready for modeling and visualization

# Data Modeling & DAX Measures
I designed a star schema with a central Fact Table (Sales) and supporting Dimension Tables (Customers, Product). 
Relationships enabled seamless filtering and cross-analysis across dashboards.

## Key DAX Measures:

- **Anchor Metrics:** Total Revenue, Total Profit, Total COGS, Total Customer

# Dashboard Design & Insights

**Sales Performance:**

- **Total Revenue:** **₦3M** | Total COGS: **₦2M** | Profit: **₦932K**

- **Top Color Sold:** White (2051), Gray **(1744)**, Black **(1405)**

- **Top Brand:** Apple (₦197K), Lenovo **(₦160K)**, Samsung **(₦160K)**

**Customer Insights:**

- **Total Customers:** **250**

- **Profit by Income Level:** Medium income level generated the most profit while high income comes second 

- Customer order value decrease in February by 1.3% than previous month

![My image description](https://github.com/abbey61/Gadgets-Sales-Performance-Analysis/blob/main/Gadget%20Sales%20Dashboard.png)

# Recommendations


# Conclusion
This project was a rewarding opportunity to apply my data analytics skills in a real-world business context. From cleaning and modeling the data to building interactive dashboards and generating insights, I was able to uncover patterns that matter, revenue concentration, customer loyalty, and digital engagement gaps. The experience reinforced the importance of structured analysis and storytelling in driving business decisions. I am proud of the work I completed and confident that these insights can help SwiftMart or any e-commerce brand grow smarter and faster through data-driven strategies.

**[View My Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmYxNTZmNjItYTEyZi00NWQyLTg4NjAtNjE1YzI0M2VhMjRhIiwidCI6ImZjY2Y0MmRmLTE2ZDktNGU4Ny1hNmUwLWU0OTYyMjAxN2Y3NCJ9)**
