# Queries-in-Mongodb

**All types of queries in mongodb - Basic to Advanced**

find() and aggregate() are the functions mainly used for querying in mongodb and you can query each and every complex statement with any of them.

Here I have tried out various types of queries and played with the above mentioned functions in order to generate queries. Along with every query, I have added the explanation for the syntax.

## Dataset used ##

### Downloading the dataset ###
Netflix_titles.csv from Kaggle.  
The dataset is available [here](https://www.kaggle.com/shivamb/netflix-shows) 

### Importing the datset in Mongodb ###
Before opening the mongo shell, mongoimport command is used to import a file in the database.  
**Syntax: mongoimport --type csv -d mydb -c netflix --headerline --drop netflix_titles.csv**   
  
Here,   
**type** is the type of file,  
**d** is the database in which the file has to be imported  
**c** is the collection in which the file has to be imported  
**headerline** denotes that first line of the file has headers  
**drop** is used to drop all the data already present in the collection



