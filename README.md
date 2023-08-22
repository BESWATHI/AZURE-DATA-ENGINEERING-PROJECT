# AZURE-DATA-ENGINEERING-PROJECT
In this project we extract the data from the API using Azure Data Factory a kind of data pipeline tool available on Azure.
So,first we will load the raw data then using AZURE DATABRICKS we will write the spark code then transform our data and then load our data back to the Transform DATA LAKE STORAGE.
Once this is done we will use SYNAPSE ANALYTICS to run the SQL queries on the top of the transform data so that we can find the insights and get the visualization on top of it.


//steps involved
We extract the data from multiple sources then we apply some transformation logic[this can be anything such as cleaning the data,removing duplicate values,null values or applying bussiness logic etc..]
Then we use the service available on Azure Cloud called DATA FACTORY.[Data Factory is an integration service where we can build data pipeline,connect to multiple sources etc..]
So we will use Azure Data Factory to extract the data from our data source and then we load data on to our DATA LAKE STORAGE.[Data Lake Storage is the object storage where we can store the file ie:STORAGE ACCOUNT].
After some basic transformation we will again load the data into our DATA LAKE STORAGE [TRANSFORMED DATA].

//IN THIS PROJECT WE HAVE USED THE OLYMPIC DATA AND BUILD AN AZURE END TO END DATA-ENGINEERING PROJECT.
