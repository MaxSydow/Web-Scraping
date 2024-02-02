# Data Wrangling Using OpenStreetMap

Introduction
When creating a database from web content, formatting inconsistencies need to be taken into account.  Data cleaning packages and regular expressions come in handy.  The central portion of the city of Minneapolis, MN was extracted from the OpenStreetMap Overpass API as an XML file.  I chose this city, because I grew up there and am currently missing it's mild summers.  Data such as street names, and zip codes can be extracted from tags in the XML file using Python's iterparse() method.  The data as elements inside the tags were then used to populate csv's.  These csv's were then used to populate tables in a SQL data base using Python's sqlite3 package.  From here the data can be explored using queries, and further cleaned with Python.

## Packages 


## Functions

## Findings
