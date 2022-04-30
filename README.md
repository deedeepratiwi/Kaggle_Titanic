# Titanic - Machine Learning from Disaster

### About the Challenge

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

Dataset: [Link](https://www.kaggle.com/competitions/titanic/data)

## Step by Step

**Exploratory Data Analysis**
* Filling missing values
* Data visualization

**Feature Engineering**
* Turn continuous numerical columns into categorical columns
* Binnings
* Create dummies

**Feature Selection**
* Use sklearn RFECV for feature selection

**Model Selection**
* Use GridSearch CV for three models: Logistic Regression, K-Nearest Neighbors, and Random Forest

**Model Training**
* Train model using the best model and selected features

For this competition, this solution got accuracy score of 0.77272 on Kaggle leaderboard.
