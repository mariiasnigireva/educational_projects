# Description of the project

## Study
Identifying the preferences of users who buy tickets to certain destinations.

## Study tasks
Our task is to understand the preferences of users of the airline operating domestic passenger air travel.
That meens to analyze the passenger demand for flights to cities where the largest festivals are held.

## Data source
Airline's archive data and open source data.

## Data
The following data was available:

The airports table - information about airports:

- **airport_code** - three-letter airport code
- **airport_name** - airport name
- **city** - city
- **timezone** - time zone

Aircrafts table - aircraft information:

- **aircraft_code** - aircraft model code
- **model** - aircraft model
- **range** - number of aircraft

Tickets table - information about tickets:

- **ticket_no** - unique ticket number
- **passenger_id** - personal identifier of the passenger
- **passenger_name** - passenger's first and last name

Flights table - flight information:

- **flight_id** - unique flight identifier
- **departure_airport** - departure airport
- **departure_time** - date and time of departure
- **arrival_airport** - arrival airport
- **arrival_time** - date and time of arrival
- **aircraft_code** - aircraft id

Table ticket_flights - flight-to-ticket splice table:

- **ticket_no** - ticket number
-**flight_id** - flight identifier

Festivals table - information about festivals:

- **festival_id** - unique number of the festival
- **festival_date** - the date of the festival
- **festival_city** - the city of the festival
- **festival_name** - the name of the festival

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Data analysis:
    - choose the top 10 cities by the number of flights
    - determination of the current time period
    - plot aircraft models and the number of flights (Column Chart)
    - plot city and the number of flights (Line Chart)
    - plot a diagram the top 10 cities and the number of flights (Column Chart)
- Summarizing

## Libraries used in the project

- *pandas*
- *seaborn*
- *matplotlib.pyplot*

*All comments in the project are in Russian.