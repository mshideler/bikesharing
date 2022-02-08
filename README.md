# bikesharing

## Overview

The purpose of this project is to use Tableau to display data from a bike-share program in New York City, NY to convince investors that a bike-share program in Des Moines, IA also can be successful.

## Results

### Summary Graphs

![Summary](https://github.com/mshideler/bikesharing/blob/main/Resources/Summary.PNG)

The above summary graphic shows four visualizations.  First, the total number of rides in NYC for the month of August 2019 is about 2.3 million.  That averages to about 75,620 checkouts per day showing this is a wildly successful program.  The "Gender Breakdown" graphic shows males make up most of the customer base with over 1.5 million rides.  There are nearly 600,000 female bike-riders, and gender was unidentified for about 225,000 riders.

There are two types of customers, as the "Customers" visual shows.  There are about 444,000 regular customers who just checkout a bike at random, and the rest of the customer base is made up of about 1.9 million subscribers.  These subscribers periodically pay a fee to guarantee access to a bike whenever they want.  This means this business model provides a steady stream of income.

The "User Trips by Gender by Weekday" heatmap compares the number of trips between customers and subscribers and breaks down the data by gender as well as the day of the week.  The darker blue-green colors under subscriber for males and females indicate heavier usage (more rides) for those groups than for the customer group.

### Checkout Times

![Checkout Times](https://github.com/mshideler/bikesharing/blob/main/Resources/Checkout_times.PNG)

The above graphic shows the number of bikes checked out and for how long in hours and minutes.  The top graph displays this for all users regardless of gender or type of customer.  The bottom graph breaks down this information by gender.  Each graph is interactive so users can see this information for longer durations.  The bottom graph can be filtered to show one, two or all three genders.  Most users checkout bikes for less than an hour.  Beyond that, significantly fewer bikes are checked out for a longer period of time.

### Bike Trips

![Bike Trips](https://github.com/mshideler/bikesharing/blob/main/Resources/Bike_trips.PNG)

The above graphic here uses heatmaps to show the number of bike trips per week and per hour using the time the bikes get checked in at the end of a trip.  As in the prior visualization, this information gets broken down by gender in the bottom graph and can be filtered by gender.  The top graphic can be filtered by the date.  Note the legend in the upper right corner of the visualization.  The darker the color, the higher the number of bike trips.  When looking at both graphs, we see most trips occur outside the typical business week (M - F, 8am - 5pm).  After that, the most popular days are the weekends (Saturday and Sunday).  We see this pattern for males and females, but it changes a little for those users whose gender was unknown/unidentified.  The highest numbers of bike trips occur on evenings and weekends.

### Link to Tableau Public

The pictures seen here may be viewed at Tableau Public by clicking this link:

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/marisa.shideler/viz/BikeTripAnalysis_16439240018120/BikeTripsbyWeekdayperHour#1)
These visualizations are best viewed in full-screen mode.

## Summary

Overall, all the visualizations indicate a bike sharing program will be successful in Des Moines, IA.  Users appear to embrace a subscription-based usage plan, which will provide a steady income stream.  Also, based on the number of subscriptions and the quantity of bike trips outside of normal business hours, we can deduce that most users reside in the city and aren't tourists--another factor that implies a steady income stream.

There are a couple of other graphs that would provide additional insight.

1.  We know the more a bike gets used, the more prone it will be to repairs.  It would be insightful to determine how both the length of checkout time and number of checkouts affect the number of repairs each bike needs so we can determine how to extend each bike's usage.

2.  We know males use the bike share program more than females.  Breaking down the customer type by gender may spark an idea on how to market this program to encourage more female subscribers.
