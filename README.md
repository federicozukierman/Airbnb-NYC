# Airbnb_NYC
Welcome to New York City, one of the most-visited cities in the world. There are many Airbnb listings in New York City to meet the high demand for temporary lodging for travelers, which can be anywhere between a few nights to many months. In this notebook, we will take a closer look at the New York Airbnb market by combining data from multiple file types like .csv, .tsv, and .xlsx.

Three files containing data on 2019 Airbnb listings are available to you:

data/airbnb_price.csv

listing_id: unique identifier of listing
price: nightly listing price in USD
nbhood_full: name of borough and neighborhood where listing is located
data/airbnb_room_type.xlsx This is an Excel file containing data on Airbnb listing descriptions and room types.

listing_id: unique identifier of listing
description: listing description
room_type: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments
data/airbnb_last_review.tsv This is a TSV file containing data on Airbnb host names and review dates.

listing_id: unique identifier of listing
host_name: name of listing host
last_review: date when the listing was last reviewed

Our goals are to convert untidy data into appropriate formats to analyze, and answer key questions including:

What is the average price, per night, of an Airbnb listing in NYC?
How does the average price of an Airbnb listing, per month, compare to the private rental market?
How many adverts are for private rooms?
How do Airbnb listing prices compare across the five NYC boroughs?
