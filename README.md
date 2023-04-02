# Netflix-Movies-and-TV-Shows-Clustering


## Problem Statement:
The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset, which includes movies and TV shows as of 2019, will be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.

## Dataset:
The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. The data includes information on all movies and TV shows available on the streaming platform as of 2019, with a total of 7787 records and 12 attributes. Each attribute provides specific information about the movie or TV show. For more information on the dataset, please visit the Kaggle website at https://www.kaggle.com/datasets/sambhajizambre/netflix-movies-and-tv-shows-clustering?select=netflix_titles.csv.

## Data Pipeline:
1.Know your data

2.Understanding Variables

3.Data Wrangling

4.Exploratory Data Analysis

5.Hypothesis Testing

6.Feature Engineering/Data Preprocessing

7.Model Implementation

8.Conclusion

## Report:

1) There are 7787 rows and 12 columns in the dataset.

2) Netflix having content from year 1925 to 2021

3) Netflix having 30.9% of TV Shows and 69.1% of Movies on its platform

4) Adults and Teens contents getting most of ratings

5) Both Movies & TV Shows productions/releases got boomed after year 2000 but Movies had more as compare to TV Shows.

6) Content after year 2015 increases more(almost doubled).

7) There is no such difference in releases for when compared monthwise.

8) International movies, dramas, comedy is prefred the most while TV Thriller, Classic & Cult TV , TV Shows are at last .

9) United States and India having more content with US having equal number of tv shows and movies while in India number of movies are more as compared to tvshows.

10) most of the content related to Life, Love , Family, Friend , World words.

11) Top TV Shows actors are from all around the world but Movies actors are all from India.

12) TFIDF Vectorization created 10000 dimensions. Then problem of dimensionality was treated by PCA(Principle Component Analysis) .3000 dimensions taken because of adding almost 80% of variance to it.

13) Implemented K-Means Clustering ,Agglomerative clustering , DB-Scan algorithms.


