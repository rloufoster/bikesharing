# NYC Bike Sharing Study

## Overview

The purpose of this project was to analyze data from New York City based CitiBike and then compile a visualized story of our findings using Tableau. The insights that are highlighted will be used to guide our client and potential investors in a start-up bike sharing company in Des Moines, Iowa.  We used August 2019 data for our analysis under the assumption that there is more bike usage during the summer months in NYC compared to months that would be more affected my inclement weather. 

### Links and Resources

 * Tableau Public CitiBike Story Page
  [My Tableau Profile](https://public.tableau.com/app/profile/robin.foster6976/viz/Bikesharing_Module14_Challenge/CheckoutTimesforUsers?publish=yes)  
 
 * Datasource
  [Datasource](https://s3.amazonaws.com/tripdata/index.html)
   
 * Tableau Public 2022.2
    
 * Python 3.7.6
 
 * Pandas Library
 
 * Jupyter Notebook

## Results

### Total Rides and Customer Demographics

![Total_Rides_Demos](https://github.com/rloufoster/bikesharing/blob/main/Resources/TotalRidesUserGender.png?raw=true)

The CitiBike data revealed that there were **2.34 M** rides during August of 2019.  81% of those riders were classified as "subscribers" and approximately 2.3 of those riders were male.

### Checkout Times for Users

![CheckoutTimesforUsers](https://github.com/rloufoster/bikesharing/blob/main/Resources/Checkout_Times_For_Users_Image.png?raw=true)

Approximately 99% of all the rides were under 60 minutes with half of all rides under 10 minutes.

### Checkout Times by Gender

![CheckoutTimesbyGender](https://github.com/rloufoster/bikesharing/blob/main/Resources/Checkout_Times_By_Gender_Image.png?raw=true)

Male riders made up 65% of the of Customers.

### Trips by Weekday for Each Hour

![WeekdayforEachHour](https://github.com/rloufoster/bikesharing/blob/main/Resources/Trips_By_Weekday_per_Hour.png?raw=true)

Most of the rides Monday thru Friday occur during commuting hours, 7-9 am and 5-7 pm.  

### Trips by Gender (Weekday per Hour)

![TripsbyGenderWeekdayPerHour](https://github.com/rloufoster/bikesharing/blob/main/Resources/Trips_By_Gender.png?raw=true)

Male riders make up most of the riders during the commuting hours.  Even though Saturday and Sunday have substantially less utilization of the bikes.

### Trips by Gender Weekday

![TripsbyGenderWeekday](https://github.com/rloufoster/bikesharing/blob/main/Resources/User%20Trips%20by%20Gender%20by%20Weekday.png?raw=true)

Thursday is the highest usage day among subscribers.  Non-subscribing customers were most likely to ride on Saturdays.

## Summary

Based on the following insights:

  * 1.) high volume of bike utilization in Lower Manhatten which is the financial district highly congested with business professionals
  * 2.) the weekday time frames of heavy usage being (7-9 am and 5-7 pm)
  * 3.) the majority of the users are subscribers which would indicate that they are more frequent users
  * 4.) most of the weekday usage within the commuter timeframes have durations of 10 minutes or less

We can then make the inference that bike sharing is most likely being used as a means of commuting to and from work.  

In summary, the proposed bike sharing company in Des Moines, could be a successful business plan.  Further research should be contributed in order to isolate the ideal locations for the stations. The following questions should be investigated and visualizations added: 1.) Where is the business district in Des Moines? Is the business district concentrated in 1 area or multiple areas? 2.) What about Universities?  Could bike sharing to and from the University bar scene be utilized?  The ideal locations to research would be densely populated areas with little parking availability. 

Additional visualizations that map out usage from starting to ending location to determine the distance traveled would be helpful. Where are specific NYC users starting and ending their trips? GeoCoordinate data could be used to map their bike paths. It would also be helpful to study highly congested college towns.  How are bike sharing programs doing in those areas?  What about usage in cities where the business districts are not as highly concentrated as Lower Manhatten? Visualizations that further break down the demographics of the riders would also be important. I would also want to research cities that better match the characteristics of Des Moines, IA.  What are the traffic patterns?  It would also be helpful to see visualizations of other months over a longer period of time.




