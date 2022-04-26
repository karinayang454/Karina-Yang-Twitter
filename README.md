# Twitter-Sentiment-Analysis
Natural Language Processing (NLP) was applied to conduct Sentiment Analysis on tweets, classifying positive/negative emotion through text mining, text analysis, data analysis and data visualization. 

## Tweets Preprocessing and Cleaning

The preprocessing of the text data is an essential step as it makes the raw text ready for mining. Noise that is irrelevant to finding the sentiment of tweets such as punctuation, special characters, numbers, and terms have been removed.
Tokenizer is then used to convert tweets into word embeddings, and padding is added where necessary. Data was then split into 60% training 40% test.

## The Model

Bi-directional LSTM's were used to analyze both forward and backwards data, while Dropout was applied to prevent overfitting. The created model achieved 83% accuracy in detecting 'positive' vs. 'negative' emotion.

