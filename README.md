# HypDev-Cap4

This application helps a business to manage tasks assigned to each employee.
The application is written using Python.

The following functions can be performed:
* register a user
* add a task
* view all tasks
* view my tasks
* generate reports
* display statistics
* exit

The user can edit its own tasks and mark them as completed.
The program offers access control by requiring valid users to log in.

Please note that the following functionality has been coded into
the program. Whenever there is user input required, the following
scenarios are applicable:
* If the user enters nothing or a string where a number is required: The error is caught and the user is requested to enter correct data. This is accomplished either by a loop or try / except.
* The user can enter -1 at any time to return to the main menu except at login and when already at the main menu.

Using files, reports can be generated.