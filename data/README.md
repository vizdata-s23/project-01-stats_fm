# Data

## Provenance

[Link to TidyTuesday repository](https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-11-08)

[Link to Wikpedia](https://en.wikipedia.org/wiki/Lists_of_radio_stations_in_the_United_States)

In addition to this data, we used 2020 Census data to get the population of each state. While this dataset has 45 variables thus offering extensive information, we were only interested in the estimated 2022 population of each state. Because of this, our codebook will only describe the variables used.

[Link to census data](https://www2.census.gov/programs-surveys/popest/datasets/2020-2022/state/totals/)

## Codebook

### `state_stations.csv`

|variable  |class     |description  |
|:---------|:---------|:------------|
|call_sign |character | Call Sign   |
|frequency |character |frequency    |
|city      |character |city         |
|licensee  |character |licensee     |
|format    |character | format      |
|state     |character | state       |

### `population_data_2022.csv`

|variable        |class     |description                |
|:---------------|:---------|:--------------------------|
|NAME            |character | name of state             |
|POPESTIMATE2022 |double    | 2022 estimated population |





