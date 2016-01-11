# bigdata-projects#datasets
These are the datasests I used for the various student projects in Big Data field, during my studies at Budapest University of Technology and Economics (BME).

**This repository uses large files. Please consider integrating [Git LFS](https://git-lfs.github.com/) into your Git workflow as well!**

# Projects
## Flight data analysis

The data are in the folder called [flight](https://github.com/benedekh/bigdata-projects/tree/datasets/flight/). The data was obtained from [Statistical Computing](http://stat-computing.org/dataexpo/2009/the-data.html) and compressed by [7zip](http://www.7-zip.org/).

* *1987-2008-allInOne.7z:* all the csv records from 1987 to 2008 in one huge csv. **Beware of the compressed size (1.6 GB) and the original size (12.5 GB).**

* *2008.7z:* csv records for year 2008. **Beware of the compressed size (112.8 MB) and the original size (689.4 MB).**

Variable descriptions of the data:

| |Name|Description|
|---|----|-----------|
|1|Year|1987-2008|
|2|Month|1-12|
|3|DayofMonth|1-31|
|4|DayOfWeek|1 (Monday) - 7 (Sunday)|
|5|DepTime|actual departure time (local, hhmm)|
|6|CRSDepTime|scheduled departure time (local, hhmm)|
|7|ArrTime|actual arrival time (local, hhmm)|
|8|CRSArrTime|scheduled arrival time (local, hhmm)|
|9|UniqueCarrier|unique carrier code|
|10|FlightNum|flight number|
|11|TailNum|plane tail number|
|12|ActualElapsedTime|in minutes|
|13|CRSElapsedTime|in minutes|
|14|AirTime|in minutes|
|15|ArrDelay|arrival delay, in minutes|
|16|DepDelay|departure delay, in minutes|
|17|Origin|origin IATA airport code|
|18|Dest|destination IATA airport code|
|19|Distance|in miles|
|20|TaxiIn|taxi in time, in minutes|
|21|TaxiOut|taxi out time in minutes|
|22|Cancelled|was the flight cancelled?|
|23|CancellationCode|reason for cancellation (A = carrier, B = weather, C = NAS, D = security)|
|24|Diverted|1 = yes, 0 = no|
|25|CarrierDelay|in minutes|
|26|WeatherDelay|in minutes|
|27|NASDelay|in minutes|
|28|SecurityDelay|in minutes|
|29|LateAircraftDelay|in minutes|





