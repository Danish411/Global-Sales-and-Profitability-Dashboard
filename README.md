# Global Sales and Profitability Dashboard 📈

## 1. Overview
Developed a dynamic Power BI dashboard to monitor key sales performance indicators (KPIs) across various regions, products, and customer segments. The primary goal was to provide executives with clear visibility into profitability drivers and temporal trends.

### 🎯 Goal
To accurately measure Month-over-Month (MoM) and Year-over-Year (YoY) performance changes, enabling management to quickly identify anomalies, evaluate marketing campaigns, and forecast future revenue.

## 2. Tools & Technologies
- **Business Intelligence:** Microsoft Power BI
- **DAX:** Advanced Time Intelligence Functions (`CALCULATE`, `SAMEPERIODLASTYEAR`, `DATESYTD`)
- **Data Modeling:** Calendar Table creation, Star Schema
- **Data Source:** Transactional sales data (Revenue, Cost, Units Sold, Geography)

## 3. Key Actions / Process (Metrics & Comparison)
- **Data Preparation:** Used Power Query to clean transaction data and ensured consistent data types and quality.
- **Data Modeling:** Created and integrated a dedicated **Date/Calendar Table** to guarantee accurate time-based calculations. 

[Image of Star Schema Diagram]

- **Advanced DAX:** Built robust DAX measures for Time Intelligence, including:
    - **Total Revenue (YTD, QTD)**
    - **Revenue MoM Change %**
    - **Gross Profit Margin %**
    - **Units Sold YoY Growth**
- **Comparative Analysis:** Created visualizations that allow users to compare current period performance against the previous period across regions and product lines.

## 4. Key Achievements & Results
- **Performance Monitoring:** Established a reliable system for tracking sales performance, enabling leadership to immediately focus on **underperforming regions** and **low-margin products**.
- **Efficiency:** Used DAX Time Intelligence to automate the calculation of MoM and YoY trends, **saving the Sales Operations team hours** on manual data aggregation.
- **Actionable Insights:** Identified key factors contributing to revenue spikes or dips, allowing for timely inventory and strategic pricing adjustments.

## 5. View Project
- **Live Interactive Dashboard:** [Insert Your NovyPro or Tableau Public Link HERE]
- **Source File:** SalesDataPBI.pbix (Available in this repository)
