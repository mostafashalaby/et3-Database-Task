# et3-Database-Task
This is my work for the 4th task (Database Task) for the et3 Graduate Internship 2022 program. I opted to use Access as my database engine of choice, and that file can be found as "Database1.accdb". My queries can also be found as .txt files. Queries "Query1a.txt" and "Query1b.txt" are both viable solutions for Query 1, but in the case of duplicate maxes, Query1a shows all the duplicated while Query1b only shows one of them.

# How to run
Open "Database1.accdb" and select the queries in order to view the results of them. Screenshots of the queries can be found in the "Screenshots" Folder.


# Notes
* Found an error in line number 239, in the "Total Fat (g)" field, where the value is "3 2".
* Normalised "Varies" to "-1" in "Caffeine (mg)" fields.
* Removed "%" in order to make fields numerical.
* While trying to create a Primary Key, SQL queries showed that there is no sensible way to form a Primary key, so I had two options:
	1- either introduce a new column, "Beverage_ID"
	2- or introduce a new column, "Size", to be used in the composite key with "Beverage" and "Beverage_Prep"
I opted for option 1.

This was a fun project to work on :)


