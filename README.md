# Beer Recommendor System

To understand if there are differences amongst the popular beer brand in terms of consumer's perceptions, I scraped ~6000 reviews from a beer review forum and performed the following analysis to develop a recommendor system to generate a list of beer brands that resonates with the constumer's preferences.

- Data Preprocessing: 
Cleaned the scraped reviews by remoing brands which had less than 50 reviews and removed stopwords

- Exploratory Data Analysis:
Generated word frequencies to understand which beer attributes are most talked about and combined similar attributes (replaced them in reviews). Performed LIFT analysis to get a sense of which beer brands are associated with which attributes and are there any noticable differences amongst the brands.

- Building Recommendor System:
I utilized two methods to build the recommendor system. One is a combination of VADER sentiment analysis and Bag of Words cosine similarity. Another is simply the cosine similarity using spacy word embeddings.


Below is the snapshot of the scraped data:




