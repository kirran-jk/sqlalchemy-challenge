# sqlalchemy-challenge - Surf’s Up!

The following repository contains climate analysis for Hawaii.

### Part 1: Climate Analysis and Exploration

The below analysis utilises SQLAlchemy ORM queries, Pandas, and Matplotlib.

Precipitation Analysis:

 * Plots the last 12 months of precipitation data.

Station Analysis:

 * Gets the min, max, and average temperatures for the most active station.

 * Plots a histogram for the last 12 months of temperature observation data (TOBS) for this station.

Analysis: [climate](climate.ipynb)


### Part 2: Climate App

The below Flask API has the following end points:

* `/`

* `/api/v1.0/precipitation`

* `/api/v1.0/stations`

* `/api/v1.0/tobs`

* `/api/v1.0/<start>` and `/api/v1.0/<start>/<end>`

API: [api](app.py)


### Bonus: Temperature Analysis 1

The followinng analysis compares June and December temperature observations data. A t-test has been conducted to determine whether the difference in means, if any, is statistically significant.

Analysis: [bonus1](temp_analysis_bonus_1.ipynb)


### Bonus: Temperature Analysis 2

* A bar plot of the minimum, average, and maximum temperature for the duration of the trip in a previous year.

* Rainfall per weather station for the duration of the trip in a previous year.

* An area plot of the daily temperature normals for the duration of the trip in a previous year.

Analysis: [bonus2](temp_analysis_bonus_2.ipynb)
