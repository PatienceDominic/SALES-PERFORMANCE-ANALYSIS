# SALES-PERFORMANCE-ANALYSIS
The project explores a sales  dataset containing inconsistencies and missing values. The goal, analyze and derive meaningful insights from the dataset to understand product and store performance across locations, time periods and categories. Key focus areas include sales trends, product returns, stock management and location based performance.

### DATASET OVERVIEW
- Initial Total Records: 200
- Final Total Records after Cleaning: 184
- Fields : 8
- Contents of the Datasets are
    - Product Id, Product Name, Category, Price, Quantity Sold, Sale_Date, Store Location, Status, Total sales.

### TOOL USED
Excel for data cleaning and uploading 

### DATA CLEANING AND PREPARATION
In this aspect the data was loaded, inspected and cleaned . 
  - Using Power query to standardize the product name and categories,
  - Corrected the inconsistent date format,
  - Removed rows with missing data.

### EXPLORATORY DATA ANLYSIS
This involves exploring the data to answer questions like
1. How many records are missing important details like sale date or status, and how could that affect our analysis?
2. What is the total revenue generated for each product and category?
3. Can you identify any trends in sales over time, despite the inconsistent date entries?
4. Which store location sold the highest and lowest number of products?
5. What is the average price within each product category, and are there any unusual or extreme values?
6. Which products are performing best in terms of quantity sold and total revenue?
7. Are we overstocking or understocking any specific products based on the current sales data?
8. Which store locations have the highest rate of product returns, and is there any identifiable pattern?
9. Can you build a dashboard that shows product performance by category and by store location?
10. Are there certain products that are being returned more frequently than others, and why might that be?
11. How does each product’s performance differ across store locations like Lagos, Abuja, and Ibadan?
12. Can you detect any seasonal patterns in product sales even with inconsistent date formats?
13. What impact are returned products having on our overall revenue?
14. Is there any connection between a product’s category, its price, and how well it sells?

### DATA ANALYSIS
1. 108 records are missing important detales like Saale date or status
 and this can affect analyss by making it diificult to track sales ovr time, identify seasonal trends. Risk of bias and reduced accuracy.

2. Total Revenue is gotten by Price x Quantity sold
   - Top Revenue by Category is Electronics and Appliances
   - Top Revenue by Product is Toaster and Fridge.

3. #### Sales trend over time
   - GROWTH PHASE: The sales consistently increased from January to March, reaching a peak in March. This may b dur to seasonal demand, successful promotions, or other mrket factors
   - DECLINE PHASE:  From April, sales began to drop and it became more severe through June and July, which may be as a result of reduced demand, market stucture, fewer marketing         efforts etc.
4. #### Store Performance
    - The store Location with highest number of product sale is - Lagos                                                                                                                    - The store Location with lowest number of product sale is - Port harcourt.

5. The product Category with the highgest average price is Appliances.

6. #### Product Performance
    - Best performing product based on Quantity sold is Fridge
    - Best performing product based on Revenue is Toaster. 

7. no specific product is overstocked or understocked.

8. #### The highest returned rate by location
    - Lagos

9. An Excel dashboard have been created to shpow product performane and slicers for interaction within the dashboard.

10. #### Most frequent returned product 
     - fridge and laptop.
     - This could be as a result of mismatch between expectation and reality.
     - Product defects or damage.

11. #### Product  performance across locations
    - Toaster and Fridge sells more in Lagos
    - Shirt and Shoes sell more in Ibadan
    - Mobile phone and Fan sells more in Kano.

12. #### Seasonal Patterns
    - Yes, seasonal patterns can still be detected after cleaning and standardizing the dates.
    - If some dates are missing or wrongly formatted, you can impute missing values or drop the unusable records.

13. #### Return Revenue Impact
 - Returns directly lower revenue because refunded sales don’t count toward net sales.
.- Returns aren’t just lost sales — they often create additional costs:

14. #### Relation between Category.Prrice and how it sells
    - A product’s category shapes how sensitive sales are to price changes.
    - High-price will lead to low-volume of sales.
    - Luxury categories often sell fewer units but at higher margins.
    - Low-price will lead to high-volume of sales.
    - Mass-market categories rely on affordable pricing and bulk sales

#### Files
 - Sales_Data_Analysis.xlsx - Contains Raw Data, Cleaned Sheets, Pivot Tables and Dashboards.
 - README.md
 - Charts
    
