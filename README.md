# sql-project-cgi
SQL mini-project for CGI Data Science

[Trello Board]()

## About the Project

You are provided with historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas.

 There are 3 Tables – `Stores`, `Features` and `Sales`

## Instructions

- [ ] Make sure you have created a cluster in the compute section - click on create cluster, name it anything, keep the settings as default, and press create cluster - once created navigate back to this notebook and ensure in the top left you are attached to the cluster that you just created and is running. 
- [ ] Please do not alter the code block below, just run the cell. It is pulling files from a google drive and creating the three SQL tables you will need to complete the exercise:
  - `sales`
  - `stores`
  - `features`
- [ ] There are three cells that output a preview of the three tables created. Use these to understand the structure of the tables. 
- [ ] Please answer all questions using only Databricks SQL syntax. 
- [ ] Remember to start each cell with `%sql` 
- [ ] Use [this documentation](https://docs.databricks.com/sql/language-manual/sql-ref-functions-builtin.html) if you get stuck or need some help with Databricks SQL functions.
- [ ] General Databricks SQL Documentation [can be found here](https://docs.databricks.com/sql/language-manual/index.html).

## Deliverables

- [ ] Completed Databricks Community workbook.

## Plan


## Data Dictionary

### `Stores Table`

Anonymized information about the 45 stores, indicating the type and size of store

### `Features Table`

Contains additional data related to the store, department, and regional activity for the given dates.

- `Store` - the store number
- `Date` - the week
- `Temperature` - average temperature in the region
- `Fuel_Price` - cost of fuel in the region
- `MarkDown1-5` - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
- `CPI` - the consumer price index
- `Unemployment` - the unemployment rate
- `IsHoliday` - whether the week is a special holiday week

### `Sales Table`

Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:

- `Store` - the store number
- `Dept` - the department number
- `Date` - the week
- `Weekly_Sales` -  sales for the given department in the given store
- `IsHoliday` - whether the week is a special holiday week

## Steps to Reproduce

### In DataBricks Community 

- [x] Read the README.md
- [ ] Run [this notebook]()


