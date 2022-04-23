# Welcome to Trump Tweets and Financial Market Relationship Analysis Repository

## About

This is a Mini-Project for CZ1115 (Introduction to Data Science and Artificial Intelligence) which focuses on Trump's tweets from https://www.kaggle.com/austinreese/trump-tweets. For detailed walkthrough, please view the source code in order from:

1. [Data Extraction](https://github.com/calebczh/Trump-Tweets-and-Financial-Market-Relationship/blob/main/dataExtraction.ipynb )
3. [Data Visualization and Combining](https://github.com/calebczh/Trump-Tweets-and-Financial-Market-Relationship/blob/main/EDA-CombineDATA.ipynb) 
5. [Natural Language Processing and Linear Regression](https://github.com/calebczh/Trump-Tweets-and-Financial-Market-Relationship/blob/main/NLP-Reg.ipynb)
  

## Problem Definition

- Are we able to predict the performance of the financial market next day based on Donald Trump's tweets?
- What determining factors are there?

## Contributors

- @calebczh - Data Preparation, Data Visualization, Natural Language Processing, Linear Regression
- Arun - Data Visualization
- Cheryl Koh - Data Visualization

## Models Used

1. Linear Regression
2. Natural Language Processing

## Conclusion

- No relationship found between topics/words of the tweets and the performance of stock market of the following day.
- Even if a association between Trump's tweets and financial markets in daily data is observed,  this association may be caused by both financial markets and Donald Trump responding to same news. Thus, causality cannot be established.
- A more probable way is to investigate the market peformance immediately after the tweet is posted, rather than the day after. This setup allows us to directly observe what happens to financial markets right after President Trump published his tweet. These results directly answer whether Trump's tweets influence financial markets

## What did we learn from this project?

- Using datetime as index
- Managing stock market data and visualizing its performance
- Natural Language Processing 
  - Text prepossessing
  - Latent Dirichlet Allocation
- Other packages such as yfinance, nltk and pyLDAvis

## References

- <https://www.kaggle.com/austinreese/trump-tweets>
- <https://www.analyticsvidhya.com/blog/2021/07/stock-prices-analysis-with-python/>
- <https://finance.yahoo.com/quote/%5EGSPC/chart?p=%5EGSPC>
- <https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#4whatdoesldado>
- <https://www.machinelearningplus.com/nlp/topic-modeling-visualization-how-to-present-results-lda-models/#6.-What-is-the-Dominant-topic-and-its-percentage-contribution-in-each-document>
- <https://towardsdatascience.com/unsupervised-nlp-topic-models-as-a-supervised-learning-input-cf8ee9e5cf28>
