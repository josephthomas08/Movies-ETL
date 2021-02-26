# Movies-ETL
Extract ,transform and load
The Purpose of the project module was  for Extracting, transforming and loading data available through the Amazing Prime Hackathon.  This  projects intent was to   create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data. 

It then further performs the needed transformations and loads the data into an existing PostgreSQL database.
For the required  analysis, we have  used the below mentioned breakdown:

#### 1. COde  ETL function to read  provided three data files,
#### 2. Next in line was to extract and transform the Wikipedia data,
#### 3. extract and transform the Kaggle and rating data,
#### 4. Lastly load the data to a PostgreSQL Movie Database.


# Results

## A. Coded and wrote  an ETL function to read three data files as provided,
The ETL function draws out  the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and created  three separate DataFrames for further analysis.

## B. Extracted  and Transformed  the Wikipedia data provided 
As required we  filtered out the shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

## C. Extracted  and Transformed  the Kaggle and rating data
Lastly  we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle data, rating data were later merged with the Wikipedia movies DataFrame.


# Summary
The ETL function created was used to collect and clean movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It was further transformed and mergesd the data in order to load it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
