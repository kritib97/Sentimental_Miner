# Sentimental_Miner
The code performs data mining on an IMDB webpage by accessing each movie and mining its user reviews. After obtaining the reviews, it stores them in a csv file. The collected reviews are then grouped based on the movie names. 
For each movie, sentiment analysis is performed on the reviews using natural language processing and based on the score, the movie is classified as worth watching or not.

Packages to be installed: <br />
*pip install beautifulsoup4* <br />
*pip install selenium* <br />
*nltk.download('vader_lexicon')* <br />
*nltk.download('punkt')* <br />

