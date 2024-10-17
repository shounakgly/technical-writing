## About Creating Workbook Email Schedules 
You can set up a schedule to share visualizations from a workbook in PDF file or PNG image format by email with one or more recipients. Schedule hourly, daily, weekly, monthly, or yearly emails to keep recipients up to date with the latest data.

This feature is currently available for preview (Enterprise Edition only). Ask your administrator to enable the Preview Workbook Email Scheduler feature in Console and Preview Workbook Email Scheduling with Bursting in System Settings to use the bursting feature. See [Preview Options](https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/analytics-cloud/acubi&id=ACABI-GUID-CA9CF906-506C-429B-BDAB-494D4918514C). 

To schedule delivery of visualizations, your organization must have email settings configured in Oracle Analytics. See [Set Up an Email Server to Deliver Reports](https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/analytics-cloud/acubi&id=ACABI-GUID-72A0F365-127F-45DB-902C-45E17376B1EC) and [Email Delivery Limits](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/servicelimits.htm#Email_Delivery_Limits). 

- You can create schedules for a workbook if you are a member of the BI Service Administrator application role with Read-Write access and the Edit share permission for that workbook.
- Delivery schedules for workbooks use the file name and workbook path. If a workbook is moved or renamed, delete the existing schedule and create a new schedule. See [Manage Workbook Email Schedules and Jobs (Preview)](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acubi/share-visualizations-using-workbook-email-schedules-preview.html#GUID-402C2583-480A-4E46-85CA-B3CD9674B431). 
- You can create schedules for workbooks in Shared Folders. Workbooks in My Folders aren't accessible by others.
- You can set a schedule to repeat hourly, daily, weekly, monthly, or yearly.
- Visualization components not supported for workbook email schedules include: Custom Plugin extensions, Filter Bar objects, and Trending Lines.
