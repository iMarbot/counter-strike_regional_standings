### Roster Details<br />
Team Name: Team Aether<br />
Roster: Drew, Frost, Lethality, LUKE4k, SolGoat<br />
Global Rank: [502](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [111]( ../standings_americas.md)<br />
<br />
Final Rank Value:  513.7<br />
<br />
Final Rank Value (513.7) = Starting Rank Value (502.9) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.9
- 400 + ( ( 0.052 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 502.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     5174 | 2024-10-12 | FLUFFY AIMERS              | L   | 0.267      | -            | -                | -                | -         |    -1.44 | Drew, Frost, Lethality, LUKE4k, SolGoat |
|           10 |     5176 | 2024-10-12 | Supernova Comets           | W   | 0.267      | 0.262        | 0.011 (0.001)    | 0.220 (0.015)    | 0 (0.000) |     6.07 | Drew, Frost, Lethality, LUKE4k, SolGoat |
|            9 |     5741 | 2024-10-02 | Nouns Esports              | L   | 0.202      | -            | -                | -                | -         |    -1.40 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            8 |     6090 | 2024-09-27 | Party Astronauts           | L   | 0.168      | -            | -                | -                | -         |    -0.98 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            7 |     6171 | 2024-09-26 | Not Mythic                 | W   | 0.161      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     2.31 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            6 |     6359 | 2024-09-24 | Homyno                     | W   | 0.147      | 0.371        | 0.008 (0.000)    | 0.192 (0.010)    | 0 (0.000) |     3.50 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            5 |     6544 | 2024-09-21 | Dangerous (Ukrainian team) | W   | 0.128      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.44 | AtomiK, Frost, Izik, LUKE4k, SolGoat    |
|            4 |     6601 | 2024-09-20 | Kinship                    | L   | 0.122      | -            | -                | -                | -         |    -2.06 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            3 |     6603 | 2024-09-20 | LAG Gaming                 | W   | 0.122      | 0.143        | 0.001 (0.000)    | 0.027 (0.000)    | 0 (0.000) |     2.52 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            2 |     6609 | 2024-09-20 | Mach 5                     | W   | 0.122      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.38 | AtomiK, Drew, Frost, LUKE4k, SolGoat    |
|            1 |     7158 | 2024-09-11 | Akimbo Esports             | L   | 0.062      | -            | -                | -                | -         |    -0.59 | AtomiK, Frost, LUKE4k, RiFT, SolGoat    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
