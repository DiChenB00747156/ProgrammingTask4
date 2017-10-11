# Programming Task 

Welcome to your first programming task 
  - You have to clone this repo to your account, you should be seeing this on your account, if someone elses name is listed call an instructor for help.
  - Use the Ubuntu VM to write the progrm.
  - Use git add, commit and push to send the code back. 
  - Don't forget to add user name and email on git. 
  - You are allowed to use any form of searching and documentation reading and book reading is promoted
  - You cannot talk to your other people or ask for help!

# Python Weather API 

Look at the weathe API from https://github.com/stevob21/weather-api and read the documentation there. You will be asked to get the weather for the next 5 days in a given city.

### Installing 

Use PIP3 and install the python3-weather-api
```
pip install python3-weather-api
```

### Objectives

1. Get a city from the user and return the current weather "Text" and the current temperature

Based on the next 5 days of forecast find the following: 

1.The day that has the highest temperature in the next 5 days of forecast

2.The day that has the lowest temperature in the next 5 days of forecast

3.If it will rain the next 5 days inform the user and tell him which day it will rain




### Development

Look at the following code and see what you can do
```py
# Lookup via location name.
location = weather.lookup_by_location('halifax')
condition = location.condition()
print condition['text']

# Get weather forecasts for the upcoming days.
for forecasts in location.forecast():
    print (forecasts['text'])
    print (forecasts['date'])
    print (forecasts['high'])
    print (forecasts['low'])
```

Now you just have to modifiy the data and report it to the user!


License
----

MIT


**Final Time for submission is 1PM**


