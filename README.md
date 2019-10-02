# Listing-crawler
A small application which searches house listings from real estate.
It will send all listings to a kafka stream where it will be read by listing consumer
it will either save the listing for later processing or dump the listing if it already exists. 