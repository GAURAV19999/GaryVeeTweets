# GaryVeeTweets
Simple Analysis of Gary Vee's Tweets in Python. The tweets scraped where from January 1st 2020 until January 12th 2021.

### Frameworks
- PIL - Image processing library
- Pandas - DataFrame Library
- Numpy - Mathematical Library
- Matplotlib - Library used for visualizations
- Wordcloud - Library used for making wordclouds
- NLTK - NLP Library
- Snscrape - Scraper for Social networks services

### Installation
Using python's package manager pip to install the dependencies
``` sh
pip install pandas
pip install PIL
pip install matplotlib
pip install wordcloud
pip install git+https://github.com/JustAnotherArchivist/snscrape.git
```
Python 3.8 or higher is required for snscrape

### How to run 
Execute the following command on the terminal
``` sh
snscrape --jsonl --progress --since 2020-01-01 twitter-search "from:garyvee" > Gary_data.json
```
```--jsonl: ``` Saves as a Json file

```--progress: ``` Displays progress every 100 tweets scraped

```--since: ``` The time from when the tweets should be scraped

```--twitter-search: ``` twitter keyword to search from

The result tweets are saved as the **Gary_data.json** file.

The **GaryVeeWC.ipynb** should be executed in either Jupyter Notebooks or Google Collab. 


