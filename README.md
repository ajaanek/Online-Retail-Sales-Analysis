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
**InvoiceNo**: Unique transaction identifiers.
**InvoiceDate & InvoiceTime**: Timestamps indicating when orders were placed.
**StockCode & Description**: Details about the products.
**Quantity & UnitPrice**: Metrics of the product sales.
**Totalsale**: Total selling price for the transactions.
**CustomerID**: Unique identifiers for customers.
**Country**: Geographical information of the transaction.


## Project Workflow
**Data Cleaning & Querying with Python**:
- Converted data into proper types (e.g., dates and numbers).
- Handled missing values and normalized product details.
- Created additional fields (e.g., quarters and sales periods) to facilitate analysis.

**Data Visualization with Tableau**:

After preprocessing the data in Python, I exported the cleaned dataset and built interactive Tableau dashboards. These dashboards include:
- Sales Volume vs. Unit Price: To analyze product pricing and stocking strategies.
- Pareto Analysis for Items & Customers: To identify which products and customers contribute the most to revenue.
- Regional sales distribution and quarterly comparisons (including year-over-year insights).
- Customer segmentation analysis based on recency, frequency, and average spend.

  <div class='tableauPlaceholder' id='viz1739553242404' style='position: relative'><noscript><a href='#'><img alt='Sales Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;On&#47;OnlineRetailSalesAnalysis_17332491897690&#47;SalesDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OnlineRetailSalesAnalysis_17332491897690&#47;SalesDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;On&#47;OnlineRetailSalesAnalysis_17332491897690&#47;SalesDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1739553242404');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='1200px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='627px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='1200px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='627px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1527px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

  
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
- **Kaggle Notebook**: The project’s complete data analysis, including Python code for data cleaning and transformation, is available in the Kaggle Notebook (link provided in the repository).
- **Tableau Visualizations**: The dashboards created in Tableau have been exported and are showcased via GitHub Pages. Visit the Deployed Dashboard for an interactive view.
- **Source Code**: All Python scripts and SQL queries used in this project are included in the repository.


## Conclusion
This project exemplifies a data-driven approach to solving real-world business challenges in online retail. By integrating Python for data cleaning and querying with advanced Tableau visualizations, I have derived actionable insights to optimize sales strategies, enhance customer segmentation, and improve inventory management.
