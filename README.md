# Project: Data Analysis Using MongoDB and Python
## nosql-challenge
## Overview
This project demonstrates the process of performing data analysis using MongoDB and Python. It involves importing and managing data, conducting exploratory analysis, and executing advanced queries to extract meaningful insights from a dataset. Below is a summary of the tasks accomplished in this project.

## Task 1: Data Import and Database Setup
#### Data Import: The project begins by importing data from an external source, specifically the establishments.json file. This data is stored in a MongoDB database named uk_food within a collection called establishments.
## Task 2: Data Manipulation and Updates
#### Data Management: The project showcases data management skills by adding a new restaurant, "Penang Flavours," to the database.

#### Data Transformation: BusinessTypeID for "Restaurant/Cafe/Canteen" is identified and appropriately assigned to the new restaurant.

#### Data Cleansing: Establishments within the "Dover" Local Authority are removed from the database.

#### Data Type Conversion: Data type conversions are performed, such as converting latitude and longitude from strings to decimals, and converting RatingValue from strings to integers.

## Task 3: Exploratory Analysis
#### Data Exploration: The dataset is explored through Python and MongoDB queries, facilitating the identification of establishments with specific criteria, such as hygiene scores of 20 and high-rated establishments in London.
## Task 4: Advanced Query and Analysis
#### Querying: Queries are executed to find the top 5 establishments with a RatingValue rating of 5, sorted by the lowest hygiene score, and to count establishments in each Local Authority area with a hygiene score of 0.
## Task 5: Data Presentation
#### Data Presentation: Query results are transformed into Pandas DataFrames for effective presentation and further analysis.
#### Data Reporting: The number of rows in the DataFrames is reported, along with the display of the first 10 rows for quick data inspection.

##### References
###### UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
###### Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
###### All codes used are from week 12 classes and troubleshooting was done with ChatGPT 
