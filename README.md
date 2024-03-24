# Uber_Data_Analysis
In this project I have attempted to analyze a Metric Data using Pandas Python

I have Explored, cleaned and analysed uber data using pandas .I have catagorised the table into fact and Dimensions table and indexed all the dimension table , changed data type , added index columns in dimension table . According to Data Dictionary for rate code and payment options , i have mapped options and type , so pandas will identify which option is mapped to what type .Finally arranged allthe columns merge the extra columns and sequenced . This helps understand data easily and also better to analyze .This is as similar to snow flake in Power BI model . 

## Date type changed of the column
<img width="440" alt="Datatype change" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/fa68d933-cb55-4d14-8bd0-670d8fab7051">

## Datetime categorized in month, day, year ,weekday
<img width="674" alt="Datetimecategorised" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/870026f0-db68-4a90-ad8e-1f14de815162">

## Date time categorised column sequenced
<img width="665" alt="Datetimecategorized columns sequenced" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/7a5481d1-8744-4844-a569-e0fb959c0ed6">

## Passenger type column - index column created and added in a dimension table   ---- similar dimension tables are  trip distance , pickup location , gropoff location 
<img width="585" alt="passenger dimension table creation" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/320ab3fc-09e4-462d-bed4-00dd41663206">

## payment options mapped to type according to Data Dictionary  ---- ---- similar dimension table is rate code type  
<img width="593" alt="Data dictionary payment options mapped with type" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/e816d51d-e3b0-4fe3-8f62-23b63df9c22b">

## Fact Table - all dimensions table merged
<img width="711" alt="Fact table" src="https://github.com/Twitter-gupta/Uber_Data_Analysis/assets/164379382/3bc38474-bc8d-464d-8b0e-1574bbbf406f">
