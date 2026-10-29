# power-BI-project
Starbucks Beverage Analysis Dashboard
An interactive Power BI dashboard exploring Starbucks beverage nutrition and beverage categories, including calories, sugar, caffeine, and protein.
Project Overview
This project was created in Microsoft Power BI (.pbix file). The report contains KPI cards, category-level charts, a beverage-level calorie chart, and a protein slicer to support interactive exploration of the beverage data.
Dashboard Features
Based on the visuals in the Power BI report, the dashboard includes:
- KPI cards for average calories, average sugar, total beverages, and average caffeine.
- Area chart showing average calories by beverage category.
- Column chart showing total beverages by beverage category.
- Donut chart showing average caffeine by beverage category.
- Bar chart comparing calories across beverages.
- Protein slicer to filter the report by protein values.
- Category callouts displaying values for selected beverage categories, including Coffee, Classic Espresso, Frappuccino Blended Coffee, Frappuccino Light Blended Coffee, and Shaken Iced Beverages.
Metrics and Fields
The report references these fields and measures:
Metric / field	Purpose in the dashboard
Average Calories	KPI and category comparison
Average Sugar	KPI
Total Beverage	KPI and category comparison
Average Caffeine	KPI and category comparison
Beverage Category	Groups beverages for comparisons
Beverage	Used for beverage-level calorie comparison
Protein (g)	Slicer field


The exact DAX definitions, units, and underlying dataset source are not documented in the report layout inspected for this README. Please add those details if available.
Tools Used
- Microsoft Power BI Desktop — dashboard creation and data visualization
- Power Query — include here if used for data cleaning or transformation
- DAX — include the specific measures used in the report if you want to document them
How to View the Project
1. Download or clone this repository.
2. Open starbucks-analysis.pbix in Microsoft Power BI Desktop.
3. Wait for the report and model to load.
4. Use the protein slicer and interact with the visuals to explore beverage categories and nutrition metrics.
The report is a Power BI file. A compatible version of Power BI Desktop may be required to open it.

Key Questions This Dashboard Can Help Explore
- How do average calories differ across beverage categories?
- Which beverage categories have higher or lower average caffeine?
- How does the number of beverages vary by category?
- How do calories compare across individual beverages?
- How does filtering by protein affect the displayed visuals?
These are analysis questions supported by the dashboard layout; this README does not claim specific findings beyond the values explicitly displayed in the report.
Suggested Repository Structure
Starbucks-Analysis/
├── README.md
├── starbucks-analysis.pbix
├── screenshots/
│   └── dashboard.png
└── data/
    └── (add the source dataset only if you have permission to share it)
Future Improvements
- Add a screenshot of the dashboard to the repository.
- Document the source dataset and its licensing or download location.
- Add DAX measure definitions and explain how each KPI is calculated.
- Include data-cleaning steps and data-model relationships, if applicable.
- Add a short findings section after validating the results in Power BI.
Author
Kiran Mirje
Power BI | Data Analysis | Data Visualization
