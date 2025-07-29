  # Furniture-Analysis
  ![](furniture_intro.jpg)
  
  Furniture Sales and Revenue Dashboard Analysis
  
  ##**Introduction##
  This Analysis designed to offer a comprehensive overview of sales performance within a furniture business. It focuses on key metrics such as total sales, revenue, average discount percentage, average profit margin, and inventory turnover. The dashboard also breaks down sales and revenue by various dimensions like product, brand, and location, and includes analyses on correlations and potential revenue loss. **It serves as a tool for business stakeholders to monitor performance, identify trends, and make informed decisions regarding sales, marketing, and inventory management**.
  
  ##**Problem Statement**
  This Analysis appears to address several critical business problems for a furniture company:
  1.  Performance Monitoring: To track and understand overall business health by monitoring key sales and financial metrics (sales volume, revenue, profit margin).
  2.  Product Performance Assessment: To identify which furniture products and brands are performing well or poorly in terms of sales and revenue, guiding product development, procurement, and marketing strategies.
  3.  Geographic Performance Analysis: To understand sales and revenue performance across different locations (Rural, Suburban, Urban), informing targeted marketing efforts, store expansion, or resource allocation.
  4.  profitability Analysis: To monitor the average profit margin and identify potential areas of revenue loss, crucial for financial health and pricing strategies.
  
  ##**Skill Demonstrated**
  The creation of this dashboard showcases a range of analytical and technical skills:
  1  KPI Definition and Calculation: Ability to define and calculate key performance indicators (KPIs) relevant to sales and finance.
  2  Dimensional Analysis: Breaking down core metrics (Sales, Revenue) across various dimensions (Product, Brand, Location) demonstrates structured analytical thinking.
  3  Correlation Analysis: Including scatter plots to show relationships between variables (Revenue vs. Sales, Inventory vs. Sales, Discount % vs. Sales) indicates an understanding of statistical analysis.
    4  Problem-Solving (Revenue Loss): Identifying and quantifying "Revenue Loss" demonstrates a proactive approach to identifying areas for improvement.
  
  Data Visualization
   ![](FURNITURE_ANALYSIS.PNG)
  1  Proficient use of various chart types (bar charts, scatter plots, KPI cards) to effectively communicate different types of information.
  2  Dashboard Design: Logical grouping of related analyses (Sales Analysis, Revenue Analysis, Correlation Analysis, Revenue Loss Analysis) and interactive filters for user exploration.
  3  Data Interpretation: The ability to present data in a way that allows users to quickly extract insights and draw conclusions.
  
 ##** Data Transformation**
  The dashboard's design implies several data transformation steps:
  
  1.  Aggregation: Summing up individual sales transactions to calculate "Total Sales," "Total Revenue," "Sum of Potential Revenue," and "Sum of Revenue Loss." Averaging for "Avg Discount %" and "Avg Profit Margin."
  2  Calculated Fields: Deriving metrics like "Avg Discount %," "Avg Profit Margin," and "Inventory Turnover." The "Revenue Loss Analysis" likely involves a calculated field for "Potential Revenue" (e.g., sales value at full price) and "Revenue Loss" (Potential Revenue - Actual Revenue).
  3  Categorization/Grouping: Grouping sales data by "Product," "Brand," and "Location" for the various bar charts.
  4  Data Cleaning: Ensuring that product names, brand names, and location data are consistent and accurate for effective grouping.
  
   
  The filters on the left-hand side for "Category," "Brand," and "Location" directly correspond to attributes in these implied dimension tables, allowing users to slice the fact data.
  
  ##**Analytics and Visualization**
  
  Analytics:
  1  KPI Monitoring: The top section effectively uses large, clear numbers to highlight critical KPIs at a glance.
  2  Sales & Revenue Breakdown: The dashboard provides a granular view of sales and revenue performance across products, brands, and locations, enabling easy identification of top and bottom performers.
  3  Correlation Analysis: The scatter plots offer visual insights into potential relationships between variables, which is valuable for understanding drivers. For instance, the "Revenue vs Sales" plot shows a strong positive linear relationship, as expected. The "Inventory vs Sales" and "Discount % vs Sales" plots indicate less obvious or weaker correlations, which is also an important finding.
  4  Loss Analysis: The "Revenue Loss Analysis" is a proactive analytical component, directly quantifying lost revenue by product, which is highly actionable.
  
 ## Revenue Loss Visualization##:
  The "Revenue Loss Analysis" chart is particularly effective, using a red indicator to highlight the lost percentage against the potential revenue bar.
  
  ##**Feedbacks**
  
  1  Correlation Interpretation: While scatter plots are present, explicitly stating the R-squared value or correlation coefficient on the plots would provide a more quantitative measure of the relationship strength, especially for "Inventory vs Sales" and "Discount % vs Sales" where the visual correlation is not strong.
  2  Date/Time Filter: The dashboard lacks a specific date range filter, which is crucial for sales and revenue analysis. Without it, the data represents an aggregate over an unspecified period, limiting trend analysis over time. This is a significant omission for a sales dashboard.
  3  Profit Margin Breakdown: While "Avg Profit Margin" is a KPI, breaking down "Profit Margin by Product," "Brand," or "Location" (similar to Sales and Revenue analysis) could yield more actionable insights into profitability drivers.
  4  Context for KPIs: The KPIs (e.g., 26% Inventory Turnover) are presented as absolute numbers. Adding context such as benchmarks, targets, or historical trends would make them more meaningful.
  
