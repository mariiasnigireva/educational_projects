# Description of the project

## Study
A/B test analysis for a large online store.

## Study tasks
The task is to choose the most promising hypotheses from a number of hypotheses, i.e. prioritize hypotheses. After conducting and receiving the results of the A/B test, draw conclusions about the success of the A/B test and make a decision on the extension, or the successful/unsuccessful completion of the test.

## Data source
Archived data of the marketing department of the client.

## Data
The following data was available:

Hypothesis table (9 hypotheses for increasing online store revenue):

- **Hypothesis** - a short description of the hypothesis;
- **Reach** - user reach on a 10-point scale;
- **Impact** - impact on users on a 10-point scale;
- **Confidence** - confidence in the hypothesis on a 10-point scale;
- **Efforts** - resource costs for hypothesis testing on a 10-point scale. The higher the Efforts value, the more expensive it is to test the hypothesis.

Orders table (information about orders, obtained as a result of A / B-test):

- **transactionId** - order identifier;
- **visitorId** - identifier of the user who made the order;
- **date** - the date when the order was made;
- **revenue** - order revenue;
- **group** - the group of the A / B test that the order fell into.

Visitors table (information about the costs of visitors, obtained as a result of an A / B test):

- **date** - date;
- **group** - A / B test group;
- **visitors** - the number of users on the specified date in the specified A / B test group

## Study plan

- 1. Part - prioritization of hypotheses:
    - Apply ICE framework for hypothesis prioritization. Sort them in descending order of priority.
    - Apply a RICE framework to prioritize hypotheses. Sort them in descending order of priority.
    - Draw conclusions about how the prioritization of hypotheses has changed when using RICE instead of ICE.
- 2. Part - analysis of the results of the A/B test:
    - Exploring general information about the data
    - Plot the cumulative revenue by group. Draw conclusions and assumptions.
    - Plot the cumulative average bill by group. Draw conclusions and assumptions.
    - Plot the relative change in the cumulative average check of group B to group A. Make conclusions and assumptions.
    - Plot the cumulative conversion by group. Draw conclusions and assumptions.
    - Plot the relative change in the cumulative conversion of group B to group A. Draw conclusions and assumptions.
    - Scatter plot of the number of orders by users. Draw conclusions and assumptions.
    - Calculate the 95th and 99th percentiles of the number of orders per user. Select a border to identify abnormal users.
    - Build a scatter plot of order values. Draw conclusions and assumptions.
    - Calculate the 95th and 99th percentiles of the order value. Select a border to identify abnormal orders.
    - Calculate the statistical significance of differences in conversion between groups based on raw data. Draw conclusions and assumptions.
    - Calculate the statistical significance of the differences in the average order receipt between groups according to the "raw" data. Draw conclusions and assumptions.
    - Calculate the statistical significance of differences in conversion between groups based on "cleaned" data. Draw conclusions and assumptions.
    - Calculate the statistical significance of the differences in the average order receipt between groups according to the "cleaned" data. Draw conclusions and assumptions.
- 3. Summarizing

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*
- *datetime*
- *scipy.stats*

*All comments in the project are in Russian.
