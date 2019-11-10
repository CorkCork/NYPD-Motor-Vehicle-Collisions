
#### Overview
[NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95) contains details on the crash events. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The dataset can be found by following this link: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95

#### High-Level Description
The data dates from 2012 to the current day, with data being updated on a daily basis. At the time of this writing, there are 1.59 million rows, each row representing a crash event, and over 29 columns which represent date, time, borough, zip code, latitude, longitude, location, on and off street name, cross street name, number of persons injured, number of persons killed, number of pedestrians injured, number of pedestrians killed, number of cyclist injured, number of cyclist killed, number of motorist injured, number of motorist killed, contributing factors, vehicle type codes and collision ID.

In this project, we will be doing the following:

* Ingest some data from the [NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95). We will use Socrata API to just select a limited number of rows.
* Clean the dataset to make it ready for analysis.
* Make analysis and visualizations.
* Explain our findings by using markdown as we go along.
