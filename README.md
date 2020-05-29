# Data Science - Spotify Track Recommender

## App
[https://bw-spotify.herokuapp.com/](https://bw-spotify.herokuapp.com/)

## Workflow
![Alt text](/Flowchart.png)

## Project Information
A Kaggle database of songs or access to the Spotify API directly. We will be accessing the Spotify API directly to pull certain information on audio tracks, and a dataset of 120k unique songs to train our model.

We were assigned to deploy a personalized song reccomendation app by creating algorithm to recommend songs based on user's input song. We created a new dataset of 120k unique song tracks to train our model with, by combining a dataset of tracks from Kaggle and updating it with additional tracks from the Spotify API directly. 

Our app takes the provided user input, matches it to it’s track ID in the Spotify API, and then applies our model to return a json list of top 10 similar songs based on the audio features back to the user. We created both a k-nearest neighbors model and a neural network. However, we chose the to only deploy the KNN model to our app as it was more lightweight and accurate given the time constraint of one fewer workday. 

## Visual Respresentation of Track Audio Data

(add image of radar chart?)


## API Endpoints


## Libraries Used


## Team Github Links
[Front-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/front-end)

[Web-UI](https://github.com/Build-Week-Spotify-Song-Suggester-2/Web-UI-Marketing)

[Back-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/back-end)
