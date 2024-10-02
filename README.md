# Eat Safe, Love
This project involves an exploratory analysis of food establishments in the UK using a MongoDB database. It specifically focuses on querying and manipulating data related to the hygiene ratings and locations of establishments. The analysis includes updating and converting data, and making adjustments to a dataset involving UK food establishments.

## Project Overview
The purpose of this notebook is to:
- Import and interact with a MongoDB database (uk_food) containing UK food establishment data.
- Perform queries and data manipulations on the establishments collection.
- Conduct exploratory data analysis to answer specific queries about food establishments.
- Update and clean data to ensure proper formats for fields like latitude, longitude, and rating values.


## Notebook Features
- Part 1: Database and Jupyter Notebook Set Up
    - Import and configure MongoDB using pymongo.
    - Verify the connection to the uk_food database and the establishments collection.
- Part 2: Update the Database
    - Insert a new restaurant entry into the establishments collection.
    - Update data types for specific fields (e.g., latitude, longitude, RatingValue).
    - Remove documents where the LocalAuthorityName is "Dover".
- Part 3: Exploratory Analysis
    - This section contains answers to the following questions:

Which establishments have a hygiene score equal to 20?

Which establishments in London have a RatingValue greater than or equal to 4?

What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant, "Penang Flavours"?

How many establishments in each Local Authority area have a hygiene score of 0?

Queries and Operations

MongoDB queries using find, count_documents, and aggregate.

Updating documents in MongoDB using update_one and update_many.

Converting MongoDB query results into Pandas DataFrames for further analysis.
