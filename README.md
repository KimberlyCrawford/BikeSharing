# Bikesharing

## Overview
A Bikesharing Analysis Using Tableau to Visualize Bike-Sharing Data.

### Purpose
Using New York City bike-sharing data, the purpose of this project was to create a business proposal and convince potential investors to invest in a bike-sharing company in Des Moines, Iowa. 

### Resources

- Data File: August 2019 City Bike Data downloaded from https://ride.citibikenyc.com/system-data. Note: August data was used because there is likely more traffic during the summer months.
- Software: Tableau Public 2021.3, Python 3.7.10. and Jupyter Notebook 6.3.0 

## Results

The analysis of the New York City bike-sharing data answers the following questions:

- How many trips were recorded during the month of August?
- What was the proportion of short-term customers to annual subscribers?
- What were peak riding hours in the month of August?
- What were the top bike stations in the city for starting a journey?
- What were the top bike stations for ending a journey?
- What was the gender breakdown of active riders?
- What was the average trip duration by age?
- How was birth year related to the length of a bike ride?
- Which bikes were most likely due for repair?
- How variable was bike utilization? 

#### How Many Trips Were Recorded During the Month of August?

Since August is a beautiful time of the year to rent a bike, this data was used as a starting point to determine how many rides an investor could expect in the city of Des Moines. According to https://www.city-data.com, New York City had a population of 8,336,817 in 2019 and Des Moines had 214,237. See statistics below: 

New York City Statistics

![NYC.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/NYC.png)

Des Moines Statistics

![Des_Moines.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Des_Moines.png)

The number of rides in NYC was 2,344,224 which is 28% of the total population. Therefore, we might expect 60,241 rides in Des Moines. 

![Number_of_rides.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Number_of_rides.png)

#### What Was the Proportion of Short-Term Customers to Annual Subscribers?

Using the breakdown of rider types in New York City, we might expect 11406 (19%) customers and 48835 (81%) subscribers in Des Moines.

![Proportion_of_customers.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Proportion_of_customers.png)

#### What Were Peak Riding Hours in the Month of August?

Knowing the peak usage hours for the month of August helped get a better idea of how many bikes will be needed in Des Moines, as well as identified which parts of the day the most bikes are needed. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to schedule maintenance. Based on the bar chart, the top riding hours during August in New York City was between 5:00 p.m. to 7:00 p.m. and suggested bike maintenance should be performed between 2:00 a.m. and 5:00 a.m.

![August_Peak_Hours.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/August_Peak_Hours.png)

#### What Were the Top Bike Stations in the City for Starting a Journey?

The following symbol map provided a visualization of the top 10 starting locations. 

![Top_Starting_Locations.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Top_Starting_Locations.png)

#### What Were the Top Bike Stations for Ending a Journey?

The following symbol map provided a visualization of the top 10 ending locations. 

![Top_Ending_Locations.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Top_Ending_Locations.png)

#### What was the Gender Breakdown of Active Riders?

The following pie chart gave a breakdown of gender.

![Gender_Breakdown.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Gender_Breakdown.png)

#### What Was the Average Trip Duration by Age?

The following area chart gave the average trip duration by age. The general trend was that younger riders tend to use the bikes for longer periods of time.

![Average_Trip_Duration.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Average_Trip_Duration.png)

#### Which Bikes Were Most Likely Due for Repair? 

The following treemap gave an idea of how often each bike was used, i.e. Bike 38124 was used the most with 479 uses.

![Bike_Repairs.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Bike_Repairs.png)

#### How Variable Is Bike Utilization? 

The following packed bubbles visualization shows how long rides were and if there were bikes that need more attention than others. 

![Bike_Utilization.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Bike_Utilization.png)


## Bikesharing Challenge
A Bike Trip Analysis was prepared to address the following questions for one of the key stakeholders:

- What was the length of time that bikes were checked out for all riders and genders?
- What was the number of bike trips for all riders and genders for each hour of each day of the week?
- What was the number of bike trips for each type of user and gender for each day of the week?

### Deliverable 1: Changed Trip Duration to a Datetime Format

Using Python and Pandas functions, the "tripduration" column was converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00) in our dataframe.

![Trip_Duration_Conversion.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trip_Duration_Conversion.png)

![New_datatypes.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/New_datatypes.png)

![Export_dataframe.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Export_dataframe.png)


### Deliverable 2: Created Visualizations for the Trip Analysis

Using Tableau, the following visualizations were created:

#### Checkout Times Length for All Users 

- A line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.

![Checkout_times_per_users.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Checkout_times_per_users.png)

#### Checkout Times by Gender 

- A line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.

![Checkout_times_by_gender.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Checkout_times_by_gender.png)

#### Trips by Weekday for Each Hour 

- A heatmap showing the number of bike trips for each hour of each day of the week.

![Trips_by_weekday_for_each_hour.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trips_by_weekday_for_each_hour.png)

#### Trips by Gender (Weekday per Hour) 

- A heatmap showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

![Trips_by_gender_weekday_per_hour.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/Trips_by_gender_weekday_per_hour.png)

#### User Trips by Gender by Weekday 

- A heatmap showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user AND gender.

![User_trips_by_gender_by_weekday.png](https://github.com/KimberlyCrawford/Bikesharing/blob/main/Resources/User_trips_by_gender_by_weekday.png)


### Deliverable 3: Create a Story and Report for the Final Presentation

[Bikesharing Analysis](https://public.tableau.com/views/NYCCitibikeAnalysis_16331442011330/KeyOutcomesoftheNYCCitibikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

# Summary:

- Summary
- Two additional visualizations suggested for future analysis:


Select your questions. During this step, you'll consider which results you want to share with your audience. What do they want to see? How can we use that information to make their decision making process easier?
Execute independent research. You'll need to look at other relevant pieces of information to build a bigger picture. Search other sources to find information that will make your visualization more powerful.
Craft your Tableau story. This is when you create your story, primarily from worksheets and other visuals, with descriptions for each of them.
Create a written analysis. The written analysis is intended to provide additional insight into what we're trying to convey to our audience. This is a good place to add extra detail so that everyone can get on the same page.
After you've practiced creating Tableau stories, let's create a story for our investors. The purpose of this story is to help them determine whether they should invest in a bike-sharing program in Des Moines.

#### Module 14, Data Analysis & Visualization Certificate Program, UT Austin McCombs School of Business, 2021.
