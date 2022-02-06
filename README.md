# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING

# Problem Statement
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

# Summary
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. Understanding what type of content is available in different countries is required. Clustering similar content by matching text-based features Netflix has increasingly focused on TV rather than movies in recent years.
1. Data Cleaning: Director and cast contains a large number of null values so we will drop it.
2. EDA: Exploratory data analysis where we tried to dig insights from the data in hand.
  * I have two types of content TV shows and Movies (30.86% contains TV shows and 69.14 % contains Movies)
  * By analyzing the content added over years we get to know that in recent years Netflix is focusing movies than TV shows (movies is increased by 80% and TV shows is increased by 73% compare to 2016 data)
  * The greatest number of the movie’s release in 2017 and TV shows in 2020 respectively and united nation have the maximum content on Netflix
  * On Netflix, Drama’s genre contains the Maximum content among all of the genres and the most of the content added in December month and less content in February.
3. In text analysis (NLP) I used stop words, TF-IDF vectorizer and other functions of NLP.
4. By applying the silhouette score method for n range clusters and we got the best score which is 0.348 for 3 clusters it means content explained well on
their own clusters, by using elbow method we also got k cluster is 3.
5. Applied different clustering models Kmeans, hierarchical, Agglomerative clustering on data we got the best cluster arrangements.
6. By applying different clustering algorithms to our dataset. We get the optimal number of clusters is equal to 3.
