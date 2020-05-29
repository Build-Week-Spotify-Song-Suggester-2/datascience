# Data Science - Spotify Track Recommender

## App :headphones: 
[https://bw-spotify.herokuapp.com/](https://bw-spotify.herokuapp.com/)

## Workflow
![Alt text](https://raw.githubusercontent.com/Build-Week-Spotify-Song-Suggester-2/datascience/master/DS%20Flowchart.jpg)

## Project Information 
A Kaggle database of songs or access to the Spotify API directly. We will be accessing the Spotify API directly to pull certain information on audio tracks, and a dataset of 120k unique songs to train our model.

We were assigned to deploy a personalized song reccomendation app by creating algorithm to recommend songs based on user's input song. We created a new dataset of 120k unique song tracks to train our model with, by combining a dataset of tracks from Kaggle and updating it with additional tracks from the Spotify API directly. 

Our app takes the provided user input, and generates a GET request that matches the track to it’s unique ID in the Spotify API, and then applies our model to return a json list of top 10 most similar songs back to the user. Song similarity was determined by model analysis of each track's audio feature, including danceability, acousticness, instrumentalness vs speechiness, loudness, energy, and valence. We created both a k-nearest neighbors model and a neural network. However, we chose the to only deploy the KNN model to our app as it was more lightweight and accurate given the time constraint of one fewer workday. 

## Visual Respresentation of Track Audio Data :notes:

(add image of radar chart?)


## API Endpoints


## Libraries Used


## Team Github Links :musical_note:
[Front-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/front-end)

[Web-UI](https://github.com/Build-Week-Spotify-Song-Suggester-2/Web-UI-Marketing)

[Back-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/back-end)
