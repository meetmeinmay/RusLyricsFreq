# RusLyricsFreq
### a small NLP project that forms a word cloud of the most frequent words in the whole discography of any Russian-speaking singer.

In the project, I used:
+ [Genius API](https://docs.genius.com/) to fetch the artist's lyrics
+ Python nltk library (stop words for Russian) to perform needed NLP
+ spaCy module to perform tokenization, and lemmatization (spaCy branch).
+ re module - filtering non-Russian words
+ pandas - counting word frequencies
+ PyMyStem - lemmatization
+ wordcloud - creating a word cloud
+ matplotlyb 

the project was initially written in Python in Jupiter and saved as .py code.

the final output looks like a word cloud: (here as an example a word cloud of a music band "Mumi Troll" for 10 songs:
[![Mumi Troll music band word cloud for 10 songs](https://i.postimg.cc/mkTfGH3w/Figure-1.png)](https://postimg.cc/k6YhQDp6)

