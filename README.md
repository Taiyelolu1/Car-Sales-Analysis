# Car Sales Analysis
This project analyzes car sales based on the company, transmission, dealer region etc. It provides an overview of the kind of transactions made between 2022-2023. It also shows the growth rate, if any.
### Step 1: Data Collection
* This dataset was provided by a friend.
### Step 2: Data Cleaning
* The dataset didn't require any cleaning to be done on it.
* I made sure that the data types were properly assigned.
### Step 3: Data Analysis
I made use of DAX (Data Analysis Expressions) in Power BI to get the KPIs (Key Performance Metrics). 
* I created a new DateTable with columns for Year, Month, MonthNumber, Day of the Week, and Qtr and sorted the Month column by MonthNumber. 
* I also created measures for Total sales, Total number of transactions, Total number of transmission by type (Auto and Manual) and Sales growth (%).
* I made sure to format these measures appropriately.
* I connected both tables (Car Sales and DateTable) to get the most out of my analysis. 
### Step 4: Data Visualization
The visualization was done using Power BI. I made use of the measures I created for the KPIs and also used them in the various charts because making use of Explicit Measures is a good practise. A stacked area chart was used to show change in sales over time, the donut chart was used to show proportional distribution of various categories (Auto and Manual). Bar and Column charts were used to compare categories like top selling companies, sales by colour and sales by dealer region. 

You can view the snapshot to my visualization below: 

![Car Sales Dashboard](https://github.com/user-attachments/assets/e78dd6ab-b7e6-474e-9239-64d2eb0f031d)

### Key Insights
1. The total number of transactions amounted to 23,706.
2. Total sales between 2022-2023 was $671.53M, of which $300.34M (2022) and $371.91M (2023).
3. January and February had the least car sales for both years. 
4. The percentage growth in sales between 2022 and 2023 was 23.6%.
5. The top selling companies were Chevrolet, Ford and Dodge. 
6. More people bought Automatic cars than Manual cars. Total Automatic cars sold were 12,571 and Manual 11,335.
7. In terms of car colour, pale white took the lead. 11,256 pale white cars, 7,857 black cars, and 4,793 red cars were sold. 
8. Austin had the highest sales for car dealer region. 
## Recommendation
The drop in sales during the months January and February should be looked into. Further analysis should be carried out to that effect with the provision of data that can be helpful for this analysis.
