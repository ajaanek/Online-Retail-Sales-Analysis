# Online-Retail-Sales-Analysis A Data-Driven Approach to Optimizing Sales and Customer Insights

Welcome to my repository for the Online Retail Sales Analysis project. This project demonstrates my ability to perform a complete data analysis workflow—from data cleaning creating dynamic, insightful visualizations in Tableau. The project leverages a comprehensive dataset from Kaggle, which contains transaction-level data including product details, invoice numbers, customer information, and sales quantities.

## Project Links
- [Github Pages](https://ajaanek.github.io/Online-Retail-Sales-Analysis/)
- [Tableau Sales Dashboard](https://public.tableau.com/app/profile/ajaane.kanagasabai/viz/OnlineRetailSalesAnalysis_17332491897690/SalesDashboard)
- [Tableau Sales Analysis](https://public.tableau.com/app/profile/ajaane.kanagasabai/viz/OnlineRetailSalesAnalysis_17332491897690/SalesAnalysis?publish=yes)
- [Kaggle Notebook](https://www.kaggle.com/code/ajaanekanagasabai/online-retail-sales-analysis)


## Overview
Project Title: Online Retail Sales Analysis: A Data-Driven Approach to Optimizing Sales and Customer Insights


## Objective:
- Identify Top-Performing Products: Determine which products drive sales volume and revenue.
- Analyze Regional Sales Trends: Uncover which regions contribute most to overall revenue.
- Examine Seasonal Trends: Identify peak sales periods and seasonal fluctuations.
- Segment Customers: Understand customer behavior through segmentation based on purchase frequency, average spend, and recency.


## Data Source
The analysis uses the Online Retail Sales Dataset from [Kaggle](https://www.kaggle.com/datasets/rohitmahulkar/online-retails-sale-dataset/code). The dataset includes:
- **InvoiceNo**: Unique transaction identifiers.
- **InvoiceDate & InvoiceTime**: Timestamps indicating when orders were placed.
- **StockCode & Description**: Details about the products.
- **Quantity & UnitPrice**: Metrics of the product sales.
- **Totalsale**: Total selling price for the transactions.
- **CustomerID**: Unique identifiers for customers.
- **Country**: Geographical information of the transaction.


## Project Workflow
**Data Cleaning & Querying with Python**:
- Converted data into proper types (e.g., dates and numbers).
- Handled missing values and normalized product details.
- Created additional fields (e.g., quarters and sales periods) to facilitate analysis.

**Data Visualization with Tableau**:

After preprocessing the data in Python, I exported the cleaned dataset and built 2 interactive Tableau dashboards. These dashboards include:
- Sales Volume vs. Unit Price: To analyze product pricing and stocking strategies.
- Pareto Analysis for Items & Customers: To identify which products and customers contribute the most to revenue.
- Regional sales distribution and quarterly comparisons (including year-over-year insights).
- Customer segmentation analysis based on recency, frequency, and average spend.

<iframe frameborder="0" marginheight="0" marginwidth="0" title="Data Visualization" allowtransparency="true" allowfullscreen="true" class="tableauViz" style="display: block; min-width: 420px; max-width: 1200px; width: 100%; min-height: 587px; max-height: 627px; height: 925.5px; margin: 0px; padding: 0px; border: none;" src="https://public.tableau.com/views/OnlineRetailSalesAnalysis_17332491897690/SalesDashboard?:embed=y&amp;:showVizHome=no&amp;:host_url=https%3A%2F%2Fpublic.tableau.com%2F&amp;:embed_code_version=3&amp;:tabs=no&amp;:toolbar=yes&amp;:animate_transition=yes&amp;:display_static_image=no&amp;:display_spinner=no&amp;:display_overlay=yes&amp;:display_count=yes&amp;:language=en-US&amp;:loadOrderID=0"></iframe>
  
## Key Insights
**Product Insights**:
The analysis revealed that the top 20 products by sales volume are not the same as the top 20 by revenue. This suggests that products with high sales frequency tend to be lower-priced, everyday items, while higher-priced, premium items-though sold less frequently-drive a significant portion of the revenue.

**Regional Performance**:
A significant concentration of sales is observed in the UK, highlighting an opportunity to either expand in other regions or further optimize operations within the UK.

**Seasonal Trends**:
Seasonal analysis helped identify peak sales periods, which can guide inventory planning and targeted promotions.

**Customer Segmentation**:
By segmenting customers based on their purchase frequency, recency, and average spend, the project highlights opportunities for targeted marketing and personalized customer retention strategies.

## Technical Skills Demonstrated
- **Data Cleaning & Transformation**: Efficiently managed and preprocessed data in Python.
- **Tableau**: Built dynamic dashboards with interactive visualizations, including bar charts, scatter plots, and Pareto analyses.
- **Analytical Thinking**: Derived actionable insights from the data, providing a comprehensive view of sales performance and customer behavior.


## How to Use This Repository
- [**Github Pages**](https://ajaanek.github.io/Online-Retail-Sales-Analysis/): The complete project - including both the Kaggle Notebook and the interactive Tableau Visualizations, is available in the deployed Github Page
- [**Kaggle Notebook**](https://www.kaggle.com/code/ajaanekanagasabai/online-retail-sales-analysis): The project’s complete data analysis, including Python code for data cleaning and transformation, is available in the Kaggle Notebook (link provided in the repository).
- **Tableau Visualizations**: The dashboards created in Tableau have been exported and are showcased via GitHub Pages. Visit the Deployed Dashboard for an interactive view.
- **Source Code**: All Python scripts used in this project are included in the repository.


## Conclusion
This project exemplifies a data-driven approach to solving real-world business challenges in online retail. By integrating Python for data cleaning and querying with advanced Tableau visualizations, I have derived actionable insights to optimize sales strategies, enhance customer segmentation, and improve inventory management.
