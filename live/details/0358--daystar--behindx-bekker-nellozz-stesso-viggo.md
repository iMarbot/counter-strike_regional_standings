### Roster Details<br />
Team Name: Daystar<br />
Roster: BehinDx, bekker, nellozz, Stesso, Viggo<br />
Global Rank: [358](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [229]( ../standings_europe.md)<br />
<br />
Final Rank Value:  621.9<br />
<br />
Final Rank Value (621.9) = Starting Rank Value (648.3) + Head To Head Adjustments (-26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.219[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 648.3
- 400 + ( ( 0.124 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 648.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     3102 | 2024-11-20 | Heimo Esports                             | W   | 0.519      | 0.372        | 0.004 (0.001)    | 0.651 (0.126)    | 0 (0.000) |    10.60 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           26 |     3156 | 2024-11-19 | Soul's Heart Esport                       | L   | 0.512      | -            | -                | -                | -         |    -9.35 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           25 |     3201 | 2024-11-18 | Poslednii3ae3d                            | W   | 0.505      | 0.372        | 0.001 (0.000)    | 0.101 (0.019)    | 0 (0.000) |     7.92 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           24 |     3488 | 2024-11-14 | HOTU                                      | L   | 0.476      | -            | -                | -                | -         |    -6.08 | BehinDx, bekker, Speedie, Stesso, Viggo |
|           23 |     3526 | 2024-11-13 | G2 Ares                                   | L   | 0.470      | -            | -                | -                | -         |    -6.23 | BehinDx, mAnGo, Speedie, Stesso, Viggo  |
|           22 |     3595 | 2024-11-11 | Kubix Esports                             | L   | 0.459      | -            | -                | -                | -         |    -2.21 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           21 |     3615 | 2024-11-11 | Mission Possible                          | L   | 0.458      | -            | -                | -                | -         |    -8.86 | BehinDx, bekker, mAnGo, Stesso, Viggo   |
|           20 |     3797 | 2024-11-08 | Natus Vincere Youth                       | W   | 0.439      | 0.278        | 0.000 (0.000)    | 0.024 (0.003)    | 0 (0.000) |     4.19 | bekker, Speedie, Stesso, Tubsy, Viggo   |
|           19 |     3950 | 2024-11-05 | HyperSpirit                               | L   | 0.418      | -            | -                | -                | -         |    -6.23 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           18 |     3995 | 2024-11-04 | GamerLegion Academy                       | L   | 0.412      | -            | -                | -                | -         |    -7.98 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           17 |     4019 | 2024-11-04 | ENTERPRISE Genesis                        | L   | 0.411      | -            | -                | -                | -         |    -6.79 | BehinDx, bekker, Speedie, Stesso, Viggo |
|           16 |     4318 | 2024-10-30 | THE GENTLEMEN ESPORTS                     | L   | 0.378      | -            | -                | -                | -         |    -5.12 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           15 |     4422 | 2024-10-28 | UNiTY esports                             | W   | 0.365      | 0.372        | 0.025 (0.003)    | 0.403 (0.055)    | 0 (0.000) |     8.56 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           14 |     4666 | 2024-10-23 | Underrated                                | W   | 0.332      | 0.372        | 0.002 (0.000)    | 0.268 (0.033)    | 0 (0.000) |     5.75 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           13 |     4740 | 2024-10-21 | GTZ.ESPORTS                               | L   | 0.318      | -            | -                | -                | -         |    -0.45 | BehinDx, bekker, nellozz, Stesso, Viggo |
|           12 |     5020 | 2024-10-16 | XI Esport                                 | L   | 0.284      | -            | -                | -                | -         |    -6.06 | BehinDx, bekker, Speedie, Stesso, Viggo |
|           11 |     5123 | 2024-10-14 | Wave Esports                              | W   | 0.270      | 0.278        | 0.002 (0.000)    | 0.110 (0.008)    | 0 (0.000) |     4.01 | BehinDx, bekker, Speedie, Stesso, Viggo |
|           10 |     5221 | 2024-10-12 | 777 Esports                               | L   | 0.257      | -            | -                | -                | -         |    -3.97 | bekker, Speedie, Stesso, Tubsy, Viggo   |
|            9 |     5350 | 2024-10-09 | HOTU                                      | W   | 0.238      | 0.372        | 0.003 (0.000)    | 0.768 (0.068)    | 0 (0.000) |     4.58 | BehinDx, bekker, nellozz, Stesso, Viggo |
|            8 |     5483 | 2024-10-07 | 500                                       | L   | 0.225      | -            | -                | -                | -         |    -0.90 | BehinDx, bekker, nellozz, Stesso, Viggo |
|            7 |     6324 | 2024-09-25 | HOTU                                      | L   | 0.143      | -            | -                | -                | -         |    -1.76 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            6 |     6384 | 2024-09-24 | RUBY                                      | L   | 0.138      | -            | -                | -                | -         |    -1.90 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            5 |     7087 | 2024-09-13 | Copenhagen Wolves (American organization) | L   | 0.065      | -            | -                | -                | -         |    -1.07 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            4 |     7186 | 2024-09-11 | 500                                       | W   | 0.052      | 0.372        | 0.093 (0.002)    | 1.000 (0.019)    | 0 (0.000) |     1.42 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            3 |     7256 | 2024-09-10 | Leo Team                                  | W   | 0.045      | 0.372        | 0.026 (0.000)    | 0.748 (0.012)    | 0 (0.000) |     1.03 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            2 |     7416 | 2024-09-07 | Dark Cloud Esports                        | W   | 0.025      | 0.372        | 0.039 (0.000)    | 0.819 (0.008)    | 0 (0.000) |     0.59 | BehinDx, bekker, Speedie, Stesso, Viggo |
|            1 |     7583 | 2024-09-05 | FAVBET Team                               | L   | 0.012      | -            | -                | -                | -         |    -0.09 | BehinDx, bekker, Speedie, Stesso, Viggo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($87.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.117 | $750.00        | $87.60          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
