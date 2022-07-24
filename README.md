# Bitcoin_NLP
Using Natural Language Processing (NLP) to determine the sentiment that Bitcoin has in the market during any particular point in time using the NewsAPI.


# Instructions
There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

# Outputs
Creating a corpus of 114 BTC and Etherium articles pulled directly from the NewsAPI:

![image](https://user-images.githubusercontent.com/99841428/180664491-c6ca293e-41aa-4893-a826-e86ce7cea93d.png)


Sentiment Analysis: using the NLTK Sentiment Intensity Analyzer, determine the mean, max, and min sentiment scores from each article for each coin. This data could be used to determine when to buy or sell a particular cryptocurrency.

![image](https://user-images.githubusercontent.com/99841428/180664554-757d391c-0d85-45d1-a570-7f1700f4c871.png)

Ngram frequency: create a dataframe that counts the number of instances of multiple words that are found together. This information could be used to predict the sentiment of future articles based on what words are used. In this case, N is set to two words.

![image](https://user-images.githubusercontent.com/99841428/180664610-31fe38be-92a3-4edf-aae4-9f6fa91ab8a0.png)

Word Clouds: preview the most frequently used words to display the data visually. This could be useful for presentations. The largest words are used the most often.

![image](https://user-images.githubusercontent.com/99841428/180664661-a5ce1db0-a011-4bb9-bbd9-9a11346861a5.png)

![image](https://user-images.githubusercontent.com/99841428/180664677-45d13d89-2f79-4120-a553-cef30edc3957.png)

Named Entity Recognition: Using the Spacey NER, identify words in the corpus of articles that are commonly known entities.

![image](https://user-images.githubusercontent.com/99841428/180664773-f5671b05-293f-4100-a8dd-034d04ed389c.png)


Credit:
NewsAPI: mattlisiv/newsapi-python
Vader Sentiment Analyis: mattlisiv/newsapi-pythonHutto, C.J. & Gilbert, E.E. (2014). VADER: A Parsimonious Rule-based Model for Sentiment Analysis of Social Media Text. Eighth International Conference on Weblogs and Social Media (ICWSM-14). Ann Arbor, MI, June 2014.
