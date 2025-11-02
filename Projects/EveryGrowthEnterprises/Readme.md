# Ever Growth Enterprises

## Project Brief
• Ever Growth Enterprises deals as a emerging market product distribution company and sales company that
runs the business across several zones, distributed in different countries, etc.  
• The company keeps track of sellers, customers, products, reviews, payment types, etc.

## Problem Statement:
• The very first issue if that the data is being stored in different storage locations as different regional managers
have their own method of storing the data.  
• To have the overall view of the data from it becomes a time consuming task to gather the files from all the
storage locations, analyse it and get the answers for some of our KPIs  
• Urgent need of a platform which can gather data from multiple sources, store it, can give us insights and help
us save time for our employees.

## Understanding Data and Locations:
1. Sellers Data – This folder contains the sellers data, you need to load the data inside this folder “as a folder” in
Power BI.  
2. Flat Files Folder – This folder contains two folders:  
   a. JSON File: - This folder contains the “Products Data” as JSON file. Load the file directly into Power BI  
   b. CSV Files:- This folder contains the “Customers Data”, “Orders Data” and “Geolocation Data”. Load
   the CVS files one by one into Power BI  
3. Snowflake Folder –  
   a. You will need to create database, create tables, load the data into the tables in snowflake.  
   b. Then you will need to load all the four tables into Power BI.  
      i. Order Payments Data  
      ii. Orders Item Data  
      iii. Product Category Data  
      iv. Orders Review Data  
   c. Note that the storage mode must be import.

## Transformations to be performed:
1. Add an index column in the PRODUCT CATEGORY table.  
2. In the Orders Review Data table, go to column Review comment title. Replace all blank values with “Review
not given”  
3. In the Orders Payment Data table, reduce the decimal value of the columns PAYMENT_INSTALLMENTS, and
PAYMENTS_VALUE to 1 decimal value after point.  
4. In the Orders Item Data, based on the shipping_LIMIT_DATA column add the columns  
   a. Month  
   b. Year  
   c. Name of the Month  
   d. Quarter of the Year  
5. Load the data into the PowerBI, create a notepad list, where you need to identify and mention the “PRIMARY
KEY” from each table.

## Data Modelling:
• You will need to perform the data modelling, and create correct relationships between different tables.

## Data Visualization:
• No need to perform data visualization, we will explore that.

## Dataset Link:
DatasetLink: https://github.com/Guruvendra47/PowerBI/tree/main/Projects/EveryGrowthEnterprises/Data


