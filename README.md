# Melbourne_WWTP


Melbourn Eastern Wastewater Treatment Plant 

Project Aim: Predicting the Total Grid Power Consumption

https://www.melbournewater.com.au/

With having the effluent data of the plant and the energy consumption we begin the project.
Later on, we obtained the daily climate reports through web-scraping from Melbourn airport weather station.

As TN and BOD samplings occurs once a week, we had missing data in these columns.

After predicting the missing values with almost (40%) accuracy, we performed a comprehensive Feature selection and machine learning study to find the best way to predict the power consumption


Grouping_Inlet :

We have several inlet flow records for each day. 
In this code, we grouped the data by averaging inlet values for each day.
