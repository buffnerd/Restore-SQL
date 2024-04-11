# Restore-SQL
Powershell Automation Script that checks for an existing SQL DB and if it doesn't exist then it restores it with backup data. The backup data file needs to be in the same directory as the script. You may change certain information in this script depending on your needs.

There are 3 .sql files included which are dependencies for the script to work.  The 3rd dependency "Client_A_Contacts.sql" calls an existing backup .csv file from within the same directory.  If you are using this for your own implementation, you may need to change some pathing in the .sql file and .csv file as well as rename them according to suit your needs.
