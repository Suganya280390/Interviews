# Instructions

Candidates are to choose and use only 1 set to implement the task. 

Set 1. MSSQL Server, Apache Kafka, Nifi, HDFS, Hive


Set 2. MSSQL Server, Talend, MongoDB



# Task

Implement a **data flow orchestration** to process raw data, generate pipe-delimited load files in the path (/dataextract/yy/MM/dd/factstore) and lastly, loads the processed data model into a database table (dbo.factstore) for querying (see sample DDL-DML.sql).

### Pipe-delimited Data Schema
DateID: date (yyyy-MM-dd)
StoreID: Int
ProductID: Int
OnHandQty: Int
OnOrderQty: Int
DaysInStock: Int
MinDayInStock: Int
MaxDayInStock: Int


### Expected Result #1: Query average number of stocks on hand by category.

Audio: 21
Cameras and camcords: 20
Cell phones: 62
Computers: 21
Games and Toys: 75
Home Appliances: 20
Music, Movies and Audio Books:
TV and Video: 20


### Expected Result #2: Query average number of stocks on hand by store.

Catalog: 59
Online: 47
Reseller: 37
Store: 24

