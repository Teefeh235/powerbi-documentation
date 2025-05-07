# PowerBi Office Supply and pinnacle dashboard

### Overview
### This project analysis aims to provide insights into the sales performance of a company over two years. By analysing various aspect of the dataset,we seek to identify the product sold between the years showing number of sales, sales proprtion and financial performance.
### The analysis will be used to determine whether there is growth or decline on any product, what key products are the drivers of perfprmance. if there is any product to discontinue due to poor outcome,what product would it be and what product do we pay the highest tax on.



### Data Importation
### Choose the data source: commom format include Text/CSV,Excel, SQL database,Dataverse,Web.
### Use appropriate tools to load the data.


### Data cleaning and processing using the power query editor
### Handling missing values.
### Remove unwanted columns
### Remove duplicates and nulls
### Convert data types, ensure numeric columns are properly formatted for calculations
### Format and sort data: remove unnecessary data and arrange logically
### Close and apply to load the data into table view


### Load Data into a Table View
### Perform calculations on the data
### Apply Mathematical operations using the following formulas:
### Discount Rate={[IF(Discount band) = "None",0, IF(Discount band)="Low",0.01,IF(Discount band)="Medium",0.05,0.1]}
### Gross sales= Unit sold * Sale price
### Discount= Discount rate * Gross sales
### Revenue= Gross sale - Discount
### Manufacture cost= Unit sold * Manufacturing price
### Profit before tax= Revenue - Manufacturing cost
### Profit Margin = Profit / Revenue * 100
### Tax = 0.05 * Profit before tax
### Perform these calculation either on a new column or new measure( callout the function sumx followed by the table title and perform the calculations)


### Data Visualization (Visualize the data to gain insights):
### Product sold between jan and dec 2014 showing number of sales,sales proportion and financial performance
### The analysis will be used to determine whether there is growth or decline on any product lines
### What key product are the drivers of performance
### Any product we would like to discontinue due to poor outcome
### what product do we pay the highest tax on

### Refine canvas (background, width and height)
### Select the right chart type e.g bar chart(compare categories), line chart(shows trend), pie chart(display proportion)
### Format charts using the format pane
### General formatting: Title, Background, Borders and shadows
### Data formatting: Data label, Axes and Legends


    

