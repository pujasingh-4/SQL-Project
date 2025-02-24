![17403653433312267588666841417067](https://github.com/user-attachments/assets/105103c1-3501-4e3e-b83d-09c92b6808fc)

# Walmart Sales Data SQL-Project

# About
Walmart is a chain of stores that sells a wide varity of 
Products, including groceries,clothing,electronics and more. Aim of this project is to explore Walmarts sales to understand the performance of it’s branches, also to understand the trend of different products and customers behaviour ,so that we can improve more and more to attract customers. I have collected the data from kaggle.
Purposes of sales:- The main purpose of this project is to gain 
Insights of Walmart’s sale to understand the growth and performance of different branches.
# About Data
This data is collected from Kaggle.It contains sales related data of Walmart.The data contains below column information:- 
   invoice_id VARCHAR(50) PRIMARY KEY,
	 branch  VARCHAR(50),
	 city  VARCHAR(100),
	 customer_type  VARCHAR(50),
	 gender  VARCHAR(50),
	 product_line  VARCHAR(100),
	 unit_price  NUMERIC(10,2),
	 quantity  INT,
	 tax_5	DECIMAL,
	 total  NUMERIC(10,2),
	 date_1  DATE,
	 time_1  TIME,
	 payment  VARCHAR(100),
	 cogs  NUMERIC,
	 gross_margin_percentage  NUMERIC(10,2),
	 gross_income NUMERIC(10,2),
	 rating NUMERIC(10,1));
  # Approach used
  Firstly we have to check ,is there  any null values and missing values are present in it . If  null values and missing values  are present in dataset then we have to remove it using replacement method.
1. Create Database
2.Creat table and insert data
3. Select column with not null values so that  there is no null values as we have selected not null values for each column. So null values are eliminated.
4.Added new column named “day_of_week”  to give insight of sales on day bases.
5. Added new column named  “month_name” that contains extracted month to give insight of 
   transaction on month based.


