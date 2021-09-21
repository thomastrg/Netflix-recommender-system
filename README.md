# Netflix recommender system


<br> 
<p align="center">
  <img src="https://logos-marques.com/wp-content/uploads/2021/03/Netflix-logo.png" width=700" />
</p>

<br>

## Context 
Have you ever wondered how Netflix recommends movies or TV shows ? Perhaps you have noticed similarities between movies recommended ... All of these recommendations are made possible thanks to recommender systems. It predicts movie that are set to attract the users based on the similarities of the chosen movie and the movies of the dataset. 
                                                                                             
Recommender systems help to personalize a platform and help the user find something they like. The easiest and simplest way to do this is to recommend the most popular items. However, to really enhance the user experience through personalized recommendations, we need dedicated recommender systems.

There are 2 types of Recommender systems :
<li> A) Content-Based Movie Recommendation Systems
Content-based methods are based on the similarity of movie attributes. Using this type of recommender system, if a user watches one movie, similar movies are recommended. For example, if a user watches a comedy movie starring Adam Sandler, the system will recommend them movies in the same genre or starring the same actor, or both. With this in mind, the input for building a content-based recommender system is movie attributes. This is the type of recommendation system that we'll see in this repositery.
<li> B) Collaborative Filtering Movie Recommendation Systems
With collaborative filtering, the system is based on past interactions between users and movies. With this in mind, the input for a collaborative filtering system is made up of past data of user interactions with the movies they watch.
For example, if user A watches M1, M2, and M3, and user B watches M1, M3, M4, we recommend M1 and M3 to a similar user C. You can see how this looks in the figure below for clearer reference.

## The dataset
The dataset is the datset of the Netflix Prize competition 2019.
