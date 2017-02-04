# MSSQL_SSIS

Developed with Visual Studio Community 2015

(All samples use the northwind database)

---

###Techs
|Tech|
|-------|
|MS SQL SERVER / SSIS|

---

###Features
|Feature|
|-------|
|Creating control tasks|
|Creating data tasks|
|Creating a SQL Server, flat file & Excel sources|
|Creating a SQL Server & Excel destinations|
|Completing & running packages|
|Running SQL commands|
|Using Data Views|
|Sorting transformations|
|Aggredate transformations|
|Sampling Data|
|Combining data using UNION ALL|
|Synchronous & Asynchronous transformations|
|Data conversion|
|Conditional Split|

### Packages
|Package|Description|
|-------|-----------|
|ExportEmployeesToExcel.dtsx|Exports Employee Table From Sql Server To Excel|
|ImportInstallersToSqlServer.dtsx|Runs a sql command to truncate installer table prior to importing data from flat file|
|LondonBerlinCustomers.dtsx| Uses a conditional split to export customers from london & berlin to different worksheets in an excel file|
|AggregateCustomers|Counts the number of customer per city and outputs to an excel worksheet|
