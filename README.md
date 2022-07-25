# Project_5_Spotify_playlist
All about "Unsupervised Machine Learning"


Music, art concerned with combining vocal or instrumental sounds for beauty of form or emotional expression, usually according to cultural standards of rhythm, melody, and, in most Western music, harmony.

Users can subscribe to their website and listen to these playlists through their preferred Music App (be it Spotify, Apple Music, Youtube Music…).
Business is scaling up fast and the music experts are slow in creating new playlists.

##### Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria? 
When you listen to two rock ballads, two operas or two drum & bass songs, you identify them as similar songs?
Are these similarities detectable using the audio features from Spotify?

##### Is K-Means a good method to create playlists? Would you stick with this algorithm moving forward, or explore other methods to create playlists?

## Summary of work done so far:

### Data Collection
Data from spotify music app(5200 songs)

### Data cleaning

1.Clean data set

2.drop unused columns

3.remove outliers

4.clean column names

### Data Scaling methods

1.MinMaxScalar

2.StandardScalar

3.RobustScaler


### Kmean clustering

1.Use “Elbow-Method” to define amount of clusters (=playlists)

2.Use Silhouette score to decide on best scaler

3.Check different song-features for each cluster to name playlists!





