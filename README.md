# Music_Genre_Classification
Music Genre Classification Project

# Music-Genre-Classification
This is competition to predict model made using python on jupyter notebooks in kaggle with Shai.

https://www.kaggle.com/competitions/shai-music-genre-classification

## Data Description:
Training dataset: 14395 rows with 18 columns Column details: artist name; track name; popularity; ‘danceability’; energy; key; loudness; mode; ‘speechiness’; ‘acousticness’; ‘instrumentalness’; liveness; valence; tempo; duration in milliseconds and time_signature. Target Variable: 'Class’ such as Rock, Indie, Alt, Pop, Metal, HipHop, Alt_Music, Blues, Acoustic/Folk, Instrumental, Country, Bollywood, Test dataset: 3600 rows with 17 columns

## Files:
<li>train(1).csv - the training set</li>
## Features
<li>artist: Name of the Artist.</li>
<li>song: Name of the Track.</li>
<li>popularity: popular the song.</li>
<li>danceability: how suitable a track is for dancing</li>
<li>energy: measure of intensity and activity.</li>
<li>key: The key of the track .</li>
<li>loudness: loudness of a track in decibels (dB).</li>
<li>mode: Mode (major or minor) of a track.</li>
<li>speechiness: presence of spoken words in a track.</li>
<li>acousticness: A confidence measure of the track.</li>
<li>instrumentalness: Predicts a track contains no vocals.</li>
<li>liveness: Higher liveness values represent an increased probability that the track was performed live.</li>
<li>valence: describing the musical positiveness</li>
<li>tempo: the speed or pace of a given piece and derives directly from the average beat duration.</li>
<li>duration in milliseconds :Time of the song</li>
<li>time_signature : how many beats (pulses).</li>
## Evaluation Metric
The evaluation metric for this competition is Root Mean Squared Error (F1-score). The F1-score can be interpreted as a harmonic mean of the precision and recall. F1 = 2 * (precision * recall) / (precision + recall)
