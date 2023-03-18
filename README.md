# Cryptocurrency Sentiment Analysis

## PROJECT SUMMARY

The aim of this project is to produce a Twitter Sentiment Analysis on the cryptocurrency market. With the rise in popularity of Bitcoin and Ethereum and the majority of  businesses moving to the web3.0 it is important to understand how the consumer actually feels about this change.
In this project a list of the most recent and relevant tweets related to crypto trading, Bitcoin and Ethereum have been scraped from Twitter data. It is then analyzed with the help of cardiffnlp/twitter-roberta-base-sentiment-latest model which is a RoBERTa based NLP model from hugging face and rated negative neutral and positive accordingly.          
## FILES AND LIBRARIES 

**To run this project, you will need to add the following Libraries to your system :-**
- transformers
- torch
- requests
- re
- pandas
- numpy 
- snscrape
- matplotlib
- seaborn

**The datasets included in the project are :-**

- `Cryptodata.csv`:- Stores the tweets extracted for the purpose of this project.
- `sentiment.csv` :- Stores the sentiment scores after performing the sentiment analysis.

## Conclusion

The goal of the study is to ascertain how people feel about cryptocurrencies on Twitter, with a focus on bitcoin, Ethereum, and crypto trading in particular. 
The following are the main question evaluated in the project:-
What are people's thoughts on, say, cryptocurrency and blockchain technology?
 What are the most important Crypto and Blockchain-related product categories?
We all know that decentralization and web3.0 has had an effect on a number of areas, including finances, healthcare, legal services, and insurance. This study will help to understand how the people perceive this ongoing change.
In this project the  negative tweet was assigned a sentiment score of  1. Similarly 2 was assigned to neutral and 3 to positive.


## Result 

![Histogram showing the `Sentiment Scores` plotted against `The Number of Tweets` ](https://github.com/Satarupa22-SD/Cryptocurrency-Sentiment-Analysis/blob/main/Result.png)
Here, the Sentiment Scores have been plotted against The Number Of Tweets

## Authors

- [@Satarupa22-SD](https://github.com/Satarupa22-SD)


## References

1.  RoBERTa: A Robustly Optimized BERT Pretraining Approach
      https://arxiv.org/abs/1907.11692

2.  BERT, RoBERTa, DistilBERT, XLNet — which one to use? 
    https://towardsdatascience.com/bert-roberta-distilbert-xlnet-which-one-to-use-3d5ab82ba5f8

3.  BERT language model
     https://www.techtarget.com/searchenterpriseai/definition/BERT-language-model


