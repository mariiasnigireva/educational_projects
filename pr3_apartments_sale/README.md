# Description of the project

## Study
Research of ads for the sale of apartments.

## Study tasks
The task is to determine the market value of real estate objects based on the basic parameters of the apartment.

## Data source
Archive of advertisements for the sale of apartments in St. Petersburg and neighboring settlements for several years from the Yandex.Real service.

## Data
The following data was available:

- **airports_nearest** - distance to the nearest airport in meters (m)
- **balcony** - number of balconies
- **ceiling_height** - ceiling height (m)
- **cityCenters_nearest** - distance to the city center (m)
- **days_exposition** - how many days the ad was posted (from publication before withdrawal)
- **first_day_exposition** - publication date
- **floor** - floor
- **floors_total** - total floors in the house
- **is_apartment** - apartments (boolean type)
- **kitchen_area** - kitchen area (m2)
- **last_price** - price at the time of unpublishing
- **living_area** - living area (m²)
- **locality_name** - name of the settlement
- **open_plan** - free layout (boolean type)
- **parks_around3000** - the number of parks within a radius of 3 km
- **parks_nearest** - distance to the nearest park (m)
- **ponds_around3000** - the number of reservoirs within a radius of 3 km
- **ponds_nearest** - distance to the nearest body of water (m)
- **rooms** - number of rooms
- **studio** - studio apartment (boolean type)
- **total_area** - the area of the apartment in square meters (m²)
- **total_images** - the number of apartment photos in the ad

## Study plan

- Exploring general information about the data
- Data processing:
    - define and fill in missing values
    - replace data types with correct ones if it is necessary
    - remove duplicates if it is necessary
- Count and add to the table:
    - price per square meter
    - day of the week, month and year of publication of the ad
    - apartment floor: options - first, last, other
    - the ratio of living space to total area
    - the ratio of kitchen area to total area
- Data analysis:
    - Study of parameters: area, price, number of rooms, height of ceilings (with histogram plotting).
    - Time of sale counting.
    - Identification of the factors that most strongly affect the cost of an apartment.
    - Average price per square meter calculation for 10 settlements with the largest number of ads. Selecting of the settlements with the highest and lowest cost of housing.
    - Price dependence on distance from the center calculation for St. Petersburg. Determination of the border of the central zone of the city.
    - Study of the factors that affect the cost of an apartment for St. Petersburg city center.
- Summarizing

## Libraries used in the project

- *pandas*
- *matplotlib.pyplot*
- *seaborn*

*All comments in the project are in Russian.