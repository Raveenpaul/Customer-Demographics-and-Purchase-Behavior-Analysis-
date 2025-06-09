# Customer-Demographics-and-Purchase-Behavior-Analysis-
Task 1: Styling Tabulation
STEPS:
Copy the data set and paste in separate sheet and iam changing the row colors into different colours 
 Applying  alternating row colors with Bold and changing  the Amount column as currency format.
Now the entire data set looks to be bold with different colors
![image](https://github.com/user-attachments/assets/f79ece8d-4812-44a7-bf7f-c390dde4105d)


Task 2:  AGE DISTRIBUTION HISTOGRAM
Select the age column press shift + ctrl+down arrow the entire ege column will be selected.
Now select Insert rippon and in that select insert statistical chart
In that select histogram chart.
The chart will be created 
After that select horizontal axis and select format axis 
In this select BIN WIDTH as 10 
And click ok
Now we can see the age gets categorized according to the age limit from (18,28),(28,38),(38,48).. 

![image](https://github.com/user-attachments/assets/371b856e-5a92-470c-bee6-fbc3d93a8581)

Task 3-Box Plot for Purchase Amounts
 Go to Axis Tiles
Choose primary  horizontal as Product category 
Choose Primary Vertical as Amount
Now the chart will be done with the output 

![image](https://github.com/user-attachments/assets/3701baeb-b16b-4d9c-8013-48161a7eb090)


Task 4-Pie Chart for Customer Distribution

Look for a column like Region, State, or Location that represents geographic regions.
Ensure each row represents one customer (or has a Customer ID column), and the region for each customer is filled in.
Insert a Pivot Table:
Select your data.
Go to Insert → Pivot Table.
Place the Pivot Table on a new sheet.
Inside  the Pivot Table:
Drag Region to the Rows area.
Drag Customer ID (or any customer field) to the Values area → change it to Count (Right-click → Summarize Values By → Count)
 Insert Pie Chart
Select the Pivot Table summary.
Go to Insert → Pie Chart → choose 2D Pie.
Right-click the pie chart → Add Data Labels → Format them to show percentage.
Highlight the Largest Region
Click on the largest slice → right-click → choose Format Data Point → use Explosion or Different Color to highlight it.

![image](https://github.com/user-attachments/assets/dda33e17-486e-44a3-ae11-92ef9309089b)

Task 5: Donut Chart for Product Revenue Contribution

Use a Pivot Table to calculate total revenue per category:
Go to Insert → PivotTable.
Select your data range → Click OK.
In the PivotTable:
Drag Product Category to Rows.
Drag Revenue to Values (make sure it is set to Sum).
Now you have total revenue per category.
Creating the Donut Chart
Select the summary table with Product Category and Total Revenue.
Go to Insert → Click on Pie Chart dropdown → Choose Donut Chart.
Add Data Labels (Percentages)
Click the chart → Click the + (Chart Elements) button.
Check Data Labels → Click the arrow next to it → Choose More Options.
In the Format Data Labels pane:
select percentage.

![image](https://github.com/user-attachments/assets/8d602903-2e08-4cf8-aaea-4d35066c3d36)

Task 6:Stacked Bar Plot for Regional Revenue by Gender
Click anywhere inside sheet
Go to Insert → Click on PivotTable.
In the PivotTable Field List:
Drag Region to Rows.
Drag Gender to Columns.
Drag Revenue (or Amount) to Values (make sure it's set to Sum)
 Insert a Stacked Bar Chart
Once Pivot Table is ready:
Select the entire pivot table (excluding Grand Totals).
Go to Insert → Click on Bar Chart icon → Choose Stacked Bar (under 2-D Bar).
Format the Chart
Add Axis Titles and Chart Title:
Chart Title: “Regional Revenue by Gender”
Axis Titles: “Revenue” and “Region”
![image](https://github.com/user-attachments/assets/452af927-cc91-432a-89d1-6f1d115e3956)

Task 7:Steps to Create Relative Stacked Bar Plot for Age Groups
Select the dataset.
Go to Insert → PivotTable
Place it in a New Worksheet.
Build the Pivot Table
Drag Region to Rows.
Drag Age Group to Columns.
Drag Purchase Amount to Values
Insert a 100% Stacked Bar Chart
Select the entire Pivot Table (without Grand Totals).
Go to Insert → Bar Chart → 100% Stacked Bar.
A chart will appear showing relative proportions of purchase amounts by age group for each region.
Insights and Business Use
Quickly identify dominant age group in each region
 Customize marketing strategies accordingly
 Allocate resources based on age-driven demand patterns
 Supports better customer segmentation
![image](https://github.com/user-attachments/assets/cd116669-ae5e-4edb-9914-627a3d65c4f8)

Task 8: Scatter Plot for Age vs. Purchase Amount
Load the dataset
Age column should be in Number format.
Similarly Amount column should be in Number Format.
Now click on Insert Rippon and select pivot chart
In the "Charts" group, click on the Insert Scatter (X, Y) or Bubble Chart icon
Change the chart type as Customer spending by Age.
Chart type change on X axis as purchase amount
For Y axis change to Age.
![image](https://github.com/user-attachments/assets/7d257af4-bdf4-4a92-ac3d-18d1bbd7be4a)

Task 9: Bar Plot for Total Purchases
Click anywhere within your data range (e.g., cell A1).
Go to the Insert tab on the Excel ribbon.
Click on PivotTable (in the "Tables" group).
In the "Create PivotTable" dialog:
Ensure the "Table/Range" is correctly selected (it should automatically select your data).
Choose "New Worksheet" for "Choose where you want the PivotTable to be placed."
Click OK.
On the right side of the screen, you'll see the "PivotTable Fields" pane.
Drag Product Category to the Rows area. This will list all your unique product categories.
Drag Product Category (again) to the Values area. By default, Excel should set this to "Count of Product Category". If it shows "Sum" or anything else, click on "Sum of Product Category" (or whatever it says), then choose "Value Field Settings...", select Count 
click OK.
![image](https://github.com/user-attachments/assets/8636303c-9af6-4b42-aa93-0ff05148e285)

























