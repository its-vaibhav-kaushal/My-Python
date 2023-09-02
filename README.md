# My-Python
#PROJECT-1: SOME BASIC PROGRAMS 
# Create a python program capable of greeting you with Good Morning, Good Afternoon and Good Evening.
# Your program should use time module to get the current hour.

import time
timestamp = time.strftime("%H h : %M m : %S s")
print(f"Time is {timestamp}")
hour = int(time.strftime("%H"))

if (00 <= hour < 12):
    print(f"Hey GOOD MORNING !,Its {timestamp} .")
elif (12 <= hour < 17):
    print(f"Hey GOOD AFTERNOON !,Its {timestamp} .")
elif (17 <= hour < 19):
    print(f"HEY GOOD EVENING !, Its {timestamp}.")
else:
    print(f"HEY GOOD NIGHT !, Its {timestamp}.")
