# evtx
Merge evtx files
* MergeEvents - The Script to merge all the evtx files from a specific folder into one single evtx file. 
Gone are the days, when you used to convert your events into csv first and then Merge the csv.

* Description
The purpose of the tool is merge all the evtx files you've have collected from your event viewer or from some sources. 
This would be helpful for SIEM professionals who requires to merge multiple evtx files for some attack analsis and use case creation.

* How to use it ?

1.Extract the zip file and place all your evtx files in a folder (you can put the evtx files in the same folder which you've extracted, it will work).
2.Run the script by giving the -FolderPath argument.From the same folder where you've kept the evtx files, 
run the script with PowerShell (Make sure the path is correct)
3.It will merge all the events inside into a Merge.evtx file and an xml file "StructuredQuery.xml" will also be created.

You can also run the installer that will create some registry entries to give the possibility
to right-click the folder then run the script that will merge the content.

Happy Merging :)

#Eyes_On_Glass_Hunt
