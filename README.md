# Movies-ETL

## Overview of Project
The biggest online merchant,on the globe, Amazing Prime, also has a streaming platform. This streaming platform is called Amaizing Prime Video. The company wants an algorithm created that will predict which low-budget flicks will be gain wide-stream popularity so they camn grab he streaming rights at a low cost. They decided to have a hackaton to not only inspire their team, but to build on connections with the local coding community. Britta an Amazing Prime Video employee has been asked to create datasets for the hackathon. One of the datasets is a data scraped from the Wikipedia website, the other is data pulled from Movie Land's website on rating data. Britta will complete the Extract, Transform and Load (ETL) process on this data by extracting from the Wikipedia and Movie Lens websites, making it one table (transforming it), and turning it into an SQL table (loading it). Amazing Prime Video loved the new data set that Britta created and wants it updated daily. You and Britta will be using the ETL process on the SQL table Britta created so that it updates daily. It will now include data from Wikipedia, Kaggle and Movie Lens.

### Purpose
Create a database for a hackathon that will update daily. The idea is that the hackathon will encourage the team, but create networks with the local IT community. 

## Analysis

### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

## Challenges and Difficulties Encountered
This was the most difficult module for me to date. I could not share my csv files on my github as they were too large so I took a screenshot of the select * statement results for both the ratings table and the movies table in pgAdmin and saved them in the Resources table. I also ran into an issue when trying to use the 'Hint' provided in section of the challenge. When I changed the code from section three from to 'replace' as the hint suggests, the wrong number of rows returned. The way I was able to obtain the correct number of rows in my GitHub was to delete both existing tables (movies and ratings) from pgAdmin and then run my code. I have inclued a screenshot of the hint below. 

#### Screenshots

##### pgAdmin Movie Table Screenshot

![Movie Results.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Resources/Movie%20Results.png)

##### pgAdmin Ratings Screenshot

![Ratings Results.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Resources/Ratings%20Results.png)

##### Hint Screenshot
![Hint.png](https://github.com/AprilVilmin/Movies-ETL/blob/main/Hint.png)

