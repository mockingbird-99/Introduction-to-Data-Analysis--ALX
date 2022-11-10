This project the details the cleaning, exploration and deduction of a data set from The Movie Database(Tmdb).The data set holds the data concerning 10,000 different movies, along with their user ratings and revenue generated from said movies. The data set is characterized by 21 columns, each holding data on varying characteristics of each movie. The movie title, starring cast, movie director,revenue, runtime, release date and release year are captured.

Per the data set, each movie has its unique ID captured in the 'id' columns, and an ID from imdb captured in the 'imdb_id' column.

The 'popularity' column describes the popularity rating of the movies.

The 'budget' column captures values equivalent to the monetary value of the resources spent in the creation of the movies. This feature could analysed to ascertain a relationship between the success of a movie and the movie budget.

The 'tagline', 'keywords' and 'overview' columns contain brief descriptions of the movie. The tagline captures a single catch phrase that best describes the movie, while the overview contains a paragraph of summary of the movie. 'keywords' hold a list of words that describe dominant features in the movies. Keywords can be used to describe the genre of each movie. For example, a movie about a monster ravaging a city could have a keyword, 'monster'.

'runtime' holds numeric values equivalent to the length of each movie in minutes. This feature could play an interesting role in the success of a movie. Do movies with shorter runtimes have higher ratings?

'genres' holds a set of genres that the movie falls in. This column is simialar in structure to the 'keywords' column.

'production_companies' holds details on the names of the production companies that cooperated to produce the movie.

'release_date' and 'release_year' hold the dates of release and year of release of each movie.

Movie patronizers were asked to rate the movies. 'vote_count' holds the number of patronizers who cast votes. They were asked to rate the movies with scores from 1 to 10, where 10 is the highest score, and 1 is the least score. 'vote_average' holds the mean rating of each movie.

The final two columns 'budget_adj' and 'revenue_adj' show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Question(s) for Analysis
The data set in this case study has the prospects to answer a plethora of questions. In this investigation however, we will be limiting ourselves to 3 questions built upon 2 dependent (popularity and revenue) variables and 3 independent variables (budget, runtime, and genre). Questions:

1. What is the relationship between the budget of a particular movie and its popularity?
2. How does the popularity of a movie affect its revenue?
3. Have more movies been made over the years? Do older movies have higher equivalent revenue than newer ones?