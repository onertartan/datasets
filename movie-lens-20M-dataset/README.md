Original dataset source: https://grouplens.org/datasets/movielens/
The given dataset and its description below are sourced from:   https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset 

Context
The datasets describe ratings and free-text tagging activities from MovieLens, a movie recommendation service. It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. This dataset was generated on October 17, 2016.
Users were selected at random for inclusion. All selected users had rated at least 20 movies.

Content
No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in six files.

* tag.csv that contains tags applied to movies by users:       "userId, movieId, tag, timestamp"

* rating.csv that contains ratings of movies by users:         "userId, movieId, rating, timestamp"
 
* movie.csv that contains movie information:                   "movieId, title, genres"

* link.csv that contains identifiers to link to other sources: "movieId, imdbId, tmbdId"

* genome_scores.csv that contains movie-tag relevance data:    "movieId, tagId, relevance"

* genome_tags.csv that contains tag descriptions:              "tagId, tag"

"To acknowledge use of the dataset in publications, please cite the following paper:"
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872
