# Unsupervised_ML_Clustering
*Python*
<br>
## Project 
Focused on unsupervised Machine Learning, where I used K-Means clustering to cluster football players based on data from FIFA 2015 (the game).

Dataset from: https://www.kaggle.com/datasets/stefanoleone992/fifa-20-complete-player-dataset (30th of November 2022)

## Description of the approach in the code
Starts of with loading necessary libraries and data. Follows by an exploratory analysis of the data to get to know it, but also identify potential problems. After that, the data is cleaned.

The analysis starts of with an exploratory clustering where I tried different techniques with different variables, and ended up finding a model that was accurate (K-Means model with 5 clusters). This clustering used 6 variables; pace, shooting, passing, dribbling, physic, defending.

### The different clusters where named:
- Finesse Offense
- Pure Goal Stoppers
- Balanced Defender
- Goal Scorer
- Middle-Man

### Key differences between the clusters:
- Finesse Offense and Goal Scorer:
    - Goal Scorers are more physical ands have better shooting, but are lacking in passing, dribbling and pace compared to finesse offence
- Pure Goal Stopper and Balanced Defender:
    - Pure Goal Stopper have the highest scores in defending, however the balanced defender have higher score in all other columns
- Middle-Man
    - Players that are great at passing and dribbling, but also have decent score all around. The are most likely playing in the midfield and are great at playmaking, but also decent at finishing and defending.

**In the attached files the code can be found, as well as a google drive used to present the project**
