# Bikesharing

## Project Overview
For this project I created a bike trip analysis on Citi bike data in New York City, utilizing Tableau. In understanding the data and creating visualizations, one can effectively better understand usage patterns, peak and low times, and the average consumer profile for bike users. For potential investors who may want to create or partner with bike sharing programs in their city, such as in Des Moines, this analysis can aid in demonstrating the potential success such a venture can bring. In order to expand, the initial steps require the data to tell its story.

The finalized Tableau story of the Citi Bike analysis can be found here: [link to dashboard](https://public.tableau.com/app/profile/leila4630/viz/CitiBikeSharingAnalysis_16543575020420/BikeSharingAnalysis?publish=yes)

## Resources
- Data Source
  - Historical Citi Bike trip data from August 2019, presented on the Citi Bike webpage
- Software/Software library
  - Tableau 
  - Pandas
- Languages
  - Python

## Results 
1. The initial page of the story provides an introduction to Citi Bike along with images of its pricing structure, instructions on how to ride, and access to their webpage

2. The second page illustrates top starting locations and peak hours of use
- There is a concentration of top starting locations in Lower Manhattan/Downtown, however there are over 750 Citi Bike stations around NY and NJ. The strategic placement of the bikes has facilitated use as consumers can easily begin and end a trip with bike stations all around
- Peak hours of use are around 8-9AM with 220,000 trips logged, and a second peak between 5-6PM. This could correlate with the traditional 9-5PM working hours, and could be reflecting the high quantity of working individuals who utilize Citi Bikes to move to and from work

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20Top%20starting%20locations.png)

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20August%20peak%20hours.png)

3. The third pages highlights average trip duration and then adds a gender component to this analysis
- Most ride durations last within the "0" category indicating a start and end time within the first hour timeframe. There seem to be more use of Citi Bikes for short term trips rather than long term trips, which could be reflecting tourists utilizing the bikes to move around to a cluster of tourist attractions concentrated in one region. 
- When gender is added, there is a clear peak of male users, followed by females, and other genders
- This information is critical in understanding the profit breakdown of Citi Bike as they charge by pass type (subscriber or customer) and by trip duration

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20trip%20duration.png)

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20trip%20duration:gender.png)

4. The fourth page shows trips by weekday/hour and trips by gender
- The graph indicating trips by weekday/hour has an X axis with the weekdays, Y axis of the hours, and the darker the color shows concentration of use
- Based off of this, there is a clear pattern that the most popular times during weekdays are 5-6AM and 5-7PM, Saturday's 9-7PM, and Sunday's 10-5PM

- The graph indicating trips by weekday/hour and gender show quite an even distribution of times regardless of gender, however, more males seem to be utilizing Citi Bikes in general

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20trips%20by%20weekday.png)

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20trips%20by%20weekday:gender.png)

5. The fifth page contains user type (customer or subscriber) usage, by gender and weekday
- In this graph, there are more subscribers than customers, where customers tend to have quite an even distribution on when they ride, and subscribers are more concentrated during the weekdays. Other genders (unknown) do not demonstrate much of a pattern, however males tend to have peak usage durng Monday-Tuesday and Thursday-Friday; female customers tend to have peaks during the same days but to lesser extents
- The gender breakdown is as follows: 1,530,272 male users, 588,431 female, and 225,521 unknown

![This is an image](https://github.com/leilacf/Bikesharing/blob/main/Images/CB%20user%20trips:gender:weekday.png)

## Summary
Citi Bike has presented itself to be quite a booming bike-sharing industry and great alternative to other public transportation or ride-sharing apps such as Uber and Lyft. Not only are the bikes more cost-friendly, but they are more user-friendly as one typically does not have to wait to begin the trip, and finalizing the trip is quite easy and fast due to the multiple station locations. For future investors, this analysis can be of great assistance in better understanding consumer profiles, peak usage, and costs associate with such a venture such as bike upkeep and subscriber retention. 

For future analysis, I would reccomend:
- Check out time for users and peak tourist times -- the focus would be on how external influences (peak tourist time/attractions) influence Citi bike trip patterns and user patterns
- Trip duration and weekday to see peak start and end times, to compare similar trends of usage and time




