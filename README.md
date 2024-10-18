# Spotify-Listenership

**Scenario**: As a Data Scientist in the music industry, I am confronted with the challenge of songs receiving zero listenership. The critical task is to find out whether it is possible to predict if a song will attract any listeners, regardless of its overall popularity. The objective is to analyze and identify key factors that influence a song's potential to gain listenership, utilizing the data provided.


Dataset includes 3,000 songs and their information on Spotify.</br>
Target Variable: ‘has_listenership’ (binary)
Data Variable Descriptions:

Metadata:
- track_id: Unique identifier for each song.</br>
- track_name: Name of the song.</br>
- track_artist: Artist of the song.</br>
- track_album_release_date: Release date of the album containing the song.</br>
- track_duration_ms: Duration of the song in milliseconds.</br>

Genre Dummy Variables:</br>
- genre_edm: Indicates if the genre is EDM.</br>
- genre_latin: Indicates if the genre is Latin.</br>
- genre_pop: Indicates if the genre is Pop.</br>
- genre_rnb: Indicates if the genre is R&B.</br>
- genre_rap: Indicates if the genre is Rap.</br>
- genre_rock: Indicates if the genre is Rock.</br>

Sound Characteristics:
- sound_danceability (double): Measures the track's suitability for dancing.</br>
- sound_energy (double): Indicates the intensity and activity level of a track.</br>
- sound_key (double): Represents the estimated overall key of the track.</br>
- sound_loudness (double): The overall loudness of the track in decibels (dB).</br>
- sound_mode (binary): Modality of the track (major or minor).</br>
- sound_speechiness (double): The presence of spoken words in a track.</br>
- sound_acousticness (double): A measure of the track's acoustics.</br>
- sound_instrumentalness (double): Indicates the likelihood of the track being instrumental.</br>
- sound_liveness (double): Detects the presence of an audience in the recording.</br>
- sound_valence (double): Describes the musical positiveness conveyed by a track.</br>
- sound_tempo (double): The overall estimated tempo of the track in BPM.</br>


**Actions performed:**

- Developed a model using numerical variables</br>
- Built Report on the model's evaluation metrics</br>
- Created textual features from the song title `track_name` using methods like Bag-of-Words and/or TF-IDF</br>
- Constructed a model incorporating both numerical and textual features and compare its performance to the numerical-only model</br>
- Analyzed if the inclusion of textual features enhances the model's predictive capability</br>
- Performed topic modeling using LDA</br>
