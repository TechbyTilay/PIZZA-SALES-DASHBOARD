# Pizza Sales Performance Analysis: End-to-End BI Project

## Project Overview
This project involves a comprehensive analysis of a pizza restaurant's sales data. I transformed a raw dataset of over **48,000 records** into an interactive Power BI dashboard to help stakeholders identify revenue trends, monitor product performance, and optimize inventory management.

---

## Phase 1: The Data Cleaning Process (Excel & Power Query)
Before any analysis could begin, the raw data required significant preparation to ensure accuracy. I performed the following steps:

* **Date Format Standardization:** The original "Order Date" column was in a format (DD-MM-YYYY) that Power BI could not parse. I used the "Using Locale" feature in Power Query to convert these into valid Date objects.
* **Redundancy Removal:** I identified and deleted unnecessary ID columns that did not contribute to the analysis, reducing file size and improving speed.
* **Data Integrity (TRIM):** I applied the TRIM function across all text columns (Category, Size, Name) to remove hidden trailing spaces that cause grouping errors.
* **Typographical Corrections:** I audited the headers to fix spelling errors (e.g., corrected "Ingerdient" to "Ingredient") to ensure professional documentation standards.
* **Data Typing:** I ensured all financial columns were set to **Currency** and quantities were set to **Whole Numbers** for 100% mathematical accuracy.

---

## Phase 2: Data Visualization & Dashboard Design
I designed a high-contrast dashboard in Power BI to provide an immediate "at-a-glance" view of business health.

### Key Dashboard Components:
* **Executive KPIs:** High-level cards showing **$817.86K Total Revenue**, **50K Pizzas Sold**, and **48.62K Total Orders**.
* **Sales Trend (Area Chart):** A temporal analysis showing the "peaks and troughs" of daily revenue throughout the year.
* **Product Breakdown:** Donut charts illustrating that **Large (38%)** and **Medium (31%)** sizes dominate the market share.
* **Top 5 Best Sellers:** A bar chart identifying the **Thai Chicken Pizza** as the primary revenue driver.
* **Interactive Filtering:** A "Pizza Name" slicer that allows the user to filter the entire report by specific menu items.

---

## Phase 3: Business Insights & Recommendations
Data without insights is just numbers. Based on my analysis, I identified the following:

* **The Insight:** The business is highly dependent on peak "rush" days as seen in the Area Chart spikes. Additionally, the **Thai Chicken Pizza** is a massive outlier, generating the most revenue.
* **The Recommendations:** 1. **Inventory:** Prioritize stock for Large and Medium boxes, as they represent 70% of total volume. 
    2. **Marketing:** Launch a "Bundle Deal" featuring the Thai Chicken Pizza to capitalize on its popularity. 
    3. **Staffing:** Use the trend data to optimize staff shifts, ensuring more coverage during the identified peak spikes.

---

## Tools Used
* **Microsoft Excel:** Initial data auditing and cleaning.
* **Power Query:** Data transformation and locale-based date parsing.
* **Power BI:** Data modeling, DAX measures, and dashboard visualization.

---

3. **Interact with the Report:** Download the `.pbix` file to test the slicers and filters in Power BI Desktop.
 ![Pizza Sales Dashboard](pizza%20dasbboard.png)
