# Description of the project

## Study
Moscow public catering market Analysis.

## Study tasks
The objective of the study is to prepare a report for investors on the current state of the Moscow public catering market. You need to check if there is a niche for a small cafe in which guests should be served by robots. As a result of the study, it is necessary to make recommendations about the type of institution, the number of seats, as well as the location, comment on the possibility of developing the network.

## Data source
Open data on catering establishments in Moscow.

## Data
The following data was available:

Rest_data table:

- **object_name** - the name of the catering facility;
- **chain** - chain restaurant;
- **object_type** - type of catering object;
- **address** - address;
- **number** - the number of seats.

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Data analysis to answer the following questions:
    - Investigate and plot the ratio of types of public catering facilities in terms of quantity.
    - Investigate and plot the ratio of network and non-network establishments in terms of number.
    - Investigate what type of catering facility is characterized by network distribution.
    - Track what is typical for chain establishments: many establishments with a small number of seats in each or few establishments with a large number of seats.
    - For each type of catering facility, describe the average number of seats. Find out which species has the most seats on average and plot it.
    - Plot the top 10 streets by the number of catering facilities. Use external information to answer the question - in which districts of Moscow these streets are located.
    - Find the number of streets with one catering facility. Use external information to answer the question - in which districts of Moscow these streets are located.
    - Look at the distribution of the number of seats for streets with a large number of catering facilities. Identify patterns.
- Summarizing
- Presentation

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*
- *plotly.express*
- *plotly.graph_objects*
- *datetime*
- *stats*

*All comments in the project are in Russian.
