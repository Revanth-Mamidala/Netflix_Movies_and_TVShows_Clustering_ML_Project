# Netflix_Movies_and_TVShows_Clustering_ML_Project

**Project Name:** Unsupervised ML - Netflix Movies and TV Shows Clustering

## Business Context

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

In this project, you are required to do

* Exploratory Data Analysis

* Understanding what type content is available in different countries

* If Netflix has been increasingly focusing on TV rather than movies in recent years.

* Clustering similar content by matching text-based features.

1. show_id : Unique ID for every Movie / Tv Show

2. type : Identifier - A Movie or TV Show

3. title : Title of the Movie / Tv Show

4. director : Director of the Movie

5. cast : Actors involved in the movie / show

6. country : Country where the movie / show was produced

7. date_added : Date it was added on Netflix

8. release_year : Actual Releaseyear of the movie / show

9. rating : TV Rating of the movie / show

10. duration : Total Duration - in minutes or number of seasons

11. listed_in : Genere

12. description: The Summary description

## **Conclusion:**

* Based on the elbow method and silhouette score, 26 clusters were identified as optimal. The evaluation metrics confirm that K-Means clustering is more effective for analysis compared to Hierarchical clustering. Within K-Means, Cluster 0 has the highest number of data points, with an even distribution across other clusters.

**Content distribution on Netflix:**

* Netflix hosts 5,372 movies and 2,398 TV shows, indicating that the platform has significantly more movies than TV shows.

* TV-MA (adult content) is the most common rating for TV shows.

**Trends in movie and TV show releases:**

* The highest number of movies were released in 2017 and 2018, with another peak in 2020.

* The number of movies on Netflix has been growing significantly faster than TV shows, with a notable surge in both movies and TV shows after 2015.

* A significant decline in the production of movies and TV shows occurred after 2020, suggesting a shift in Netflix’s focus towards increasing movie content over TV shows.

* Most content is added to Netflix between October and January, marking a seasonal pattern.

**Genres:**

* Documentaries are the most popular movie genre on Netflix, followed by Stand-up Comedy, Dramas, and International Movies.

* For TV shows, Kids’ TV is the most prominent genre.

**Durations and seasons:**

* Most movies on Netflix have a runtime of 50 to 150 minutes.

* TV shows on Netflix predominantly have single seasons, reflecting a focus on limited-series formats.

* Movies rated NC-17 have the longest average duration, while movies with a TV-Y rating have the shortest runtime.

**Regional content distribution:**

* The United States has the highest number of Netflix titles, followed by India, which leads in the number of movies available on the platform.

**Release origin of content:**

* 30% of the movies were released exclusively on Netflix, while 70% were initially released through other channels before being added to the platform.









