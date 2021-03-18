# Numpy

numpy index 负的也行

===================

https://datatofish.com/get-previous-current-and-next-day-system-dates-in-python/

```
import datetime
 
Current_Date_Formatted = datetime.datetime.today().strftime ('%d%m%Y') # format the date to ddmmyyyy
print ('Current Date: ' + str(Current_Date_Formatted))
 
Previous_Date = datetime.datetime.today() - datetime.timedelta(days=1)
Previous_Date_Formatted = Previous_Date.strftime ('%d%m%Y') # format the date to ddmmyyyy
print ('Previous Date: ' + str(Previous_Date_Formatted))
 
NextDay_Date = datetime.datetime.today() + datetime.timedelta(days=1)
NextDay_Date_Formatted = NextDay_Date.strftime ('%d%m%Y') # format the date to ddmmyyyy
print ('Next Date: ' + str(NextDay_Date_Formatted))
```

======================================

