# Stuudents-performance-and-Payments-POWERBI-
Group 6 LuxDev

This File contains a flat table students data with 324 rows 
It contains details on school, students ,teachers , Fee payments and assessments
DATA CLEANING
Started by removing duplicates to ensure no id is repeating itself. 
There was some alphabetical error on names,all locations(subcounty,county,region and country),Fixed by Capitalising each first word
Recreated students , subject and teachers id column using conditional function for validity
Replaced nulls in text columns with unknown and replaced errors in numeric function as null
Created a custom column to fix guardians phone numbers to be similar in all rows
Some student ages were -4 so i replaced them as null
The dates were in text form so i converted all to dates 
 Fixed all inconsistency in the location of the teachers , school and students respectively

 DATA MODELLING
 Here , i am creating a star schema , with one fact table and dimension tables
 Created a dimension table on teachers table , students ,school table and location table
 In Location , i created mini tables of location of the students , teachers and schools , appended the 3 tables as a new query and created one location table 
 
