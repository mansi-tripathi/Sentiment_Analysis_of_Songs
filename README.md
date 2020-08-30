# Text_classification
This project involves using sentiment analysis to predict if a song entered is a happy or sad. 

The 'Data' folder consists of 3 files- stopwords_eng, train_lyrics_1000 and valid_lyrics_200.</br>
a. The training data is in 'train_lyrics_1000'. It consists of 1000 rows and 7 columns namely file, artist, title, lyrics, genre, mood and year. </br>
b. The testing data is  with the name 'valid_lyrics_200'. It consists of 200 rows of data.</br>
c. I created a list of stopwords and added it to the text file called stopwords_eng. It is a corpus of stopwords used by the model to remove stopwords from the training data.</br>

# MusicMoodPrediction
For the purpose of predicting the mood of the song, the following python notebooks were implemented.</br>
a. Main notebook (MusicMood_SongClassification) that has been used to implement the model (MLP).</br>
b. Secondary notebook (Implementing Multiple Classifiers) that contains implementation of other models such as SVM, RF, Bagging and Boosting.</br>
