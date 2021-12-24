# <font color = 'red'> Case-Study & Mini-Project 1 - IMDB Movie Visualization Mini-Project </font>

------------------------------------------------

`This was an assignment I completed as a part of my Post Graduate Diploma in Data Science from Upgrad & IIIT-Bangalore. The dataset and the Problem Statement was provided to me by Upgrad. 
Since this was my very first Data Science assignment, so a Jupyter notebook was provided to me with the instructions on how to proceed with the assignment. 
I also had to answer some particular questions related to the assignment.`

<font color = 'purple'> **The report that follows is my explanation of what was performed in the assignment.**</font>

## Problem Statement: 
We have the data for the 100 top-rated movies from the famous movie database IMDb from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online.
Our objective for this mini-project is to try to find some interesting insights into these movies and their voters, using exploratory Data Analysis.


## Key Insights from the Data Analysis

#### Looking at Budget v/s Profit
- There is a slightly proportional relationship between Budget and Profit.
- Most of the Movies have positive profit. But there are few movies with negative profit as well. 
- Most of the movies have a very low gross value, i.e., in the range of (0 to 50 million Dollars).
- Most of the movies have a positive Profit in the range of (0 to 200 million Dollars)
- There are some movies that have a very high budget range, but are still producing negative profits.

#### Looking at Actors and Facebook Likes
I analyzed the Facebook likes columns for the respective actors and found out the most popular actor trios based on it. They were – 
>-  ['Dev Patel', 'Nicole Kidman', 'Rooney Mara']
>-  ['Leonardo DiCaprio', 'Tom Hardy', 'Joseph Gordon-Levitt']
>- 	['Jennifer Lawrence', 'Peter Dinklage', 'Hugh Jackman']
>- 	['Casey Affleck', 'Michelle Williams ', 'Kyle Chandler']
>- 	['Tom Hardy', 'Christian Bale', 'Joseph Gordon-Levitt']

#### Looking at Running Time of Movies
- Most of the movies appeared to be sharply 2 hour-long.

#### Looking at Genres & Votes
- Age group "under 18" and "above 45" have voted more than the age group between "18 to 44", irrespective of their gender.
- Romance is the least rated category as voted by men irrespective of their gender, while for females it is not the case.
- Apart from Sci-fi, which is liked by both genders irrespective of their ages, adults i.e., age category 45 and above also voted a lot of Action, Adventure and Thriller movies.
- Even though the average number of votes for romance is less by male the average rating is more or less same as females. This means romance movies, in general, are watched less or voted less by males but the movies are good as they are rated well irrespective of gender especially for U18.
- The age category of "45 and above" have given lower ratings for all movie categories, as compared to other age categories irrespective of their genders. This could mean that adults are not easily impressed by a movie.
- We also saw that the genre of 'animation' is better rated by females as compared to men, as we can see Animation genres has been voted steadily in Female gender, whereas in the male there is a significant difference (decrease) as age increases.

#### Looking at Votes – US vs International
- Non-US people gave more votes to the movies as compared to the US people on average.
- USA movies got higher number of votes from both USA and Non-USA voters as compared to Non-USA movies.
- The median rating is higher from USA people compared to that from non- USA people.
- Both USA and non-USA people have rated non-USA movies significantly less than that of USA movies.

#### Looking at Voting v/s Genres 
- Sci-Fi is the most popular movies genre whereas Romance is the least popular genre among the top 1000 voters.
- There is not a significant difference in popularity amongst Action, Thriller and Adventure. This means that these three genres go hand in hand.
- The genre Romance seems to be most unpopular among the top 1000 voters.


