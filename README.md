# ProcessMaker_Processes
A set of support processes made in ProcessMaker to add additional functionality

# Bulk Case Management
ProcessMaker does not currently have a way to "mass" delete cases and I'm sure they wouldn't recommend modifiyng the database. This process will allow you to have a mass-cancelation of cases under a specific user.

# Clone Case
This process will allow you to clone a specific case (giving it a new case #) as they do not currently have a way of doing something like this for testing purposes.

# Copy Case Data
Similar to the clone case process, this process will allow you to complete copy all of the cases data to a new case. However, this will not copy the exact case and current task. This will allow you to start over with the same exact data, for example. If you were "stuck" on a loop or dead end task.

# Export Report Table as CSV
Self explanatory - this process will allow you to select a report table from ProcessMaker and export it as a CSV file instead of their default extension.

# Set date in case
This is only useful in certain situations, for example if a calendar script is being used and the task is submitted without a date scheduled. It will get stuck while waiting infinitely for that set date. An easy solution would be to just have a trigger set so that if (@@DateVariable == "") it will then route to the initial date creation task.
