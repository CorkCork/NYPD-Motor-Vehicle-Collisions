<<<<<<< Updated upstream

#### Overview
[NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95) contains details on the crash events. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The dataset can be found by following this link: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95

#### High-Level Description
The data dates from 2012 to the current day, with data being updated on a daily basis. At the time of this writing, there are 1.59 million rows, each row representing a crash event, and over 29 columns which represent date, time, borough, zip code, latitude, longitude, location, on and off street name, cross street name, number of persons injured, number of persons killed, number of pedestrians injured, number of pedestrians killed, number of cyclist injured, number of cyclist killed, number of motorist injured, number of motorist killed, contributing factors, vehicle type codes and collision ID.

In this project, we will be doing the following:

* Ingest some data from the [NYPD Motor Vehicle Collision Dataset](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95). We will use Socrata API to just select a limited number of rows.
* Clean our data to prepare it for analysis.
* Make analysis and visualizations.
* Explain our findings by using markdown as we go along.
=======
Google Doc Coordination: https://docs.google.com/document/d/1iMbYMWPdWa9e85KVXcxux2m4X-5QLbzXhIhF7AodBOY/edit

# NYPD Motor Vehicle Collision 

NYPD Motor Vehicle Collision dataset has a breakdown of every collision in NYC by location and injury. It has 1.57M rows and 29 columns. 

https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95


* Obtaining and ingestion one (or, optionally, more) datasets. 
* The principal dataset will be provided from pre-defined publicly available data sources 

DATA CLEANING
* drop data missing above 70 percent: Esin had?
* rop  columns 3-5 for contributing factors
* drop  columns 3-5 for vehicle types?
* drop unique value [we have an index]
* to_datetime: Alan had
* learn regex to combine contributing factor values and vehicle types [Alan]

DATA ANALYSIS
* value counts for accident on street?

* Alan: Death Rates by motorist/cyclist/pedestrian, main contributing factors, death by date
    > idea: group by external/internal causes [drunk vs falling rocks]

* Kristin: Pedestrians 

* Esin: Seasons/Time variability [other datasets?] Avg death by hour and Avg death by borough
> idea: Maybe corelate with traffic volume?

Data Viz
* Show the analyses?

WEEK 10-13
* Add Statistical Analyses
* Better Visualizations


>>>>>>> Stashed changes
