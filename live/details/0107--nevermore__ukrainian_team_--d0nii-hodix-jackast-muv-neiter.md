### Roster Details<br />
Team Name: NEVERMORE (Ukrainian team)<br />
Roster: D0nii, hodix, jackast, MUV, neiter<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.1<br />
<br />
Final Rank Value (837.1) = Starting Rank Value (759.5) + Head To Head Adjustments (77.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.5
- 400 + ( ( 0.180 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 759.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      583 | 2025-02-10 | Zero Tenacity                             | L   | 1.000      | -            | -                | -                | -         |   -14.46 | D0nii, hodix, jackast, MUV, neiter |
|           41 |      591 | 2025-02-10 | 3DMAX                                     | L   | 1.000      | -            | -                | -                | -         |    -0.56 | D0nii, hodix, jackast, MUV, neiter |
|           40 |      665 | 2025-02-08 | Little Red Door                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.87 | D0nii, hodix, jackast, MUV, neiter |
|           39 |      677 | 2025-02-08 | ToxicAndCritic                            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.72 | D0nii, hodix, jackast, MUV, neiter |
|           38 |      697 | 2025-02-08 | Dynamo Eclot                              | W   | 1.000      | 0.143        | 0.127 (0.018)    | 0.703 (0.100)    | 0 (0.000) |    23.93 | D0nii, hodix, jackast, MUV, neiter |
|           37 |      760 | 2025-02-07 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | 0.016 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    19.89 | D0nii, hodix, jackast, MUV, neiter |
|           36 |     1277 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.781      | -            | -                | -                | -         |    -8.80 | D0nii, hodix, jackast, MUV, neiter |
|           35 |     1289 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.780      | -            | -                | -                | -         |    -9.38 | D0nii, hodix, jackast, MUV, neiter |
|           34 |     1304 | 2024-12-28 | 0to100                                    | W   | 0.778      | 0.303        | 0.007 (0.002)    | 0.176 (0.041)    | 0 (0.000) |    11.49 | D0nii, hodix, jackast, MUV, neiter |
|           33 |     1329 | 2024-12-27 | ALASKA                                    | W   | 0.772      | 0.333        | 0.030 (0.008)    | 0.875 (0.225)    | 0 (0.000) |    16.23 | D0nii, hodix, jackast, MUV, neiter |
|           32 |     1360 | 2024-12-24 | Infinite Gaming                           | W   | 0.752      | -            | -                | -                | 0 (0.000) |     4.09 | D0nii, hodix, jackast, MUV, neiter |
|           31 |     1372 | 2024-12-23 | ROYALS                                    | W   | 0.746      | 0.333        | 0.004 (0.001)    | 0.205 (0.051)    | 0 (0.000) |     8.28 | D0nii, hodix, jackast, MUV, neiter |
|           30 |     1393 | 2024-12-22 | Doge Soldiers                             | W   | 0.739      | -            | -                | -                | 0 (0.000) |     4.34 | D0nii, hodix, jackast, MUV, neiter |
|           29 |     1394 | 2024-12-22 | Infinite Gaming                           | L   | 0.739      | -            | -                | -                | -         |   -19.31 | D0nii, hodix, jackast, MUV, neiter |
|           28 |     1409 | 2024-12-22 | Belfast Storm                             | W   | 0.738      | -            | -                | -                | 0 (0.000) |     9.59 | D0nii, hodix, jackast, MUV, neiter |
|           27 |     1414 | 2024-12-22 | Preasy Esport                             | L   | 0.738      | -            | -                | -                | -         |   -13.28 | D0nii, hodix, jackast, MUV, neiter |
|           26 |     1446 | 2024-12-21 | C.S.D.E                                   | L   | 0.733      | -            | -                | -                | -         |   -15.46 | D0nii, hodix, jackast, MUV, neiter |
|           25 |     1451 | 2024-12-21 | WildHunt                                  | W   | 0.733      | -            | -                | -                | -         |     2.19 | D0nii, hodix, jackast, MUV, neiter |
|           24 |     1455 | 2024-12-21 | Dragon Esports Club                       | L   | 0.732      | -            | -                | -                | -         |   -16.06 | D0nii, hodix, jackast, MUV, neiter |
|           23 |     1473 | 2024-12-21 | C.S.D.E                                   | W   | 0.731      | -            | -                | -                | -         |     6.76 | D0nii, hodix, jackast, MUV, neiter |
|           22 |     1492 | 2024-12-20 | BadGuys                                   | L   | 0.727      | -            | -                | -                | -         |   -17.35 | D0nii, hodix, jackast, MUV, neiter |
|           21 |     1496 | 2024-12-20 | Rejected by all                           | W   | 0.727      | -            | -                | -                | -         |     1.90 | D0nii, hodix, jackast, MUV, neiter |
|           20 |     1531 | 2024-12-19 | SkyFury                                   | L   | 0.720      | -            | -                | -                | -         |   -16.62 | D0nii, hodix, jackast, MUV, neiter |
|           19 |     1764 | 2024-12-13 | Ex-GODSENT                                | W   | 0.681      | -            | -                | -                | -         |     3.59 | D0nii, hodix, jackast, MUV, neiter |
|           18 |     1771 | 2024-12-13 | P0RTUGAL                                  | W   | 0.680      | 0.143        | 0.037 (0.004)    | -                | -         |    10.21 | D0nii, hodix, jackast, MUV, neiter |
|           17 |     1775 | 2024-12-13 | FORZE Reload                              | W   | 0.680      | 0.143        | 0.026 (0.003)    | 0.559 (0.054)    | -         |    12.73 | D0nii, hodix, jackast, MUV, neiter |
|           16 |     1780 | 2024-12-13 | UNiTY esports                             | W   | 0.680      | 0.143        | 0.025 (0.002)    | 0.412 (0.040)    | -         |    11.23 | D0nii, hodix, jackast, MUV, neiter |
|           15 |     1871 | 2024-12-11 | AMKAL ESPORTS                             | L   | 0.667      | -            | -                | -                | -         |    -9.70 | D0nii, hodix, jackast, MUV, neiter |
|           14 |     1922 | 2024-12-10 | BRUTE                                     | W   | 0.660      | 0.333        | 0.004 (0.001)    | 0.345 (0.076)    | -         |     7.90 | D0nii, hodix, jackast, MUV, neiter |
|           13 |     1976 | 2024-12-08 | SINNERS Academy                           | W   | 0.647      | -            | -                | -                | -         |     7.74 | D0nii, hodix, jackast, MUV, neiter |
|           12 |     2119 | 2024-12-06 | GardenGarage                              | W   | 0.634      | 0.333        | -                | 0.413 (0.087)    | -         |     8.27 | D0nii, hodix, jackast, MUV, neiter |
|           11 |     2203 | 2024-12-04 | ENTERPRISE Genesis                        | W   | 0.620      | -            | -                | -                | -         |     6.41 | D0nii, hodix, jackast, MUV, neiter |
|           10 |     2265 | 2024-12-03 | Chroma                                    | W   | 0.613      | 0.303        | 0.005 (0.001)    | -                | -         |     7.48 | D0nii, hodix, jackast, MUV, neiter |
|            9 |     2326 | 2024-12-02 | MYSKILL                                   | W   | 0.607      | -            | -                | -                | -         |     7.24 | D0nii, hodix, jackast, MUV, neiter |
|            8 |     2350 | 2024-12-02 | ROYALS                                    | W   | 0.605      | -            | -                | -                | -         |     7.72 | D0nii, hodix, jackast, MUV, neiter |
|            7 |     2510 | 2024-11-30 | DAViNCi ESPORTS                           | W   | 0.593      | -            | -                | -                | -         |     2.04 | D0nii, hodix, jackast, MUV, neiter |
|            6 |     2597 | 2024-11-29 | Chroma                                    | W   | 0.585      | -            | -                | -                | -         |     7.38 | D0nii, hodix, jackast, MUV, neiter |
|            5 |     2615 | 2024-11-28 | XI Esport                                 | L   | 0.580      | -            | -                | -                | -         |   -11.11 | D0nii, hodix, jackast, MUV, neiter |
|            4 |     2672 | 2024-11-27 | Metizport X                               | W   | 0.573      | -            | -                | -                | -         |     6.35 | D0nii, hodix, jackast, MUV, neiter |
|            3 |     2790 | 2024-11-24 | HOTU                                      | L   | 0.552      | -            | -                | -                | -         |    -9.57 | D0nii, hodix, jackast, MUV, neiter |
|            2 |     2833 | 2024-11-23 | AMKAL ESPORTS                             | W   | 0.547      | 0.262        | -                | 0.681 (0.097)    | -         |     9.66 | D0nii, hodix, jackast, MUV, neiter |
|            1 |     2841 | 2024-11-23 | Ex-DOSKI                                  | W   | 0.547      | -            | -                | -                | -         |     2.04 | D0nii, hodix, jackast, MUV, neiter |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,328.96)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.780 | $1,500.00      | $1,169.48       |
| 2024-12-22 |      0.740 | $119.70        | $88.52          |
| 2024-12-15 |      0.692 | $600.00        | $415.33         |
| 2024-12-03 |      0.613 | $2,700.00      | $1,655.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
