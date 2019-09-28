# crimes_nyc
This project was created during the Big Data Analytics course at OsloMet. This is a joint work of four students.

About the dataset:

We have initially gathered 4 sources of data:
- 2006-2017 NYPD Complaint Data Historic. Source: https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
- 2012-2013 School Zones. Source: https://data.cityofnewyork.us/Education/2012-2013-School-Zones/4szu-rxzq
- 2013 - 2018 Demographic Snapshot School. Source: https://data.cityofnewyork.us/Education/2013-2018-Demographic-Snapshot-School/s52a-8aq6
- 2012 SAT Results. Source: https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4

Our original dataset consists of 6.5 million rows of crimes occurring from 2006 to 2017 in New York. As we only found SAT data from 2012 and we demographic data from 2013, we chose to only look at crimes from 2013 → 500 000 rows. Dropped rows with NaN values and invalid data and grouped / dropped certain crime types → approx. 98 000+ rows.

