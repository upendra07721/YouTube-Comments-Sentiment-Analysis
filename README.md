# YouTube-Comments-Sentiment-Analysis
In the first step i parsed the comments from youtube thanks to the website(https://www.thepythoncode.com/article/extract-youtube-comments-in-python) and author of the article Abdou Rockikz 
Then i have a function to get rid of the emojis in the comments but its not necessary as i have used vader sentiment which takes care of the emojis on its own and even analyse the sentence in accordance to the emoji used which is cool
Then i took care of the punctuation marks and converting all the text to lowercase
In the next step i detected the language of each comment as vader library wokrs well on english 
And remove all other and did the sentiment analysis on only those comments written in english
Then calculated the compound score of all comments and classified them as positive,neutral and negative based on some criteria 
Also made a wordcloud for the comments

Note: This is my first data science project so my approach might look naive and if you want to suggest something you're welcome and can find on LinkedIn as 'Upendra Dixit'
