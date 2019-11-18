
#### Overview
[NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95) contains details on the crash events. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The dataset can be found by following this link: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95
***** 
#### High-Level Description
The data dates from 2012 to the current day, with data being updated on a daily basis. At the time of this writing, there are 1.59 million rows, each row representing a crash event, and 29 columns which represent date, time, borough, zip code, latitude, longitude, location, on and off street name, cross street name, number of persons injured, number of persons killed, number of pedestrians injured, number of pedestrians killed, number of cyclist injured, number of cyclist killed, number of motorist injured, number of motorist killed, contributing factors, vehicle type codes and collision ID.
***** 
#### The Project
In this project, our main goal is to influence lawmakers to improve legislation to lower speed rates at certain times or implement other traffic calming activities at specific times. Additionally, our goal is to inform people to take extra precautions during certain times and/or in certain areas or avoid if possible.

To do so, we will be doing the following:

* Ingest some data from the [NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95). We will use Socrata Open Data API to just select a limited number of rows.
* Clean the dataset to make it ready for analysis.
* Make analysis and visualizations to see the boroughs and times when collisions occur mostly. 
* Explain our findings by using markdown as we go along.
*****
#### Dependencies
In order to use make analysis, you need to ingest 3000000 rows from the [NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95) via Socrata Open Data API and its `limit` parameter. 
`pd.read_csv("https://data.cityofnewyork.us/resource/h9gi-nx95.csv?$limit=3000000")` 
***** 
#### Authors
Esin Alpturk<br/>
Alan Leidner<br/>
Kristin Medlin
