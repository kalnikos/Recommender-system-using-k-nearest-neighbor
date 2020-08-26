# Recommender system using k-nearest neighbor technique

In this project I tried to create some tools in order to help a general manager to build a basketball team with the features that he needs. I split the project in two parts, at the first part I created a recommendation model which present players to the manager based on the features that he defined  and at the second part, I tried to build a prediction model aiming to predict the position of the player based on specific features.

I created the recommendation model using the K nearest neighbour technique. I started with the hypothesis that us a general manager of the Milwaukee Bucks I was looking for a good fit for Antentokoumbo in order to win the championship. Giannis has a very strong skill package but needs more players to support him. 

Giannis needs a player that can create for him and also utilizes his creative ability. So I am looking for a young ambitious players with offensive skills.

I started my searching with these features: age=27, 3P%=0.40, 3PA=6, 2P%=0.45, AST=6, TOV=3 and I specify the number of neighbors as 3. The model recommend three players and one of them is currently Giannis teammate. Despite that Middleton is  a nice shooting guard I tried to make my search more specific in order to pick a point guard.

From the column position I convert the categorical variables into dummy variables and also in my second target group I add the salary feature. The recommendation results were interesting, the first player was Malcom Brogdon former Giannis teammate that Milwaukee chose to trade, the second one was Terry Rozier a player with potential with great playoff series against Bucks and the third player wasn’t a point guard.   

