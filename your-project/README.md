<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# AC/BC (After Colau/Before Colau)
Raul Castrillo & Pol Serramalera

Data Analytics full time 30/oct/2020

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
Our project seeks to analyze the impact of the latest government change (Ada Colau's) by comparing the data of the 2 years prior to the goverment change and the 2 years after.

## Questions & Hypotheses
Our hypoteses is that the inmigration and aging index increased after colau's government, the average birth rate dropped and also we think that the family income distribution has balanced between the poorest and the wealthiest districts.
·Did the inmigration increase After Colau's government compared to the period Before?
·Has the aging index increased After Colau's government compared to the period Before ?
·Did the average birth drop After Colau's government compared to the period Before?
·Have the districts become more balanced in terms of family income After colau compared to the period Before?


## Dataset
Provided by ironhack:

·births.csv
·deaths.csv
·immigrants-by-nationality.csv
·immigrants-emigrants-by-age.csv
·immigrants-emigrants-by-destination.csv
·immigrants-emigrants-by-sex.csv
·Population of Barcelona

From the bcn.cat

·Disposable family income (https://www.bcn.cat/estadistica/catala/dades/anuari/cap14/C1401030.htm)


## Database
We created new tables from the gathered datasets to calculate rates for each district for each year and then we created a final table with 10 rows ( 1 for each district) with all the gathered rates Before Colau and After Colau

#Include a drawing or computer-generated image of the ERD (Entity Relationship Diagram) of your database.

## Workflow

1. First we have cleaned the official datasets with the information that mattered to us and took years 2013-2017 as a sample
2.  Creating  sub data frames to study the data  by year and district  out of the main database
3. Adding new columns with statistics and operations  to the new data frames
4. Merging immigration and population demography dataframes to a final table


## Organization

To organize our work we created a kanbas board in trello.com, and we divided the tasks between us 2.

Our repository has 2 initial folders, one for the datasets and another for the project files, the project files include a Readme.md file and in a separate folder
named 'code' we have all the python3 coding files.

## Links

[Repository](https://github.com/polserramalera/Project-Week-2-Barcelona)  
[Slides](https://docs.google.com/presentation/d/1_dXjmLu-4XQp2hb52MGz8fbdAeuj1RgDd-ifIM9lZpA/edit#slide=id.gc6fa3c898_0_0)  
[Trello](https://trello.com/b/cugCk511/project2-2-year-balance-on-a-new-government)  
