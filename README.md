# MTA_TurnstileAnalysis
Scrape and clean MTA subway data, compare 04/2019 with 04/2020 (during stay at home). 
Tools: Python, Pandas, Seaborn

The aim is to find the subway stations, the overall traffic has changed the least. 

Combining data from:
* http://web.mta.info/developers/turnstile.html
* https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49

Least and Most Effected Stations:

<img src="ChangeTraffic_1.jpeg" alt="Max & Min Effected Stations" width="600" height="166">

The final data is exported to a csv, final mapping is done in QGIS

<img src="ChangeTraffic.jpeg" alt="Traffic Change <-80%" width="400" height="400">
