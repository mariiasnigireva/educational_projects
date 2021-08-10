# Description of the project

## Study
Customer segmentation by consumption profile.

## Study tasks
The purpose of the study is to segment buyers by their consumption profile in order to build a recommendation system based on their previous buying activity in the future:

- to form typical portraits of users: to highlight several of the most typical consumer baskets;
- to analyze the basic properties of users (average income from one user, how often they make purchases, is there any seasonality, etc.);
- to formulate and test the main hypotheses:
    - the store's revenue from users from different segments is the same;
    - the average revenue from one user from each segment is the same.

## Data source
Сustomer's databank.

## Data
The following data was available:
User data for the month preceding the check of the outflow fact:

- **gender** - gender
- **Near_Location** - living or working in the area where the fitness center is located
- **Partner** - an employee of the club's partner company (cooperation with companies whose employees can receive discounts on a subscription - in this case, the fitness center stores information about the client's employer)
- **Promo_friends** - the fact of the initial registration as part of the "bring a friend" campaign (used a promo code from a friend when paying for the first subscription)
- **Phone** - availability of a contact phone number
- **Age** - age
- **Lifetime** - time since the first visit to the fitness center (in months)

Information based on the history of visits, purchases and information about the current status of the client's subscription:

- **Contract_period** - duration of the current valid subscription (month, 3 months, 6 months, year)
- **Month_to_end_contract** - period until the end of the current valid subscription (in months)
- **Group_visits** - the fact of attending group classes
- **Avg_class_frequency_total** - the average frequency of visits per week for the entire time since the beginning of the subscription
- **Avg_class_frequency_current_month** - average frequency of visits per week for the previous month
- **Avg_additional_charges_total** - total revenue from other services of the fitness center: cafes, sports goods, beauty and massage parlor

## Study plan

1. Step - Learning general information
2. Step - Exploratory Analysis:
    - to bring the data to the required types, find and fill in the gaps if necessary;
    - to build a chart showing the amount of purchases by day;
    - to build a histogram showing the distribution of orders by amount.
3. Step - segmentation of buyers by consumption profile:
    - to build a model for the classification of buyers (approximate breakdown: summer residents, flower growers, etc.);
    - to split data by customer classes;
4. Step - testing statistical hypotheses:
    - the store's revenue from users from different segments is the same;
    - the average revenue from one user from each segment is the same. 
    
## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib*
- *plotly*
- *sklearn*
- *math*
- *datetime*
- *scipy*

*All comments in the project are in Russian.
