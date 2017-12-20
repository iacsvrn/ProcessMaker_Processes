# ProcessMaker_Processes
A set of support processes made in ProcessMaker to add additional functionality

-----------------------

## [Bulk Case Management](https://github.com/donawick/ProcessMaker_Processes/blob/master/Bulk_Case_Management-2.pmx)
ProcessMaker does not currently have a way to "mass" delete cases and I'm sure they wouldn't recommend modifiyng the database. This process will allow you to have a mass-cancelation of cases under a specific user.

## [Clone Case](https://github.com/donawick/ProcessMaker_Processes/blob/master/Clone_Case_Process-4.pmx)
This process will allow you to clone a specific case (giving it a new case #) as they do not currently have a way of doing something like this for testing purposes.

## [Copy Case Data](https://github.com/donawick/ProcessMaker_Processes/blob/master/Copy_case_data-1.pmx)
Similar to the clone case process, this process will allow you to complete copy all of the cases data to a new case. However, this will not copy the exact case and current task. This will allow you to start over with the same exact data, for example. If you were "stuck" on a loop or dead end task.

## [Export Report Table as CSV](https://github.com/donawick/ProcessMaker_Processes/blob/master/Export_Report_Table_or_PM_Table_as_CSV_File-2.pmx)
Self explanatory - this process will allow you to select a report table from ProcessMaker and export it as a CSV file instead of their default extension.

## [Set date in case](https://github.com/donawick/ProcessMaker_Processes/blob/master/Set_date_in_case-1.pmx)
This is only useful in certain situations, for example if a calendar script is being used and the task is submitted without a date scheduled. It will get stuck while waiting infinitely for that set date. An easy solution would be to just have a trigger set so that if (@@DateVariable == "") it will then route to the initial date creation task.
