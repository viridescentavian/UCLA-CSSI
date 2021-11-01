# UCLA-CSSI

Over the three weeks of UCLA CSSI’s CS97 class, we learned the basics of data science through the implementation of various models on real-world statistics and datasets. A variety of concepts such as prediction, classification, and clustering were demonstrated in vivid examples inside Google Colab notebooks. In order to demonstrate our overall skills developed in this course, we are choosing the topic of data clustering as the central focus of our final project.

Cluster analysis is the grouping of numerous data points into clusters, with the goal of maximizing intra-class similarity while minimizing inter-class similarity. Our project utilizes this principle in a recommender system for Steam games, such that games with similar tags will be recommended according to user preferences.

In this report, we review our two different models for our recommender system. The first model implements the K-Nearest Neighbors (KNN) algorithm, which calculates the Euclidean distances between data points and makes predictions based on the neighboring data points that are the shortest distances away. Our second model uses the concept of cosine similarity, in which similarity is measured by the cosine of the angle between two vectors. This model does not rely on Euclidean distances, which allows it to be an effective complement to our first model.
