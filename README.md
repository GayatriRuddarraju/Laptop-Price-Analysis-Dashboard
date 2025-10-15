# Laptop-Price-Analysis-Dashboard

💻 Laptop Price Analysis Dashboard
📊 Overview

The Laptop Price Analysis Dashboard is a dynamic and interactive Power BI report designed to analyze and visualize the relationship between laptop features and their market prices.
It provides key insights into how specifications like RAM, storage, company brand, operating system, and type influence pricing trends in the global laptop market.

This dashboard helps businesses, analysts, and buyers make data-driven decisions by exploring brand performance, pricing distribution, and component-based trends.

🎯 Objectives

To analyze the impact of hardware specifications on laptop prices.

To identify pricing patterns across different brands and categories.

To provide an interactive view for users to filter and compare laptops based on features.

To summarize key performance indicators (KPIs) for business insights.

📁 Dataset Information
Attribute	Description
Company	Laptop manufacturer (e.g., Dell, HP, Apple, Acer, Lenovo)
TypeName	Category of laptop (Gaming, Workstation, Notebook, Ultrabook, etc.)
Inches	Screen size (inches)
Ram	Memory size (GB)
Weight	Laptop weight (kg)
Price_euros	Price of laptop (in Euros)
OpSys	Operating system (Windows, macOS, Linux, Chrome OS, Android)
Gpu_Company	GPU manufacturer (AMD, Intel, ARM, Nvidia)
Touchscreen	Whether the laptop has touchscreen functionality (Yes/No)
Storage	Combined HDD + SSD storage capacity (GB/TB)

📦 Total Models Analyzed: 576

🧮 KPI Cards
KPI	Value	Description
Model Count	🧱 576	Total number of unique laptop models analyzed.
Average Price (€)	💰 1.13K	The mean laptop price in the dataset. Indicates market affordability range.
Average Storage (GB)	💾 620.59 GB	Average storage capacity across all laptops (HDD + SSD combined).
Average RAM (GB)	🧠 8.44 GB	Mean memory size, suggesting mid-tier to performance-level specs.
Sum of Price (€)	💶 75.9K+	Total value of all laptop models combined. Useful for revenue estimation.
Goal Comparison (Price vs. Storage)	🎯 356 (+21220%)	Benchmark goal analysis for business insight (storage-to-price ratio).
Avg Storage & Price by OS	📊 369.24 (-78.11%)	Measures the correlation between storage and price across operating systems.

These KPI cards are displayed at the top of the dashboard, offering a quick snapshot of the market summary before diving into detailed visuals.

📊 Visuals & Insights
🧩 1. Avg Price & Avg Storage by Operating System

macOS and Windows 10 laptops are priced the highest.

Chrome OS and Android are the most budget-friendly options.

Indicates brand and OS-based market segmentation.

🏢 2. Avg Storage & Avg Price by Company

Apple, Dell, and Asus dominate premium pricing segments.

Acer, HP, and Lenovo target the mid-range market.

Highlights pricing strategy differences among brands.

💸 3. Avg Price by TypeName

Workstations (€2.28K) and Gaming laptops (€1.73K) are top-priced categories.

Ultrabooks and Convertible laptops balance performance with portability.

Netbooks and Notebooks are budget-friendly for light users.

🧮 4. Avg Storage & Price by OS

Helps understand how OS impacts hardware capacity and cost.

Windows OS dominates both count and mid-range pricing.

⚙️ 5. Sum of Inches & Weight by TypeName

Gaming laptops and Workstations have higher screen sizes and weights.

Ultrabooks are lightweight with moderate display sizes — ideal for professionals on the go.

🧱 6. Avg Storage & Avg Price Trend by Company

Line chart comparing price and storage trends among all manufacturers.

Useful for identifying brand performance consistency.

⚙️ Filters & Slicers

The dashboard includes multiple interactive filters for deeper analysis:

Company: Acer, Apple, Dell, HP, Lenovo, etc.

Operating System (OS): Windows, macOS, Chrome OS, Android, Linux.

Touchscreen: Yes / No toggle for user preference.

GPU Company: AMD, Intel, ARM, Nvidia.

RAM Range: Adjustable slider for filtering laptops by RAM size.

These filters allow users to dynamically explore the dataset and focus on specific brand or technical combinations.

🧠 Key Insights Summary

💰 Workstations and Gaming laptops are significantly more expensive due to high-performance hardware.

🍏 macOS devices retain a premium even with moderate RAM/storage.

⚡ RAM and Storage strongly influence pricing, especially for high-end models.

💻 Windows OS has the widest range of models and prices.

🏢 Apple, Dell, and Asus lead in pricing; Acer and Lenovo offer competitive mid-range options.

🧰 Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard creation & visualization
Power Query	Data cleaning and transformation
DAX (Data Analysis Expressions)	KPI calculation & data modeling
Excel / CSV	Source data handling
Power BI Filters	Interactive user exploration
🚀 How to Use

Download or open the .pbix file in Power BI Desktop.

Connect the data source if needed.

Use the slicers (Company, OS, RAM, etc.) to filter and explore.

Hover over visuals for tooltips showing detailed values.

Analyze KPI cards for quick business insights.

📷 Dashboard Preview

🧩 Project Motivation

The goal of this project is to demonstrate data analysis and visualization skills using Power BI — by analyzing a real-world dataset that reflects consumer electronics market trends.
It shows the ability to transform raw data into actionable insights, a core skill for Data Analysts and Business Intelligence professionals.

🔮 Future Improvements

Add time-series analysis (price trends by year/quarter).

Integrate with web scraping or API for live market price updates.

Include profit margin or demand prediction metrics.

Enhance the design with drill-through pages and dynamic bookmarks for deeper storytelling.

👩‍💻 Author

Gayatri Ruddarraju
📊 Data Analyst | Power BI | SQL | Python

📧 Email: your.email@example.com

🔗 LinkedIn: linkedin.com/in/yourprofile

📂 GitHub: github.com/yourusername
