README.md

# Tripleten Sprint 1 Project - AirBnB

This was the first project done for the bootcamp, it instilled many of the data fundamentals into my workflow.

### AirBnB Stays

The goal of the project was to clean up the data and prepare pivot tables to give insight on which AirBnB units are more likely to be rented.

### The Data

The data was originally set in four tab groups:

- `raw_data`: The untouched source data for the rest of the sheets
- `data_dictionary`: A summary of all of the different data and the purpose it serves
- `listings`: A list of all the different AirBnB listings along with their specifications and locations
    - `'id'`: ID number the identifies each AirBnB
    - `'neighborhood'` The neighborhood each listing is located in
    - `'neighborhood_group'` The bourough the listing is located within
    - `'property_type'` The type of rental
    - `'room_type'` The amounbt of space being rented
    - `'accomodates'` The number of people the space is meant to accomodate
    - `'bathrooms_text'` The amount of bathrooms in the listing
    - `'bedrooms'` The number of bedrooms in the listing
    - `'price'` The cost to rent the listing
    - `'Occupancy_rate'` The percentage of time that the listing is rented out
    - `'minimum_nights'` The minimun amount of nights the listing can be rented for
    - `'maximum_nights'` The maximum amount of nights the listing can be rented for
    - `'number_of_reviews_ltm'` The number of reviews from the last twelve months
    - `'first_review'`The first review given to the AirBnb
    - `'last_review'` The last time that the AirBnb was reviewed
    - `'review_scores_rating'` The average rating of the reviews the listing has gotten
- `Calendar_Raw` The date the listing was made available along with the prices and number of nights the listing can be rented
    - `'listing_id'` The ID number that identifies each listing
    - `'date'` The date the listing was made available
    - `'available'` If the listing is available it will show t for True if not, then f for False
    - `'price'` The price to rent out this listing
    - `'adjusted price'` Price adjusted for currency
    - `'minimum_nights'` The minumum number of nights the listing can be rented for
    - `'maximum_nights'` The maximum number of nights the listing can be rented for

### The Process

I first cleaned up all of the data for spelling errors and duplicates, I then performed the proper calculations to fill in the missing context for my analysis. Finally I created the proper pivot tables and graphs to form and subsequently back up my analyis.

Please have a look at the spreadsheet for a full description of the results.