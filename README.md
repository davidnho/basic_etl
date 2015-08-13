ETL (EXTRACT,TRANSFORM,LOAD)

source : https://en.wikipedia.org/wiki/Extract,_transform,_load

In computing, Extract, Transform and Load (ETL) refers to a process in database usage and especially in data warehousing that:

Extracts data from homogeneous or heterogeneous data sources
Transforms the data for storing it in proper format or structure for querying and analysis purpose
Loads it into the final target (database, more specifically, operational data store, data mart, or data warehouse)
Usually all the three phases execute in parallel since the data extraction takes time, so while the data is being pulled another transformation process executes, processing the already received data and prepares the data for loading and as soon as there is some data ready to be loaded into the target, the data loading kicks off without waiting for the completion of the previous phases.

ETL systems commonly integrate data from multiple applications(systems), typically developed and supported by different vendors or hosted on separate computer hardware. The disparate systems containing the original data are frequently managed and operated by different employees. For example, a cost accounting system may combine data from payroll, sales and purchasing.
