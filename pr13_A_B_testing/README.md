# Description of the project

## Study
Analysis of the customer behavior in a network of fitness centers, creating an action plan for customer retention.

## Study tasks
- to predict the likelihood of a churn (at the next month's level) for each client;
- to form typical portraits of users: to highlight several of the most striking groups and to characterize their main properties;
- to analyze the main signs that most strongly affect the outflow;
- to formulate the main conclusions and develop recommendations for improving the quality of work with clients:
    - highlight target groups of clients;
    - propose measures to reduce churn;
    - identify other features of interaction with customers.

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
    - to find out if there are missing features in the dataset;
    - to calculate and analyze the average values of features in two groups - those who left for the outflow and those who remained;
    - to build columnar histograms and feature distributions for those who left (outflow) and those who stayed (did not get into the outflow);
    - to build a correlation matrix.
    
3. Step - building a user churn forecasting model:
    - to build a binary classification model for users, where the target feature is the fact of user churn in the next month;
    - to split the data into training and validation sets;
    - to train the model on a train sample in two ways: logistic regression and random forest;
    - to evaluate the accuracy, precision and recall metrics for both models on the validation set. Compare the models on them.

4. Step - user clustering:
    - to standardize data;
    - to construct a matrix of distances on a standardized matrix of features;
    - to draw a dendrogram;
    - based on the resulting graph, to suggest how many clusters can be identified;
    - to train a clustering model based on the K-Means algorithm and predict customer clusters;
    - to study the average values of the features for the clusters and, if possible, draw conclusions;
    - to build feature distributions for clusters;
    - to calculate the churn share for each obtained cluster. Analyze which clusters are prone to outflow and which are reliable.

5. General conclusions and basic recommendations for working with clients. 

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib*
- *plotly*
- *sklearn*
- *math*
- *scipy*

*All comments in the project are in Russian.
