### Roster Details<br />
Team Name: THE SPELLS<br />
Roster: azizz, Brain, darko, discoStar, Sobol<br />
Global Rank: [423](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [260]( ../standings_europe.md)<br />
<br />
Final Rank Value:  581.3<br />
<br />
Final Rank Value (581.3) = Starting Rank Value (535.9) + Head To Head Adjustments (45.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 535.9
- 400 + ( ( 0.068 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 535.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3088 | 2024-11-20 | GTZ.ESPORTS                               | L   | 0.519      | -            | -                | -                | -         |    -0.64 | azizz, Brain, darko, discoStar, Sobol |
|           13 |     3112 | 2024-11-20 | Underrated                                | L   | 0.519      | -            | -                | -                | -         |    -6.60 | azizz, Brain, darko, discoStar, Sobol |
|           12 |     3124 | 2024-11-20 | GamerLegion Academy                       | W   | 0.518      | 0.372        | 0.000 (0.000)    | 0.219 (0.042)    | 0 (0.000) |     7.90 | azizz, Brain, darko, discoStar, Sobol |
|           11 |     3508 | 2024-11-13 | Infinite Gaming                           | W   | 0.472      | 0.372        | 0.000 (0.000)    | 0.059 (0.010)    | 0 (0.000) |     6.25 | azizz, Brain, darko, discoStar, Sobol |
|           10 |     3602 | 2024-11-11 | FORZE Reload                              | W   | 0.459      | 0.372        | 0.026 (0.004)    | 0.552 (0.094)    | 0 (0.000) |    12.03 | azizz, Brain, darko, discoStar, Sobol |
|            9 |     3996 | 2024-11-04 | Passion UA                                | L   | 0.412      | -            | -                | -                | -         |    -0.97 | azizz, Brain, darko, discoStar, Sobol |
|            8 |     4382 | 2024-10-29 | ADEPTS                                    | W   | 0.371      | 0.372        | 0.000 (0.000)    | 0.287 (0.040)    | 0 (0.000) |     6.47 | azizz, Brain, darko, discoStar, Sobol |
|            7 |     4423 | 2024-10-28 | Kay Team                                  | W   | 0.365      | 0.372        | 0.000 (0.000)    | 0.049 (0.007)    | 0 (0.000) |     5.08 | azizz, Brain, darko, discoStar, Sobol |
|            6 |     4674 | 2024-10-23 | PCIFIC Espor                              | L   | 0.331      | -            | -                | -                | -         |    -2.41 | azizz, Brain, darko, discoStar, Sobol |
|            5 |     4684 | 2024-10-23 | TEAM NEXT LEVEL                           | W   | 0.331      | 0.372        | 0.003 (0.000)    | 0.464 (0.057)    | 0 (0.000) |     7.18 | azizz, Brain, darko, discoStar, Sobol |
|            4 |     5013 | 2024-10-16 | HOTU                                      | W   | 0.284      | 0.372        | 0.003 (0.000)    | 0.768 (0.081)    | 0 (0.000) |     6.50 | azizz, Brain, darko, discoStar, Sobol |
|            3 |     5073 | 2024-10-15 | Copenhagen Wolves (American organization) | L   | 0.278      | -            | -                | -                | -         |    -1.30 | azizz, Brain, darko, discoStar, Sobol |
|            2 |     5117 | 2024-10-14 | QUAZAR                                    | W   | 0.271      | 0.372        | 0.005 (0.001)    | 0.251 (0.025)    | 0 (0.000) |     6.18 | azizz, Brain, darko, discoStar, Sobol |
|            1 |     5346 | 2024-10-09 | ALASKA                                    | L   | 0.238      | -            | -                | -                | -         |    -0.26 | azizz, Brain, darko, discoStar, Sobol |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
