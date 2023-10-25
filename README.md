# ANALYSIS REPORT ON AIRLINE DELAYS FOR 2019 AND 2020

# INTRODUCTION
Airline delay analysis aims to evaluate which factors most likely contribute to airline delays, which can help airline companies avoid airline delays and make better flight planning to minimize their loss.

# ABOUT THE DATA/DATA COLLECTION
It is a structured data, and it is a secondary data collected. The data contains a table in csv files. It contains 3351 rows and 21 columns. The dataset was gotten from Kaggle
The analysis to be carried out is to answer the following questions;

1.	What is the total number of arrivals of carriers?
2.	What is the proportion of delays in 2019 and 2020?
3.	What is the total number of cancelled flight and flight diversion in 2019 and 2020?
4.	What are the top five airport with the most delays?
5.	What is the total minutes delay caused by National Aviation System?
6.	What is the proportion in total minutes of security by year?
7.	What are the total minutes of delay caused by bad weather?
8.	What are the total minutes of late_aircraft_delay by year?
   
# TOOLS

The tool used is Microsoft Power bi for analysis and using power query editor for data cleaning.

# DATA CLEANING AND TRANSFORMATION

The following are the different cleaning procedures;
•	The data contained blanks and duplicates which was removed
•	Inserted text after delimiter ‘space ‘to separate the year from the date
•	Removed errors
•	Changed the format for months and year to text format

# EXPLORATORY DATA ANALYSIS(EDA) AND INSIGHT
For the analysis to be understood and the questions to be answered pivot tables were created for it to properly analyzed for insights. The following consist of questions, its analysis and insight for each;

1.	What is the total number flight arrivals of carriers?
At the total of 178,784, carrier code WN named Southwest Airlines Co was the highest and carrier code HA named Hawaiian Airlines Inc was the lowest with 10,415 of flight arrivals. 

![top no of arrivals](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/02088269-ff3c-4559-9cf3-40cc5058ad43)
                
A stacked bar chart was created to show the total number of flight arrivals by each of the airline.

2.	What is the proportion of delays in 2019 and 2020?
The year 2019 had the highest number of flight delays with 65.52% compared to year 2020 being the lowest with 34.48% of delays. There was a reduction of delays in 2020 with 31.04%.

  ![proportion of delays](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/77ff200f-24d0-4604-8b2a-c6ad7654c8ae)
                   
A donut chart was created to show the proportion of delays between the two years.

3.	What is the total number of cancelled flight and flight diversion in 2019 and 2020?
   
In year 2019, cancelled flight was 5793, and flight diverted was 1358 while for year 2020, cancelled flight was lower with 3850 and diverted flight was 567. There was a massive drop in the cancelled flight and diverted flight in 2020 with 1943 and 791 respectively.

![total no of cancelled flight](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/9b088ff3-8d1a-4f1c-97b9-f3020bdedb43)
        
A clustered chart was created to show both the cancelled flight and diverted flight for both year and to make comparison.

4.	What are the top five airport with the most delays?

The top five airport with the highest delays includes; Dallas/Fort Worth International being the highest airport with most delays with 583,048 delays, Chicago O’Hare International with 502,875, Denver International with 423,216, San Francisco International with 417,229 and Newark Liberty International being the lowest five with 402,693.

![top 5](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/10469d6b-498e-40e7-af0b-fc9eaeda7960)
                   
A clustered column chart was created to show the top five airports with the most delays.

5.	What is the total minutes delay caused by National Aviation System?

 The airport with the highest minutes of delay caused by National Aviation        System was the Newark Liberty International with 226776 total minutes while the lowest was Charlotte Douglas International with 44621 minutes.
  	
![delay caused by nas](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/4ae1f17d-b422-411c-b4af-a5f0e3ac1c34)
        
A clustered bar chart was created to show the total minutes of delay caused by National Aviation System.

6.	What is the proportion in total minutes of security by year?
   
The year with the most total minutes of delay caused by security was in 2019 with 11,081 minutes that is 61.37% and in 2020, was 38.63% with 6974 minutes.

   ![tot min of security](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/0b55bc92-2245-49f2-8cd8-ad38db601f16)

A donut chat was used to show the proportion of delays caused by security in the 2019 and 2020.

7.	What are the total minutes of delay caused by bad weather?
   
The airlines with the highest total minutes of delays caused bad weather was SkyWest Airline with 219602 minutes of delay and the lowest is Hawaiian Airlines Inc with 1956 minutes

![bad weather](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/4aa50b62-fa6d-4fb9-8ec5-f45bf7bbd11e)

A clustered bar chart was created to show the total minutes of delay caused by National Aviation System.

8.	What are the total minutes of late_aircraft_delay by year?
   
The total minutes of late_aircraft delay in 2019 was 3577033 minutes with 85.16% while 2020 was 623558 minutes with 14.84%

![tot min of late flight](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/97edd2dd-4eea-4ded-8883-5e71172edc22)

A donut chat was used to show the proportion of delays caused by security in the 2019 and 2020.

# VISUALIZATION
![page A](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/d7a25fb4-38d2-4031-aaba-f1c11619f5e7)

![page A1](https://github.com/Deborah-Marizu/Analysis-on-Airline-delay-for-december-2019-2020/assets/147628427/e7f6d621-5367-41f3-b777-4e74931b735a)


# RECOMMENDATION

•	There are several preflight strategies, such as advising customers as early as possible – in the case of major delays, potentially even before they leave for the airport – and always, always, keeping them informed.

•	Crew scheduling: Efficiently manage crew schedules to reduce fatigue-related delays. implement contingency plans for crew shortages or delays.

•	Air traffic management: Collaborate with air traffic control authorities to optimize routes and reduce congestion. Advocate for improvements in air traffic management systems to enhance efficiency.

•	Weather management: Utilize advanced weather forecasting systems to anticipate and plan for adverse weather conditions. Develop strategies for rerouting or delaying flights in response to weather-related challenges.
