
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

![image](https://user-images.githubusercontent.com/60556766/150615211-3b1ab70f-8087-48f3-a425-17d9550d2ce2.png)

![image](https://user-images.githubusercontent.com/60556766/150615304-3862ce40-7415-47a2-88ed-c0cc6f5743cb.png)



## Roadmap

- Overview of Data
- Exploratory Data Analysis
- Linear Regression to predict popularity score
- Logistic Regression to predict popular/not popular

## Model Built

- Linear Regression:

![image](https://user-images.githubusercontent.com/60556766/150615391-4e06b028-78ab-4769-9883-fefbd562b0cc.png)


- Regression Tree:

![image](https://user-images.githubusercontent.com/60556766/150615418-a52d3e68-a2d2-454e-b2f9-687a235e757e.png)
![image](https://user-images.githubusercontent.com/60556766/150615428-bbcd0edf-c51a-4fb2-bd0d-6a2650bcc401.png)

- Multilayer Perceptron:

![image](https://user-images.githubusercontent.com/60556766/150615464-e4e606a9-40a2-45b1-b51e-3f2af144b30d.png)




## Screenshots


![image](https://user-images.githubusercontent.com/60556766/150615106-a1c2faf7-709a-42ee-8dc7-23cf85756e80.png)
![image](https://user-images.githubusercontent.com/60556766/150615122-e53f1d62-c1ce-4ff5-a13c-9618e1d98df2.png)
![image](https://user-images.githubusercontent.com/60556766/150615135-7ecbfe51-b16a-474b-8cd8-8d1d86653a0a.png)


## Lessons Learned

The average error and RMSE metrics indicate that all the models other than MLP have decent performance.


