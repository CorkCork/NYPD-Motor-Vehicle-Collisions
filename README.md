Google Doc Coordination: https://docs.google.com/document/d/1iMbYMWPdWa9e85KVXcxux2m4X-5QLbzXhIhF7AodBOY/edit

# NYPD Motor Vehicle Collision 

NYPD Motor Vehicle Collision dataset has a breakdown of every collision in NYC by location and injury. It has 1.57M rows and 29 columns. 

https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions-Crashes/h9gi-nx95



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


