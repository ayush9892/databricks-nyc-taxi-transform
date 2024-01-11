# trans-nyc-taxi-data

### Concept of the Project 💡
- This project involves the acquisition of several NYC Taxi Trip Datasets from the New York City Taxi services. The primary objective is to transform the datasets using PySpark in Databricks and then load the resultant data into Delta Lake to get the useful insights from them. 
  
### Source Data: 📤
- NYC (https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [Download these Datasets](https://github.com/ayush9892/trans-nyc-taxi-data/tree/main/raw_datasets)

### Destination: 📥📍
- Azure Data Lake Gen2 Storage


### Business Requirements

1. Campaign to encourage credit card payments
   - Trips made using credit card/ cash payments
   - Payment behaviour during days of the week/ weekend
   - Payment behaviour between boroughs
     
2. Identify taxi demand
   - Demand based on borough
   - Demand based on day of the week/ weekend 
   - Demand based on trip type (i.e., Street hail/ Despatch)
   - Trip distance, trip duration, total fare amount etc per day/ borough
  

### Non Functional Requirements

   - Reporting data to be pre-aggregated for better performance
   - Pre-aggregate data for each year/ month partition in isolation
   - Able to read data efficiently for specific months from aggregated data
   - Minimize the number of aggregated tables created


# Used Technologies
- Azure Databricks (Pyspark)
- Azure Storage Account
- Azure Key Vaults
- Azure Data Lake Gen2




