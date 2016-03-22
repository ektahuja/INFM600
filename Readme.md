I# INFM600
-----------
Version
-----------

Version 1.0 (March 2016)

-----------
Description
-----------

**Focal Data**

**Crime.csv**

This file includes data about all the crimes committed at various locations in the state of Maryland. It includes important details such as zipcode, latitude, longitude, city, class of crime and so on.

**Supporting Data Set**

**Public_Elementary_Schools.csv**

This data set includes information about the elementary schools in the state of Maryland. It has data values describing name of the school, address, city, state, zip code, latitude, lontitude and so on.


**Merged Dataset**

**Crime_PublicElementarySchools_merged.csv**

TThis dataset consists of all records from the Crime and Public Elementary Schools database in Montgomery County, joined on the column “City”.



---------------
Analysis
---------------

Does crime happen in or around school areas? Which would the safest school in Montgomery county?
General perception is that school areas are generally safe. This question will help understand whether that’s the case.


All analysis was done using the freely available analysis tool Tableau and Microsoft Excel.


The Public Elementary Schools dataset was analyzed first. Here, we identified the unique school areas (according to zip code) in Montgomery County. (please refer Fig.1)




![alt tag](https://github.com/ektahuja/INFM600/blob/master/Public_Elementary_Schools_zipcode.jpg)

Fig. 1

Then, the merged dataset Crime_PublicElementarySchools_merged.csv was used to analyze whether crime happens in school areas. (please refer Fig.2)


![alt tag](https://github.com/ektahuja/INFM600/blob/master/Crime_PublicElementarySchools_merged.csv)
  
Fig. 2

The results were entered in an Excel file to analyze the change seen in the number of records for every zip code.(please refer Analysis.xls)

Initial Conclusion
There was a huge increase seen in the values for every zip code. However, the change in number of records for Zip Code 20896 was only 1. Therefore, we believe crime does happen in or around school areas. However, the safest school in Montgomery County would be for the Zip Code 20896 i.e. Garrett Park ES (Construction) school in Garrett Park.


-----
Files
-----

*Crime.csv*

*Public_Elementary_Schools.csv*

*Crime_PublicElementarySchools_merged.csv*

*Process Documentation.pdf*

------- 
License
-------

The data in the INFM600 repository is distributed under a Creative Commons 
Attribution-NonCommercial-ShareAlike 4.0 International License (see 
http://creativecommons.org/licenses/by-nc-sa/4.0/).
   
	The data is made available for non-commercial use. Those interested in using the data 
   	in a commercial context should contact the owner(Ekta Ahuja).

----------
References
----------

The Geographic Information Systems Division. (2015). Presubmission Community Meetings [Data set CSV file]. Retrieved from https://data.howardcountymd.gov/. October 21, 2015

The Geographic Information Systems Division (2014) Age Restricted Houses [Data set CSV file]. Retrieved from https://data.howardcountymd.gov/. October 21, 2015

The Geographic Information Systems Division (2014) Age Restricted Apartments [Data set CSV file]. Retrieved from https://data.howardcountymd.gov/. October 21, 2015

Ekta, A. (2016). Crime_PublicElementarySchools_merged [Data CSV file]. Available from https://github.com/ektahuja/INFM600/.

-------
Author
-------

Ekta Ahuja