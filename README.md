# Big-Data-Project
The objective of the project is to get the following information from original NCDC records(Data) for a decade between 1921-1930:
* Maximum Temperature
* Minimum Temperature
* Average Temperature

# Procedure and Methodology
* Developed a Mapper and Reducer application to retrieve Year and Temperature from original NCDC records and then write the Year and Temperature data into a text file.
* The text file is loaded into Pig to get the highest and lowest temperatures for each year
* The text file is loaded into Hive to get the average temperature for each year

# Technology & Resources
* Hadoop
* Hive
* Pig
* WinSCP
* Putty
* AWS - EC2, S3 Storage

# Repository Content
* Data Folder -- Contains all the NCDC Record gz files for the project
* Jar Files Folder -- Contains all the jar files required for the Hadoop
* Java Files Folder -- contains all the java files required for the functions
* Code -- Contains all code in Hadoop, Hive and Pig for the whole procedure
* Output Files -- Max Temp, Min Temp and Avg Temp are the output screen shots of the process.
