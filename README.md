# calendar-pythonn
I have created to get any month and year calendar.
#python program to print a calendar
#of the specified month and year
import calendar
year = int( input("Enter year: "))
month = int(input("Enter Month: "))
print("\n" , calendar.month(year,month))
