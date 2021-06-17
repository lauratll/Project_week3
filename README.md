# Project_week3<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*[Laura]*

*[Remote DA Bootcamp, IRONHACK May 2021]*

## Content
- [Project Description](#project-description)
- [Organization](#organization)
- [Links](#links)


## Project Description
This projects consists on creating a music recomendator. For that two data bases will be created. 

One of 100 Hot song from the most cpopular song this week. Tgis information will be scrapp from the website [100 Hot Songs](https://www.billboard.com/charts/hot-100). 

A second one, with approximately 10.000 songs, that will be obtained parsing the API of Spotify. 

For each song in both DB, we will obtain the audio features. According to the audio features, we will create categories of songs, clustering with k-mean ML method.

Once the user inputs a song, we will be able to predict to which category it belongs. We will recommend a song from the same group, from our 100 Hot Songs (if the song enter by the user is also in this DB). When the song does not belong to the 100 Hot Songs, we wil recommend the song from the Spoty DB.


## Organization

This projects was organize by blocks, working by daily challenges. Every day was one step further of the process for building the song recommendation.

Repositoty Structure:

In the data folder we find the following:

- spotify_db.csv (database of Spotify songs with categories included)
- scaler.pickle
- playlists.txt (a text with all the playlists used for creating the database)
- kmeans.pickle
- hotsongs_db.csv (databe of the 100 Hot songs with categories included)
- audio_features_for_cluster.csv
- audio_features_for_cluster_labeled.csv

In the project folder you can find three jupyter notebooks:

- CREATE 100 HOTSONGS AND SPOTY DB.ipynb (where the Databases are created)
- Scaling and training K-mean.ipynb (where the model k means is trainned)
- User_Interaction.ipynb (The Song recommender code)

## Links


[Repository](https://github.com/)  
[Slides](https://slides.com/lauratrapero/deck)  
[Trello](https://trello.com/b/1NOHOYPv/project-week-3)  

[100 Hot Songs](https://www.billboard.com/charts/hot-100)
