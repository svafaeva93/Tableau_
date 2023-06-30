# Citibike Analysis with Tableau 

![citi_bike](https://github.com/svafaeva93/Tableau_/assets/124627601/df2a3f50-5287-4276-aece-6c1d7740462b)

# Background

Congratulations on your new job! As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

Please find below a link to the Tableau dashboard: 
https://public.tableau.com/views/Citibike_assignment/Homepage?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

# Instructions

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

Create your final presentation:

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

# Data Source 

Used csv files covering a period of three months from March, April and June, 2023. As they contained similar information, they were merged using 'Union' in Tableau. The csv used in Tableau was a combined form of the three csv files. 

# Dashboards

Consist of a homepage and four corresponding dashboards were designed to provide visualization and comprehensive analysis of data. 

## Homepage 

* This page provides general introduction about the project and gives options to navigate to page of interest. 

<img width="1005" alt="Screenshot 2023-06-29 at 9 35 49 PM" src="https://github.com/svafaeva93/Tableau_/assets/124627601/a7df1419-8966-4c8d-8b66-c86f3e0c2f42">

## Station Information with Analysis 

* Provides information on cumulative number of start and end stations, the total bikes used and the total trip duration of bike rides. There is also an analysis of popular stations to start and end a journey. Furthermore, one can see the distance traveled by different bikes in the station.
  
<img width="1007" alt="Screenshot 2023-06-29 at 9 37 33 PM" src="https://github.com/svafaeva93/Tableau_/assets/124627601/686025bf-e541-4a18-9408-d567389743e5">

* Based on the gathered data, there seems to be more end stations compared to start stations. 
* The bubble chart shows the top ten start and end stations. It can be seen that South Waterfront Walkway - Sinatra Dr & 1 St to South Waterfront Walkway - Sinatra Dr & 1 St 0 are the most frequent stations for starting and ending trips, with a total of 1, 128 trips. 
* The line chart of 'Average Distance Traveled' shows a steady rise in distance traveled progressing into May and June. This could be due to the warmer season in this time of year and lack of snowy conditions which would significantly lower the length of bike trips. 
* The total distance traveled by classic bikes far exceeds the other two bike types. 


## Trip Information 

* Displays analysis of bike usage based on days of the week within the three months. There is also data on the types of bikes used for the trips. 
  
<img width="1004" alt="Screenshot 2023-06-29 at 9 37 45 PM" src="https://github.com/svafaeva93/Tableau_/assets/124627601/d478771f-299a-414e-a81d-257f8260f958">

* Based on this dashboard, it can be seen that bike usage increased overall each month and that it is more frequently used during the weekdays as compared to weekends. This May, bikes were most frequently used on Wednesdays and least frequently used on Saturdays. There is a similar trend for the other months. This may be attributed to the proximity of biking stations to one's office or home and the ease of using it. Perhaps more people prefer to get away from the city on weekends and hence relativly less bikes are used from Citibike's program. The statistical analysis also showed the precent of increase in bike usage with May making up 40.04%. 

* More bike rides were taken with classic bikes in comparison to the rest. Electric bikes might require periodic charging, and docked bikes might be limited by the total time of use available. 


## User Information 

* Presents a heatmap of bike usage based on weekdays and specific time of day. This page also includes info on member status. 

<img width="1009" alt="Screenshot 2023-06-29 at 9 37 57 PM" src="https://github.com/svafaeva93/Tableau_/assets/124627601/5c7e68b2-0040-4881-a47b-06da85484aec">

* Based on the data from the recent three months, bike stations are most busy on Wednesdays at 6pm with a total of 4, 597 trips. Weekdays between 5 and 6pm seems to be the prime time for bike usage. This is most probably associated with the time when people finish work and school for the day and head off to other destiantions using the bike. It is also quite busy at 8 am on weekdays, which may further support the hypothesis that bikes may be used to get to work/school. 

* There are more bike riders who are members vs. casual and the number of members has grown from March to May. This may suggest that more people rely on the Citibike program for their daily commutes. Although, the duration of trip time measured in minutes is greater for casual bike riders, this may just provide an implication that members are faster bike riders and require less time to get to their final destinations. 

## Map 

* Incldues the geographical locations of start and end stations. 

<img width="1005" alt="Screenshot 2023-06-29 at 9 38 08 PM" src="https://github.com/svafaeva93/Tableau_/assets/124627601/db346518-2442-4270-8e16-8ebe509ae310">


* These maps present the collection of start and end stations from March till May, 2023. It can be seen that the concentration of most frequently used stations fall in the zipcode of 070302 and 07030. This shows that residents of Jersey City rely on the bike sharing service based on its cost-effectiveness in comparison to other modes of transportation. 

## Conclusion 

This Tableau analysis gives a brief overview of the trends and patterns in Citibike usage in the recent three month period. One of the insightful phenomenons observed is the high reliance on bikes by residents of Jersey City, New Jersey, especially during weekdays in rush hours. This gathered information serves as a valuable resource for use in further research of Citibike. 















