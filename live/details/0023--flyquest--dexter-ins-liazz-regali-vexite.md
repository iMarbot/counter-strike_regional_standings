### Roster Details<br />
Team Name: FlyQuest<br />
Roster: dexter, INS, Liazz, regali, Vexite<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1122.2<br />
<br />
Final Rank Value (1122.2) = Starting Rank Value (1097.7) + Head To Head Adjustments (24.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.401[<sup>2</sup>](#table1)

The average of these factors is 0.349<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1097.7
- 400 + ( ( 0.349 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1097.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      367 | 2025-02-16 | SAW                              | L   | 1.000      | -            | -                | -                | -         |   -10.87 | dexter, INS, Liazz, regali, Vexite   |
|           34 |      442 | 2025-02-15 | BIG                              | L   | 1.000      | -            | -                | -                | -         |    -7.15 | dexter, INS, Liazz, regali, Vexite   |
|           33 |      501 | 2025-02-14 | Team Falcons                     | L   | 1.000      | -            | -                | -                | -         |    -0.66 | dexter, INS, Liazz, regali, Vexite   |
|           32 |     1112 | 2025-01-30 | Astralis                         | L   | 0.991      | -            | -                | -                | -         |    -0.92 | dexter, INS, Liazz, regali, Vexite   |
|           31 |     1126 | 2025-01-29 | 3DMAX                            | L   | 0.983      | -            | -                | -                | -         |    -2.81 | dexter, INS, Liazz, regali, Vexite   |
|           30 |     1170 | 2025-01-18 | Team Spirit                      | L   | 0.912      | -            | -                | -                | -         |    -0.28 | dexter, INS, Liazz, regali, Vexite   |
|           29 |     1200 | 2025-01-14 | MIBR                             | W   | 0.883      | 0.363        | 0.142 (0.045)    | 0.465 (0.149)    | -         |    22.98 | dexter, INS, Liazz, regali, Vexite   |
|           28 |     2316 | 2024-12-02 | MIBR                             | L   | 0.602      | -            | -                | -                | -         |    -3.40 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2384 | 2024-12-01 | PaiN Gaming                      | L   | 0.595      | -            | -                | -                | -         |    -1.35 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2462 | 2024-11-30 | Team Liquid                      | L   | 0.588      | -            | -                | -                | -         |    -1.86 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     2561 | 2024-11-30 | BIG                              | W   | 0.583      | 1.000        | 0.248 (0.145)    | 0.572 (0.333)    | 1 (0.583) |    16.30 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     2572 | 2024-11-29 | Complexity                       | W   | 0.581      | 1.000        | 0.098 (0.057)    | 0.226 (0.131)    | 1 (0.581) |    10.61 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3527 | 2024-11-13 | Lynn Vision Gaming               | W   | 0.470      | 0.143        | 0.017 (0.001)    | 0.365 (0.025)    | 1 (0.470) |     3.01 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3540 | 2024-11-12 | Adventurers                      | W   | 0.468      | 0.143        | 0.016 (0.001)    | -                | 1 (0.468) |     2.67 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3590 | 2024-11-11 | Ex-GR Gaming                     | W   | 0.462      | 0.143        | 0.012 (0.001)    | -                | 1 (0.462) |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3629 | 2024-11-11 | TALON                            | L   | 0.457      | -            | -                | -                | -         |   -13.76 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     4835 | 2024-10-19 | Mindfreak (Australian team)      | W   | 0.308      | -            | -                | -                | -         |     1.01 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     4919 | 2024-10-18 | Mindfreak (Australian team)      | W   | 0.295      | -            | -                | -                | -         |     0.96 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     5375 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.236      | -            | -                | -                | -         |    -6.72 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     5378 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.236      | -            | -                | -                | -         |    -6.76 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     5516 | 2024-10-06 | BIG                              | W   | 0.219      | 0.500        | 0.248 (0.027)    | 0.572 (0.063)    | 1 (0.219) |     6.19 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     5539 | 2024-10-06 | Wildcard                         | W   | 0.217      | 0.500        | 0.178 (0.019)    | 0.422 (0.046)    | 1 (0.217) |     5.47 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     5662 | 2024-10-04 | SAW                              | W   | 0.205      | 0.500        | 0.266 (0.027)    | 0.326 (0.033)    | 1 (0.205) |     5.12 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     5681 | 2024-10-04 | BetBoom Team                     | W   | 0.204      | 0.500        | 0.104 (0.011)    | 0.379 (0.039)    | 1 (0.204) |     2.57 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     5946 | 2024-09-30 | Rooster                          | W   | 0.176      | 0.333        | -                | 0.220 (0.013)    | -         |     0.47 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     5947 | 2024-09-30 | Rooster                          | W   | 0.176      | 0.333        | -                | 0.220 (0.013)    | -         |     0.47 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     6166 | 2024-09-27 | Only One Word                    | W   | 0.156      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     6168 | 2024-09-27 | Only One Word                    | W   | 0.156      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     6238 | 2024-09-26 | Housebets                        | W   | 0.149      | -            | -                | -                | -         |     0.31 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     6243 | 2024-09-26 | Housebets                        | W   | 0.149      | -            | -                | -                | -         |     0.31 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     6330 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.143      | -            | -                | -                | -         |     0.23 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     6336 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.142      | -            | -                | -                | -         |     0.23 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     7466 | 2024-09-07 | HEROIC                           | L   | 0.023      | -            | -                | -                | -         |    -0.39 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     7533 | 2024-09-06 | Lynn Vision Gaming               | W   | 0.017      | -            | -                | -                | 1 (0.017) |     0.12 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     7684 | 2024-09-04 | FaZe Clan                        | L   | 0.004      | -            | -                | -                | -         |    -0.00 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,652.23)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-12-15 |      0.683 | $10,000.00     | $6,827.55       |
| 2024-10-19 |      0.308 | $3,250.00      | $1,001.63       |
| 2024-10-06 |      0.219 | $50,000.00     | $10,954.86      |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
