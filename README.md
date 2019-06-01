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
What is the movie release trend across the dataset <br/>
Which is the most profitable movie? <br/>
Which movie had the gretest loss?  <br/>
Which was the most popular genre? <br/>
Which actor has acted in maximun number of movies? <br/>
What is the voting trend across the years? <br/>
Which Production company has prdouced highest number of movies? <br/>

### Cleaning Data <br/>
Information That We Need To Delete Or Modify <br/>

We need to remove duplicate rows from the dataset <br/>
Remove the unused colums that are not needed in the analysis process. <br/>
Remove the movies which are having zero value of budget and revenue. <br/>


### Deriving insights from data
Number of movies produced has gradually increased over the years <br/>
Avatar in 2009 was the most profitable movie <br/>
The Warrior's Way in 2010 was the least profitable movie <br/>
Most movies produced were from Drama genre <br/>
Documentary , Foreign and TV Movies genre had least movies <br/>
Universal Pictures and Waren Bros produced most number of movies <br/>
Robert De Niro was the actor with highest number of movies<br/>
Voting trend gradually declined after 1975 <br/>
Movies after 2005 were more popular <br/>
There is a weak corelation of 0.26 between Budget and run time of movie .Movies with more budget may or may not have higher run time<br/>
Movie with higher vote may or may not be popular due to biased decision of people.<br/>
