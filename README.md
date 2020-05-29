# Data Science - Spotify Track Recommender

## App :headphones: 
[https://bw-spotify.herokuapp.com/](https://bw-spotify.herokuapp.com/)

## Workflow
![Alt text](https://raw.githubusercontent.com/Build-Week-Spotify-Song-Suggester-2/datascience/master/DS%20Flowchart.jpg)

## Project Information 
We were assigned to deploy a personalized song reccomendation app by creating an algorithm to recommend songs based on a user's inputted song. We created a new dataset of 120k unique song tracks to train our model with by combining a dataset of tracks from [Kaggle](https://www.kaggle.com/tomigelo/spotify-audio-features) and updating it with additional tracks from the [Spotify API]( https://api.spotify.com) directly. 

Our app takes the provided user input, and generates a GET request that matches the track to its unique ID in the Spotify API, and then applies our model to return a json list of top 10 most similar songs back to the user. Song similarity was determined by model analysis of each track's audio features, including danceability, acousticness, instrumentalness vs speechiness, loudness, energy, and valence. We created both a k-nearest neighbors model and a neural network. However, we chose to only deploy the KNN model to our app as it was more lightweight and accurate given the time constraint of one fewer workday. 

## Visual Respresentation of Track Audio Data :notes:

![Radar chart visualization for Aerodynamic by Daft Punk](https://raw.githubusercontent.com/Build-Week-Spotify-Song-Suggester-2/datascience/f7adc65e3366a0df1fe83e732baea3419d9d134b/daft_punk_audio_features_radar_chart.jpg)

## API Endpoints


## Libraries Used
In this project we used Libraries such as:

* ['Pandas'](https://pandas.pydata.org/docs/)

* ['Numpy'](https://docs.scipy.org/doc/)

* ['Flask'](https://flask.palletsprojects.com/en/1.1.x/)

* ['Sklearn'](https://scikit-learn.org/stable/)

* ['Plotly'](https://github.com/plotly/plotly.py)

* ['Joblib'](https://joblib.readthedocs.io/en/latest/)

* ['Tensorflow'](https://www.tensorflow.org/overview/)






### 'Requests'

## **Contributers**
|[Karl Manalo](https://github.com/karlmanalo)                                        |[Fatai King](https://github.com/fataik1)                                        |[Miriam Ali](https://github.com/maiali13/)                                        |
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                      [<img src="https://avatars1.githubusercontent.com/u/60849521?s=460&u=1c0422c701fc566ecd9edcea912801a88f1ce720&v=4" width = "200" />](https://github.com/karlmanalo)                       |                      [<img src="https://avatars0.githubusercontent.com/u/53956594?s=460&u=c75a90473ca33926d32e1bca8fb1746020e3ab23&v=4" width = "200" />](https://github.com/KyleTy1er)                       |                      [<img src="https://avatars2.githubusercontent.com/u/57272996?s=460&u=7bd094ffa064db7948f3f4db3aa7664e27250366&v=4" width = "200" />](https://github.com/CodingDuckmx)                       |                      [<img src="https://avatars2.githubusercontent.com/u/5897107?s=460&v=4" width = "200" />](https://github.com/cedro-gasque)                       
|                 [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/dougscohen)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/fataik1)             |           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/maiali13/)            |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/dougcohen3/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/fatai-king-8b2b5a9b/) | 

## Team Github Links :musical_note:
[Front-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/front-end)

[Web-UI](https://github.com/Build-Week-Spotify-Song-Suggester-2/Web-UI-Marketing)

[Back-End](https://github.com/Build-Week-Spotify-Song-Suggester-2/back-end)
