### Deatils
This is a data set from TMDb with list of movies from 1966 to 2015, which is around 5000 movies.
Here we are cleaning and analyzing the dataset for the movie trends across the years.
This project is done as part of udacity's nanodegree program.

### Gathering Data <br/>
Data is taken from udacity's nanodegree project 

### Analyzing Data <br/>
The movie data set provided by TMDb has list of movies from 1966 to 2015. The data set has following attributes :<br/>

id , imdb_id , popularity , budget , revenue , original_title , cast , homepage , director , tagline , keywords , overview , runtime , genres , production_companies , release_date , vote_count , vote_average , release_year , budget_adj ,revenue_adj

`Questions to be answered`
What is the movie release trend across the dataset
Which is the most profitable movie?
Which movie had the gretest loss?
Which was the most popular genre?
Which actor has acted in maximun number of movies?
What is the voting trend across the years?
Which Production company has prdouced highest number of movies?

### Cleaning Data <br/>
Information That We Need To Delete Or Modify <br/>

We need to remove duplicate rows from the dataset
Remove the unused colums that are not needed in the analysis process.
Remove the movies which are having zero value of budget and revenue.


### Deriving insights from data
Number of movies produced has gradually increased over the years
Avatar in 2009 was the most profitable movie
The Warrior's Way in 2010 was the least profitable movie
Most movies produced were from Drama genre
Documentary , Foreign and TV Movies genre had least movies
Universal Pictures and Waren Bros produced most number of movies
Robert De Niro was the actor with highest number of movies
Voting trend gradually declined after 1975
Movies after 2005 were more popular
There is a weak corelation of 0.26 between Budget and run time of movie .Movies with more budget may or may not have higher run time
Movie with higher vote may or may not be popular due to biased decision of people.
