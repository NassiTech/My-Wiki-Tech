# datetime library

**Links** :
 link : https://stackoverflow.com/questions/36341484/get-day-name-from-weekday-int
 https://stackoverflow.com/questions/8380389/get-day-name-from-datetime
https://stackoverflow.com/questions/8380389/get-day-name-from-datetime
https://stackoverflow.com/questions/74853453/days-till-year-end


 in order to use the datetime function, it is necessary to import it first. -> command "import datetime" module 
 The datetime module has arrays : datetime, date, day, now, deltatime,hours, years......
  We only need the datetime class and the timedelta class from the
datetime module since we don't need access to other
 parts of the datetime module like datetime.date or
datetime.time. Like this we don't need to qualify the
 datetime class with the module name, e.g. for the statement
 'today = datetime.now()'

import datetime
from datetime import datetime, timedelta

 days_to_keydate is a function that calculates the number of days from today to an user entered date
 the input parameter (selected_day).
 The function gives a return parameter Difference today - selected_day
 the user is asked to enter a date through input()


 the number of days without extra hours could be obtained in 3 different ways
 .days in the function definition that we want to run
 .days could be in the argument difference in line  118
 line 123 in the print after the argument days_to_keyday


 day_of_the_week() is a function that compares the user entered date with calendar function
 the input parameter entered-day is transformed from a string to a datetime format with strptime
 the asked day is transformed from the datetime format again to string format strftime -> %A weekday
 the return value is a week day as a string type data

