### Roster Details<br />
Team Name: Only One Word<br />
Roster: BaN4na, Freeman, Oath, Terryyy, viridian<br />
Global Rank: [293](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [41]( ../standings_asia.md)<br />
<br />
Final Rank Value:  652.0<br />
<br />
Final Rank Value (652.0) = Starting Rank Value (634.5) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 634.5
- 400 + ( ( 0.117 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 634.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       31 | 2025-02-25 | KZG                         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.165 (0.024)    | 0 (0.000) |    14.56 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           23 |       34 | 2025-02-25 | Vantage Esports             | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.337 (0.048)    | 0 (0.000) |    17.43 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           22 |       52 | 2025-02-24 | Justice For Tomorrow        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.427 (0.061)    | 0 (0.000) |    17.41 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           21 |       68 | 2025-02-24 | SemperFi Esports            | L   | 1.000      | -            | -                | -                | -         |   -11.54 | BaN4na, Freeman, Oath, Terryyy, viridian |
|           20 |      648 | 2025-02-08 | Shika                       | L   | 1.000      | -            | -                | -                | -         |   -17.23 | BaN4na, neo, Oath, Terryyy, viridian     |
|           19 |      728 | 2025-02-07 | Gods Reign                  | L   | 1.000      | -            | -                | -                | -         |    -6.56 | BaN4na, neo, Oath, Terryyy, viridian     |
|           18 |     4908 | 2024-10-18 | Housebets                   | L   | 0.304      | -            | -                | -                | -         |    -5.02 | BaN4na, neo, Oath, Terryyy, viridian     |
|           17 |     4959 | 2024-10-17 | Mindfreak (Australian team) | L   | 0.297      | -            | -                | -                | -         |    -3.73 | BaN4na, neo, Oath, Terryyy, viridian     |
|           16 |     5364 | 2024-10-09 | MANTRA                      | W   | 0.244      | 0.333        | 0.000 (0.000)    | 0.175 (0.014)    | 0 (0.000) |     3.45 | BaN4na, neo, Oath, Terryyy, viridian     |
|           15 |     5368 | 2024-10-09 | MANTRA                      | W   | 0.244      | 0.333        | 0.000 (0.000)    | 0.175 (0.014)    | 0 (0.000) |     3.52 | BaN4na, neo, Oath, Terryyy, viridian     |
|           14 |     5549 | 2024-10-05 | SemperFi Esports            | L   | 0.223      | -            | -                | -                | -         |    -4.31 | BaN4na, neo, Oath, Terryyy, viridian     |
|           13 |     5550 | 2024-10-05 | Mindfreak (Australian team) | W   | 0.222      | 0.143        | 0.002 (0.000)    | 0.093 (0.003)    | 0 (0.000) |     4.16 | BaN4na, neo, Oath, Terryyy, viridian     |
|           12 |     5553 | 2024-10-05 | Vantage Esports             | W   | 0.221      | 0.143        | 0.003 (0.000)    | 0.337 (0.011)    | 0 (0.000) |     3.64 | BaN4na, neo, Oath, Terryyy, viridian     |
|           11 |     5632 | 2024-10-04 | Housebets                   | W   | 0.217      | 0.143        | 0.001 (0.000)    | 0.123 (0.004)    | 0 (0.000) |     3.30 | BaN4na, neo, Oath, Terryyy, viridian     |
|           10 |     5638 | 2024-10-04 | Rebound                     | W   | 0.216      | -            | -                | -                | 0 (0.000) |     2.25 | BaN4na, neo, Oath, Terryyy, viridian     |
|            9 |     5642 | 2024-10-04 | Vantage Esports             | L   | 0.215      | -            | -                | -                | -         |    -3.22 | BaN4na, neo, Oath, Terryyy, viridian     |
|            8 |     5796 | 2024-10-02 | DXA Esports                 | L   | 0.198      | -            | -                | -                | -         |    -3.47 | BaN4na, neo, Oath, Terryyy, viridian     |
|            7 |     5798 | 2024-10-02 | DXA Esports                 | W   | 0.197      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     2.79 | BaN4na, neo, Oath, Terryyy, viridian     |
|            6 |     6154 | 2024-09-27 | FlyQuest                    | L   | 0.164      | -            | -                | -                | -         |    -0.35 | BaN4na, neo, Oath, Terryyy, viridian     |
|            5 |     6156 | 2024-09-27 | FlyQuest                    | L   | 0.164      | -            | -                | -                | -         |    -0.35 | BaN4na, neo, Oath, Terryyy, viridian     |
|            4 |     6319 | 2024-09-25 | Mindfreak (Australian team) | L   | 0.151      | -            | -                | -                | -         |    -1.94 | BaN4na, neo, Oath, Terryyy, viridian     |
|            3 |     6325 | 2024-09-25 | Mindfreak (Australian team) | W   | 0.151      | 0.333        | 0.002 (0.000)    | 0.093 (0.005)    | -         |     2.84 | BaN4na, neo, Oath, Terryyy, viridian     |
|            2 |     6949 | 2024-09-15 | KZG                         | W   | 0.084      | 0.333        | -                | 0.165 (0.005)    | -         |     1.30 | BaN4na, neo, Oath, Terryyy, viridian     |
|            1 |     6954 | 2024-09-15 | KZG                         | L   | 0.084      | -            | -                | -                | -         |    -1.36 | BaN4na, neo, Oath, Terryyy, viridian     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($332.21)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.316 | $1,050.00      | $332.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
