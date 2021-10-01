# Bikesharing

## Overview
A Bike Trip Analysis Using Tableau to Visualize Bike-Sharing Data.

### Purpose
To present a business proposal to fund a bike-sharing company in DeMoine, Iowa using New York City bike-sharing data. 

### Resources

#### Data Files:
August 2019 City Bike data.

Software:
Tableau Public 2021.3 

## Deliverable 1: Change Trip Duration to a Datetime Format

Using Python and Pandas functions, the "tripduration" column was converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00) in our dataframe.

![Trip_Duration_Conversion.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trip_Duration_Conversion.png)

![New_datatypes.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/New_datatypes.png)

![Export_dataframe.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Export_dataframe.png)


## Deliverable 2: Create Visualizations for the Trip Analysis

Using Tableau, the following visualizations were created:

#### Checkout Times Length for All Users 

- A line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.

![Checkout_times_per_users.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Checkout_times_per_users.png)

#### Checkout Times by Gender 

- A line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.

![Checkout_times_by_gender.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Checkout_times_by_gender.png)

#### Trips by Weekday for Each Hour 

- A heatmap is created showing the number of bike trips for each hour of each day of the week.

![Trips_by_weekday_for_each_hour.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trips_by_weekday_for_each_hour.png)

#### Trips by Gender (Weekday per Hour) 

- A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

![Trips_by_gender_weekday_per_hour.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trips_by_gender_weekday_per_hour.png)

#### User Trips by Gender by Weekday 

- A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user AND gender.

![Filename.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/filename.png)


## Deliverable 3: Create a Story and Report for the Final Presentation




## Other Visualizations for Decision-Making

How Many Trips Were Recorded During the Month of August?

Since August is a beautiful time of the year to rent a bike, we want to use this data as a starting point to determine how many rides we could expect in the city of Des Moines.

![Number_of_rides.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Number_of_rides.png)

What Is the Proportion of Short-Term Customers to Annual Subscribers?

Knowing the breakdown of rider types in New York City helped predict the customer breakdown in Des Moines and, in turn, propose a business model to investors.

![Proportion_of_customers.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Proportion_of_customers.png)

What Are Peak Riding Hours in the Month of August?

Knowing the peak usage hours for the month of August helped get a better idea of how many bikes will be needed in Des Moines, as well as identified which parts of the day the most bikes are needed. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that.

Based on the bar chart, the top riding hours during August in New York City was between 5:00 p.m. to 7:00 p.m. and suggested bike maintenance should be performed between 2:00 a.m. and 5:00 a.m.

![August_Peak_Hours.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/August_Peak_Hours.png)

What Are the Top Bike Stations in the City for Starting a Journey?

The following symbol map provides a visualization of the top 10 starting locations. 

![Top_Starting_Locations.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Top_Starting_Locations.png)

What Are the Top Bike Stations for Ending a Journey?

The following symbol map provides a visualization of the top 10 ending locations. 

![Top_Ending_Locations.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Top_Ending_Locations.png)

What is the Gender Breakdown of Active Riders?

The following pie chart gives a breakdown of gender.

![Gender_Breakdown.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Gender_Breakdown.png)

What Is the Average Trip Duration by Age?

The following area chart gives the average trip duration by age:

![Average_Trip_Duration.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Average_Trip_Duration.png)

How is birth year related to the length of a bike ride? The general trend is that younger riders tend to use the bikes for longer periods of time. 

Which Bikes Are Most Likely Due for Repair? The following treemap gives an idea of how often each bike is used, i.e. Bike 38124 was used the most with 479 uses.

![Bike_Repairs.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Bike_Repairs.png)

How Variable Is Bike Utilization? The following packed bubbles visualization shows how long rides are and if there are bikes that need more attention than others. 

![Bike_Utilization.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Bike_Utilization.png)
