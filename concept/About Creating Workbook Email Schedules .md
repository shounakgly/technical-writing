# About Creating Workbook Email Schedules 
You can set up a schedule to share visualizations from a workbook in PDF file or PNG image format by email with one or more recipients. Schedule hourly, daily, weekly, monthly, or yearly emails to keep recipients up to date with the latest data.

This feature is currently available for preview (Enterprise Edition only). Ask your administrator to enable the Preview Workbook Email Scheduler feature in Console and Preview Workbook Email Scheduling with Bursting in System Settings to use the bursting feature. See [Preview Options](https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/analytics-cloud/acubi&id=ACABI-GUID-CA9CF906-506C-429B-BDAB-494D4918514C). 

To schedule delivery of visualizations, your organization must have email settings configured in Oracle Analytics. See [Set Up an Email Server to Deliver Reports](https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/analytics-cloud/acubi&id=ACABI-GUID-72A0F365-127F-45DB-902C-45E17376B1EC) and [Email Delivery Limits](https://docs.oracle.com/en-us/iaas/Content/General/Concepts/servicelimits.htm#Email_Delivery_Limits). 

- You can create schedules for a workbook if you are a member of the BI Service Administrator application role with Read-Write access and the Edit share permission for that workbook.
- Delivery schedules for workbooks use the file name and workbook path. If a workbook is moved or renamed, delete the existing schedule and create a new schedule. See [Manage Workbook Email Schedules and Jobs (Preview)](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acubi/share-visualizations-using-workbook-email-schedules-preview.html#GUID-402C2583-480A-4E46-85CA-B3CD9674B431). 
- You can create schedules for workbooks in Shared Folders. Workbooks in My Folders aren't accessible by others.
- You can set a schedule to repeat hourly, daily, weekly, monthly, or yearly.
- Visualization components not supported for workbook email schedules include: Custom Plugin extensions, Filter Bar objects, and Trending Lines.

## Bursting Schedules
Create a bursting schedule to deliver workbook data visualizations to recipients if the data visualizations contain confidential data that is accessed by specific application roles and user groups configured in Oracle Analytics. Each recipient receives a customized data visualization based on their data access configuration instead of the data access configuration of the administrator user who creates the schedule. See [Create a Bursting Workbook Email Schedule (Preview)](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acubi/share-visualizations-using-workbook-email-schedules-preview.html#GUID-FD7B1432-B8B5-4E2A-AB84-80F5BCBC81FD)

- Bursting is available for schedules created from workbooks saved in Shared Folders.
- By default, bursting is disabled when you begin creating a new schedule.
- Bursting does not allow you to send visualizations to external recipients that are not already configured in Oracle Analytics.
- When using bursting, you can add up to 100 recipients that are individual users or application roles configured in Oracle Analytics. For example, if you add an application role BI Consumer as a recipient where more than 100 users are assigned this role, the schedule will fail to send the visualizations to any recipient after the 100 recipients.

## Managing Schedules
You can manage existing workbook email schedules and check the status of scheduled jobs, view, edit, or delete schedules. See [Manage Workbook Email Schedules and Jobs (Preview)](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acubi/share-visualizations-using-workbook-email-schedules-preview.html#GUID-402C2583-480A-4E46-85CA-B3CD9674B431).

- A workbook email schedule is edited by the schedule’s author or any user with the same access and edit permissions for the workbook. The data visualizations shared with recipients are based on the data access configuration of the administrator user who edits and saves changes to the schedule.
- When the data visualizations in a workbook are edited once a workbook email schedule is created from the workbook, the saved changes to the workbook’s data visualizations are reflected in the scheduled emails based on the data access configuration of the administrator user who saved the schedule.
- Bursting workbook email schedules with more than one recipient trigger jobs for each recipient in the schedule whether they are an individual user or part of an application role. Each recipient receives a customized version of a data visualization based on their data access configuration in Oracle Analytics.



