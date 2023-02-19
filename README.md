# nosql-challenge

In this repo, the folder contains the main jupyter notebook script for noSQL setup and the exploratory analysis done on the establishments JSON file. The JSON file used for the analysis is available in the folder named Resources.

# Summary

PyMongo and Python was used to setup the database and do exploratory analysis on the file provided which contains the information from The UK Food Standards Agency who evaluates various establishments across the United Kingdom, and gives them a food hygiene rating.

## Part 1: Database and Jupyter Notebook Set Up (Use NoSQL_setup.ipynb for this section)

* Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments.
* Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).
* Create an instance of the Mongo Client.
* Confirm that you created the database and loaded the data properly.

## Part 2: Update the Database (Use NoSQL_setup.ipynb for this section)

* Update the database with information regarding a new halal restaurant just opened in Greenwich.
* Update the new restaurant with the BusinessTypeID for "Restaurant/Cafe/Canteen".
* The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
* Convert longitude and latitude into decimal numbers data type.

## Part 3: Exploratory Analysis (Use NoSQL_analysis.ipynb for this section)

* Which establishments have a hygiene score equal to 20?
* Which establishments in London have a RatingValue greater than or equal to 4?
* What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.