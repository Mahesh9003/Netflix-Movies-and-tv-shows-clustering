# Netflix-Movies-and-tv-shows-clustering
Netflix is a popular subscription-based online platform for streaming movies and TV shows. To keep users interested, Netflix relies on recommendation systems to provide valuable content suggestions. In this project, we analyze Netflix data to uncover trends and insights using a dataset collected from Flixable, a third-party Netflix search engine. The data reveals a significant increase in TV shows and a decrease in movies since 2010. By implementing clustering models like K-means and Agglomerative Clustering, we build a recommendation system that suggests content based on user preferences. The project includes data exploration, null value treatment, and text pre-processing for natural language processing (NLP). Despite the data's size and potential irrelevance, we successfully perform exploratory data analysis (EDA) and draw important conclusions to address relevant business challenges.
# Dataset
The dataset includes the following fields:
show_id : Unique ID for every Movie or Tv Show

type :This variable indicates whether the entry is a movie or a TV show. It acts as an identifier to distinguish between the two types of content.

title : Title of the Movie or Tv Show

director : Director of the Movie

cast : actors involved in the movie or TV show

country : Country where the movie or show was produced

date_added :date when the movie or TV show was added to the Netflix platform

release_year : Actual Releaseyear of the movie or show

rating : TV Rating of the movie or show

duration : Total Duration in minutes or number of seasons

listed_in : The listed_in variable denotes the genre or category of the movie or TV show.

description: A brief summary or description of the movie or TV show.
# Steps involved in this project:
Loading the data into data frame

Understanding the Variables

Data Wrangling

Data Vizualization

Hypothesis Testing

Feature Engineering & Data Pre-processing

Textual Data Preprocessing

ML Model Implementation
# Results
* United States and India are among the top 5 countries that produce all of the available content on the platform.
* Majority of the content available on Netflix is Movies.
* The most common ratings for both movies and TV shows on Netflix are TV-MA and TV-14.
* Using the Elbow approach, we chose 18 clusters.
* The years 2015-2019 witnessed the highest production of movies and TV shows.
* Most of these contents are released either in the year ending or the beginning.
* We then used KMeans to predict the labels on our data.
The most common genre of content on Netflix is Dramas, followed by Comedies and Documentries.
