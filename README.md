# nosql_challenge

-- Repo Files --

NoSQL_setup_starter.ipynb is the first notebook to be run. This notebook has two parts which are labeled.
    Part 1 sets up a mongo database and imports a json file found in the Resources folder.
    The first line in Part 1 is an import statement which creates a database called uk_food, a collection called establishments, and imports the json file Resources/establishments.json into the collection. This json file contains data on a number of buisinesses. 
    The rest of Part 1 imports dependencies, sets up the mongoDB connections, and assigns variables for easy reference later.
    
    Part 2 cleans the database.
        A new establishment with the name 'Penang Flavours' is inserted and updated in the database.
        Other establishmens are deleted that have the 'LocalAuthorityName' of 'Dover'.
        Finally, the data-types of 'latitude' and 'longitude' are converted to the double and 'RatingValue' is converted to integer
        
NoSQL_analysis_starter.ipynb is the second notebook to be run. 
    The section 'Notebook Set Up' imports all dependencies, creates an instance of the MongoClient, and sets variables for the database and collection that was set up in the previous notebook.
    Part 3 answers four questions about the data in the establishments collection of the uk_food database. Queries are made for each of these questions and the results are converted into pandas dataframes and displayed.
    

-- Notes --
All work from the .ipynb files is my own and I had no collaboration with others on this work other than outlines that was given from the starter_code files.

