This Repository Contains my Projects based on Data Science and Machine Learning.
I have done a Simple movie recommendation System based my learning about data pre processing
and training using the sci-kit Learn library in python.

This project is a Bollywood Movie Recommendation System that suggests movies based on the user's preferred genres and the number of years since the movie's release (the "age of cinema").
The system uses a Random Forest Classifier model to predict age groups and then recommends Bollywood movies accordingly.

Flow of the process:

1. Cleans and preprocesses a dataset of movies .
2. Calculates the "age of cinema" (the number of years since a movie's release).
3. One-hot encodes movie genres for easier analysis and prediction.
4. Groups movies into age categories.
5. Uses a Random Forest Classifier(Fast and Effecient - for multi class classification) to predict movie recommendations based on the user’s input (age and preferred genres).
6. Recommends movies based on the predicted age group and genres.
