# Project3 : Recommendation Systems with IBM Watson Studio Data.
# Introduction
This project, takes practices on  the recommendation systems. We deal with the real data from IBM Watson Studio to craft pertinent article recommendations.

# Tools & Technologies
Language: Python 3.9.7
Libraries:
NumPy
Pandas
Matplotlib
Seaborn
# Key Insights from Data Exploration
in the project, the data was explored to understand the number of users, articles, and details about the interactions that occur between them.

The dataset boasts 5148 distinct users and encapsulates 45,993 user-article interactions.
On average, a user interacts with about 9 articles. Yet, the median is lower, showing that 50% of users engage with just 3 articles or fewer.
Of the 1051 articles available, 714 have garnered at least one interaction.
#  Recommendation Techniques
##          1. Rank-Based Recommendations
Approach: Sort articles by their popularity, derived from user interactions, and pick the top 'n' articles as recommendations.

##          2. User-User Collaborative Filtering
Approach:

Construct a user-item matrix.
Identify similar users through dot product calculations.
Recommend unread articles that similar users have engaged with.


##          3. Matrix Factorization (SVD)
Approach: Use Singular Value Decomposition (SVD) to make predictions.

Testing: The method can be evaluated offline using a train-test data split. Note that due to the 'Cold Start Problem', this method is applicable only for users available in both train and test datasets.

# Conclusion
Through this project, we explored multiple methodologies, each with its unique strengths, to provide relevant and personalized article recommendations to users.

# Future work
Explore the other recommondation system.
