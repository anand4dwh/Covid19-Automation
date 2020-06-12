# Worldometer_Automation_UIPath
Demo project on Scraping Covid-19 Data from worldometer website.

Update -- 26.05.2020

Added CleanUpExcelSheet, This will clean up the unwanted/repeated sheets in the excel COVID19_Report.

Added GetPowerBIScreenshot, GetPowerBIScreenshot will log in into the PowerBI server and gets the screenshot of the COVID19 latest report. (IMP Note: GetPowerBIScreenshot is not mandatory if you have an official account to PowerBI Server leave the workflow as-it-is, if not then you can disable the GetPowerBIScreenshot activity from the workflow and remove the path from (Attach Files) argument from SMTP Email activity.)

For email setup, change your password at GetPassword Activity in the workflow.

Update on 14.05.2020 -- Added Date & Time column in excel sheet
Update on 14.05.2020 -- Email format slightly changed.

