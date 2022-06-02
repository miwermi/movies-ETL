                                                                                           Michelle Werner (6/1/2022)
# ETL: Extract Transform and Load
---

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/movies-ETL/blob/main/resources/extract-transform-load.png" align="right" width="640" height="278" alt="graphic: ETL: Extract, Transform, Load">

<br />
Creating consistent, robust data storage systems with data relationships that maintain data integrity and efficient querying performance is what the ETL process strives for. In this project, data was extracted from two different web sources, then supplied for cleaning, to be loaded into a new database. The cleaning process was intense.

<br />
(Pictured: "ETL: Extract Transform and Load")

## About the project:

Amazing Prime Video is the world's largest online retailer.  They also have a platform that streams movies and tv shows.  They have sponsored a hackathon to see if data nerds can figure out a way to loop through video data and identify low-budget films that will have demand - so they can purchase the streaming rights on the cheap. 

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/movies-ETL/blob/main/resources/APV-ETL-hackathon.png" align="right" width="500" height="293" alt ="graphic: hackathon">

Data sources supplied include:  

 - Wikipedia info all movies released since 1990 (in JSON format)
 - MovieLens rating data from Kaggle (in a GIANT csv)


MovieLens is a website run by the GroupLens research group at the University of Minnesota. The Kaggle dataset pulls from the MovieLens dataset of over 20 million reviews and contains a metadata file with details about the movies from The Movie Database (TMDb).  The first task was to inspect both the movies_metadata.csv and ratings.csv files.
<!--![alt](resources/___.png)-->

<br />
(Pictured: Module 8 Hackathon Graphic)

