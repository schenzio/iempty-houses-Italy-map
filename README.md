# Animated choroplet map of empty houses in Italy
This map shows the unoccupied dwellings by Italian provinces with an animation that switches between 2011 and 2019 data, and a menu to control it. It was programmed with d3.js, merging with Python two different dataset of Istat (previously analyzed and cleaned with Google spreedsheet, see [2011](https://docs.google.com/spreadsheets/d/1-aK98x_evBIsakuV_yLzOtDu2ShSLwJT-9QgQU-yS3A/edit?usp=sharing) and [2019](https://docs.google.com/spreadsheets/d/1bGEKx3bTTivCBM8G-a5vTal71f0xz_HztmodrAeqNjk/edit?usp=sharing) raw data), the Italian institute of statistics. The merge required some operations in the 2011 data since some boundaries of provinces have changed during the years (ex. provinces of Medio Campidano and Carbonia-Iglesias were joined in Sud Sardegna). As a result, the map present the 2019 provinces’ boundaries both for 2011 and 2019 (see the jupyter notebook for details).

## Sources:
- [2011 Istat housing and population census](http://dati-censimentopopolazione.istat.it/index.aspx?queryid=11967) 
- [2021 Istat housing and population census](http://dati-censimentipermanenti.istat.it/?lang=en&SubSessionId=aa99f561-c6ec-4244-bb42-6ce2443efe16)
- [Topojson data of Italian provinces](https://github.com/openpolis/geojson-italy/blob/master/topojson/limits_IT_provinces.topo.json)
