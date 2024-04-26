# Music Genre Classification

## Overview

This project focuses on Music Genre Classification, aiming to predict models using Python on Jupyter notebooks in Kaggle with Shai.

Competition link: [Music Genre Classification](https://www.kaggle.com/competitions/shai-music-genre-classification)

### Data Description:

- **Training Dataset**: 14,395 rows with 18 columns.
  - Column details: artist name, track name, popularity, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration in milliseconds, and time signature.
- **Target Variable**: 'Class' such as Rock, Indie, Alt, Pop, Metal, HipHop, Alt_Music, Blues, Acoustic/Folk, Instrumental, Country, Bollywood.
- **Test Dataset**: 3,600 rows with 17 columns.

### Files:

- `train(1).csv`: The training set.

### Features:

- **Artist**: Name of the Artist.
- **Song**: Name of the Track.
- **Popularity**: Popularity of the song.
- **Danceability**: How suitable a track is for dancing.
- **Energy**: A measure of intensity and activity.
- **Key**: The key of the track.
- **Loudness**: Loudness of a track in decibels (dB).
- **Mode**: Mode (major or minor) of a track.
- **Speechiness**: The presence of spoken words in a track.
- **Acousticness**: A confidence measure of the track.
- **Instrumentalness**: Predicts if a track contains no vocals.
- **Liveness**: Higher liveness values increase the probability that the track was performed live.
- **Valence**: Describing the musical positiveness.
- **Tempo**: The speed or pace of a given piece, derived directly from the average beat duration.
- **Duration in Milliseconds**: Time of the song.
- **Time Signature**: How many beats (pulses).

### Evaluation Metric:

The evaluation metric for this competition is Root Mean Squared Error (F1-score). The F1-score can be interpreted as the harmonic mean of precision and recall. 

F1 = 2 * (precision * recall) / (precision + recall)
