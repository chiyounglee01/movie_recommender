# Building a Movie Recommender Using the Movie Lens Dataset

**In this project, we will explore two types of recommender systems: 1) collaborative filtering, and 2) content-based filtering. We will build our own recommendation system using the [MovieLens](https://movielens.org/home) dataset in Python.**

### What is MovieLens?

MovieLens is a recommender system that was developed by GroupLens, a computer science research lab at the University of Minnesota. It recommends movies to its users based on their movie ratings. It is also a dataset that is widely used in research and teaching contexts.

**This project is based on the following tutorial from Jill Cates (Data Scientist, Shopify). [tutorial link](https://www.youtube.com/watch?v=XfAe-HLysOM)**

**Project outline - This recommender build is broken down into 7 steps**

1. Import Libraries.
2. Load the data.
3. Exploratory data analysis.
4. Data pre-processing.
5. Collaborative filtering using K-Nearest Neighbors.
6. Handling the cold start problem with content-based filtering
7. Dimensionality reduction with matrix factorization

### Results for Collaborative Filtering Model

**Below are the Top 10 movies recommended for users who liked "Toy Story" using the Collaborative Filtering model.**

1. Toy Story 2 (1999)
2. Mission: Impossible (1996)
3. Independence Day (a.k.a. ID4) (1996)
4. Bug's Life, A (1998)
5. Nutty Professor, The (1996)
6. Willy Wonka & the Chocolate Factory (1971)
7. Babe (1995)
8. Groundhog Day (1993)
9. Mask, The (1994)
10. Back to the Future

The recommendation system seems to be working well as it has recommended family friendly movies from the 90s. These recommendations are based solely on user-item ratings.

### Results for Collaborative Filtering Model

**Below are the Top 10 movies recommended for users who liked "Toy Story" using the Content Filtering model.**

1. Antz (1998)
2. Toy Story 2 (1999)
3. Adventures of Rocky and Bullwinkle, The (2000)
4. Emperor's New Groove, The (2000)
5. Monsters, Inc. (2001)
6. Wild, The (2006)
7. Shrek the Third (2007)
8. Tale of Despereaux, The (2008)
9. Asterix and the Vikings (Astérix et les Viking...
10. Turbo (2013)

The recommendation system seems to be working as the movies recommended are family friendly animation films.

### Conclusion

Both the collaborative filtering and content filtering models were decent at recommending 10 most similar movies of a single movie. However, a drawback of this model and data is that there is no concrete way to measure evaluation metrics. If this was used in the real world, a good way to measure the effectiveness of this model would be to do an A/B test to see if the model was effective in increasing user viewing time or user engagement. However, due to the limitations of this project, it was not possible to do such a test.



