# File_System_Cleaner

A simple tool that can be used to clean up one's file system. This cleaning process consists of some menial tasks such as:
* Deleting all empty directories starting from a specified root directory
* Deleting the TEMP directory
* Deleting all files older than a given time period from a specified root directory
    
This tool is used on the command line in the following way.
FileSystemCleaner.exe /empty

* Remove empty directories (no confirmation given)</br>
FileSystemCleaner.exe /empty /quiet
