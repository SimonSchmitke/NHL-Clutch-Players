# NHL-Clutch-Players
Graphs of the most clutch (most points in the last 5 minutes of the third period or overtime) players in the NHL since 2011. The SQL and graphs were made in R.

## Clutch Goals Scored By A Player
![Points Graph](https://github.com/SimonSchmitke/NHL-Clutch-Players/raw/master/pointsGraph.png "Points Graph")

Using the data provided by Kaggle [here](https://www.kaggle.com/martinellis/nhl-game-data) and R studio, the above graph was made. Using SQL and some simple if/else statements, I generated the graph using ggplot to display the players who have the most goals in the last 5 minutes of the third period since 2011. Each player has his goals separated into 4 "types of goals" - reducing a deficit, game tying, go ahead, or advancing a lead. 
### Points of interest
- There are 3 Boston Bruins (Bergeron, Krejci and Marchand) who have made the list.
- Ovechkin has the most goals overall
- Staal has the most game tying goals


## Clutch Goals Scored By A Player - Only Go Ahead and Game Tying
![Points Graph](https://github.com/SimonSchmitke/NHL-Clutch-Players/raw/master/onlyImportantGoals.png "Points Graph")
This graph is the same as the one above. However, two of the types of goals has been removed as "game tying" and "go ahead" were deemed to be the most important type of clutch goals for a player to score.
### Points of interest
- Ovechkin has the most go ahead goals
- Kopitar has the most combined go ahead and game tying goals


## Clutch Goals Scored By A Player With OT, Separated By Playoff vs Regular Season
![Points Graph](https://github.com/SimonSchmitke/NHL-Clutch-Players/raw/master/pointsGraphOT.png "Points Graph with OT")

This graph displays goals scored in the last 5 minutes of the 3rd period or OTm separated by playoff and regular season games. Each player has his goals separated into 4 "types of goals" but only 2 are shown in this graph - game tying and go ahead. These are the only categories shown as they were deemed the "most important to show".
### Points of interest
- Kane has the most playoff clutch goals
