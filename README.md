# Integrated-Fiscal-Analysis-of-India-
📌 Project Title
Integrated Fiscal Analysis of India – Power BI Dashboard

📝 Short Description
This project provides a detailed fiscal analysis of Indian states using Power BI. It includes insights on Actual, Budgeted, and Revised revenue amounts, deviations, expenditure, fiscal deficit, and year-over-year growth patterns.
The project uses data extracted from the official Reserve Bank of India (RBI) website. The data was processed using Python, stored in MySQL, and finally visualized in Power BI with advanced slicers, multiple dashboards, and custom insights.

🧰 Tech Stack
•	Power BI Desktop
•	Python (for initial data preprocessing)
•	MySQL (for structured storage and view creation)
•	Power Query
•	DAX (Custom Calculations)
•	Microsoft Excel
•	Power BI Visuals: Bar charts, Line charts, Cards, Tables, Tooltips, Filters

🌐 Data Source
The dataset was downloaded from the official Reserve Bank of India (RBI) website in the form of Excel files.
Workflow followed:
1.	Downloaded Excel files from RBI website
2.	Cleaned and preprocessed data using Python
3.	Loaded the processed data into MySQL
4.	Created multiple SQL views for structured reporting
5.	Imported the SQL views into Power BI
6.	Merged tables, modeled relationships, and built visuals
	
⭐ Features

📍 1 Business Problem
India’s fiscal information is spread across many government reports and formats, making it hard to compare how different states are performing financially. It becomes difficult to understand the difference between Actual, Budgeted, and Revised amounts, track revenue or expenditure trends, or identify deviations and year-to-year changes. Because the data isn’t organized in one place, analysing state-wise performance is slow and confusing. This creates the need for a single, clear dashboard that presents all fiscal insights together.

📍 2 Goal of the Dashboard
Fiscal data in India is scattered across multiple state reports, PDFs, and government formats, making cross-state comparison slow and difficult. Policymakers and analysts often struggle to understand whether states are meeting their Budget, Revised, or Actual financial targets, and to detect deviations or year-over-year growth trends. Because the data is not centralized or visual, identifying performance gaps or financial volatility becomes time-consuming. This dashboard solves the problem by consolidating all fiscal data into a single, interactive analytical view.

📍 3 Walkthrough of Key Visuals
🔹 Dashboard 1 – All States Overview
•	Revenue Amount Comparison for Actual, Revised, and Budget (2017–2022)
•	Total Expenditure, Total Revenue, Total Fiscal Deficit, and Total Primary Deficit by Year
•	Deviation of Grants from the Centre (Waterfall Chart)
•	Year-over-Year Growth for Grants (Line Chart)
•	Insight cards describing key trends
•	Slicers Used:
oYear (between range)
o	Version
o	Revenue Type

🔹 Dashboard 2 – Individual State Insights
•	Revenue Amount for Actual, Budget, Revised for the selected state
•	Volatility between Actual, Budget, and Revised grants
•	YoY Growth for the selected state
•	Deviation trend over multiple years
•	High-performing table showing deviation and performance categories
•	Insight box summarizing state-level trends
•	Slicers Used:
o	Year (between range)
o	Version
o	Revenue Type
o	Subcategory
o	Performance Category

📍 4 Business Impact and Insights
•	Helps identify high-performing and underperforming Indian states
•	Highlights discrepancies between Actual, Budgeted, and Revised financials
•	Shows the volatility in state-level grants from the Centre
•	Displays YoY growth patterns to understand economic momentum
•	Helps governments, researchers, and analysts make informed fiscal decisions
•	Presents deviations and anomalies clearly for auditing and planning
•	Provides a unified fiscal picture across multiple years and categories

🖼️ Screenshot

1.Integrated Fiscal Analysis of India  for Allstates: https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20for%20Allstates.png 

2. Integrated Fiscal Analysis of India for Allstates Slicer Panel: https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20for%20Allstates%20Slicer.png

3. Integrated Fiscal Analysis of India for Allstates Deviation tooltip: https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20for%20Allstates%20Slicer.png https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20for%20Allstates%20Deviation%20tooltip.png

4. Integrated Fiscal Analysis of India for States Finance: https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20states%20Finance.png
   
5. Integrated Fiscal Analysis of India for States Finance Slicer Panel: https://github.com/PoornimaG-poorvi/Integrated-Fiscal-Analysis-of-India-/blob/main/Integrated%20Fiscal%20Analysis%20of%20India%20states%20Finance%20Slicer.png

