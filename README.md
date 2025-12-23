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
