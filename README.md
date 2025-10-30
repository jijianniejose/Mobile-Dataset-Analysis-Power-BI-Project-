
## 📊 Mobile Dataset Analysis (Power BI Project)
### 🧠 Project Overview

This Power BI project demonstrates end-to-end data analysis and visualization of a global mobile dataset, sourced directly from a SharePoint folder. It showcases a complete workflow from data acquisition and cleaning to advanced analytics, charting, and interactive reporting — ideal for both data analysts and Power BI learners.

### 🌐 Data Source

Primary Source: Microsoft SharePoint Folder

Integration Tools: Power BI Desktop + Power Query

Supporting Tools: ChatGPT (for automated column cleaning, conversion table creation, and data insights)

Data Format: Excel and CSV datasets uploaded via SharePoint

### ⚙️ Key Workflow Steps

Data Connection

Created SharePoint site and connected it to Power BI

Loaded raw mobile dataset with multiple attributes (price, RAM, camera, processor, etc.)

Data Cleaning & Transformation

Removed duplicates and standardized text formats

Cleaned columns such as PKR price, RAM, and launch price

Created conversion factor table for USD, AED, PKR, INR, and CNY

Adjusted data types and added computed columns using DAX functions

Feature Engineering

Added slicers for model filtering (Company, Launch Year, Processor, RAM)

Created new metrics for average launch price and model count per brand

### Visualizations & Insights

Overview Page: Models by company, processor count, RAM distribution

![Dashboard Overview](https://i.ibb.co/ksL5bJ10/overview.jpg)

Price Analysis Page: Launch price by model and company

![PriceAnalysis](https://i.ibb.co/gL47Pvs6/price-analysis.jpg)


Feature Comparison & Regional Analysis: Relationship between RAM, weight, battery, and price including Separate bookmarks for India,usa,china,pakistan

![Features Comparisons](https://i.ibb.co/N26SxV8Y/Features-Comparsion.jpg)


### Advanced Power BI Techniques

Implemented bookmarks and drill-through filters

Used DAX functions like CONCATENATE, LEN, IF, LEFT, SUMMARIZE, and AVERAGE

Designed interactive dashboards for comparative analysis across multiple brands

### 📈 Key Insights

Top Brands by Model Count: Oppo, Apple, and Honor lead in variety and model launches


Camera Trends: Majority of modern models use 48MP or 50MP primary cameras

RAM Patterns: Average flagship RAM ranges between 8GB and 12GB across brands

Price Distribution: Apple and Huawei dominate high-end pricing; Realme and Infinix offer budget options

Feature-Price Correlation: Higher battery capacity and RAM are positively linked with price in premium segments

## 🧩 Technologies & Tools Used

Microsoft Power BI

Power Query (ETL)

DAX (Data Analysis Expressions)

Microsoft 365 SharePoint Integration

ChatGPT (Data preprocessing and currency conversion assistance)

### 📘 Deliverables

Interactive Power BI Dashboard (.pbix)

SharePoint-linked dataset

Conversion factor table (USD base)

Visual reports: Overview, Price Analysis, and Feature Comparison

### 🚀 Learning Outcomes

Connect and automate data refresh from SharePoint to Power BI

Apply Power Query for real-world data cleaning

Build multi-page interactive dashboards with drill-through and bookmarks

Leverage AI-assisted preprocessing with ChatGPT for real-time efficiency
