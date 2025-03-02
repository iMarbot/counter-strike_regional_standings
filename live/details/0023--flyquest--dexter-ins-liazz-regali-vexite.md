### Roster Details<br />
Team Name: FlyQuest<br />
Roster: dexter, INS, Liazz, regali, Vexite<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1126.4<br />
<br />
Final Rank Value (1126.4) = Starting Rank Value (1102.1) + Head To Head Adjustments (24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.405[<sup>2</sup>](#table1)
- Opponent Network: 0.087[<sup>2</sup>](#table1)
- LAN Wins: 0.409[<sup>2</sup>](#table1)

The average of these factors is 0.351<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.1
- 400 + ( ( 0.351 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1102.1


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
|           36 |      355 | 2025-02-16 | SAW                              | L   | 1.000      | -            | -                | -                | -         |   -11.03 | dexter, INS, Liazz, regali, Vexite   |
|           35 |      430 | 2025-02-15 | BIG                              | L   | 1.000      | -            | -                | -                | -         |    -7.27 | dexter, INS, Liazz, regali, Vexite   |
|           34 |      489 | 2025-02-14 | Team Falcons                     | L   | 1.000      | -            | -                | -                | -         |    -0.68 | dexter, INS, Liazz, regali, Vexite   |
|           33 |     1100 | 2025-01-30 | Astralis                         | L   | 0.999      | -            | -                | -                | -         |    -0.96 | dexter, INS, Liazz, regali, Vexite   |
|           32 |     1114 | 2025-01-29 | 3DMAX                            | L   | 0.991      | -            | -                | -                | -         |    -2.89 | dexter, INS, Liazz, regali, Vexite   |
|           31 |     1158 | 2025-01-18 | Team Spirit                      | L   | 0.920      | -            | -                | -                | -         |    -0.29 | dexter, INS, Liazz, regali, Vexite   |
|           30 |     1188 | 2025-01-14 | MIBR                             | W   | 0.891      | 0.363        | 0.141 (0.046)    | 0.471 (0.152)    | -         |    23.14 | dexter, INS, Liazz, regali, Vexite   |
|           29 |     2304 | 2024-12-02 | MIBR                             | L   | 0.610      | -            | -                | -                | -         |    -3.49 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2372 | 2024-12-01 | PaiN Gaming                      | L   | 0.603      | -            | -                | -                | -         |    -1.42 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2450 | 2024-11-30 | Team Liquid                      | L   | 0.596      | -            | -                | -                | -         |    -1.90 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2549 | 2024-11-30 | BIG                              | W   | 0.591      | 1.000        | 0.246 (0.145)    | 0.579 (0.342)    | 1 (0.591) |    16.48 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     2560 | 2024-11-29 | Complexity                       | W   | 0.590      | 1.000        | 0.097 (0.057)    | 0.229 (0.135)    | 1 (0.590) |    10.71 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3515 | 2024-11-13 | Lynn Vision Gaming               | W   | 0.478      | 0.143        | 0.017 (0.001)    | 0.368 (0.025)    | 1 (0.478) |     3.02 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3528 | 2024-11-12 | Adventurers                      | W   | 0.476      | 0.143        | 0.017 (0.001)    | -                | 1 (0.476) |     2.70 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3578 | 2024-11-11 | Ex-GR Gaming                     | W   | 0.470      | 0.143        | 0.011 (0.001)    | -                | 1 (0.470) |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3617 | 2024-11-11 | TALON                            | L   | 0.465      | -            | -                | -                | -         |   -14.02 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     4823 | 2024-10-19 | Mindfreak (Australian team)      | W   | 0.316      | -            | -                | -                | -         |     1.02 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     4907 | 2024-10-18 | Mindfreak (Australian team)      | W   | 0.304      | -            | -                | -                | -         |     0.97 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     5363 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.244      | -            | -                | -                | -         |    -6.97 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     5366 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.244      | -            | -                | -                | -         |    -7.01 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     5504 | 2024-10-06 | BIG                              | W   | 0.227      | 0.500        | 0.246 (0.028)    | 0.579 (0.066)    | 1 (0.227) |     6.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     5527 | 2024-10-06 | Wildcard                         | W   | 0.225      | 0.500        | 0.176 (0.020)    | 0.428 (0.048)    | 1 (0.225) |     5.65 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     5650 | 2024-10-04 | SAW                              | W   | 0.214      | 0.500        | 0.262 (0.028)    | 0.329 (0.035)    | 1 (0.214) |     5.29 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     5669 | 2024-10-04 | BetBoom Team                     | W   | 0.212      | 0.500        | 0.103 (0.011)    | 0.382 (0.041)    | 1 (0.212) |     2.66 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     5934 | 2024-09-30 | Rooster                          | W   | 0.184      | 0.333        | -                | 0.222 (0.014)    | -         |     0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     5935 | 2024-09-30 | Rooster                          | W   | 0.184      | 0.333        | -                | 0.222 (0.014)    | -         |     0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     6154 | 2024-09-27 | Only One Word                    | W   | 0.164      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     6156 | 2024-09-27 | Only One Word                    | W   | 0.164      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     6226 | 2024-09-26 | Housebets                        | W   | 0.158      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     6231 | 2024-09-26 | Housebets                        | W   | 0.157      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     6318 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.151      | -            | -                | -                | -         |     0.24 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     6324 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.151      | -            | -                | -                | -         |     0.24 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     7454 | 2024-09-07 | HEROIC                           | L   | 0.031      | -            | -                | -                | -         |    -0.52 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     7521 | 2024-09-06 | Lynn Vision Gaming               | W   | 0.025      | -            | -                | -                | 1 (0.025) |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     7672 | 2024-09-04 | FaZe Clan                        | L   | 0.012      | -            | -                | -                | -         |    -0.00 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     7749 | 2024-09-03 | Eternal Fire                     | L   | 0.005      | -            | -                | -                | -         |    -0.00 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,227.89)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-12-15 |      0.691 | $10,000.00     | $6,909.49       |
| 2024-10-19 |      0.316 | $3,250.00      | $1,028.26       |
| 2024-10-06 |      0.227 | $50,000.00     | $11,364.58      |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
