# Song-Recommendation-System-based-on-Spotify-Dataset
1. The project is a song recommendation system using collaborative filtering techniques. It processes a dataset of song information including track, artist, album, and listening duration. The data is normalized and loaded into a surprise library format for recommendation modeling.
   
2. It employs the SVD (Singular Value Decomposition) algorithm, optimized using GridSearchCV for hyperparameter tuning. After training, the system generates song recommendations based on user preferences, particularly by filtering for a specific artist and suggesting similar songs.
   
3. The model's performance is evaluated using cross-validation, making it robust in providing personalized music suggestions.

4. SongRecommender.pynb contains the main code.

5. MyData.csv is the dataset which is the filtered version of the data I requested from Spotify.
