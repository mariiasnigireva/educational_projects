# Description of the project

## Study
Analysis of the behavior of users of the mobile application of a grocery store.

## Study tasks
The purpose of the study is to understand how mobile application users behave. It is necessary to study the sales funnel, find out how users arrive at a purchase. How many users reach the purchase, and how many are "stuck" at the previous steps and on which ones. Next, you need to examine the results of the A/A/B experiment before and after changing the font in the application and find out which font is better. First, it is necessary to compare the control groups.

## Data source
User orders history data.

## Data
The following data was available:

Logs_exp table: Each log entry is a user action or event.

- **EventName** - the name of the event;
- **DeviceIDHash** - unique user identifier;
- **EventTimestamp** - event time;
- **ExpId** is the experiment number: 246 and 247 are control groups, and 248 is experimental.

## Study plan

1. Step - Learning General Information
2. Step - data preparation
3. Step - study and validate data
4. Step - Exploring the Funnel of Events
5. Step - study the results of the experiment

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*
- *plotly.express*
- *plotly.graph_objects*
- *datetime*
- *scipy.stats*
- *math*
- *scipy*

*All comments in the project are in Russian.
