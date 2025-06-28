# Netflix-Movies-and-TV-Shows-Clustering

Project tile - Netflix Movies and TV Shows Clustering
Description:
This is a Unsupervised ML (Clustering) capstone project on Netflix Movies and TV Shows Clustering given by Alma Better.


Problem statement:
This dataset consist of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that number of TV Shows on Netflix has nearly tripled since 2010. The streaming service's number of movies has decreased by more than 2,000 titles since 2010, while its number of TV Shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external dataset such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

Dataset description:
The dataset is collected from Flixable which is a third-party search engine of Netflix. The dataset consist of the information of the Movies and TV Shows available on Netflix as of 2019

Attribute Information:

show_id - Unique ID for every Movie / Tv Show
type - A Movie or TV Show
title - Title of movie/show
director - Director of the show
cast - Actors involved
country - Country of production
date_added - Date it was added on Netflix
release_year - Actual release year of the show
rating - TV ratings of the show
duration - Total duration in minutes or number of seasons
listed_in - Genre
description - The summary description
github

Project Flowchart:
Initial preparations(Loading the dependencies and the data)

Data Inspection

Data Wrangling

Handling null values
Handling duplicate values
Removing Irrelevant Features
Exploratory Data Analysis (EDA)

Data Preprocessing

Feature Encoding
Text Preprocessing
Removing Punctuations
Removing Stopwords
Lemmatization
Scaling
Feature Engineering

Creating new features
Vectorization
Model implementation

KMeans Clustering
Elbow Method
Silhouette Score
Hierarchical Clustering
Dendogram Visualization
Agglomerative Clustering
DBSCAN
github

Conclusion:
EDA insights:

Netflix started becomming popular in 2008 and in 2015, it gets a boost in its growth.
There are two types of content available on Netflix ,i.e., Movies and TV Shows.
Earlier there were only Movies (before 2002), but in recent years both of the * content is increasing drastically specially TV Shows because the young generation is prefering TV Shows over Movies.
USA has contributed the largest number of contents(both Movies & TV Shows) on Netflix.
Japan & South Korea are two top countries who have contributed more number of * TV Shows as compare to Movies.
Most of the content available on Netflix is for Mature audience.
Top 3 genre of the content are International, Dramas & Comedies.
Most of the content is added in the month of December on Netflix.
Results from ML models:

KMeans Clustering :
Elbow Method ---> K values is 2.
Silhouette Score ---> When the K value is 2, silhouette score is highest ,i.e., 0.42.
Hierarchical Clustering :
Dendogram ---> No. of Clusters = 2.
DBSCAN :
I applied DBSCAN with min_samples = 2.
Challenges faced:

Feature Encoding
Text Preprocessing
Vectorization
Finding Optimal Value of K
github

For further information you can check the google colab file added in the repository.

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - anasmalik081@gmail.com

My LinkedIn profile - Anas Malik

Thankyou for tagging along to the end.
