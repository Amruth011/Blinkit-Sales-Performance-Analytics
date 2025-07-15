# Blinkit Sales & Performance Analytics

## Project Overview
This project involves a comprehensive end-to-end data analysis of grocery retail sales data, aiming to uncover key performance indicators (KPIs), identify sales trends, and provide actionable insights for strategic business decision-making. The analysis covers data cleaning, exploratory data analysis (EDA), and interactive dashboard creation.

## Problem Statement / Goal
The primary goal of this project was to understand the underlying patterns and drivers of sales within the Blinkit grocery dataset. By analyzing various dimensions such as item properties, outlet characteristics, and geographical factors, the project aimed to:
* Identify top-performing products and outlets.
* Understand sales distribution across different categories and locations.
* Derive key metrics to assess overall business performance.
* Provide a visual and interactive platform for stakeholders to explore data and make informed decisions.

## Data Source
The analysis is based on the `BlinkIT Grocery Data.csv`/ https://github.com/Amruth011/Blinkit-Sales-Performance-Analytics/blob/main/BlinkIT%20Grocery%20Data.csv dataset, which contains detailed information about various items sold, their properties, sales figures, and characteristics of the outlets.

## Methodology & Analysis Steps

The project followed a structured data analysis pipeline:

1.  **Data Cleaning and Preprocessing (SQL):**
    * Performed initial data inspection and identified inconsistencies.
    * Cleaned and standardized the `Item_Fat_Content` field to ensure data accuracy and consistency for analysis (e.g., standardizing 'LF', 'low fat' to 'Low Fat', and 'reg' to 'Regular').
    * Calculated fundamental KPIs like Total Sales, Average Sales, Number of Items, and Average Rating.

2.  **Exploratory Data Analysis (EDA) with Python:**
    * Utilized **Python** (Pandas, Matplotlib, Seaborn) within a Jupyter Notebook to conduct in-depth exploratory data analysis.
    * Analyzed sales distribution by various categorical features such as `Item_Type`, `Outlet_Size`, `Outlet_Location_Type`, and `Item_Fat_Content`.
    * Identified relationships between item/outlet characteristics and sales performance through visualizations.

3.  **Data Visualization & Dashboarding (Power BI):**
    * Developed an interactive **Power BI dashboard** to present key findings and insights dynamically.
    * Visualized sales trends, item performance, outlet contributions, and other relevant metrics.
    * The dashboard allows stakeholders to filter and drill down into data, facilitating self-service analytics and aiding strategic planning.

## Key Findings & Insights
* [**Example Insight 1:** You can add specific insights you found, e.g., "Identified that 'Tier 1' Outlet Locations consistently generated the highest sales." (Based on your Power BI dashboard, 'Tier 1' is a prominent category)]
* [**Example Insight 2:** "Certain item types or fat content categories show significantly higher sales volumes, indicating areas for focused marketing or inventory management." (Based on your SQL queries and Python analysis)]
* [**Example Insight 3:** "Visualized month-over-month sales trends to identify peak seasons and potential dips." (If your data had a time component or you derived this)]

## Technologies Used
* **Programming Languages:** Python (Pandas, Matplotlib, Seaborn)
* **Databases & Querying:** SQL (for data cleaning and KPI derivation)
* **Business Intelligence & Visualization:** Power BI
* **Development Environment:** Jupyter Notebook, VS Code (for code editing and management)
* **Version Control:** Git, GitHub
* **Softwares used:** Jupyter(Python), SSMS(SQL), Excel, &  Power BI

## Files in this Repository
* `Blinkit analysis.ipynb`: Jupyter Notebook containing the Python code for data loading, EDA, and visualization.
* `Blinkit Data Analysis Project Report.docx`: Word document containing SQL queries used for data cleaning and KPI calculation.
* `BlinkIT Grocery Data.csv`: The raw dataset used for the analysis.
* `blinkitPOWERBI2.jpg`: Screenshot of the interactive Power BI dashboard.
* `blinkitPYTHON.jpg`: Screenshot of Python code/visualizations from Jupyter.
* `blinkitSQL.jpg`: Screenshot of SQL queries.
* `blinkitEXCEL.jpg`: Screenshot of Excel data.

## How to View / Run This Project
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Blinkit-Sales-Performance-Analytics.git](https://github.com/YourUsername/Blinkit-Sales-Performance-Analytics.git)
    cd Blinkit-Sales-Performance-Analytics
    ```
2.  **SQL Queries:** Review the `Blinkit Data Analysis Project Report.docx` for the SQL commands used.
3.  **Python Analysis:** Open `Blinkit analysis.ipynb` in Jupyter Notebook or Google Colab to run the Python code and explore the EDA steps.
4.  **Power BI Dashboard:** View the `blinkitPOWERBI2.jpg` image for a snapshot of the dashboard. For the interactive version use : https://github.com/Amruth011/Blinkit-Sales-Performance-Analytics/blob/main/Blinkit%20Analysis%20Dashboard.pbix / ` Blinkit Analysis Dashboard.pbix` file.

---
## Snapshots
### DASHBOARD - POWER BI
![WhatsApp Image 2025-07-14 at 21 58 51_2b8e5d45](https://github.com/user-attachments/assets/3801580e-6567-48e1-bd22-144538129f53)

### SQL - SSMS(SQL SERVER MANAGEMENT STUDIO)
![WhatsApp Image 2025-07-14 at 21 42 46_5d1fb1a5](https://github.com/user-attachments/assets/aa9e4298-55ef-45de-a92f-07482a438cf2)

### EXCEL
![WhatsApp Image 2025-07-14 at 21 58 16_1a285e4b](https://github.com/user-attachments/assets/2dfb70f8-95fe-48d3-a452-49f477a929e1)

### PYTHON - JUPYTER
![WhatsApp Image 2025-07-14 at 22 01 09_f02fbf56](https://github.com/user-attachments/assets/762c9ae3-cdde-46d0-a030-441b2c5aa9e8)
