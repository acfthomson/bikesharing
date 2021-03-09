# bikesharing

## Overview
Analysts inspected New York City Citibike data from August 2019 in order to determine if Citibikes would be a good fit for Des Moines, Iowa.  The NYC data was analyzed to show trends for times of day, days of the week, gender, starting locations, and ending locations. This analysis required analysts to used Pandas to change the 'tripduration' column from an integer to a datetime datatype. Using the converted datatype, visualizations were created to show the length of time the bikes are checkout for all riders and genders, show the number of bike trips for all riders and genders for each hour of each day of the week, show the number of bike trips for each type of user and gender for each day of the week, top starting locations, and top ending locations.


## Resources
- Python v3.x
    - Pandas
- [201908-citibike-tripdata](https://s3.amazonaws.com/tripdata/index.html)
- Tableau Public


## Results of NYC Citibike Data for August 2019

### Link to Tableau Dashboard
[NYC_CitiBike_Challenge_Trip_Analysis](https://public.tableau.com/profile/amanda.thomson4403#!/vizhome/NYC_CitiBike_Challenge_Trip_Analysis/NYCCitibikeStory?publish=yes)

### Top Starting Locations
![Top_Starting_Locations](https://user-images.githubusercontent.com/73897240/110529045-c4f29e00-80e6-11eb-828b-ebe561f07c34.PNG)

The most popular places for Citibike customers to begin their journeys in New York City are:
1. Pershing Square
2. Broadway
3. Tribecca Bridge


### Top Ending Locations
![Top_Ending_Locations](https://user-images.githubusercontent.com/73897240/110529023-befcbd00-80e6-11eb-9e54-c13ee8e7f8a7.PNG)

The most popular places for Citibike customers to end their journeys in New York City are the same as starting locations.


## Checkout Times for Users
![Checkout_Times_for_Users](https://user-images.githubusercontent.com/73897240/110528976-b2786480-80e6-11eb-9aaa-8aac9edcf534.PNG)

Peak usage for NYC Citibikes occurs at 5 minutes.  146,752 bikes were checked out at 5 minutes for August 2019.  33 Citibikes were checked out for at least 2 hours and 59 minutes.


### Checkout Times by Gender
![Checkout_Times_by_Gender](https://user-images.githubusercontent.com/73897240/110529322-1e5acd00-80e7-11eb-9a5d-32f794451ae6.PNG)

Males were the primary user of Citibikes in August 2019.  There were 34,151 female Citibike users at peak usage, which is 68.4% less than male rideres.


### Trips by Weekday
![Trips_by_Weekday](https://user-images.githubusercontent.com/73897240/110529673-8b6e6280-80e7-11eb-9942-c74fbe635fb8.PNG)

Citibikes are used the least between 12 AM and 5 AM Sundays through Saturdays.  This may be a good time for Citibikes to perform maintenance on their bikes.


### Trips by Gender (Weekday per Hour)
![Trips_by_Gender_(Weekday_per_Hour)](https://user-images.githubusercontent.com/73897240/110530430-6e865f00-80e8-11eb-8ea1-972516e43d57.PNG)

Citibikes are popular amongst males and females around 8 AM, 5 PM, and 6 PM Monday through Friday.  Usage is popular on Saturdays between 9 AM and 7 PM for male and femal riders.  On Sundays, male and female riders appear to use Citibikes the most between 11 AM and 5 PM.


### User Trips by Gender by Weekday
![User_Trips_by_Gender_by_Weekday](https://user-images.githubusercontent.com/73897240/110530752-cf159c00-80e8-11eb-96e3-d4fd403b0c64.PNG)

In August 2019, Thursdays are the most popular days to use Citibikes amongst male and female subscribers.  Sundays were the most popular days to use Citibikes for male and female customers.


## Summary
Overall, males were the primary users of Citibikes in New York City during August 2019.  The most usage occurred on Thursdays and starting and ending locations of Citibike trips were the same.  Additional analysis is needed in order to determine if Citibikes is a great fit for Des Moines, Iowa.

In order to determine if Citibikes is a good fit for Des Moines, Iowa, analysts visualize population growths between Des Moines and New York City.  Publicly available census data could be used to look at population totals and growth rates between the two cities.  If population growth for Des Moines is greater than New York City's, the Citibikes has potential to be a great fit for Des Moines.

An additional visualizatin that may help investors determine if Citibikes are a good fit for Des Moines include correlating weather data between Des Moines and New York City.  Both cities have four seasons, and if there temperatures and weather are similar, than this may also provide a stronger case to investors that Citibikes is a great fit for Des Moines, Iowa.
