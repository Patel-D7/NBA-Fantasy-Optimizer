# NBA-Fantasy-Optimizer

__Objective__

For this project, we are developing an optimization model that takes all 450 current players in the NBA and builds the best fantasy team possible in order to guarantee success in a fantasy basketball league. This model considers each player’s fantasy score, position, salary, team, and more to find whether or not a respective player is the right fit. Additionally, the model also considers which players are best suited to come off the bench as “backup”, when certain players are injured or are not playing.
__Constraints__

•	The biggest constraint would be the salary cap. A lot of the best players in the league make quite a bit of money, no team can afford 5 max-contract players.
•	Second constraint would be position. We can only have 2 guards, 2 forwards, and 1 center. So at times, we would have to choose one player over the other, which is something our model would have to handle.
We collected our data - in-game statistics, player salary, position, etc. - on all NBA players in the 2019-2020 season from Hashtag Basketball and Basketball-Reference. Both websites refresh and update their data 

__Advanced Optimizer__

The **Advanced Statistics Optimizer** uses a new dataset that builds on the existing one above, adding the following statistics:
- Assists
- Attempted Field Goals
- Attempted Free Throws
- Attempted Three-Point Field Goals
- Blocks
- Defensive Rebounds
- Offensive Rebounds
- Games Played
- Games Started
- Made Field Goals
- Made Free Throws
- Made Three Point Field Goals
- Minutes Played
- Points
- Fouls <br>
<br>

To obtain and assign weights associated to each of the statistics, we use a <b>Linear Regression Model</b> to determine the weights of each feature.
