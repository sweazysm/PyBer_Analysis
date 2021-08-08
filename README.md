# PyBer Analysis 2021

## Overview

The purpose of the following analysis was to create a summary DataFrame of the ride-sharing data (PyBer data) by city type for the client, V. Isualize. This was done to visualize weekly fares by city type which include Urban, Suburban, and Rural.

## Results

#### The results garnered from the PyBer Analysis were as follows:

There are three analyzed city types: Urban, Suburban, and Rural. From these three types the data was analyzed to create several outcomes that include data on total rides, total drivers, total fares, average fare per ride, average fare per driver, and total fare by city type. 

- In regards to Total Rides, the analysis returned 125 rides in Rural settings, 625 rides in Suburban settings, and 1625 in Urban settings.
<img width="268" alt="Screen Shot 2021-08-08 at 7 01 11 PM" src="https://user-images.githubusercontent.com/86274124/128648232-9bb5709e-b959-4982-9261-c64f790471be.png">


- In regards to Total Drivers, the analysis returned 78 drivers in Rural settings, 490 drivers in Suburban settings, and 2405 drivers in Urban settings.
<img width="295" alt="Screen Shot 2021-08-08 at 7 03 43 PM" src="https://user-images.githubusercontent.com/86274124/128648263-fe86f6c4-6160-4cd1-bf93-e10e3dead98a.png">


- In regards to Total Fares, the analysis returned $4,327.93 in total fares for Rural settings, $19,356.33 in total fares for Suburban settings, and $39,854.38 in total fares for Urban settings.
<img width="242" alt="Screen Shot 2021-08-08 at 7 07 06 PM" src="https://user-images.githubusercontent.com/86274124/128648314-8965b9d3-cf14-47a9-891b-21775da0cdc0.png">


- In regards to Average Fare per Ride, the analysis returned $34.62 to be the average fare per ride for Rural settings, $30.97 to be the average fare per ride in Suburban settings, and $24.52 to be the average fare per ride in Urban settings.
<img width="236" alt="Screen Shot 2021-08-08 at 7 10 21 PM" src="https://user-images.githubusercontent.com/86274124/128648403-c6861022-341a-4bbc-93ed-d0bfb70f6f91.png">


- In regards to Average Fare per Driver, the analysis returned $55.48 to be the average fare per driver in Rural settings, $39.50 to be the average fare per driver in Suburban settings, and $16.57 to be the average fare per driver in Urban settings. 
<img width="204" alt="Screen Shot 2021-08-08 at 7 13 45 PM" src="https://user-images.githubusercontent.com/86274124/128648466-d1e5ceb6-3f32-463c-8126-c48e29f5f3c4.png">


- The following five outputs can also be shown in a Dataframe created within Jupyter Notebook.
<img width="606" alt="Screen Shot 2021-08-08 at 7 14 44 PM" src="https://user-images.githubusercontent.com/86274124/128648483-85fdbdb3-37e3-41ed-9231-109f1c995c5a.png">


- In regards to Total Fare by City Type, the data analyzed was formated n Jupyter Notebook to return a line graph visualizng the data across 12 months for the three city types analyzed. A snapshot of the results shown are as below and can also be found in the "analysis" folder along with several other figures:
<img width="984" alt="Screen Shot 2021-08-08 at 7 17 35 PM" src="https://user-images.githubusercontent.com/86274124/128648541-13076d42-2091-43f0-8735-8cf70013ae5a.png">

------
# Summary

Several disparities seen among the city types from the data analyzed are as follows. 

- Fares for each city type analyzed dropped off beginning in the month of May, with Urban fares taking the largest tole. It would be recommended to switch up business strategies for May in order to encourage more rides for riders and more work for drivers. This can be in the form of Summer Bonuses, Driver Rewards, Peak Hours (for pay for drivers), and PyBer ride share services catering to Summer Hot Spots such as beaches, clubs, bars, and other social events. While we do not have a comprehensive picture of the data for summer activity(s) (that is for another analysis perhaps!), these are changes that are recommended for trial beginning in May to boost revenue. 

- While fares are the highest (overall) in Urban settings ($39,854.38) along with highest total number of drivers (2405) and highest total number of rides (1625), the amount earned by drivers in these areas are the lowest ($16.57/driver) along with the fares for Urban settings also being the lowest ($25.52/ride). This discrepency could possibly be accounted for if more data was available in regards to length of drives in these settings, payment per mile driven, fare per mile driven, average tip per drive per setting, and density of drivers in each setting. To address issues in regards to this, it is recommended to apply incentivies to drivers and riders alike to keep them on the PyBer platform in high-activity, high-density areas such as Saturday Specials, Weekly Surges, Rideshare Bonuses etc. Drivers could get discouraged with lower wages in Urban settings, so such changes may alleviate financial frustration. As well, it may be suggested that for Rural areas that the average fare cost be lowered for consistent riders, as such high costs (compared to other settings) could discourage people from using PyBer services. For a more comprehensive idea on what should be done, further analysis should be done in regards to distance of rides, ride times, and driver wages + tips for each area/setting analyzed. As well, it could be said that there are simply too many drivers in Urban settings, thus driving down fare costs. 
