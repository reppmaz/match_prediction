# About the Dataset

This dataset captures interactions from a speed-dating experiment conducted by Columbia University between 2002 and 2004. Over 21 sessions, young adults primarily seeking to meet people of the opposite sex participated, and various data points about these interactions were collected. We used the dataset from kaggle: https://www.kaggle.com/datasets/mexwell/speed-dating/data

Dating today offers endless opportunities, but finding the right match has become a challenge. Over the past few decades, dating options have expanded from traditional face-to-face encounters to online platforms, speed dating, and now even online speed dating. This dataset provides insights into some early experiments with structured speed dating, shedding light on how different characteristics influence mutual interest and attraction.

# Dataset Overview

Each row in the dataset represents a speed-dating interaction and includes the following columns:
Demographics (first five columns): Information such as age, gender, and other attributes that may help in analyzing subgroups.
Decision & Ratings:
dec: A binary decision indicating whether the individual wanted to pursue a match.
Six key characteristics (rated out of ten): Scores for attractiveness, sincerity, intelligence, fun, ambition, and shared interests.
like: An overall rating of the individual.
prob: The rater’s estimation of whether their interest would be reciprocated.
Met before: A binary column indicating if the pair had previously met before the speed date (lower values represent prior acquaintance).

# Methodology
For our analysis, we approached this dataset as a mini machine learning project, testing various classification models to predict match outcomes based on the participants’ ratings and characteristics. We applied several algorithms, including:

K-Nearest Neighbors (KNN)
Logistic Regression
Decision Tree
Random Forest
After evaluating the models, Random Forest achieved the best accuracy score, making it the most effective algorithm for this dataset.

Presentation link: https://docs.google.com/presentation/d/1tCzR6JT7edsRJCoy4dllUVqCnfrIybTGl_HRslgBe-Y/edit#slide=id.g310507e82a7_0_1032
