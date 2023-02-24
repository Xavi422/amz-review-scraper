# Amazon Product Review Scraper

## Description

The idea for this project stems from wanting to learn how to scrape data programmatically combined with finding the best flavour of a protein powder to try.

Functionality: Scrapes all amazon product reviews from verified purchasers of a particular Amazon product and outputs to json file.

Tools: BeautifulSoup, requests, urrllib.parse

Methodology:

* Get url of first page of verified purchase reviews for the product
* Use a user agent to replicate a popular browser to prevent Amazon from blocking programmatic requests
* Implement a random sleep of between 0 and 0.5 seconds to reduce chances of Amazon blocking requests
* Get url of next page from "Next Page" button link

Notes:

* Foreign review titles are not links and not stored in a tags
* Chose not to remove stopwords since they provide context in sentiment analysis

License:

## Potential Use Case

### Sentiment Analysis

* Determine what flavour of a product is preferred.

## Possible improvements

* Filter for reviews with words relating to taste e.g. "flavour", "tasty", "delicious"

