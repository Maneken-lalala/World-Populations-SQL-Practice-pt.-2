# World-Populations-SQL-Practice-pt.-2

In this project I am working with another world population dataset provided by Codecademy.com. The dataset contains info  world population by country and continent data from recent years.

The dataset contains two tables:

countries:

| Column  | Type  |   Notes   |
|---------|-------|-----------|
|   id    |Integer|Primary Key|
|   name  | Text  |           |
|continent| Text  |           |

population_years:
|  Column  | Type  |    Notes    |
|----------|-------|-------------|
|    id    |Integer| Primary Key |
|population| Number|(in millions)|
|   year   | Number|             |
|country_id|Integer| Foreign Key |
