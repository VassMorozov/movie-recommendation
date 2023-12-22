# Movie Recommendation System using TMDb Data

The Jupyter Notebook included in this repository runs exploratory data analysis and develops a content based recommendation system for 4803 movies. These movies and their data are made available on Kaggle via The Movie Database (TMDb). The data is linked below:

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?rvi=1

No user data is included as part of this dataset so the scope of the recommendation system is limited to information connecting different movie titles, such as genre, director and crucially, the overview of the movie. As no user data is available, the notebook includes commentary on the dropping of fields which are irrelevant to the content and focus on user input (such as ratings or vote count).

An example of 10 recommendations for Pirates of the Caribbean can be seen below:
![image](https://github.com/VassMorozov/movie-recommendation/assets/28609388/fff5fab0-5dea-4760-8ddc-ec519d38dde6)

Next steps for this recommendation system can include (but not limited to):
* Accessing user data including what they watched or rated.
* Extracting more content based information: fields like cast were explored but deemed to granular at this stage to include.
* Exploring alternative content based recommendation system methodologies, including deep learning and clustering.
