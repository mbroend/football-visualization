# English Premier League Exploration
## by Mathias Brønd Sørensen


## Dataset

The dataset is a SQLite database describing football matches, players and teams from Europe and is obtained from [Kaggle](https://www.kaggle.com/hugomathien/soccer).

In order to limit the dataset and make it tidy, the following operations were performed:
1. Joining relevant tables to denormalize data
2. Limiting rows to only be matches in the English Premier League
3. Limit number of features by removing excessive ones
4. Added catagorical variable to indicate result
5. Ordered catagorical variable season as it is ordinal

## Summary of Findings
The most common match result across all stages and seasons in the 1-1.
All of the seasons in the available dataset seem to have the same characteristics in terms of home and away goals. The only exception seem to be the home teams in season 09/10 with a higher median of goals. There's some variaence in the stages of the season as with respect to the goals scored, with the away team seemingly having a hard time scoring in the middle of the season. 

The betting companies seem to very much agree on the odds on the likely side of the results - the higher the odds, the more variability across the different vendors.


## Key Insights for Presentation

The key findings were definately the homogenity across seasons in terms of goals - there doesn't seem to be much difference to the league from season to season. Plots are the same as in the exploratory part, just cleaned up a bit.