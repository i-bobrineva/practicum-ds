# Research of the scooter rental service data
## Task
Analyzing the data from the scooter rental service about users from several cities, as well as their trips, and then testing hypotheses that may help the business grow.

To make trips around the city, users of the service use a mobile application. The service can be used:
* without a subscription: no subscription fee; the cost of one minute of the trip is 8 units; the cost of starting (beginning the trip) is 50 units;
* with an Ultra subscription: the subscription fee is 199 units per month; the cost of one minute of the trip is 6 units; the cost of starting is free.

## Data description
Users:
* user_id - unique identifier of the user
* name - user's name
* age - age
* city - city
* subscription_type - subscription type (free, ultra)

Rides:
* user_id - unique identifier of the user
* distance - distance traveled by the user in the current session (in meters)
* duration session duration (in minutes) — the time from when the user pressed the "Start Trip" button to when they pressed the "End Trip" button
* date - date of the trip

Subscriptions:
* subscription_type - subscription type
* minute_price - cost of one minute of the trip for this subscription
* start_ride_price - cost of starting the trip
* subscription_fee - cost of the monthly fee

## Libraries

* pandas
* matplotlib
* numpy
* scipy
* math
