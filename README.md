# My Boy Suga

## Tl;dr: clean dataset for further NLP analyses. Example projects. 

This repository contains an already processed, scraped tweets csv from Japan Minister Yoshihide Suga's official Twitter account. 
I also included my take on sentiment analysis on his tweets. Rather than using Twitter's API to scrape the tweets, I used Twint,
as it can 

1) fetch all Tweets made by PM Suga.
2) be used anonymously.
3) no rate limitations.

Further cleaning of the data was done using R, and data column translation from 'ja' to 'en' was done through Google Sheets.

My two project includes Sentiment Analysis and a Co-occurance Network of Japan's Prime Minister Yoshihide Suga's tweets.
Credited below is Hironsan and Asari, a Japanese sentiment analyzer implemented in Python. Please note that
one of Asari's dependencies, Janome, a morphological analysis engine, is only supported by Python 3.6 and below, so one way
to navigate through this is to downgrade from Janome 0.4.1 to Janome 0.3.7. 


For your personal project, I've uploaded the dataset onto


https://www.kaggle.com/andresha/yoshihide-suga-tweets-sugawitter. 


Would love to see what insights you all come up with. 


```
pip install "Janome == 0.3.7"

```
 
Readings: 

https://asia.nikkei.com/Politics/Suga-s-approval-rating-remains-low-at-43-Nikkei-poll

https://github.com/Hironsan/asari

https://studymachinelearning.com/jaccard-similarity-text-similarity-metric-in-nlp/

https://networkx.org/documentation/stable/tutorial.html

http://www.ie110704.net/
