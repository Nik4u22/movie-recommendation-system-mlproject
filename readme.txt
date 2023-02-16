@author: Nikhil Jagnade
@date: 15 Feb, 2023

Recommender System
A recommender system, or a recommendation system (sometimes replacing 'system' with a synonym such as platform or engine), is a subclass of information filtering system that provide suggestions for items that are most pertinent to a particular user.
Typically, the suggestions refer to various decision-making processes, such as what product to purchase, what music to listen to, or what online news to read.

Three types of recommender system as follows

Personality Based systems

1. Content based: Content-based filtering approaches utilize a series of discrete, pre-tagged characteristics of an item in order to recommend additional items with similar properties. Content-based filtering methods are based on a description of the item and a profile of the user's preferences. These methods are best suited to situations where there is known data on an item (name, location, description, etc.), but not on the user. Content-based recommenders treat recommendation as a user-specific classification problem and learn a classifier for the user's likes and dislikes based on an item's features.

A widely used algorithm is the tf–idf representation (also called vector space representation).[49] The system creates a content-based profile of users based on a weighted vector of item features. machine learning techniques such as Bayesian Classifiers, cluster analysis, decision trees, and artificial neural networks in order to estimate the probability that the user is going to like the item

2. Collaborative filtering: Collaborative filtering approaches build a model from a user's past behavior (items previously purchased or selected and/or numerical ratings given to those items) as well as similar decisions made by other users. Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items. Eg. amazon.com

Models used are as follows
A) Matrix factorisation
B) k-nearest neighbour and the Pearson correlation

Collaborative filtering approaches often suffer from three problems: cold start, scalability, and sparsity.

Cold start: For a new user or item, there isn't enough data to make accurate recommendations. Note: one commonly implemented solution to this problem is the Multi-armed bandit algorithm.

Scalability: There are millions of users and products in many of the environments in which these systems make recommendations. Thus, a large amount of computation power is often necessary to calculate recommendations.

Sparsity: The number of items sold on major e-commerce sites is extremely large. The most active users will only have rated a small subset of the overall database. Thus, even the most popular items have very few ratings.

3. Hybrid approach: Hybrid approaches can be implemented in several ways: by making content-based and collaborative-based predictions separately and then combining them; by adding content-based capabilities to a collaborative-based approach (and vice versa); or by unifying the approaches into one model (see[33] for a complete review of recommender systems). Eg. Netflix

Some hybridization techniques include:

Weighted: Combining the score of different recommendation components numerically.
Switching: Choosing among recommendation components and applying the selected one.

Mixed: Recommendations from different recommenders are presented together to give the recommendation.
Feature Combination: Features derived from different knowledge sources are combined together and given to a single recommendation algorithm.[54]

Feature Augmentation: Computing a feature or set of features, which is then part of the input to the next technique.[54]

Cascade: Recommenders are given strict priority, with the lower priority ones breaking ties in the scoring of the higher ones.

Meta-level: One recommendation technique is applied and produces some sort of model, which is then the input used by the next technique.[55]

Knowledge based systems

Project Name: Movie recommender system
Recommender system type: content based recommender system

Project FLow
1. Data scrapping
2. Preprocessing
3. Model building
4. Website development
5. Deployment

1. Data Scrapping

Dataset link - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

