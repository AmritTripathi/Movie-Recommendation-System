# Movie-Recommendation-System
A Python script to recommend movies to the user based on user's favourite movie.
Steps it performs:
1. It takes some important attributes out from the data table into consideration while training the model.
2. It converts the string attributes into numbers using TfidfVectorizer.
3. Each movie is given a similarity score using Cosine Similarity.
4. It searches for the close match for the favourite movie input given by the user using difflib.
5. Movies are sorted on the basis of there similarity score with respect to the movie given by user and first 30 movies are shown as output.
