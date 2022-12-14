# Beer Recommendor System

To understand if there are differences amongst the popular beer brand in terms of consumer's perceptions, I scraped ~6000 reviews from a beer review forum and performed the following analysis to develop a recommendor system to generate a list of beer brands that resonates with the constumer's preferences.

- Data Preprocessing: 
Cleaned the scraped reviews by remoing brands which had less than 50 reviews and removed stopwords

- Exploratory Data Analysis:
Generated word frequencies to understand which beer attributes are most talked about and combined similar attributes (replaced them in reviews). Performed LIFT analysis to get a sense of which beer brands are associated with which attributes and are there any noticable differences amongst the brands.

- Building Recommendor System:
I utilized two methods to build the recommendor system. One is a combination of VADER sentiment analysis and Bag of Words cosine similarity. Another is simply the cosine similarity using spacy word embeddings.


Below is the snapshot of the scraped data:
| product\_name    | user\_rating | product\_review                                                                                                                                                                                                                       |
| ---------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Guinness Draught | 4.05         | smooth a little creamy but still bright medium bitterness                                                                                                                                                                             |
| Guinness Draught | 4.34         | from tap at irish pub in nÃ¶rdlingen in germany smells like caramel coffee perfectly balanced taste drinks like water carbonation makes for a very creamy amazing mouthfeel from tap is significantly better than guinness from a can |
| Guinness Draught | 3.8          | i mean its a guinness best beer ever for cooking 20 of these and a glass of milk and you have your rda for all essential calories and nutrients irish car bomb anyone totally amazing                                                 |




