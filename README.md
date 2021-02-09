# Lyrics-generator
### Lyrics generation based on different music genres given a user input seed

## Dataset
### The dataset is created by using Spotify API and Genius API. 
Spotify API is used to retrieve songs from five different genres (Pop, Rock, Blues, Country, Hip-Hop) and Genius API is used to search for the song lyrics for each song. The lyrics are then retrived from the Genius website using web-scaping. 
* See Creating Dataset.ipynb*

## Model
Character-level language model is used for this project. The model used is RNN with LSTM layers.
* For more detailed explanation, read the Report.pdf * 

**How to run the program** :
1. Run User interface.ipynb
2. Choose the genre for the song you want to write
3. Enter a few words (at least 20 characters).
4. Press the ‘Generate’ button and wait for results.
5. To generate another song lyric, click Reset and repeat 1 to 4.

**Screenshot of User interface:** <br>

![alt text](https://github.com/bebbieyin/lyrics-generator/blob/master/image/ui1.png)

![alt text](https://github.com/bebbieyin/lyrics-generator/blob/master/image/ui2.png)



