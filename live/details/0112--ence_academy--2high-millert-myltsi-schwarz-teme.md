### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, millert, myltsi, Schwarz, teme<br />
Global Rank: [112](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  816.8<br />
<br />
Final Rank Value (816.8) = Starting Rank Value (820.2) + Head To Head Adjustments (-3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.115[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.210<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.2
- 400 + ( ( 0.210 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 820.2


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
|           57 |      155 | 2025-02-22 | JANO Esports                              | L   | 1.000      | -            | -                | -                | -         |   -17.20 | 2high, millert, myltsi, Schwarz, teme |
|           56 |      180 | 2025-02-21 | HAVU                                      | W   | 1.000      | -            | -                | -                | 1 (1.000) |    10.39 | 2high, millert, myltsi, Schwarz, teme |
|           55 |      293 | 2025-02-17 | SAUCEMEN                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.30 | 2high, millert, myltsi, Schwarz, teme |
|           54 |      510 | 2025-02-13 | Heimo Esports                             | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.658 (0.094)    | 0 (0.000) |    12.64 | 2high, millert, myltsi, Schwarz, teme |
|           53 |      636 | 2025-02-09 | FCottoNd                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.92 | 2high, millert, myltsi, Schwarz, teme |
|           52 |     1015 | 2025-02-03 | Smuuttikusilkki                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.65 | 2high, millert, myltsi, Schwarz, teme |
|           51 |     1063 | 2025-02-01 | HAVU                                      | L   | 1.000      | -            | -                | -                | -         |   -20.82 | 2high, millert, myltsi, Schwarz, teme |
|           50 |     1127 | 2025-01-26 | JANO Esports                              | W   | 0.972      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    16.19 | 2high, millert, myltsi, Schwarz, teme |
|           49 |     1143 | 2025-01-23 | Ex-UHKA eSports                           | W   | 0.953      | -            | -                | -                | 0 (0.000) |     5.92 | 2high, millert, myltsi, Schwarz, teme |
|           48 |     1362 | 2024-12-24 | WOPA Esport                               | L   | 0.752      | -            | -                | -                | -         |    -9.71 | 2high, millert, myltsi, Schwarz, teme |
|           47 |     1380 | 2024-12-23 | KONO.ECF                                  | L   | 0.744      | -            | -                | -                | -         |    -8.01 | 2high, millert, myltsi, Schwarz, teme |
|           46 |     1547 | 2024-12-19 | ESC Gaming                                | W   | 0.718      | -            | -                | -                | 0 (0.000) |     5.05 | 2high, millert, myltsi, Schwarz, teme |
|           45 |     1558 | 2024-12-18 | ALASKA                                    | W   | 0.712      | 0.333        | 0.030 (0.007)    | 0.875 (0.208)    | 0 (0.000) |    15.27 | 2high, millert, myltsi, Schwarz, teme |
|           44 |     1625 | 2024-12-15 | Dark Cloud Esports                        | L   | 0.693      | -            | -                | -                | -         |   -10.12 | 2high, millert, myltsi, Schwarz, teme |
|           43 |     1793 | 2024-12-13 | Copenhagen Wolves (American organization) | W   | 0.679      | 0.333        | 0.016 (0.004)    | 1.000 (0.226)    | 0 (0.000) |    12.39 | 2high, millert, myltsi, Schwarz, teme |
|           42 |     1811 | 2024-12-13 | ADEPTS                                    | W   | 0.677      | 0.333        | -                | 0.292 (0.066)    | -         |     6.91 | 2high, millert, myltsi, Schwarz, teme |
|           41 |     1954 | 2024-12-09 | Dark Cloud Esports                        | L   | 0.652      | -            | -                | -                | -         |    -9.42 | 2high, millert, myltsi, Schwarz, teme |
|           40 |     1964 | 2024-12-09 | Mission Possible                          | W   | 0.651      | 0.333        | -                | 0.295 (0.064)    | -         |     4.24 | 2high, millert, myltsi, Schwarz, teme |
|           39 |     2341 | 2024-12-02 | Illuminar Gaming                          | L   | 0.606      | -            | -                | -                | -         |    -9.07 | 2high, millert, myltsi, Schwarz, teme |
|           38 |     2591 | 2024-11-29 | Astralis Talent                           | W   | 0.586      | 0.333        | -                | 0.733 (0.143)    | -         |     9.04 | 2high, millert, myltsi, Schwarz, teme |
|           37 |     2648 | 2024-11-28 | Dark Cloud Esports                        | L   | 0.578      | -            | -                | -                | -         |    -7.50 | 2high, millert, myltsi, Schwarz, teme |
|           36 |     2756 | 2024-11-25 | Illuminar Gaming                          | W   | 0.559      | 0.333        | 0.007 (0.001)    | 0.593 (0.110)    | -         |     9.42 | 2high, millert, myltsi, Schwarz, teme |
|           35 |     2867 | 2024-11-23 | Iberian Soul                              | L   | 0.546      | -            | -                | -                | -         |    -7.67 | 2high, millert, myltsi, Schwarz, teme |
|           34 |     3033 | 2024-11-21 | TEAM NEXT LEVEL                           | L   | 0.533      | -            | -                | -                | -         |    -7.36 | 2high, millert, myltsi, Schwarz, teme |
|           33 |     3120 | 2024-11-20 | Iberian Soul                              | W   | 0.526      | 0.333        | 0.015 (0.003)    | 0.553 (0.097)    | -         |     8.98 | 2high, millert, myltsi, Schwarz, teme |
|           32 |     3166 | 2024-11-19 | Viperio                                   | W   | 0.517      | 0.333        | -                | 0.411 (0.071)    | -         |     6.75 | 2high, millert, myltsi, Schwarz, teme |
|           31 |     3213 | 2024-11-18 | Illuminar Gaming                          | L   | 0.511      | -            | -                | -                | -         |    -7.30 | 2high, meLty, myltsi, Schwarz, teme   |
|           30 |     3465 | 2024-11-14 | Leo Team                                  | L   | 0.485      | -            | -                | -                | -         |    -6.38 | 2high, millert, myltsi, Schwarz, teme |
|           29 |     3859 | 2024-11-07 | Copenhagen Wolves (American organization) | L   | 0.438      | -            | -                | -                | -         |    -6.04 | 2high, millert, myltsi, Schwarz, teme |
|           28 |     4075 | 2024-11-03 | Lilmix                                    | W   | 0.412      | -            | -                | -                | -         |     3.70 | 2high, millert, myltsi, Schwarz, teme |
|           27 |     4332 | 2024-10-30 | Copenhagen Wolves (American organization) | L   | 0.384      | -            | -                | -                | -         |    -5.30 | 2high, millert, myltsi, Schwarz, teme |
|           26 |     4811 | 2024-10-20 | JANO Esports                              | L   | 0.318      | -            | -                | -                | -         |    -3.54 | 2high, millert, myltsi, Schwarz, teme |
|           25 |     5117 | 2024-10-14 | GenOne                                    | L   | 0.278      | -            | -                | -                | -         |    -4.22 | 2high, millert, Schwarz, teme, Whitey |
|           24 |     5296 | 2024-10-10 | KONO.ECF                                  | L   | 0.251      | -            | -                | -                | -         |    -2.95 | 2high, millert, myltsi, Schwarz, teme |
|           23 |     5529 | 2024-10-06 | JANO Esports                              | W   | 0.225      | 0.143        | 0.022 (0.001)    | -                | -         |     4.55 | 2high, millert, myltsi, Schwarz, teme |
|           22 |     5590 | 2024-10-05 | Heimo Esports                             | W   | 0.219      | -            | -                | -                | -         |     2.87 | 2high, millert, myltsi, Schwarz, teme |
|           21 |     5608 | 2024-10-05 | Johnny Speeds                             | L   | 0.218      | -            | -                | -                | -         |    -2.68 | 2high, millert, myltsi, Schwarz, teme |
|           20 |     5663 | 2024-10-04 | 500                                       | W   | 0.213      | 0.333        | 0.091 (0.006)    | 1.000 (0.071)    | -         |     4.90 | 2high, millert, myltsi, Schwarz, teme |
|           19 |     5725 | 2024-10-03 | Los kogutos                               | W   | 0.205      | 0.333        | 0.032 (0.002)    | -                | -         |     4.75 | 2high, millert, myltsi, Schwarz, teme |
|           18 |     5778 | 2024-10-02 | Tricked Esport                            | W   | 0.199      | 0.333        | 0.033 (0.002)    | -                | -         |     3.33 | 2high, millert, myltsi, Schwarz, teme |
|           17 |     5923 | 2024-09-30 | Leo Team                                  | L   | 0.185      | -            | -                | -                | -         |    -2.67 | 2high, millert, myltsi, Schwarz, teme |
|           16 |     6070 | 2024-09-28 | HOTU                                      | L   | 0.171      | -            | -                | -                | -         |    -3.28 | 2high, millert, myltsi, Schwarz, teme |
|           15 |     6152 | 2024-09-27 | Lazer Cats                                | W   | 0.164      | -            | -                | -                | -         |     2.01 | 2high, millert, myltsi, Schwarz, teme |
|           14 |     6293 | 2024-09-25 | RUBY                                      | L   | 0.153      | -            | -                | -                | -         |    -3.11 | 2high, millert, myltsi, Schwarz, teme |
|           13 |     6391 | 2024-09-24 | HOTU                                      | W   | 0.145      | -            | -                | -                | -         |     1.79 | 2high, millert, myltsi, Schwarz, teme |
|           12 |     6489 | 2024-09-23 | Natus Vincere Junior                      | L   | 0.137      | -            | -                | -                | -         |    -1.26 | 2high, millert, myltsi, Schwarz, teme |
|           11 |     6524 | 2024-09-22 | JANO Esports                              | L   | 0.131      | -            | -                | -                | -         |    -1.46 | 2high, millert, myltsi, Schwarz, teme |
|           10 |     6778 | 2024-09-18 | Rhyno Esports                             | L   | 0.104      | -            | -                | -                | -         |    -2.26 | 2high, millert, myltsi, Schwarz, teme |
|            9 |     6855 | 2024-09-17 | QUAZAR                                    | L   | 0.097      | -            | -                | -                | -         |    -1.97 | 2high, millert, myltsi, Schwarz, teme |
|            8 |     6938 | 2024-09-15 | Smuuttikusilkki                           | W   | 0.085      | -            | -                | -                | -         |     0.34 | 2high, millert, myltsi, Schwarz, teme |
|            7 |     7047 | 2024-09-14 | GameAgents                                | L   | 0.077      | -            | -                | -                | -         |    -1.64 | 2high, millert, myltsi, Schwarz, teme |
|            6 |     7141 | 2024-09-12 | Ex-9INE Academy                           | W   | 0.065      | -            | -                | -                | -         |     0.48 | 2high, millert, myltsi, Schwarz, teme |
|            5 |     7152 | 2024-09-12 | RUBY                                      | L   | 0.064      | -            | -                | -                | -         |    -1.35 | 2high, millert, myltsi, Schwarz, teme |
|            4 |     7206 | 2024-09-11 | Team Spirit Academy                       | L   | 0.058      | -            | -                | -                | -         |    -0.66 | 2high, millert, myltsi, Schwarz, teme |
|            3 |     7213 | 2024-09-11 | Copenhagen Wolves (American organization) | L   | 0.057      | -            | -                | -                | -         |    -1.50 | 2high, millert, myltsi, Schwarz, teme |
|            2 |     7354 | 2024-09-08 | Cspojat                                   | W   | 0.038      | -            | -                | -                | -         |     0.16 | 2high, millert, myltsi, Schwarz, teme |
|            1 |     7683 | 2024-09-04 | Preasy Esport                             | W   | 0.011      | -            | -                | -                | -         |     0.17 | 2high, millert, myltsi, Schwarz, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,868.09)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,046.46      | $1,046.46       |
| 2024-12-25 |      0.758 | $1,000.00      | $758.26         |
| 2024-10-20 |      0.318 | $1,631.14      | $518.23         |
| 2024-10-05 |      0.218 | $2,500.00      | $545.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
