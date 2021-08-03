# Description of the project

## Study
Adjustment of the advertising budget for a telecom company.

## Study tasks
The task is to make a preliminary analysis of tariffs for a small sample of 500 customers. It is necessary to analyze the behavior of customers and draw a conclusion - which tariff is more profitable, which means which tariff to spend most of the advertising budget.

## Data source
Data archive of the telecom company.

## Data
We have five tables at our disposal: users, calls, messages, internet and tariffs:

Users table (information about users):

- **user_id** - unique user identifier
- **first_name** - username
- **last_name** - user's last name
- **age** - the user's age (years)
- **reg_date** - tariff activation date (day, month, year)
- **churn_date** - date of termination of using the tariff
- **city** - the user's city of residence
- **tariff** - the name of the tariff plan

Calls table (information about calls):

- **id** - unique call number
- **call_date** - date of the call
- **duration** - call duration in minutes
- **user_id** - identifier of the user who made the call

Messages table (information about messages):

- **id** - unique message number
- **message_date** - date of the message
- **user_id** - the identifier of the user who sent the message

Internet table (information about internet sessions):

- **id** - unique session number
- **mb_used** - the amount of Internet traffic spent per session (in megabytes)
- **session_date** - date of the internet session
- **user_id** - user ID

Tariffs table:

- **tariff_name** - tariff name
- **rub_monthly_fee** - monthly subscription fee in rubles
- **minutes_included** - the number of minutes of conversation per month included in the subscription fee
- **messages_included** - number of messages per month included in the subscription fee
- **mb_per_month_included** - the amount of Internet traffic included in the monthly fee (in megabytes)
- **rub_per_minute** - the cost of a minute of conversation in excess of the tariff package
- **rub_per_message** - the cost of sending a message in excess of the tariff package
- **rub_per_gb** - the cost of an additional gigabyte of Internet traffic in excess of the tariff package

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Data analysis:
    - a description of the behavior of the operator's clients based on the sample
- Hypothesis testing:
    - the average revenue of users of the two tariffs differs / does not differ
    - the average revenue of users from Moscow differs / does not differ from the revenue of users from other regions
- Summarizing

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*
- *scipy.stats*

*All comments in the project are in Russian.