# Genre prediction of songs using KNN algorithms
Modern streaming software in the likes of spotify and Apple music contain an abundance of tracks accounting for more than 220 years worth of listening. This amount is too large for any amount of workforce to classify into genres. Thus there exists a real world need of an algorith which is capable of classifying various songs into appropriate genres and presenting them to curious listeners. Classification through various languages, cultures, and eras is a complicated manner as it is near impossible to find distinguishing futures for all the possible categories. 
We humans however, are capable of feeling and reasonoing about curtain characteristics of songs by just listening to them for a few seconds and intuit about their genre. Desipite the simplicity for us, What characteristics we use to distinguish genre is not necessarily clear and might be mainly sub-conscious. In the following project, we will apply a K-nearest-neighbor algorithm on a dataset containing songs from the four genres R&B, Pop, Rock and Rap and see if the model applies adequately given its predictors which are:
- Liveness: Detects presence of audience in the recording and acts as a confidence measure for wether the song was performed live or not.
- Daceability: Considers tempo, rythm, stability, beat strength and overall regularity to measure how suitable a track is for dancing.
- Valence: Measure of musical positiveness.
- Acousticness: Confidence measure of wether a track is acoustic or not.
- Speechiness: The ratio of speech presence in a track.
- Loudness: The overall loudness of a track in decibels scaled to be between 0 and 1 from -60 to 0 db.

The two quesitons we are attempting to answer through this notebook are:
1. Is the K-nearest neighbor algorithm applicable to classifcation of music across multiple genres?
2. Are the chosen charecteristics good predictors of a songs genre?
