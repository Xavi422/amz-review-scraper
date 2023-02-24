# Amazon Product Review Scraper

## Description

The idea for this project stems from wanting to learn how to scrape data from the web combined with finding the best flavour of a protein powder to try.

Functionality: Scrapes all amazon product reviews from verified purchasers of a particular Amazon product.

Tools: BeautifulSoup, requests, urrllib.parse

Methodology:

* Get url of first page of verified purchase reviews for the product
* Use a user agent to replicate a popular browser to prevent Amazon from blocking programmatic requests
* Implement a random sleep of between 0 and 0.5 seconds to reduce chances of Amazon blocking requests

Notes:

* Foreign review titles are not links and not stored in a tags

How to run:

License:

## Potential Use Case

### Sentiment Analysis

- Determine what flavour of a product is preferred.
- Determine sentiments regarding specific characteristics of a product e.g. consistency, colour


