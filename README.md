# SpotifyVsYoutube-EDA

The Dataset was collected from Kaggle in order to Explore and generate Insights.</br>
The dataset contains 20718 rows and 26 columns</br>
It includes 26 variables for each of the songs collected from spotify. These variables are briefly described next:</br>

Track: name of the song, as visible on the Spotify platform.</br>
Artist: name of the artist.</br>
Url_spotify: the Url of the artist.</br>
Album: the album in wich the song is contained on Spotify.</br>
Album_type: indicates if the song is relesead on Spotify as a single or contained in an album.</br>
Uri: a spotify link used to find the song through the API.</br>
Danceability: describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.</br>
Energy: is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.</br>
Key: the key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.</br>
Loudness: the overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.</br>
Speechiness: detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.</br>
Acousticness: a confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.</br>
Instrumentalness: predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.</br>
Liveness: detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.</br>
Valence: a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).</br>
Tempo: the overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.</br>
Duration_ms: the duration of the track in milliseconds.</br>
Stream: number of streams of the song on Spotify.</br>
Url_youtube: url of the video linked to the song on Youtube, if it have any.</br>
Title: title of the videoclip on youtube.</br>
Channel: name of the channel that have published the video.</br>
Views: number of views.</br>
Likes: number of likes.</br>
Comments: number of comments.</br>
Description: description of the video on Youtube.</br>
Licensed: Indicates whether the video represents licensed content, which means that the content was uploaded to a channel linked to a YouTube content partner and then claimed by that partner.</br>
official_video: boolean value that indicates if the video found is the official video of the song.</br>
</br>
## Insights

Danceability score comparison:-</br>
![image](https://github.com/DAKSH1-HUB/SpotifyVsYoutube-EDA/assets/81084807/eb83c90e-f92a-45d3-9ace-fba247238c67)

Based on Correlation between variables, Major relations are:-</br>

Relationship between Loudness and Acousticness</br>
![image](https://github.com/DAKSH1-HUB/SpotifyVsYoutube-EDA/assets/81084807/7447b261-6fe5-4c19-adcb-fb88393d6603)

#### Loudness and Acousticness have inverse relation ie. more the loudness and less the song will be acoustic.

Relationship between Loudness and Energy</br>
![image](https://github.com/DAKSH1-HUB/SpotifyVsYoutube-EDA/assets/81084807/15bea8f9-05c9-4a37-817d-5d7f72f4e76f)



Relationship between Energy and Acousticness</br>
![image](https://github.com/DAKSH1-HUB/SpotifyVsYoutube-EDA/assets/81084807/b2ce58f9-7425-496e-bf2e-5bbc7e1b6a35)

Relationship between Loudness and Instrumentalness
![image](https://github.com/DAKSH1-HUB/SpotifyVsYoutube-EDA/assets/81084807/ff480e19-bd48-4bcb-9d96-ebf14daa462d)



