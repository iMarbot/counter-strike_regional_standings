### Roster Details<br />
Team Name: Wu-Tang Clan<br />
Roster: Maze, Q-Q, SeBreeZe, shushan, tvs<br />
Global Rank: [496](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [307]( ../standings_europe.md)<br />
<br />
Final Rank Value:  518.8<br />
<br />
Final Rank Value (518.8) = Starting Rank Value (504.0) + Head To Head Adjustments (14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 504.0
- 400 + ( ( 0.052 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 504.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     4398 | 2024-10-29 | OG                    | L   | 0.370      | -            | -                | -                | -         |    -1.08 | Maze, Q-Q, SeBreeZe, shushan, tvs |
|            6 |     4455 | 2024-10-28 | Zero Tenacity         | L   | 0.363      | -            | -                | -                | -         |    -1.47 | Maze, Q-Q, SeBreeZe, shushan, tvs |
|            5 |     4754 | 2024-10-21 | ENJOY (Russian team)  | W   | 0.318      | 0.143        | 0.000 (0.000)    | 0.029 (0.001)    | 0 (0.000) |     4.92 | Maze, Q-Q, SeBreeZe, shushan, tvs |
|            4 |     4781 | 2024-10-20 | RUSH B (Russian team) | W   | 0.312      | 0.143        | 0.028 (0.001)    | 0.915 (0.041)    | 0 (0.000) |     8.80 | Maze, Q-Q, SeBreeZe, shushan, tvs |
|            3 |     4787 | 2024-10-20 | Taradzuri             | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.50 | Maze, Q-Q, SeBreeZe, shushan, tvs |
|            2 |     7508 | 2024-09-06 | Partizan Esports      | L   | 0.018      | -            | -                | -                | -         |    -0.02 | Maze, Q-Q, superflik, tvs, xicoz  |
|            1 |     7526 | 2024-09-06 | INation               | W   | 0.018      | 0.221        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.20 | Maze, Q-Q, superflik, tvs, xicoz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
