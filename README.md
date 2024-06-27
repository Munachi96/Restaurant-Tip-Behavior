## Restaurant-Tip-Behavior
A project that analyzed the tipping behavior in a restaurant setting. Collected over a significant period, The dataset includes various factors that could influence the tip amount customers give.


##  Table Of Content
[Project Overview](project-overview)  <br> <br>
[Data Sources](data-sources) <br> <br>
[Data Analysis Tools Used](data-analysis-tools-used) <br> <br>
[ Data Collection](data-collection) <br> <br>
[Data Cleaning and Formatting](data-cleaning-and-formatting) <br> <br>
[Loading Data into Power BI](loading-data-into-power-bi) <br> <br>
[Exploratory Data Analysis (EDA)](exploratory-data-analysis-(eda)) <br> <br>
[Data Analysis](data-analysis) <br> <br>
[Results and Findings](results-and-findings) <br> <br>
[Recommendations](recommendations) <br> <br>

## Project Overview:
The data in this dataset has been collected from a restaurant over time. Each entry represents a unique transaction, capturing details about the bill amount, tip given, the gender of the person paying, smoking preference, day of the week, time of day, and the size of the dining party. This dataset gives insight on tipping behavior and factors that influence the amount of tip given. 

##  Data Source:
the primary dataset used for this analysis was the Restaurant Tips data, containing detailed information about each activity made by the restaurant and was extracted from the company’s database using SQL codes.
SQL queries were written to the restaurant database to extract the required data for this project analysis.

## 	Data Analysis Tools used :
-	SQL (PostgreSQL) – for data collection, Data cleaning, Data Analysis
-	Power BI- for  Data Modelling, Visualization, and interactive Report creation.

##  Data Collection : 
-	Database Inspection: I inspected the restaurant database using SQL Code to check for (null) in each of the tables.
-	I extracted the required data for the analysis using SQL queries.

##  Data cleaning/ formatting:
-	I used SQL codes to clean and format the data to conform to the required data format needed for the analysis.

##  Exploratory Data Analysis (EDA): 
this involves exploring the restaurant data to answer some key questions such as :
-	What is the total revenue by the restaurant bill over the period?
-	What is the total revenue from the tips bill over the period?
-	What is the relationship between restaurant bills and tip bills in percentage?
-	Which gender gives the most tipping amount based on the analysis?
-	Based on smoking preferences which customer tipped the most?
-	What time of the day has the most tipping customer based on the analysis?
-	What days of the week have the most tipping customers based on the analysis?
-	What order size has the most tipping amount?

##	Data Analysis:
this project aims to explore a dataset on restaurant-tipping behavior setting
```SQL
/* query 1: the total bill of USD
   select "Total_bill_usd"
   from resturant_tips

/* query 2: the total tip of USD
   select "Tip_Usd"
   from resturant_tips

/* query 3: gender
    select "Sex"
   from  resturant_tips

  /* query 4: for smoker preference
      select "Smoker"
     from resturant_tips

 /* query 5: Day of the week
    select "Day"
   from resturant_tips

  /*  query 6: time of the week
    select "Time"
  from  resturant_tips

 /* query 7: the size of the order
   select "Size
   from  resturant_tips

```



## Findings 
The Analysis findings are summarized as follows

-	The total revenue by the restaurant bill over the period is accounting for $4.827.77
-	The total revenue by the restaurant tip over the period is accounting for $731.58
-	Percentage relationship, the bill amount percentage accounts for 86.84% while
  The tip amount is accounting for 13.16% 
-	Based on the analysis the Male customers have the most tips given the amount
-	Non-smoker customer gives the most tip amount.
-	The Dinner time has the most tip customers give based on this analysis compared to lunch.
-	The top the 2dyas of the week with the most tips by customers are Saturday and Sunday.
-	The 3 order sizes with the most tips given by customers are 2platter,4platters, and 3platters which were ordered during dinner time.

## 	Recommendation:
-	 The restaurant management should implement more interesting activities during lunchtime to get more engagement this will increase the revenue on both end
-	The management should invest effort in engagement  every other day of the week.




