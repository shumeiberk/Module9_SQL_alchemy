# Module 9 Surfs Up Analysis

# Challenge Overview

Gather data on the seasons of Oahu and determine whether the seasons could affect the surf and ice cream shop business. Specifically, are there certain times of the year when business might be slower, or the type of customer could be different?
Your investors want to ensure that there are enough customers between seasons to sustain the business throughout the year.
Find a few key aspects of Oahu’s seasonal weather data. The investors want to ensure you’ve hit all of the key points before opening the surf shop.

# Sources
Data Source: hawaii.sqlite
Software: Python 3.6.1, Jupyter Notebook 6.0.1, SQLalchemy, SQLite

# Challenge Results

- Based on the annual analysis of the Oahu precipitation levels it's observed that across all months, the potential for rain is fairly low.  As you can see below chart and the precipitation statistics, between 2016-08-23 to 2017-07-10, there have only been short spurts of heavy rain while over 50% of the time it's pretty mild.
This is good for the surf & ice cream shop business because the annual business outlook provides majority where business and customers won't be impacted by rain. 

![precipitation](https://github.com/shumeiberk/Module9_SQL_alchemy/blob/master/images/precipitation.PNG)
![prcp_stats](https://github.com/shumeiberk/Module9_SQL_alchemy/blob/master/images/prcp_stats.PNG)

- In the most active station (USC00519281) we also observe over the year that the temperature are between 60-87 degrees with the majority of the year staying around 75 degrees which is also good for business as it's comfortable temperatures for people to be outside especially at the beach for a surf and ice cream business 

![tobs](https://github.com/shumeiberk/Module9_SQL_alchemy/blob/master/images/tobs.PNG)

- If we look at just June statistics, we can see that the temperatures are also comfortable with average 75 degrees and max 85 degrees

![june_stats](https://github.com/shumeiberk/Module9_SQL_alchemy/blob/master/images/june_stats.PNG)

- If we compare June to Dec statistics, Dec is a little cooler with average at 71 degrees and max is 83 degrees.  For both these months, weather is comfortable with maybe a few outliers where weather might be a little cooler but probably in the evenings.

![dec_stats](https://github.com/shumeiberk/Module9_SQL_alchemy/blob/master/images/dec_stats.PNG)

# Recommendations for further analysis

We can see that overall assessment is that majority of the year in Oahu, weather is prime for a surf & ice cream business as it's majority warm with few rainy occurrences.  However, we know there is a small group that are outliers in both temperature and precipitation.  Further analysis to dig deeper to optimize sales or prepare a strategy is finding out when and where exactly these outliers occur.  We can dig into the extreme changes for heavy rains during the year and can potentially cut back on the number of hours the business is open and also thinking through which station would be impacted.

