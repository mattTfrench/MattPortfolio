# MattPortfolio
Project 3 is an example of data cleaning using SQL for real estate in Nashville.

Unfortunately, my project in Microsoft Access was too big to upload here. Instead, I uploaded the data set and my SQL queries in a Word Document.

The following 12 SQL queries were used for data cleaning an Excel document uploaded to Microsoft Access. The queries were organized as follows: 

    •	Query 1 tests that all data was successfully uploaded.

    •	Query 2 standardizes the date format.

•	Queries 3-6 correct missing PropertyAddress values for multiple rows.

    o	Through a quick test (query 3), you can see that each Parcel ID value corresponds to an address. Therefore, the missing property addresses can be found by finding the corresponding Parcel IDs and matching them to a missing property address.
    
    o	Query 3 tests that the values are null.
    
    o	Query 4 creates a new table new_table.
    
    o	Query 5 inserts values from the raw data to the new_table.
    
    o	Query 6 updates the original table with the necessary PropertyAddress values.
    
    •	Queries 7-9 change Y/N values to Yes/No to help with comprehension.
    
•	Queries 10 and 11 remove duplicates.

    o	Query 10 shows duplicates.
    
    o	Between queries, I made a second version (v2) of my table by copy and pasting the “structure only” option. In the new table, I changed the Property Address, Sale Date, Sale Price, and Legal Reference to be primary keys. These are the indicators of a unique row.
    
    o	Query 11 appended the old table’s data to the new data. The primary key change from the last step prevented duplicates from appending over because they were deemed key violations.
    
    o	Only unique rows are in the second version (v2) of the table.
    
•	Query 12 deletes unused columns.
