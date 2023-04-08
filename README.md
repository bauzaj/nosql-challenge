# nosql-challenge: Eat Safe, Love

**Introduction**

Eat Safe, Love is a project that analyses UK Food Standards Agency data to provide insights into food establishment hygiene ratings. This README provides an overview of the Jupyter Notebook used in the project and the tasks performed. The tasks covered are setting up the Notebook, exploratory analysis, and data visualization.

**Notebook Set Up**

In the first part of the Notebook, the following dependencies were imported:

MongoClient from pymongo to work with MongoDB

pprint from pprint to pretty print documents

pandas to work with data in a Pandas DataFrame.

An instance of MongoClient was created, the UK Food database assigned to a variable name, and the collections in the database printed to the console. Finally, the "establishments" collection was assigned to a variable name.

**Exploratory Analysis**

The exploratory analysis was divided into four parts that answered the following questions:


Which establishments have a hygiene score equal to 20?

Which establishments in London have a RatingValue greater than or equal to 4?

What are the top 5 establishments with a RatingValue rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

How many establishments in each Local Authority area have a hygiene score of 0?

***For each question, the answer was provided in three formats:***

Count the number of documents in the result

Display the first document in the result using pprint

Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.



**Conclusion**

This project explored UK Food Standards Agency data using Jupyter Notebook to answer four questions. The questions were answered using pprint and Pandas DataFrame. Finally, a map was created to visualize the top 5 food establishments in London with a hygiene score of 5.
