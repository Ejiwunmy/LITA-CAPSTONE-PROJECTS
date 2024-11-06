# LITA-CAPSTONE-PROJECTS
This is where i documented all my projects whilw learning Data Analysis with Incubator Hub.

```
### Project Title: Data sources 
The primary source of data used here is Salesdata.csv and Customerdata.csv.

```
### Tools used are:
- Mcrosoft Excel [Download Here](https://www.microsoft.com)
   1. For Ddata Cleaning
   2. For Analysing
   3. For Data Visualization
- SQL- Structured Query Language for querying of data
- Github for portfolio building

### Exploratory Data analysis
It involve the exploring of data to answer some questions about the data such as:-
 - What is the sum of sales data?
 - Which products are top seller?
 - What is the totalproduct of sales data?
 -  What are the products on peak sales?

 ### Data Analysis
 This is where we include some basic lines of code or queries used during analysis

 ```SQL
SELECT * FROM [Lita capstone salesdata]
........Number One..........
select product,
sum(quantity*unitprice) as
totalsale
From [Lita capstone salesdata]
Qroup by product;
```
    
