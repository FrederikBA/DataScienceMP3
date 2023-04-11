# DataScienceMP3
Data Science Mini Project 3
### Janus, Julius, Frederik

#### Provide a brief discussion on the possible advantages of NLP the implementation, as well as on the difficulties you have experienced developing it.

##### Possible advantages:
We have created a program to analyze company reputation based on their reviews given on the popular website TrustPilot. Here we have webscraped each review for a given company where we then can process the review and put it through sentiment analysis to see if the review is positive, neutral or negative. This is an advantage for many people, because they can easily see - without scrolling through trustpilot, a companys reputation.

##### Difficulties:
1. We had some difficulties with sentiment analysis specifically on the danish language as many built-in functions only worked on english texts.

2. Instead we found a CSV file specifically tailored to perform sentiment analysis on the danish language. This file had weights for a lot of words and gave a polarity score based on each word in the text and their weights. Unfortunately this file had some weights that, in our opinion, is not precise or well justified. Therefore the results are less than optimal in comparison to what we would analyze the text to be.


