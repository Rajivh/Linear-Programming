# Linear Programming (Optimization problem) with Python

Objective: Buy 11 players for creating a Club football team from scratch from a pool of 50 available players so that the overall capability (each player has an individual score under the column overall in the Data associated with him) of the team is maximized.

Such that (constraints)
	Total budget for buying the 11 players is less than $950M 
	There is at least one player with GK – Diving, Handling, Kicking, Positioning, Reflexes more than 85. (GK stands for goal keeper)
	There are at least four players with Interception and Marking more than 80.
	There are at least two players with Sliding Tackle more than 75.
	There are at least four players with standing tackle more than 83.
	There are at least six players with Short passing more than 80.
	There are at least four players with Long passing more than 80.
	There are at least three players with Reaction more than 85.
	There are at least three players with jumping more than 75.
	There is at least one player with finishing more than 90.
	There are at least three players with Acceleration more than 80.
	There are at least four players with Ball Control more than 80.
	There are at least two players with crossing more than 85.
	There are at least two players with Dribbling more than 80.
	There are at least five players with Penalties more than 75.
	There is at least one player with Free Kick more than 87.

Decision Variable: 
Xj – whether player j is selected or not (from the pool of 50 players)

Parameters:
Overall Rating, Value, the various skills mentioned in the constraints above

Objective Function – Maximize 
∑_(j=1)^50▒〖(Xj * Rj)〗

Where Xj is 1 or 0 depending on whether player j is selected or not and Rj is the rating of the player j.


Dataset: https://www.kaggle.com/thec03u5/fifa-18-demo-player-dataset\

References: http://benalexkeen.com/linear-programming-with-python-and-pulp-part-6/
For using PuLp for solving linear optimization problems
