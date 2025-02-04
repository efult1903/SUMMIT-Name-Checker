# SUMMIT-Name-Checker
The purpose of this program is to compare the names of an older client list to a newer client list
This will identify who is no longer in the newer client list, allowing us to inquiry about them.

Walk-Through below, see "RB Comparison Trick" text file for advanced info
[Startup]
Double click the "Name Check" application (blue character icon)
Startup may be a bit longer than the other programs, that is normal

[Uploading Files]
***IMPORTANT: Make sure the column names (the headers) are the first row!***
Click "Upload Least Recent CSV" and you may select any .csv file on your computer to be used
as the file we will be checking for names that are unique to it
Select the column that contains the names of the clients

Click "Upload Most Recent CSV" and you may select any .csv file on your computer to be used
as the file we will be check for names that are missing
Select the column that contains the names of the clients

[Checking & Exporting]
Ensure the names of the CSV files and the chosen columns are correct 
(In "File Status" listed in blue)

Click "Compare Names" to get a list
If no unique names are present, check to ensure the files were uploaded in the proper order
If they were, then nothing has changed between the two months

If everything looks accurate, you may click "Export Unique Rows" to any CSV file you'd like
I have provided a "missingNames" CSV file you may use. If uploading multiple results, you may
save it to the same file.
***IMPORTANT: It will ask if it's okay to replace the file that already exists. Select YES,
it will save the previously exported data as well.***
