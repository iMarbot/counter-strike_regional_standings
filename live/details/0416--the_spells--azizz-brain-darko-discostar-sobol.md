### Roster Details<br />
Team Name: THE SPELLS<br />
Roster: azizz, Brain, darko, discoStar, Sobol<br />
Global Rank: [416](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [257]( ../standings_europe.md)<br />
<br />
Final Rank Value:  584.0<br />
<br />
Final Rank Value (584.0) = Starting Rank Value (536.5) + Head To Head Adjustments (47.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.5
- 400 + ( ( 0.068 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 536.5


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
|           14 |     3076 | 2024-11-20 | GTZ.ESPORTS                               | L   | 0.527      | -            | -                | -                | -         |    -0.65 | azizz, Brain, darko, discoStar, Sobol |
|           13 |     3100 | 2024-11-20 | Underrated                                | L   | 0.527      | -            | -                | -                | -         |    -6.76 | azizz, Brain, darko, discoStar, Sobol |
|           12 |     3112 | 2024-11-20 | GamerLegion Academy                       | W   | 0.526      | 0.372        | 0.000 (0.000)    | 0.223 (0.044)    | 0 (0.000) |     7.99 | azizz, Brain, darko, discoStar, Sobol |
|           11 |     3496 | 2024-11-13 | Infinite Gaming                           | W   | 0.480      | 0.372        | 0.000 (0.000)    | 0.059 (0.011)    | 0 (0.000) |     6.30 | azizz, Brain, darko, discoStar, Sobol |
|           10 |     3590 | 2024-11-11 | FORZE Reload                              | W   | 0.467      | 0.372        | 0.026 (0.005)    | 0.559 (0.097)    | 0 (0.000) |    12.22 | azizz, Brain, darko, discoStar, Sobol |
|            9 |     3984 | 2024-11-04 | Passion UA                                | L   | 0.420      | -            | -                | -                | -         |    -0.99 | azizz, Brain, darko, discoStar, Sobol |
|            8 |     4370 | 2024-10-29 | ADEPTS                                    | W   | 0.380      | 0.372        | 0.000 (0.000)    | 0.292 (0.041)    | 0 (0.000) |     7.81 | azizz, Brain, darko, discoStar, Sobol |
|            7 |     4411 | 2024-10-28 | Kay Team                                  | W   | 0.374      | 0.372        | 0.000 (0.000)    | 0.050 (0.007)    | 0 (0.000) |     5.18 | azizz, Brain, darko, discoStar, Sobol |
|            6 |     4662 | 2024-10-23 | PCIFIC Espor                              | L   | 0.339      | -            | -                | -                | -         |    -2.47 | azizz, Brain, darko, discoStar, Sobol |
|            5 |     4672 | 2024-10-23 | TEAM NEXT LEVEL                           | W   | 0.339      | 0.372        | 0.003 (0.000)    | 0.465 (0.059)    | 0 (0.000) |     7.35 | azizz, Brain, darko, discoStar, Sobol |
|            4 |     5001 | 2024-10-16 | HOTU                                      | W   | 0.292      | 0.372        | 0.003 (0.000)    | 0.777 (0.085)    | 0 (0.000) |     6.69 | azizz, Brain, darko, discoStar, Sobol |
|            3 |     5061 | 2024-10-15 | Copenhagen Wolves (American organization) | L   | 0.286      | -            | -                | -                | -         |    -1.34 | azizz, Brain, darko, discoStar, Sobol |
|            2 |     5105 | 2024-10-14 | QUAZAR                                    | W   | 0.279      | 0.372        | 0.005 (0.001)    | 0.257 (0.027)    | 0 (0.000) |     6.37 | azizz, Brain, darko, discoStar, Sobol |
|            1 |     5334 | 2024-10-09 | ALASKA                                    | L   | 0.246      | -            | -                | -                | -         |    -0.27 | azizz, Brain, darko, discoStar, Sobol |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
