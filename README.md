# ☕ Coffee Shop Sales Analysis (Jan–June 2023)
##📌Project Overview
This project involves a comprehensive analysis of over 149,000 transactions for a multi-location coffee shop. The goal was to transform raw transactional data into actionable business intelligence to optimize inventory, staffing, and sales strategy.

📊 Key Insights (Data-Driven)
Revenue Performance: Analyzed a total revenue of $698,812.33. Identified Coffee ($269,952) and Tea ($196,405) as the primary revenue drivers.

Inventory Efficiency: Pinpointed Packaged Chocolate ($4,407) and Flavours ($8,408) as the lowest-performing categories, contributing less than 2% to total sales. Recommended a 25% reduction in these stocks to free up working capital.

Sales Seasonality: Discovered that Fridays are the highest-earning days ($101,373), while Saturdays show a surprising dip in volume (20,510 transactions), suggesting a heavy commuter customer base rather than weekend tourists.

Operational Peak: Identified the 8:00 AM – 10:00 AM window as the critical "Rush Hour," accounting for the highest transaction density.

🛠️ Technical Workflow
Data Cleaning (Power Query): Handled 149,000+ rows, removed duplicates, standardized date/time formats, and handled null values in product details.

Feature Engineering: Created new columns for "Total Bill," "Hour of Day," and "Day Name" to enable deeper time-series analysis.

Data Modeling: Built Pivot Tables to aggregate sales by category, size, and location.

Interactive Dashboard: Developed a dynamic UI using Slicers and Timelines, allowing stakeholders to filter data by Month, Location, and Product Category instantly.

📈 Visualizations Included
Total Sales by Category: (Bar Chart)

Daily Transaction Trends: (Line Chart)

Sales Heatmap by Hour: (To optimize staffing)

Product Proportion: (Pie/Donut Chart for Category Mix)

🚀 Recommendations
Bundle Strategy: Increase the Average Order Value (currently ~$4.68) by bundling high-margin Bakery items with top-selling Coffee during the morning rush.

Staffing: Reallocate staff from Saturday shifts to Friday mornings to reduce wait times and improve customer retention during peak hours.
