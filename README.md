# Recommendation-Engines-with-IBM

## Introduction
In this project, the interactions that users have with articles on the IBM Watson Studio platform is analyzed, and a few recommendation systems are build to recommend to users about new articles they might like. 

## Types of Recommendation Systems
- Rank Based Recommendations: recommending the most popular articles simply based on the most interactions
- User-User Based Collaborative Filtering: finding users that are similar in terms of the items they have interacted with and built a user-item interaction matrix
- Content Based Recommendations: using NLP Doc2Vec model with gensim to recommend articles that are most similar to what user has interacted with
- Matrix Factorization:  using the user-item interactions, a matrix decomposition is built. An optimized number of latent features is chosen based on the prediction accuracy on the test data.

# Requirement
python
pandas 
numpy
matplotlib
project_tests
gensim
progressbar 
nltk - nltk.download(['stopwords', 'punkt', 'averaged_perceptron_tagger', 'wordnet'])
