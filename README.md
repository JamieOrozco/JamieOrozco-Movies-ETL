# Movies_ETL

## Overview:

Amazing Prime loves the dataset and wants to keep it updated on a daily basis. They need help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. The code needs refactored to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database..

* Deliverable 1: Write an ETL Function to Read Three Data Files
* Deliverable 2: Extract and Transform the Wikipedia Data
* Deliverable 3: Extract and Transform the Kaggle data
* Deliverable 4: Create the Movie Database

## Results: 
#### Write ETL Function to Read Three Data Files:

<i<img width="362" alt="Wiki" src="https://user-images.githubusercontent.com/95591222/153272499-6e7914fe-c372-4eb8-84db-a82384346e72.png">
mg width="338" alt="3 Functions" src="https://user-images.githubusercontent.com/95591222/153271485-ab4692d4-c367-4387-9add-cbed5483705b.png">
<img width="314" alt="Kaggle" src="https://user-images.githubusercontent.com/95591222/153272506-979348a8-1ae4-4abe-b1dc-81413e9325db.png">
<img width="144" alt="rate" src="https://user-images.githubusercontent.com/95591222/153272512-6b15e2a0-6af7-4011-abe7-d787a4c3c1d7.png">

* An ETL function is written to read in the three data files. The JSON file, the matadata file, and the data file are all converted into a Pandas dataframe.

#### MentorExtract and Transform the Wikipedia and Kaggle Data:

* Used  Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data to merge it with the Kaggle metadata.

#### Create the Movie Database: 

<img width="526" alt="Movies-Query" src="https://user-images.githubusercontent.com/95591222/153271846-43d5509b-2b4c-43b1-8d65-7bc866db82b7.png">
<img width="476" alt="Ratings_Query" src="https://user-images.githubusercontent.com/95591222/153271858-9d7b1738-309d-4e97-a0ba-045810c30f36.png">

* There are 26,024,289 ratings and 6052 movies.


