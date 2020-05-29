# Data Science - Spotify Track Recommender

## App :headphones: 
[https://bw-spotify.herokuapp.com/](https://bw-spotify.herokuapp.com/)

## Workflow
![Alt text](https://raw.githubusercontent.com/Build-Week-Spotify-Song-Suggester-2/datascience/master/DS%20Flowchart.jpg)

## Project Information 
We were assigned to deploy a personalized song reccomendation app by creating an algorithm to recommend songs based on a user's inputted song. We created a new dataset of 120k unique song tracks to train our model with by combining a dataset of tracks from [Kaggle](https://www.kaggle.com/tomigelo/spotify-audio-features) and updating it with additional tracks from the [Spotify API]( https://api.spotify.com) directly. 

Our app takes the provided user input, and generates a GET request that matches the track to its unique ID in the Spotify API, and then applies our model to return a json list of top 10 most similar songs back to the user. Song similarity was determined by model analysis of each track's audio features, including danceability, acousticness, instrumentalness vs speechiness, loudness, energy, and valence. We created both a k-nearest neighbors model and a neural network. However, we chose to only deploy the KNN model to our app as it was more lightweight and accurate given the time constraint of one fewer workday. 

## Visual Respresentation of Track Audio Data :notes:

![Radar chart visualization for Aerodynamic by Daft Punk](https://https://github.com/karlmanalo/datascience/blob/master/daft_punk_audio_features_radar_chart.jpg)

## API Endpoints


## Libraries Used
In this project we used Libraries such as:

### 'Pandas'

### 'Flask'

### 'Plotly'

### 'Joblib'

### 'Sklearn'

### 'Requests'

## Team Github Links :musical_note:
[Front-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/front-end)

[Web-UI](https://github.com/Build-Week-Spotify-Song-Suggester-2/Web-UI-Marketing)

[Back-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/back-end)
