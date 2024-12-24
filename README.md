# PowerBI - Sales-Dashboard
---

**DATASET USED**

For this analysis I have used Sales dataset where I have 4 sheets of data: 

* People - The sheet has data of the name of the Sales Person and the Team to which the Sales Person belongs to along with their picture. There are 25 Sales person distributed into 4 teams named Yummies, Delish, Juices and Tempo.
* Calendar - The calendar table has the date for each month start for which we have the data. The date starts from Jan-23 and ends at Feb-24.
* Targets - For each Sales person, we have the target Sales revenue that has to be acheived for each month from Jan-23 to Feb-24. The amount is in USD.
* Actuals - For each Sales person, we have the actual Sales revenue that has each Sales person has been able to acheive from Jan-23 to Feb-24. The amount is in USD.
---

**DATA CLEANING**

* After loading the data into the Power BI, the data has been cleaned in the Power Query.
* For each sheet the blanks were removed, data type was updated, headers were promoted. For Actual and Target sheets, data was unpivoted so that Sales data and dates were easier to be used in calculations.
* For calendar table, columns of Year, Month and Month Name were calculated and added besides the date table.
* New table was created to keep all the calculations created in one place and be easily tracked.
---

**Calculations**

* Total Sales Target - Sum of Target Sales
* Total Sales Actual - Sum of Actual Sales
* Variance - Total Sales Actual - Total Sales Target
* Variance percentage - Variance divided by Total Sales Target
* Target Status - Target status calculated as 1 for Sales target reached and -1 for Sales target not reached
* Months Target Reached - Calculated the months where targets where reached
 ---

 **Dashboard**
![image](https://github.com/user-attachments/assets/9c701469-b2b6-451c-ac13-549907ec0962)

 The dashboard consists of 4 main components: 
 **Key Performance Indicators:** 
 The KPIs include indicators such as Target Sales, Actual Sales, Variance, Variance percentage and no of months when target was reached.

 **Charts**
 There are 2 charts in the dashboard, 
 * Stacked bar graph for comparison of actual and targeted sales revenue plotted for all the months.
 * Bar graph for Target status tracking by months, where red signals not acheived and green signals acheived.
 * Table - Table is used to showcase detailed data for each Sales person, the team they belong to, sum of target sales for the individual, sum of sales target acheived for the individual, and overall status of 
   their target reach where red signals target not reached and green signals target reached.

**Slicers**
Year - The data can be filtered based on specific year, quarter and month.
Team - The data can be filtered based on the specific sales teams.



