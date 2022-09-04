# BikeSharing Project - Proposal for Des Moines

Create worksheets, dashboards and stories to visualize data using Tableau.

## Overview
![bikeimage](https://user-images.githubusercontent.com/103727169/188327118-b59b4137-9859-4c97-8567-24fb8d40bad2.png)

The purpose of this analysis is to provide a business proposal that will convince investors that developing a bike-sharing program in Des Moines can be a profitable venture. Throughout the process, we use data that is publicly available from the NYC CitiBike program archives and Tableau to create visualizations.

While the data is based on activity that occurred in New York City which is very different from Des Moines, we use our data expertise and critical thinking skills to build a story that can be presented to the investors.

For our presentation, we decide to use data from August 2019 to build our analysis. It is assumed that there is more traffic or usage during the summer months compared to other times of the year in which weather can impact activity.

## Tableau Public Link
Link to Dashboard

## Results

### Importing Data 

For bikesharing project first we import panda and file to load and print out comes out like it showing in image.

![importandread](https://user-images.githubusercontent.com/103727169/188327632-608b9a6b-f8b2-4dbe-88a3-1ee94824537b.png)

### Check Datatype

we can see tripduration column is integer datatype which we can see following image.
![checkdatatype](https://user-images.githubusercontent.com/103727169/188327690-772186a1-b84e-46c1-bf3a-9fd5f1b8f295.png)

### Change Datatype into Datetime Datatype and Add another column with Datetime Datatype.

![addcolumn](https://user-images.githubusercontent.com/103727169/188327745-8f1ed123-52d3-409d-973c-b8f68d0ad353.png)


### Total Rides, 
![totalride](https://user-images.githubusercontent.com/103727169/188327193-ae6bdb96-6b42-4e50-b0ad-577891b004a0.png)

### Gender Breakdown
![genderbrakedown](https://user-images.githubusercontent.com/103727169/188327257-0cea8d5e-c06b-4d50-a609-d8063fd6eedc.png)


In NYC, there were over 2.3M trips that occurred during the month of August with 81% of the riders in the "subscriber" category and that Men were the primary user of this program (65%).

### Checkout Times for Users
![checkouttimeuser](https://user-images.githubusercontent.com/103727169/188327325-df72020c-5541-4356-b0be-195370b353f6.png)

Almost all of the trips (99%) were under 60 minutes with 49% under 10 minutes.

### Checkout Times by Gender
![checouttimebygender](https://user-images.githubusercontent.com/103727169/188327349-10df1c3a-8653-41f7-8023-1a1a5e5d158a.png)

Male riders are the primary user of the bike share program making up 65% of the population, with the remaining being 25% female and 10% unknown.

### Trips by Weekday for Each Hour
![tripbyweekdayforeachhour](https://user-images.githubusercontent.com/103727169/188327394-5043ab7f-f642-4329-b7eb-e15feabf8575.png)

Most of the rides during the weekdays (M-F) occur during commuting hours of 8-9a and 5-7pm. It can be assumed that the bike sharing program is the preferred method for commuting to and from work.

### Trips by Gender (Weekday per Hour)
![tripbygenderweedayperhour](https://user-images.githubusercontent.com/103727169/188327425-3e64d5f8-0238-4565-811b-4c5c671c9064.png)

Male riders are more inclined to use the bike sharing program to commute to and from work, as well as during the weekend.

### Trips by Gender by Weekday
![tripbygenderbyweekday](https://user-images.githubusercontent.com/103727169/188327439-b327025d-32ab-4e72-8d29-161670290ca8.png)

Thursday was the highest usage day among subscribers with the most usage occurring on Saturday for non-subscribers.

### Auguest Pick Hours
![auguestpickhors](https://user-images.githubusercontent.com/103727169/188327459-20f4b47c-363f-4d74-8596-3d9c08672669.png)

Auguest pick hours are 5 pm to 6 pm was the busyest hours for bikerides.

## Summary
Based on the visualizations above for activities that occurred in New York City, we can summarize:

  1.  Stalls located in heavily concentrated business areas, such as Midtown and Downtown made up the majority of the usage.
  2.  Subscribers are the primary user.
  3.  The duration of most trips were under 10 minutes.

In summary, introducing a bike share program in Des Moines, IA may be a good business venture, as long as the program is installed in densely populated areas where mass transportation is highly used and parking is limited. However, we would need to review additional data in order to provide a strong case to support this recommendation by adding:

  1.  Create visualization that maps out usage from starting to ending location to determine the distance traveled. Where are users starting their trip from and why?         Are they using the bike to complete their commute after taking the bus or the train?
  2.  Add visualization to explore the activity by age group and adding demographic information to identify areas in which bikeshares would most likely be used (i.e.         census data).

## Additional

Review data from other cities that may be a closer match to the population, size and traffic pattern of Des Moines. (Limiting our analysis to activity in New York City is not the correct comparison as New York City has a very large commuter population, as well as higher people traffic from tourism.)
Create visualization by month for an entire year to identify if weather affected usage.
