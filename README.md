# Yankee-Met-Fan-Locations-Via-Taxi-Data

This is a quick project I did for a Data Scientist interview that ended up landing me the job!  I was given a week to utilize any data from NYC Open Data (https://opendata.cityofnewyork.us/) to try and answer some interesting questions and give a 10 or 15-minute presentation about my methods and findings.

I took a look at NYC Taxi data after the Yankees and Mets games to show where people headed to after the games.  I utilized a single class support vector machine to try to normalize the traffic data and remove what was considered ordinary traffic not caused by the games themselves.  I then produced choropleth maps of what the model believed was traffic caused by games to show where people were heading.  

Please see the pdf file included in the repo as the output for the presentation I gave during the interview.  

## Files

* taxi.ipynb - Where most of the work occurred.  SVM model is located here as well as the output charts.
* build_db.ipynb - The code to build the SQLite database where I pulled the relevant information from the taxi trip datasets.
* schedule.ipynb - The code where I extracted the game data to determine what taxi trips I needed to pull.  

* Data_Dict.pdf - Overview of the NYC Taxi data
* Where do Yanks and Mets Fan Live.pdf - The slide deck for the presentation I gave.  This was the single deliverable asked for.  


