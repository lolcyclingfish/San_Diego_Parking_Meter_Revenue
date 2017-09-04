# San_Diego_Parking_Meter_Revenue_Prediction

## Objective:
- Turn payment transaction data from smart parking meters into occupancy and payment behavioral
information for on-street parking. Predict daily parking revenue for the City of San Diego.

## Agenda:
- 1) Generate a file that includes: poleid, sub-area, year, month, day, time (being the 5 minute interval like
08:05:00, 08:10:00, 08:15:00), the % of time during that interval that was paid for, count of transactions
that started in that interval, count of transactions that expired during that interval)
- 2) create a column named "Paid Occupied Percentage" - this will be the % of the time interval that we
know someone has paid for based on the transaction start time and expire time
- 3) develop predictive model to predict the daily parking meter revenue for the whole City of San Diego
- 4) Create a separate tab that shows your daily revenue predictions in comparison to actuals
