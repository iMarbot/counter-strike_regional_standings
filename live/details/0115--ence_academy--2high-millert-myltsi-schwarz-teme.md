### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, millert, myltsi, Schwarz, teme<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  815.6<br />
<br />
Final Rank Value (815.6) = Starting Rank Value (819.6) + Head To Head Adjustments (-4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.112[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.210<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 819.6
- 400 + ( ( 0.210 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 819.6


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
|           57 |      168 | 2025-02-22 | JANO Esports                              | L   | 1.000      | -            | -                | -                | -         |   -17.15 | 2high, millert, myltsi, Schwarz, teme |
|           56 |      192 | 2025-02-21 | HAVU                                      | W   | 1.000      | -            | -                | -                | 1 (1.000) |    10.45 | 2high, millert, myltsi, Schwarz, teme |
|           55 |      305 | 2025-02-17 | SAUCEMEN                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.32 | 2high, millert, myltsi, Schwarz, teme |
|           54 |      522 | 2025-02-13 | Heimo Esports                             | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.651 (0.093)    | 0 (0.000) |    12.57 | 2high, millert, myltsi, Schwarz, teme |
|           53 |      648 | 2025-02-09 | FCottoNd                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.94 | 2high, millert, myltsi, Schwarz, teme |
|           52 |     1027 | 2025-02-03 | Smuuttikusilkki                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.66 | 2high, millert, myltsi, Schwarz, teme |
|           51 |     1075 | 2025-02-01 | HAVU                                      | L   | 1.000      | -            | -                | -                | -         |   -20.74 | 2high, millert, myltsi, Schwarz, teme |
|           50 |     1139 | 2025-01-26 | JANO Esports                              | W   | 0.964      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    16.11 | 2high, millert, myltsi, Schwarz, teme |
|           49 |     1155 | 2025-01-23 | Ex-UHKA eSports                           | W   | 0.945      | -            | -                | -                | 0 (0.000) |     5.89 | 2high, millert, myltsi, Schwarz, teme |
|           48 |     1374 | 2024-12-24 | WOPA Esport                               | L   | 0.743      | -            | -                | -                | -         |    -9.63 | 2high, millert, myltsi, Schwarz, teme |
|           47 |     1392 | 2024-12-23 | KONO.ECF                                  | L   | 0.736      | -            | -                | -                | -         |    -7.97 | 2high, millert, myltsi, Schwarz, teme |
|           46 |     1559 | 2024-12-19 | ESC Gaming                                | W   | 0.709      | -            | -                | -                | 0 (0.000) |     5.00 | 2high, millert, myltsi, Schwarz, teme |
|           45 |     1570 | 2024-12-18 | ALASKA                                    | W   | 0.703      | 0.333        | 0.031 (0.007)    | 0.867 (0.203)    | 0 (0.000) |    15.21 | 2high, millert, myltsi, Schwarz, teme |
|           44 |     1637 | 2024-12-15 | Dark Cloud Esports                        | L   | 0.684      | -            | -                | -                | -         |   -10.01 | 2high, millert, myltsi, Schwarz, teme |
|           43 |     1805 | 2024-12-13 | Copenhagen Wolves (American organization) | W   | 0.671      | 0.333        | 0.016 (0.004)    | 1.000 (0.224)    | 0 (0.000) |    12.25 | 2high, millert, myltsi, Schwarz, teme |
|           42 |     1823 | 2024-12-13 | ADEPTS                                    | W   | 0.669      | 0.333        | -                | 0.287 (0.064)    | -         |     5.64 | 2high, millert, myltsi, Schwarz, teme |
|           41 |     1966 | 2024-12-09 | Dark Cloud Esports                        | L   | 0.644      | -            | -                | -                | -         |    -9.31 | 2high, millert, myltsi, Schwarz, teme |
|           40 |     1976 | 2024-12-09 | Mission Possible                          | W   | 0.643      | 0.333        | -                | 0.292 (0.063)    | -         |     4.16 | 2high, millert, myltsi, Schwarz, teme |
|           39 |     2353 | 2024-12-02 | Illuminar Gaming                          | L   | 0.598      | -            | -                | -                | -         |    -8.98 | 2high, millert, myltsi, Schwarz, teme |
|           38 |     2603 | 2024-11-29 | Astralis Talent                           | W   | 0.578      | 0.333        | -                | 0.724 (0.139)    | -         |     8.87 | 2high, millert, myltsi, Schwarz, teme |
|           37 |     2660 | 2024-11-28 | Dark Cloud Esports                        | L   | 0.570      | -            | -                | -                | -         |    -7.41 | 2high, millert, myltsi, Schwarz, teme |
|           36 |     2768 | 2024-11-25 | Illuminar Gaming                          | W   | 0.551      | 0.333        | 0.007 (0.001)    | 0.581 (0.107)    | -         |     9.25 | 2high, millert, myltsi, Schwarz, teme |
|           35 |     2879 | 2024-11-23 | Iberian Soul                              | L   | 0.538      | -            | -                | -                | -         |    -7.59 | 2high, millert, myltsi, Schwarz, teme |
|           34 |     3045 | 2024-11-21 | TEAM NEXT LEVEL                           | L   | 0.525      | -            | -                | -                | -         |    -7.27 | 2high, millert, myltsi, Schwarz, teme |
|           33 |     3132 | 2024-11-20 | Iberian Soul                              | W   | 0.518      | 0.333        | 0.015 (0.003)    | 0.551 (0.095)    | -         |     8.82 | 2high, millert, myltsi, Schwarz, teme |
|           32 |     3178 | 2024-11-19 | Viperio                                   | W   | 0.509      | 0.333        | -                | 0.404 (0.069)    | -         |     6.59 | 2high, millert, myltsi, Schwarz, teme |
|           31 |     3225 | 2024-11-18 | Illuminar Gaming                          | L   | 0.503      | -            | -                | -                | -         |    -7.23 | 2high, meLty, myltsi, Schwarz, teme   |
|           30 |     3477 | 2024-11-14 | Leo Team                                  | L   | 0.477      | -            | -                | -                | -         |    -6.32 | 2high, millert, myltsi, Schwarz, teme |
|           29 |     3871 | 2024-11-07 | Copenhagen Wolves (American organization) | L   | 0.429      | -            | -                | -                | -         |    -5.95 | 2high, millert, myltsi, Schwarz, teme |
|           28 |     4087 | 2024-11-03 | Lilmix                                    | W   | 0.403      | -            | -                | -                | -         |     3.62 | 2high, millert, myltsi, Schwarz, teme |
|           27 |     4344 | 2024-10-30 | Copenhagen Wolves (American organization) | L   | 0.376      | -            | -                | -                | -         |    -5.20 | 2high, millert, myltsi, Schwarz, teme |
|           26 |     4823 | 2024-10-20 | JANO Esports                              | L   | 0.310      | -            | -                | -                | -         |    -3.45 | 2high, millert, myltsi, Schwarz, teme |
|           25 |     5128 | 2024-10-14 | GenOne                                    | L   | 0.269      | -            | -                | -                | -         |    -4.12 | 2high, millert, Schwarz, teme, Whitey |
|           24 |     5307 | 2024-10-10 | KONO.ECF                                  | L   | 0.243      | -            | -                | -                | -         |    -2.87 | 2high, millert, myltsi, Schwarz, teme |
|           23 |     5541 | 2024-10-06 | JANO Esports                              | W   | 0.217      | 0.143        | 0.022 (0.001)    | -                | -         |     4.39 | 2high, millert, myltsi, Schwarz, teme |
|           22 |     5602 | 2024-10-05 | Heimo Esports                             | W   | 0.211      | -            | -                | -                | -         |     2.76 | 2high, millert, myltsi, Schwarz, teme |
|           21 |     5620 | 2024-10-05 | Johnny Speeds                             | L   | 0.210      | -            | -                | -                | -         |    -2.60 | 2high, millert, myltsi, Schwarz, teme |
|           20 |     5675 | 2024-10-04 | 500                                       | W   | 0.205      | 0.333        | 0.093 (0.006)    | 1.000 (0.068)    | -         |     4.71 | 2high, millert, myltsi, Schwarz, teme |
|           19 |     5737 | 2024-10-03 | Los kogutos                               | W   | 0.197      | 0.333        | 0.032 (0.002)    | -                | -         |     4.54 | 2high, millert, myltsi, Schwarz, teme |
|           18 |     5790 | 2024-10-02 | Tricked Esport                            | W   | 0.190      | 0.333        | 0.034 (0.002)    | -                | -         |     3.18 | 2high, millert, myltsi, Schwarz, teme |
|           17 |     5935 | 2024-09-30 | Leo Team                                  | L   | 0.177      | -            | -                | -                | -         |    -2.57 | 2high, millert, myltsi, Schwarz, teme |
|           16 |     6082 | 2024-09-28 | HOTU                                      | L   | 0.163      | -            | -                | -                | -         |    -3.13 | 2high, millert, myltsi, Schwarz, teme |
|           15 |     6164 | 2024-09-27 | Lazer Cats                                | W   | 0.156      | -            | -                | -                | -         |     1.90 | 2high, millert, myltsi, Schwarz, teme |
|           14 |     6305 | 2024-09-25 | RUBY                                      | L   | 0.145      | -            | -                | -                | -         |    -2.96 | 2high, millert, myltsi, Schwarz, teme |
|           13 |     6403 | 2024-09-24 | HOTU                                      | W   | 0.137      | -            | -                | -                | -         |     1.68 | 2high, millert, myltsi, Schwarz, teme |
|           12 |     6501 | 2024-09-23 | Natus Vincere Junior                      | L   | 0.129      | -            | -                | -                | -         |    -1.20 | 2high, millert, myltsi, Schwarz, teme |
|           11 |     6536 | 2024-09-22 | JANO Esports                              | L   | 0.123      | -            | -                | -                | -         |    -1.37 | 2high, millert, myltsi, Schwarz, teme |
|           10 |     6790 | 2024-09-18 | Rhyno Esports                             | L   | 0.096      | -            | -                | -                | -         |    -2.08 | 2high, millert, myltsi, Schwarz, teme |
|            9 |     6867 | 2024-09-17 | QUAZAR                                    | L   | 0.089      | -            | -                | -                | -         |    -1.81 | 2high, millert, myltsi, Schwarz, teme |
|            8 |     6950 | 2024-09-15 | Smuuttikusilkki                           | W   | 0.077      | -            | -                | -                | -         |     0.31 | 2high, millert, myltsi, Schwarz, teme |
|            7 |     7059 | 2024-09-14 | GameAgents                                | L   | 0.069      | -            | -                | -                | -         |    -1.47 | 2high, millert, myltsi, Schwarz, teme |
|            6 |     7153 | 2024-09-12 | Ex-9INE Academy                           | W   | 0.057      | -            | -                | -                | -         |     0.41 | 2high, millert, myltsi, Schwarz, teme |
|            5 |     7164 | 2024-09-12 | RUBY                                      | L   | 0.056      | -            | -                | -                | -         |    -1.18 | 2high, millert, myltsi, Schwarz, teme |
|            4 |     7218 | 2024-09-11 | Team Spirit Academy                       | L   | 0.050      | -            | -                | -                | -         |    -0.57 | 2high, millert, myltsi, Schwarz, teme |
|            3 |     7225 | 2024-09-11 | Copenhagen Wolves (American organization) | L   | 0.049      | -            | -                | -                | -         |    -1.29 | 2high, millert, myltsi, Schwarz, teme |
|            2 |     7366 | 2024-09-08 | Cspojat                                   | W   | 0.030      | -            | -                | -                | -         |     0.12 | 2high, millert, myltsi, Schwarz, teme |
|            1 |     7695 | 2024-09-04 | Preasy Esport                             | W   | 0.003      | -            | -                | -                | -         |     0.04 | 2high, millert, myltsi, Schwarz, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,826.04)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,046.46      | $1,046.46       |
| 2024-12-25 |      0.750 | $1,000.00      | $750.07         |
| 2024-10-20 |      0.310 | $1,631.14      | $504.86         |
| 2024-10-05 |      0.210 | $2,500.00      | $524.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
