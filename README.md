# Data-Engineering-and-analysis-with-Pyspark   
ETL and analysis with pyspark    
  
**Summary:** This project can be broken into 3 sections: Data Engineering, Data Analysis, and Additional Data Exploration.
## Table of Contents
- [Data Engineering](#data-engineering)
- [Data Analysis](#data-analysis) 
- [Additional Data Exploration](#additional-data-exploration)  


## Data Engineering:
**Imported dependencies, created spark session, and brought in the csv files:**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/d46c0463-b4db-4a71-bbbc-696206006883)
**Dropped duplicate records:**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/a9738221-ee20-43f8-8f40-562c90d4f262)
**Joined the dataframes on matching columns**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/de158c1e-3f67-4ee7-8a06-edc086f8c1e4)

**Renamed columns and corrected datatypes:**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/866f0d59-9df7-4598-b472-cb8131471051)
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/fb83b6d2-7af9-4d0f-9505-4ef73332ed91) <br />
**Exported as parquet to my local environment and my mounted google drive**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/a2f08316-3d47-4328-aa85-0fef3c4d53e2)

## Data Analysis
**Imported dependencies, created spark session, and brought in the parquet files:**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/ed84f5db-0986-42ee-9a93-0d7f5ef241a1)

**Answered the business question: How many cars are there by make?**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/1f2e9c6f-5a45-4f17-b874-b38f1500de85)

**Answered the business question: What is the average number of cars per household? ~3.8**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/3e5bb5ca-19bb-4862-8bdf-52422430367c) <br />

**Answered the business question: What is the average age of customers? 50.56**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/9fb38ad8-6236-4f17-a280-5fa54f7d1c3a)

## Additional Data Exploration
**Answered the business question: What age group has the most claims? 65 and Over**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/783cc203-898e-44a7-992e-b98b11873e5e)

**Answered the business question: What marital status has the highest average claim price? Divorced: $1,232**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/d544a967-b59b-4626-823f-05f43be71092) 

**Answered the buisness question: Which age group has the most customers? 65 and Over: 272,098**
![image](https://github.com/dclaxto1/Data-Engineering-and-analysis-with-Pyspark/assets/128431134/47dbd6ea-8e9b-488d-b5b6-9d031ed55fd2)




