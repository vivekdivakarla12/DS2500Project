# DS2500Project
DS2500 Project - Applying WAR to the NBA

In basketball, the goal of a team is to win games. As analytics have evolved, data scientists have started to heavily influence the sports world, with managers attempting to use data to improve teams. Wins Above Replacement (WAR) is a statistic that originates from baseball, with a goal to measure how much better a player is than an average replacement player would be. This metric aims to encompass all of the contributions a player has to a team, and thus is a very complex formula. The sabermetric community has spent years refining the formula for the baseball world. However, the translation to the basketball world has not exactly happened. There are a few different WAR metrics, but they are very volume based, meaning the league’s stars who take a lot of shots per game will be at the top of the list, and their efficiency is not heavily factored. Tying back to the first two sentences, we wanted to create our own Wins Above Replacement metric incorporating efficiency, with the goal of trying to optimize a team’s assets/salary cap to create the best team they possibly can. After creating Efficiency WAR, we decided to model a Volume WAR that used popular NBA counting stats as opposed to efficiency. Finally, we combined the two WAR’s with salary to understand the league’s most undervalued and overvalued players. Below, you will find how we created these WAR statistics in addition to our analysis once they were created.
