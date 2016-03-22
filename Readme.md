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


![alt tag](https://github.com/ektahuja/INFM600/blob/master/Crime_PublicElementarySchools_merged_zipcode.jpg)
  
Fig. 2

The results were entered in an Excel file to analyze the change seen in the number of records for every zip code.(please refer Analysis.xls)

---------------
Intial Conclusion
---------------
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
   	in a commercial context should contact the owners(Ekta Ahuja and Rohan Khadilkar).

----------
References
----------

dataMontgomery. (2016, Mar 15). Crime [Dataset CSV file] Available: https://data.montgomerycountymd.gov/Public-Safety/Crime/icn6-v9z3 Date Accessed: March 17, 2016.

dataMontgomery. (2016, Mar 15). Public Elementary Schools [Dataset CSV file] Available: https://data.montgomerycountymd.gov/Education/Public-Elementary-Schools/j7rm-vyfs Date Accessed: March 15, 2016.

Khadilkar, R., & Ahuja, E., (2016, March 15). Crime Rate near Public Elementary Schools. [Dataset CSV file]. Available: https://github.com/ektahuja/INFM600/blob/master/Crime_PublicElementarySchools_merged.csv

-------
Credits
-------

This dataset was built by Ekta Ahuja and Rohan Khadilkar. To reference, you can use the following citation:
hadilkar, R., & Ahuja, E., (2016, March 15). Crime Rate near Public Elementary Schools. [Dataset CSV file]. Available: https://github.com/ektahuja/INFM600/blob/master/Crime_PublicElementarySchools_merged.csv