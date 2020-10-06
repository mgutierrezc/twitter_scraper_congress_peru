# Twitter Scraper for Peruvian Congressmen Accounts
**Programmer:** Marco Gutierrez

This [jupyter notebook](https://github.com/mgutierrezc/twitter_scraper_congress_peru/blob/master/Scraper%20for%20congress%20data.ipynb) uses `python-twitter` and `ntlk` packages to scrap the possible twitter accounts of peruvian congressmen and find the best match based on common ngrams for people involved in politics.

This is done by:

1. Scraping the user names of people with similar names to congressmen
1. Scraping their descriptions and first tweets
1. Decomposing the scraped data into ngrams
1. Scoring each user comparing the ngrams of the scraped data to the ones obtained from congress/politics related keywords
1. Keeping the users with the highest scores

Feel free to add any suggestion/comment as an issue or contact me directly by clicking [here](mailto:ma.gutierrezch@up.edu.pe)

