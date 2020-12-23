Climate Analysis and Exploration

Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii! To help with your trip planning, you need to do some climate analysis on the area. The following outlines what you need to do.

Technology:

Python

SQLAlchemy ORM queries

Pandas

Matplotlib

Directions:

Use SQLAlchemy create_engine to connect to your sqlite database.


Use SQLAlchemy automap_base() to reflect your tables into classes and save a reference to those classes called Station and Measurement.

Design a query to retrieve the last 12 months of precipitation data.


Select only the date and prcp values.


Load the query results into a Pandas DataFrame and set the index to the date column.


Sort the DataFrame values by date.


Plot the results using the DataFrame plot method.

Use Pandas to print the summary statistics for the precipitation data.



Station Analysis


Design a query to calculate the total number of stations.


Design a query to find the most active stations.


List the stations and observation counts in descending order.


Which station has the highest number of observations?


Hint: You will need to use a function such as func.min, func.max, func.avg, and func.count in your queries.




Design a query to retrieve the last 12 months of temperature observation data (TOBS).


Filter by the station with the highest number of observations.


Plot the results as a histogram with bins=12.

Use Flask to create your routes.

Hawaii is reputed to enjoy mild weather all year. Is there a meaningful difference between the temperature in, for example, June and December?


You may either use SQLAlchemy or pandas's read_csv() to perform this portion.


Identify the average temperature in June at all stations across all available years in the dataset. Do the same for December temperature.


Use the t-test to determine whether the difference in the means, if any, is statistically significant. Will you use a paired t-test, or an unpaired t-test? Why?

Use the calc_temps function to calculate the min, avg, and max temperatures for your trip using the matching dates from the previous year (i.e., use "2017-01-01" if your trip start date was "2018-01-01").


Plot the min, avg, and max temperature from your previous query as a bar chart.


Use the average temperature as the bar height.


Use the peak-to-peak (TMAX-TMIN) value as the y error bar (YERR).

Analysis: The best time to vacation in Hawaii is in August according to 2017 data. According the most active station the lowest temperature is only 54 while the highest is 85 and the average is 71.66. This seems like it won't be too hot or too cold for vacation time.

This was not done in a day, pulled from homework repository.

![image](https://user-images.githubusercontent.com/66101341/101559867-48cdaa80-397f-11eb-8c14-876019ba5abb.png)

![image](https://user-images.githubusercontent.com/66101341/101559893-5c791100-397f-11eb-95b8-d52b91a68aa0.png)

![image](https://user-images.githubusercontent.com/66101341/101559931-69960000-397f-11eb-932d-102c66b7fe9e.png)
