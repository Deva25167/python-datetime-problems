# python-datetime-problems
from datetime import datetime

now = datetime.now()
print(now)


# Get only Current date

from datetime import date

today = date.today()
print(today)

# Get only current time

from datetime import datetime
current_time = datetime.now().time()
print(current_time)

# check wheather the office is open or closed

from datetime import datetime

hour = datetime.now().hour

if 9 <= hour < 17:
    print("Office Open")
else:
    print("Office Closed")

# Get day name

from datetime import datetime

today = datetime.now()
print(today.strftime("%A"))

