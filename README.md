
# Playlist Popularity Prediction

The goal here is to mimic the Spotify's version of Top Songs of the Year, released every year.
Spotify assigns each song values from 13 different attributes/features. These features are mostly numerical values but include some categorical data as well (the key the song is in, for instance). 
Spotify also assigns each song a popularity score, based on total number of clicks/listens. To predict whether a song is popular or not based on given features.



## Acknowledgements

 - [Data Set](https://www.kaggle.com/tomigelo/spotify-audio-features/home) - we use the Kaggle to source  a mock of the typical data that Spotify uses.
 

## Authors

- [@vignesh](https://github.com/maroovi)


## Features

- This dataset has 116,191 unique songs.
- There are 32,105 unique artists.
- 17 attributes for each song, 13 of them numerical.
- Dependent variable is the Popularity Score - a value between 0 and 100 based on total recent streams.


- 1 - Acousticness (float)	A confidence measure from 0.0 to 1.0 of whether the track is acoustic.
- 2 - Danceability (float)	Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
- 3 - duration_ms (int)	Duration of the track in ms
- 4 - energy (float)	Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.
- 5 - instrumentalness (float)	Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context.
- 6 - key (int)	The estimated overall key of the track.
- 7 - liveness (float)	Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live.
- 8 - loudness	The overall loudness of a track in decibels (dB)
- 9 - mode (int)	Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived.
- 10 - speechiness (float)	Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.
- 11 - tempo (int)	The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
- 12 - time signature (int)	An estimated overall time signature of a track.
- 13 - valence (float)	A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry)


## Roadmap

- Overview of Data
- Exploratory Data Analysis
- Linear Regression to predict popularity score
- Logistic Regression to predict popular/not popular



## Screenshots




## Lessons Learned

The average error and RMSE metrics indicate that all the models other than MLP have decent performance.


