# Electricity Costs at a Data Center

## Project Brief 

You are working at a data center. One of the biggest costs for the center is the electricity required to run all of the servers. To ensure that they will continue to charge customers appropriately for their services, it’s important for them to be able to estimate the price they will have to pay for running the center - in particular the electricity price. As well as knowing whether it is possible to get a reasonable estimate of the price, they would like to know if there are factors that cause the price to increase, so they can charge customers more for those situations.

## Data

Dataset containing the price of electricity for a data center in addition to factors that might affect the price.


- DateTime: String, defines date and time of sample
- Holiday: String, gives name of holiday if day is a bank holiday
- HolidayFlag: integer, 1 if day is a bank holiday, zero otherwise
- DayOfWeek: integer (0-6), 0 monday, day of week
- WeekOfYear: integer, running week within year of this date
- Day integer: day of the date
- Month integer: month of the date
- Year integer: year of the date
- PeriodOfDay integer: denotes half hour period of day (0-47)
- ORKTemperature: the actual temperature measured at Cork airport
- ORKWindspeed: the actual windspeed measured at Cork airport
- CO2Intensity: the actual CO2 intensity in (g/kWh) for the electricity produced
- ActualWindProduction: the actual wind energy production for this period
- SystemLoadEP2: the actual national system load for this period
- SMPEP2: the actual price of this time period, the value to be forecasted
