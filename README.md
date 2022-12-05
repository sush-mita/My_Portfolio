# [Project 1 : Web_Scraping Using Python](https://github.com/sush-mita/Web_Scraping)
### Objective : To  Scrape IMDB Website using Beautiful Soup Library.
- Scraped IMDB Website using Requests, Beautiful Soup and Pandas
- Extracted top 50 movies from each genre.
- Information like Movie Title,Rating,Year of release,certificate rating for each movie was scraped.
- Exported the extracted data of each Genere into a CSV file

![](/images/web.PNG)

# Project 2 : Data Extraction through API and Importing Data into AWS Cloud Database 
### This Project has two Parts : 
- Part 1 : Extracting Data from a Youtube API. 
- Part 2 : Uploadng the Data from the API to a Cloud Database.

## [Project 2a : Data_Extraction_API from Youtube API](https://github.com/sush-mita/Youtube_Data_Extraction_Through_API)
- I extracted Data from a Youtubel channnel using Requests,Pandas.
- I used Google Youtube Data API for this project.
- I Extracted basic Youtube Video ddata like Video Title, ID, Uploaded Date, No of Likes,views and comments for Each Video using Youtube Data API.
- I then appended all this into a dataframe. 

![](/images/you.PNG)

## [Project 2b : Cloud_Data_Storage_DF_to_DB](https://github.com/sush-mita/Cloud_Data_Storage_DF_to_DB)
- This Project is about how to store the data into a cloud database from the dataframe which is exracted from an API
- I am continuting with the Data_Extraction_API Project here and trying to upload the dataframe values into a database.
- I used AWS Console to get my Cloud Database Setup.
- I used Postgre Database and then tried writing SQL queries to achieve this task.
- I used psycopg2 adapter to connect to the postgre AWS Database.
- I then uploaded the values returing from the API into the database and have also written a function to update it whenever new videos or changes to the existing videos are made in the youtube channel.

### Project 2 Images : Database Updates 
##### The DataFrame Video Details

![](/images/df.PNG)

##### The Old Dataframe Video Details in the Database

![](/images/db.PNG)

##### The Temp Dataframe Storing New Video Details

![](/images/new_df.PNG)

##### The New Uploaded videos in the channel, which are reflecting in the Database as well.

![](/images/update_db.PNG)


