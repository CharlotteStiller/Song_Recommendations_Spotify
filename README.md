# Song Recommendation - Spotify API

Working with my favorite three spotify playlists, to recommend more songs which belongs into my favorit music clusters.

<img src="https://i.pinimg.com/564x/82/aa/80/82aa8009fdea2e261cfc371eb80a7e0b.jpg" width="500">

## Installing

Create a spotify application with own clientId and clientSecret. (https://developer.spotify.com/documentation/web-api/)

## Workflow

1. **Building dataframe with my favorite songs** [Here](https://github.com/CharlotteStiller/Song_Recommendations_Spotify/blob/main/1_Top_Spotify_Songs.ipynb)
    - Files: Top_Spotify_Songs.ipynb / Top_Spotify_Songs.csv /
    - Abstract my favorite songs from three different playlist and save them in a csv file. 

2. **Cluster the songs with k-means** [Here](https://github.com/CharlotteStiller/Song_Recommendations_Spotify/blob/main/2_Clusterings_Top_Spotify_Songs.ipynb)

3. **Finde songs in this clusters** [Here](https://github.com/CharlotteStiller/Song_Recommendations_Spotify/blob/main/3_Song_Recommendation.ipynb)

## Libaries 
- [IPython](https://docs.python.org/3/library/) 
- [pandas](https://pandas.pydata.org/docs/) 
- [spotipy](https://spotipy.readthedocs.io/en/2.19.0/) 
- [matplotlib](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html) 
- [numpy](https://numpy.org/doc/)
- [sklearn](https://scikit-learn.org/stable/) 
- [warnings](https://docs.python.org/3/library/warnings.html)
