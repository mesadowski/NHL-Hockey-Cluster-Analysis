# NHL-Hockey-Cluster-Analysis

The idea of this analysis is to use NHL player and team performance data to determine the characteristics of a high-performing NHL team, i.e., what kind of players do they have? With a model like this, we can look at the roster of a team, and determine their chances of going deep into the playoffs, and we can also make suggestions about what kinds of player moves they must make in order to become a great team.

I decided to use regular season player statistics, because this ensures we have a lot of data on every player in the league. However, to determine if a team is a high-performer, I used playoff performance, not regular season performance. It might be worth trying to use regular season data, but playoff performance is the ultimate test, and arguably the nature of the game changes in the playoffs.

My approach was as follows:

Use clustering to group similar players. I used three different segments of players--forwards, defenders, and goalies, and created clusters in each
Use those clusters to characterize the 32 NHL teams for various seasons between 2008/9 and 2021/22. How many players from each cluster do the teams have?
Then use logistic regression to see if we can find relationships between teams having certain mixes of players, and going "deep" in the playoffs. e.g., What's the relationship between having a forward from cluster 3 and going deep in the playoffs? If we know that, we know how important it is to have such players on your roster.
