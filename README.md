# NYC CitiBike

## Overview
The purpose of the analysis is to understand better how CitiBike bikes are rented/utilized by customers in NYC, adn whether or not the bikes are being sufficiently utillized across diffierent days of week/times of day etc. This will help to understand if a similar program can be set up in Des Moines and other cities across the country.

The project will display the results in a Tableau story, thus givnig readers visual analysis of raw data from CitiBike.

## Results
Let's take a look at the analysis on the data and salient points.

### Number of Rides
This is a self explanatory feature that indicates the total number of rides taken on the bikes.
![#_of_rides](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/Number_Of_Rides.png)

### Gender Breakdown
The pie-chart below shows the gneder breakdown of the customers renting/subscribing to ride bikes. From the pie-chart, it is evident that men represnent an overwhelming majority of CitiBike customers (~ 65%)
![gender_breakdown](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/Gender_Breakdown.png)

### Checkout Time for users
The chart below shows the duration for which bikes were checked out. The largest number of bikes were rented for 5 minutes, and the long tail indicates that more bikes were rented for more than 5 mintes, than for less than 5 minutes.
![checkout_times_all](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/Checkout_TIme_For_Users.png)

### Checkout Times by Gender
This chart breaks down the previous one into genders. While 5/6 minutes, is still the the timeslot for maximum number of bikes - it is evident that not only men rented more bikes, they also rented them for longer duration than other genders.
![checkout_times_by_gender](https://github.com/abhi82git/bikesharing/blob/d54e4f1c5a3044bc7152b0b8bcb63ac7e1596d64/images/Checkout_Times_by_Gender.png)

### Trips By Weekday per hour
This is a heatmap showing what days of the week and what times of the day are most bikes being rented/used. From the chart it is clear, that most bike are rented between 7 AM to 6 PM on weekdays (barring the evening on Fridays, probaly due to the oncoming weekend party/trips/recreation).
![trips_by_weekday_all](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/Trips_By_Weekday_Per_Hour.png)

### Trips by Gender (Weekday per Hour)
This heatmap further breaks down the previous heatmap by genders. While the peak days/times remain same as the previous heatmap, this ocnfirms the prevous conclusion that men rent much much more than other genders.
![trips_by_weekday_gender](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/Trips_by_Gender.png)

### User Trips by Gender by Weekday
This heatmap breaks the users how are using bikes by gender and type of user. From th heatmp, it is clear that subscribers rent more than customers and men more than other genders.
![user_trips_by_weekday](https://github.com/abhi82git/bikesharing/blob/7c52049d8674d47f2e088a3eec8b4f986bcc7a2f/images/User_Trips_by_Gender_by_Weekday.png)

## Tableau Dashboards/Stories
 - [Dashboard_Part_1](https://public.tableau.com/authoring/NYC_CitiBike_Challenge_16454952739690/NYCCititBikeDashboard_____#1)
 - [Dashboard_Part_2](https://public.tableau.com/authoring/NYC_CitiBike_Challenge_16454952739690/NYCCItibikeDashhboardPg2#1)
 - [Story_Part_1](https://public.tableau.com/authoring/NYC_CitiBike_Challenge_16454952739690/NYCCitibikeStoryPt1#1)
 - [Story_Part_2](https://public.tableau.com/authoring/NYC_CitiBike_Challenge_16454952739690/NYCCitibikeStoryPt2#1)

## Summary
To summarize, following are the main points from the analysis:
 - Subscribers use more bikes than customers.
 - Weekdays are busier than weekends - most likely because subscribers use bikes more on weekdays and tourist are the more common users on weekends.
 - Men ride much much more than other genders
 - Evenig hours are the busiest, followed by early morning hours.

Two visualizations that would help in gleaning more insight from the data could be:
 - Distance covered on each ride. This would help in understanding if customers are ok with riding bikes for moderate distances, or are they looking for bikes for shorter - a bloc or two - routes.
 - Reasons behind the disparity between men and women renting bikes. This could be a huge growth opportunity among female customers.




