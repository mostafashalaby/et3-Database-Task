Found an error in line number 239, in the "Total Fat (g)" field, where the value is "3 2".
Normalised "Varies" to "-1" in "Caffeine (mg)" fields.
Removed "%" in order to make fields numerical.
While trying to create a Primary Key, SQL queries showed that there is no sensible way to form a Primary key, so I had two options:
	1- either introduce a new column, "Beverage_ID"
	2- or introduce a new column, "Size", to be used in the composite key with "Beverage" and "Beverage_Prep"
I opted for option 1.