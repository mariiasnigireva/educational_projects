# Description of the project

## Study
Optimization of marketing costs Yandex.Afisha.

## Study tasks
To optimize the marketing costs of the Yandex.Afisha service, it's necessary to study how customers use the product, when they start buying, how much money each customer brings when the customer pays off.

## Data source
Yandex.Afisha data from June 2017 to the end of May 2018:
- server log with data on visits to the Yandex.Afisha website
- unloading of all orders for this period
- statistics of advertising costs

## Data
The following data was available:

The visits table (server log with information about site visits):

- **Uid** - unique identifier of the user
- **Device** - user device category
- **Start Ts** - date and time of the session start
- **End Ts** - date and time of the end of the session
- **Source Id** - the identifier of the advertising source from which the user came

Orders table (order information):

- **Uid** - unique id of the user who made the order
- **Buy Ts** - date and time of order
- **Revenue** - Yandex.Afisha's revenue from this order

Costs table (information about marketing costs):

- **source_id** - ad source identifier
- **dt** - date
- **costs** - the cost of this ad source on that day

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Data analysis to answer the following questions:
    1. **Product**
     - How many people use it per day, week, month?
     - How many sessions per day?
     - How long is one session?
     - How often do people come back?
    2. **Sales**
     - When do people start buying?
     - How many times are purchased per period?
     - What is the average check?
     - How much money do they bring in? (LTV)
    3. **Marketing**
     - How much money did you spend? Total / per source / by time
     - How much did it cost to attract one customer from each source?
     - How much has the cost paid off? (ROI)
- Summarizing

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*

*All comments in the project are in Russian.
