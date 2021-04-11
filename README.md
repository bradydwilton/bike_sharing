# Overview of Bike Ride Analysis

The following analysis was prepared using Tableau Public to provide an analysis how customers used bikes in NYC's CitiBike business.

The accompanying data for this report can be found _[here](https://public.tableau.com/profile/brady6686#!/vizhome/BikeTripAnalysisChallenge/BikeTripAnalysis?publish=yes)_.

This analysis was prepared with three questions in mind:
1. Who uses the bike sharing service?
2. When are bikes used the most?
3. How long does the typical bike trip last?

# Results

### 1. Who uses the bike sharing service?

<img src='https://github.com/bradydwilton/bike_sharing/blob/main/images/whoUsesBikeSharingService.png'>

The `Customer Type` and `Gender Breakdown` pie charts show that the _**highest amount of usage comes from male riders who subscribe to the service.**_  </br></br>
The `Trips by Gender (Weekday per Hour)` heatmap shows that both men and women have similar usage patterns, with the service being used the most during rush hour (8 A.M and 5-6 P.M.). However, similar to what was previously shown in the `Gender Breakdown` pie chart, there are more male than female customers during those hours.

### 2. When are bikes used the most?

<img src='https://github.com/bradydwilton/bike_sharing/blob/main/images/whenAreBikesUsed.png'>

The `Trips by Weekday per Hour` and `User Trips by Gender by Weekday` heatmaps show that the bike sharing service is most heavily utilized *__during the hours of 8 A.M. and 5-6 P.M.__* on the weekdays, and most heavily by male subscribers. This indicates that the majority of business done by the bike sharing business is from _**everyday residents of the city making the daily commute to work**_, and not from tourists, which is great news for the bike sharing companies Des Moines opportunity!

### 3. How long does the typical bike trip last?

<img src='https://github.com/bradydwilton/bike_sharing/blob/main/images/howLongAreBikeTrips.png'>

As shown in the `Checkout Times for Users` line chart, the majority of bike trips last under 10 minutes. Drilling down in the `Checkout Times by Gender` plot further demonstrates this point, showing that the majority of trips for both male and female customers are under 10 minutes in length.

# Summary

The bike sharing business has potential to work in places with less tourist attraction than NYC, as demonstrated by the fact that the majority of business for the business is from subscribed customers during the hours in which people are generally travelling to and from work. 

The next step of the analysis is to dig into the cost to maintain the bikes by looking at the average amount of time each bike has been in use and determining how long each bike should go between maintenance cycles.