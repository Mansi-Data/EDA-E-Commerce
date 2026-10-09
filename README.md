Exploratory Data Analysis of E-Commerce Sales
An interactive Microsoft Excel dashboard built to explore e-commerce sales data, identify business trends, and present key insights in a clear visual format.

📌 Project Overview
E-commerce datasets can contain large numbers of rows and multiple business dimensions, making it difficult to identify useful trends by reviewing raw data manually. This project uses Excel data-preparation tools, PivotTables, PivotCharts, and slicers to turn sales data into an interactive dashboard.

🎯 Objectives
- Organize and prepare raw sales data for analysis.
- Summarize sales across product categories, regions, and customer segments.
- Visualize patterns using interactive charts.
- Enable users to filter dashboard views quickly.
- Support faster, data-driven business decisions.
- 
🗂️ Dataset
- Source: Kaggle — Superstore Sales dataset
- Data fields highlighted in the project: Region, Category, Sales, and customer segment
- Purpose: Explore sales performance across business dimensions.
Add the dataset link here if you redistribute or reference a specific Kaggle dataset: Kaggle dataset

🛠️ Tools & Techniques
- Microsoft Excel
- Data cleaning and preparation
- PivotTables for summarization
- PivotCharts for visualization
- Slicers for interactive filtering
- Dashboard layout and visual reporting
- 
⚙️ Workflow
1. Clean the data — check accuracy and remove blank or duplicate records.
2. Summarize the data — use PivotTables to condense the dataset.
3. Segment the data — organize results by category, region, and customer segment.
4. Create charts — build PivotCharts to visualize sales patterns.
5. Add interactivity — connect slicers to the charts so filters update the dashboard.
6. Review findings — use the dashboard to identify trends and compare business areas.
7. 
📊 Dashboard Visualizations
The project includes the following visualizations:
- Sales by Category: Pie chart
- Sales by Region: Pie chart
- Customer Segment: Bar chart
The dashboard also uses slicers for interactive filtering. The presentation describes linking slicers to the visual charts so selections can update the dashboard together.

🔎 Key Findings
According to the analysis presented in the project:
- Top region: The West region generates the highest total sales.
- Main customer segment: The Consumer segment outpaces Corporate and Home Office.
- Product demand: Sales are described as balanced across Furniture, Technology, and Office Supplies.
These findings reflect the project presentation and should be revalidated against the final workbook and dataset if the underlying data or filters change.

💡 Challenges & Solutions
Challenge	Solution
Large amounts of raw data	Summarized data with PivotTables
Trends were difficult to spot by scrolling through rows	Used charts for visual comparison
Recreating charts could disrupt slicer connections	Used a copy-paste workflow for the base PivotTable and modified the relevant columns
Multiple business areas needed to be monitored	Combined visualizations into one dashboard

🚀 How to Use
1. Download or clone this repository.
2. Open the Excel workbook included in the repository.
3. If prompted, enable editing and confirm that the workbook's data connections or PivotTables are available.
4. Use the dashboard slicers to filter the data.
5. Compare the charts to explore sales performance by category, region, and customer segment.
Note: The PDF presentation describes the project but is not itself an interactive Excel dashboard. Include the actual .xlsx workbook in the repository for users to interact with the dashboard.

📁 Suggested Repository Structure
exploratory-data-analysis-ecommerce-sales/
├── README.md
├── data/
│   └── superstore_sales.csv        # Add if sharing is permitted
├── dashboard/
│   └── ecommerce_sales_dashboard.xlsx
└── presentation/
    └── project_presentation.pdf

    Adjust the folder and filenames to match the files you actually upload. Do not commit private, restricted, or otherwise unauthorized dataset files.
🔮 Future Improvements
- Add more KPIs, such as total sales and order counts, if supported by the dataset.
- Explore profit and discount trends if those fields are available.
- Add time-based analysis to compare sales across months or years.
- Improve dashboard usability with clearer labels and filter instructions.
- Validate the reported findings against the source data.
👤 Author
Mansi Agrawal
📄 License & Data Attribution
Add a license if you intend to publish this project for reuse. Review the dataset's license and attribution requirements before redistributing the data. Credit any third-party images or assets used in the presentation.
