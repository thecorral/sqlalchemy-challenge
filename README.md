# sqlalchemy-challenge

In this climate analysis report, we explore the climate data of Honolulu, Hawaii, to aid in planning a long holiday vacation. We used SQLAlchemy ORM to reflect the tables from an existing database and retrieve data from the measurement and station tables.

For the exploratory precipitation analysis, we found the most recent date in the data set and designed a query to retrieve the last 12 months of precipitation data. We saved the query results as a Pandas DataFrame, sorted it by date, and used Pandas Plotting with Matplotlib to plot the data. We also calculated summary statistics for the precipitation data using Pandas.

For the exploratory station analysis, we calculated the total number of stations in the dataset and found the most active stations with the most rows. We then used the most active station id to calculate the lowest, highest, and average temperature. Finally, we queried the last 12 months of temperature observation data for this station and plotted the results as a histogram.

In conclusion, our analysis shows that the precipitation levels in Honolulu, Hawaii, are relatively constant throughout the year, with some occasional spikes during the months of November and December. The most active station in the area is USC00519281, which has a minimum temperature of 54°F, a maximum temperature of 85°F, and an average temperature of 71.7°F. Based on our analysis, the best time to visit Honolulu, Hawaii, is during the months of April, May, September, and October when the temperatures are mild and the precipitation levels are low.