# CitiBike Data sharing
## Resources Used
- Python 3.10, Jupyter Notebook, Tableau Public 2021.4
## Overview of Project

Tableau was used to visualize the bike sharing data collected in New York to determine whether a similar model should be used in Des Moines. The graphs created are used as aids to present to investors to answer any potential questions or concerns they might have for the bikesharing program. 

## Results
### Tableau Story 
[link to dashboard](https://public.tableau.com/app/profile/rhian.doy/viz/Bikesharing_challenge_16480236836290/NYCCitibikeAnalysis?publish=yes)
### NYC Citibike Data for August 2019
#### Trips Based on Usertype by Weekday & Gender
![usertype](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/usage_gender_weekday.png)

- When taking into account usertype, gender and weekdays, subscribers to the Citibike service dominate each day of the week when looking at female data and even higher with males. The "Unknown" category is higher under the Customer usertype which could be due to them not having a regular subscription to the service so they are less likely to input this information. 

#### Trips by Weekday Per Hour
![weekday_per_hour](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/trips_weekday.png)

- On weekdays, between the hours of 7am and 9am as well as 5pm to 7pm, usage is at its highest point. This follows a typical start and end time for working adults as well as school-aged children. On the weekends, peak usage is during times of daylight starting around 9am until 7pm. 

#### Trips by Gender based on Weekday & Hourly
![weekday_and_hourly](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/trips_gender_hourly.png)

- While the genders show similar time patterns of usage, a higher number of males compared to females and unknown use Citibike services.

#### Checkout Time by Usage and Gender
![checkout_time](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/checkout_usage.png)
![checkout_gender](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/checkout_gender.png)

- At the highest peak, 146,752 bikes are checked out out for 5 minutes with 108,087 of those being from males, 33,041 being from females, and 5,624 being from Unknown. 
- Check out time drops drastically after the first 5-6 minutes which could show users in urban areas benefit highly from a bike sharing service. 

#### Bike Usage for Each Indivudal Bike
![bike_usage](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/count_bike_usage.png)

- Bike usage data is shown in a stepped tree map where the most used bike has been ridden 479 times and the least used bike has been ridden 1 time. Collecting this data shows which bikes, based on their usage and bike ID number, will be more likely to need repairs in the near future.

#### Peak Hours in August
![peak_hours](https://github.com/rhiandoy/bikesharing/blob/ecdcd00662a61600f316ca7fd570c5c4838ffd83/peak_hours.png)

- The peak hours for bike usage in August are around 8am and 5pm-6pm. 
- Since bike repairs will be necessary for the highly used bikes, this graph shows that the best hours for repairs would be between the hours of 3am and 4am. 
- Bikes can then be put back on the street and ready for use before the early morning commute.

## Summary

Based on all of the data collected during the month of August for Citibike, it is shown that most bikes are utilized by males during typical rush hour times in the morning and in the evening. A majority of the users are subscribers who are using the service consistently throughout the week. 

If we wanted to add on to this analysis, we could look into a different time of year, specifically a winter month to see how much of an impact weather has on the citibike service. We could also dive deeper into the length of trips and why a majority of trips begin and end within the first 5 minutes of riding., 
