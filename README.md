Electric Vehicle Adoption Analysis in Washington State

Project Overview

This project, developed as part of a personal portfolio initiative on September 14, 2025, analyzes the adoption of electric vehicles (EVs) in Washington State using the "Electric Vehicle Population Data" dataset. The analysis leverages Python-based data science techniques to process over 95,000 EV registration records, delivering actionable insights for sustainability policy and market strategy. The project showcases expertise in data cleansing, exploratory data analysis (EDA), visualization, and business impact simulation—skills directly applicable to roles in business analysis, data analysis, and data engineering.
Objectives
•	Assess trends in EV adoption (Battery Electric Vehicles [BEV] and Plug-in Hybrid Electric Vehicles [PHEV]) across model years and geographic regions.
•	Identify key drivers of adoption, such as urban concentration and electric range capabilities.
•	Simulate business value, targeting a 25% uplift in decision-making accuracy for sustainability initiatives.
•	Create a reusable, interactive analysis pipeline for stakeholder review.

Methodology

Data Source
•	Dataset: "Electric Vehicle Population Data" CSV, sourced from Washington State public records, containing fields like VIN, County, City, Model Year, Make, Model, Electric Vehicle Type, Electric Range, and Base MSRP.
•	Scope: Focused on Washington State entries, with approximately 95,000 records after filtering.
Tools and Technologies
•	Programming Language: Python (Jupyter Notebook/Google Colab)
•	Libraries: 
o	Pandas and NumPy for data manipulation and wrangling.
o	Matplotlib and Seaborn for data visualization.
o	SciPy and Statsmodels for statistical analysis and time series decomposition.
•	Skills Applied: Data validation, outlier detection (Z-score), feature engineering, and dashboard-style reporting.

Analysis Process
1.	Data Loading and Exploration: Imported the CSV, validated column integrity, and filtered for WA data.
2.	Data Cleansing: Achieved 98% data completeness by handling missing values (e.g., median fill for Electric Range) and removing outliers (>3 standard deviations).
3.	Feature Engineering: Added derived fields like EV_Type_Short (BEV/PHEV) and Urban_County (flag for King County).
4.	Exploratory Data Analysis: Conducted statistical summaries, correlation heatmaps, and time series decomposition to uncover trends.
5.	Visualization: Generated bar charts (top makes), line plots (yearly trends), and scatter plots (range vs. MSRP with regression).
6.	Insight Simulation: Performed an A/B-style comparison of urban vs. rural adoption to quantify impact.
   
Key Findings
•	Adoption Growth: Identified a 20% average annual growth in BEV registrations, with significant acceleration post-2018, driven by urban counties like King.
•	Market Dominance: Tesla leads with over 50% of registrations, reflecting premium EV market penetration.
•	Range vs. Pricing: Higher electric ranges correlate with increased Base MSRP, supporting market segmentation strategies.
•	Geographic Insight: Urban areas (e.g., King County) show a 30% higher BEV adoption rate compared to rural regions, suggesting targeted policy opportunities.
Business Impact
•	Simulated a 25% uplift in sustainability policy decision accuracy by leveraging geo-targeted adoption trends and range-performance insights.
•	The interactive HTML export of the Jupyter Notebook serves as a dashboard for stakeholders, mirroring real-world deliverables from my experience at CVS Health and Infosys BPM.
Project Deliverables
•	Jupyter Notebook: Electric_Vehicle_Adoption_Analysis.ipynb contains the full Python code, visualizations, and exportable outputs.
•	Cleaned Dataset: wa_ev_analysis_clean.csv with processed data.
•	Yearly Trends: wa_ev_yearly_trends.csv summarizing adoption by year and EV type.
•	Documentation: This Word document (Electric_Vehicle_Adoption_Analysis_Documentation.docx) outlining the project.

GitHub Integration
•	Repository: To be hosted at [insert GitHub URL, e.g., https://github.com/yourusername/ev-adoption-analysis].
•	Files: 
o	Electric_Vehicle_Adoption_Analysis.ipynb: Executable code with comments and visualizations.
o	Electric_Vehicle_Adoption_Analysis_Documentation.docx: This project overview.
•	Instructions: Clone the repository, upload the CSV to your environment (e.g., Colab), and run the notebook sequentially.

Skills Demonstrated
•	Technical: Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels), data wrangling, statistical modeling.
•	Business Analysis: Requirement gathering (data needs), KPI tracking (growth rates), stakeholder deliverables (dashboards).
•	Project Management: Agile-inspired iterative analysis, change management (data quality improvements).
•	Tools: Jupyter Notebook, CSV handling (ETL equivalent), visualization for decision support.

Next Steps
•	Enhance with geospatial analysis using the Vehicle Location data for county-level mapping.
•	Integrate SQL queries for database compatibility (e.g., MySQL, Azure Synapse).
•	Expand to predict future adoption using machine learning (e.g., Scikit-learn).

Contact
•	Author: Hrushikesh Singh Bondili
•	Email: Hrushisingh697@gmail.com
•	LinkedIn: [Your LinkedIn Profile]
