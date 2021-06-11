# Power-BI-AdventureWorks-Performace-Report

The data consists of multiple tables such as Customers, Sales, Products, Budget, Regions, and Calendar. Report shows the drill down of the AdventureWorks' performance in terms of sales for the year 2016. 

The data and format of Budget table was not Power BI friendly. Hence, used "Query Editor" to transform the data into a readable format by unpivoting columns, removing irrelevant rows, promoting the first row as headers, and changing data types where needed.  

In the "Model" phase all the 6 tables were linked using the Relationship Model and their common columns. Several "Measures" have been created on the fly using DAX to help with computation and saving up space by minimizing the creation of new computed columns. 

The final stage consists of creating and publishing "Visualization" or reports to easily read and understand the performance of AdventureWorks in the year 2016. Utilized various tools such as Column Chart, Bar Chart, Line Chart, Card, and Table by making necessary changes to their formatting style.

P.S. In case you are unable to open the .pbix file here on GitHub, please navigate to the below link where the report is published. 

Power BI Report Link: https://app.powerbi.com/groups/me/reports/72c6a687-1f34-4a7b-8ca7-cffba730749d/ReportSection?ctid=6edb49c1-bf72-4eea-8b3f-a7fd0a25b68c
