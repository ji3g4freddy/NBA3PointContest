# NBA Three-Point Contest
(Final Project for IS590PR)

## Team Member(s): 
MingFu Chou, Wenhao Hou, Han Li

# Monte Carlo Simulation Scenario & Purpose:
(be sure to read the instructions given in course Moodle)

Based on the wide open three-point percentage (NBA.com), stamina (2K18), shooting stability (Standard Deviation of 3pt%) ,the chosen location of money balls and strategy of each player, we first present one game simulation result to enable user to understand the game rules and then simulate the score of all the participants in each round and pick players with the top three scores (player numbers may bigger than 3 if three or more get the top three scores simultaneously) to the final round. And then, we simulates the winner. After thousands of simulations, the program concludes the winning rate for each player and print out the best strategy and chosen location of money balls for each player.


## Simulation's variables of uncertainty
List and describe your simulation's variables of uncertainty (where you're using pseudo-random number generation). For each such variable, how did you decide the range and probability distribution to use?  Do you think it's a good representation of reality?

The variable "shoot" is a pseudo-random int number generated from 1 to 100, in this scenario, if the field goal percentage is larger than "shoot", this shoot would score; The variable "runtime" is a pseudo-random number generated from 2 to 4, it represents the time a player needs to run from one spot to the next spot; The variable "shootingtime" is a pseudo-random number which could be generated by different strategies, it represents the shooting time of one shot of one player; The variable "prob" is a pseudo-random int number generated from 1 to 100,
if the one-fire probability is larger than "prob", the player would reach to a on-fire state.

## Hypothesis or hypotheses before running the simulation:
The winning rate of each player may highly depend on his wide open 3 point-field goal and influenced by his performance stability, which is up to the variance of each player's 3 point-field goal. And most of players may choose strategy 3 to get as higher points at money ball location as possible or strategy 4 to achieve a relative a good state at the very start.

## Analytical Summary of your findings: (e.g. Did you adjust the scenario based on previous simulation outcomes?  What are the management decisions one could make from your simulation's output, etc.)
Based on their 3 point shooting behavior of this season, players tend to choose the spot 1 and 2 as the money ball location and number 3,4 as the strategy. Among all the players, Klay Thompson, Kyle Korver and Kevin Love have shown a significant advantage to win the game. Devin Booker have the worst performance and only get 0.7% chance to win the championship.

## Instructions on how to use the program:
Specify the simulation times and run to see the simulation result.

## All Sources Used:

1. NBA official stats website:
http://stats.nba.com/players/shots-closest-defender/?Season=2017-18&SeasonType=Regular%20Season&sort=FG3M&dir=1&CloseDefDistRange=6%2B%20Feet%20-%20Wide%20Open

2. NBA 2k18:
http://www.2kratings.com/
