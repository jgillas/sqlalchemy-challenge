# sqlalchemy-challenge

In this challenge we were asked to do a Precipitation Analysis and a Station Analysis for the state of Hawaii. 

In the precipitation analysis we were asked to find the most recent date in the dataset which was 2017-08-23. Then I performed a query to gather data and precipitation scores greater than or equal to one year from the most recent date (2017-08-23). Then I created a dataframe with this information and created columns for Date and Precipitation. I then sorted this by the date and created a graph to display the data. 

The graph is below: 
  
  <img width="701" alt="Screenshot 2023-05-11 at 2 34 14 AM" src="https://github.com/jgillas/sqlalchemy-challenge/assets/125215083/41a75ba8-2822-4de2-80f5-2c391daa172b">
  
I then created a summary statistics table for the precipitation data that I gathered. The table is below: 

  <img width="161" alt="Screenshot 2023-05-11 at 2 15 23 AM" src="https://github.com/jgillas/sqlalchemy-challenge/assets/125215083/176ba830-2cba-4c7b-a7e2-a2e72e83ed85">

After the precipitation analysis was done, I moved onto the station analysis. Here I found that there were nine total stations in Hawaii. The most active station was station USC00519281. The minimum temperature for this station was 54. The maximum temperature for this station was 85. Lastly the average temperature for this station was 71.66. I then did a query for the past 12 months of this data and I used the temperature, filtered it by the most active station and then filtered the whole query by the date being greater than or equal to one year from the most recent date (2017-08-23). I created a histogram to display this data. 

The histogram is below:

  <img width="432" alt="Screenshot 2023-05-11 at 2 31 34 AM" src="https://github.com/jgillas/sqlalchemy-challenge/assets/125215083/3c27e1cb-93ae-474d-b31e-673886b90dcc">

This concludes the first half of the assignment. 

The second half of this assignment I designed a Climate App for the climate of Hawaii. I started off with a homepage which welcomes viewers to the site and shows them all the available routes they can take. 

The first route they can take is "/api/v1.0/precipitation" which will take them to a page showing them all the dates with the corresponding prcp values for 12 months of data. 

The second route they can take is "/api/v1.0/stations" which will take them to a page showing them all the different stations in Hawaii. 

The third route they can take is "/api/v1.0/tobs" which will take them to a page showing them all the dates with the corresponding temperature observations for the most active station in the previous year. 

The fourth route they can take is "/api/v1.0/<start>" where they can enter a date in the format of "%Y-%m-%d" and the page will show them the minimum , maximum , and average temperatures for the specified start date.

The fifth and final route they can take is "/api/v1.0/<start>/<end>" where they can enter a start date in the format "%Y-%m-%d" and an end date in the format "%Y-%m-%d" and the page will show them the minimum, maximum, and average temperatures from the start date to the end date. 
  
This concludes the second part of the assignment. 
