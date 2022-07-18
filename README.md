<p align="center"> 
  <img src="images/netflix-logo-png-2574.png" alt="netflix-logo-png-2574.png" width="80px" height="80px">
</p>
<h1 align="center"> 📌 NETFLIX MOVIES & TV SHOWS CLUSTERING 📌 </h1>

<p align="center"> 
<img src="images/netflix-netflix-logo.gif" alt="Animated gif" height="300px">
</p>

**TA-DUMMM... !!** 

This iconic intro sound has got so much popularity in the recent years due to the unique set of shows and series Netflix bring to its platform. Netflix is essentially a storehouse of content, including movies, documentaries, and television series, both pre-existing and its own. For a flat monthly fee, subscribers can consume any program at any time on whatever device they prefer.

Netflix has become dominant company in the on-demand media industry, with 167 million paying subscribers around the world. By creating compelling original programming, analyzing its user data to serve subscribers better, and above all by letting people consume content in the ways they prefer. Netflix disrupted the television industry and forced cable companies to change the way they do business.

<h2>📄 Introduction</h2>
Netflix initially started as a DVD rental service in 1998. It mostly relied on a third-party postal service to deliver its DVDs to the users. This resulted in heavy losses which they soon mitigated with the introduction of their online streaming service in 2007. In order to make this happen, Netflix invested in a lot of algorithms to provide a flawless movie experience to its users. One of such algorithms is the recommendation system that is used by Netflix to provide suggestions to the users. A recommendation system understands the needs of the users and provides suggestions of the various cinematographic products.

The recommendation system searches for movies that are similar to the ones you have watched or have liked previously. It makes easier for the user to choose better options from a wide variety of movie products. With over 139 million paid subscribers (total viewer pool ~300 million) across 190 countries, 15,400 titles across its regional libraries and 112 Emmy Award Nominations in 2018 — Netflix is the world’s leading Internet television network and the most-valued largest streaming service in the world. The amazing digital success story of Netflix is incomplete without the mention of its recommender systems that focus on personalization. There are several methods to create a list of recommendations according to your preferences. You can use Collaborative filtering and Content-based Filtering for recommendation.

<h2>🎯 Objective</h2>
Netflix Recommender recommends Netflix movies and TV shows based on a user's favorite movie or TV show. It uses a Natural Language Processing (NLP) model and a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions. 
The motivation behind this project is to develop a deeper understanding of recommender systems and create a model that can perform Clustering on comparable material by matching text-based attributes. Specifically, thinking about how Netflix create algorithms to tailor content based on user interests and behavior.

<h2>💾 Data</h2>
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

The following are the columns in the dataset:

* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show 
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release Year of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description

<h2>🛠️ Tools and Technologies Used</h2>
The whole project was done using python, in Google Collaboratory. 

Following libraries were used for analyzing the data and visualizing it and to build the model to predict the Netflix clustering

* Pandas: Extensively used to load and wrangle with the dataset.
* Matplotlib: Used for visualization.
* Seaborn: Used for visualization. 
* Nltk: It is a toolkit build for working with NLP.
* Datetime: Used for analyzing the date variable.
* Warnings: For filtering and ignoring the warnings.
* NumPy: For some math operations in predictions.
* Wordcloud: Visual representation of text data.
* Sklearn: For the purpose of analysis and prediction.

<h2>🪜 Steps Involved</h2>

* Handling missing values 
* Duplicate Values Treatment
* Natural Language Processing (NLP) Model
* Exploratory Data Analysis
* Hypothesis from the data visualized
* Tfidf vectorization
* Data Preprocessing
* Clustering
