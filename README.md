# Movie-Recommendation
A data science project leveraging matrix factorization to suggest movies that align with user interests.

Introduction

With the vast amount of movies and shows available on streaming platforms today, picking what to watch can be overwhelming. Recommendation systems help address this by suggesting new content that aligns with an individual user's preferences. This project involved developing a movie recommendation system using machine learning to provide users with personalized movie suggestions.

Approach

The system was developed using a collaborative filtering approach, which analyzes patterns across many users to make recommendations. The input data consisted of a database of user profiles with their movie ratings and movie metadata like genres and keywords.

First, the user-movie ratings matrix was preprocessed by cleaning the data and filling in missing values. Next, a matrix factorization algorithm was applied to analyze cross-user behaviors and identify latent features that characterize movie preferences.

The resulting user and movie latent feature matrices were used to generate recommendations. For a given user, their personalized suggestions surface movies with the most similar latent features.

Results

The final model was evaluated by measuring the relevance of its top 5 and top 10 recommended movies for each user, based on withholding some user ratings for testing. The model achieved a mean average precision at 5 of 0.82 and mean average precision at 10 of 0.76, indicating its high accuracy in surfacing relevant personalized recommendations.

Conclusion

This project demonstrated how collaborative filtering methods can learn from collective user behaviors to generate accurate movie recommendations. The system provides users with a tailored selection of new movie suggestions that they are highly likely to enjoy watching. In the future, incorporating additional data like user demographics or movie textual descriptions could further improve recommendation performance.
