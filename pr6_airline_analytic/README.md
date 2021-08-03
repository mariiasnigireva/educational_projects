# Description of the project

## Study
Adjustment of the advertising budget for an online computer games store.

## Study tasks
Our task is to identify the regularities that determine the success of the game. This will allow you to bet on a potentially popular product and plan an advertising campaign for 2017 for an online computer games store.

## Data source
Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources.

## Data
The following data was available:

- **Name** - the name of the game
- **Platform** - platform's name
- **Year_of_Release** - release year
- **Genre** - game genre
- **NA_sales** - North American sales (millions of dollars)
- **EU_sales** - Sales in Europe (millions of dollars)
- **JP_sales** - Sales in Japan (millions of dollars)
- **Other_sales** - sales in other countries (millions of dollars)
- **Critic_Score** - Critic score (maximum 100)
- **User_Score** - user score (maximum 10)

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Data analysis:
    - calculation of total sales in all regions
    - determination of the current time period
    - assessment of the typical lifespan of platforms
    - selection of potentially profitable platforms
    - study of the impact of reviews on sales within one popular platform
    - highlighting genres with high and low sales
- Modeling of a user portrait in each region:
    - identification of the most popular platforms (top 5)
    - identification of the most popular genres (top-5)
    - determining the degree of influence of the ESRB rating on sales in a particular region
- Hypothesis testing:
    - the average user ratings for Xbox One and PC platforms are the same
    - the average user ratings of Action and Sports genres are different
- Summarizing

## Libraries used in the project

- *pandas*
- *numpy*
- *seaborn*
- *matplotlib.pyplot*
- *scipy*
- *scipy.stats*

*All comments in the project are in Russian.