### Roster Details<br />
Team Name: Chimera Esports<br />
Roster: bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  842.5<br />
<br />
Final Rank Value (842.5) = Starting Rank Value (840.6) + Head To Head Adjustments (1.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.6
- 400 + ( ( 0.221 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 840.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |      139 | 2025-02-22 | MASONIC                                   | L   | 1.000      | -            | -                | -                | -         |   -24.07 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           59 |      490 | 2025-02-14 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -15.34 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           58 |      530 | 2025-02-12 | ECSTATIC                                  | L   | 1.000      | -            | -                | -                | -         |   -16.46 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           57 |      553 | 2025-02-11 | Natus Vincere Junior                      | L   | 1.000      | -            | -                | -                | -         |   -13.43 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           56 |     1009 | 2025-02-04 | K27                                       | L   | 1.000      | -            | -                | -                | -         |   -19.27 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           55 |     1139 | 2025-01-24 | ALASKA                                    | L   | 0.960      | -            | -                | -                | -         |   -16.18 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           54 |     1594 | 2024-12-16 | GUN5 Esports                              | L   | 0.698      | -            | -                | -                | -         |   -10.71 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           53 |     1630 | 2024-12-15 | LEON Esports                              | W   | 0.692      | -            | -                | -                | 0 (0.000) |     5.95 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           52 |     1648 | 2024-12-15 | Sashi Esport                              | W   | 0.691      | 0.371        | 0.013 (0.003)    | 0.503 (0.129)    | 0 (0.000) |    11.39 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           51 |     1708 | 2024-12-14 | Iberian Soul                              | W   | 0.685      | 0.371        | 0.015 (0.004)    | 0.553 (0.140)    | 0 (0.000) |     8.49 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           50 |     1719 | 2024-12-14 | Team Spirit Academy                       | L   | 0.684      | -            | -                | -                | -         |    -9.78 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           49 |     1838 | 2024-12-12 | GUN5 Esports                              | W   | 0.673      | 0.435        | 0.102 (0.030)    | 0.515 (0.150)    | 0 (0.000) |    11.59 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           48 |     1841 | 2024-12-12 | Betclic Apogee Esports                    | W   | 0.672      | 0.371        | -                | 0.515 (0.128)    | 0 (0.000) |     9.21 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           47 |     1890 | 2024-12-11 | Sashi Esport                              | L   | 0.665      | -            | -                | -                | -         |    -9.57 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           46 |     1932 | 2024-12-10 | Metizport                                 | W   | 0.658      | 0.435        | 0.074 (0.021)    | 0.513 (0.147)    | 0 (0.000) |    14.30 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           45 |     1963 | 2024-12-09 | GenOne                                    | W   | 0.651      | 0.371        | 0.012 (0.003)    | 0.848 (0.205)    | 0 (0.000) |     9.40 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           44 |     2064 | 2024-12-07 | ECSTATIC                                  | W   | 0.640      | 0.435        | 0.033 (0.009)    | 0.828 (0.230)    | 0 (0.000) |     9.66 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           43 |     2132 | 2024-12-06 | LEON Esports                              | W   | 0.632      | -            | -                | -                | 0 (0.000) |     7.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           42 |     2159 | 2024-12-05 | Tricked Esport                            | W   | 0.626      | 0.435        | 0.033 (0.009)    | 0.696 (0.189)    | 0 (0.000) |    10.30 | bl1x1, bluewh1te, m1QUSE, Pumpkin66, VILBy   |
|           41 |     2202 | 2024-12-04 | AMKAL ESPORTS                             | W   | 0.620      | 0.333        | -                | 0.681 (0.141)    | -         |     8.30 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           40 |     2223 | 2024-12-04 | GUN5 Esports                              | L   | 0.619      | -            | -                | -                | -         |    -7.73 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           39 |     2232 | 2024-12-04 | 9INE                                      | L   | 0.618      | -            | -                | -                | -         |    -9.44 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           38 |     2266 | 2024-12-03 | ZennoX                                    | W   | 0.613      | -            | -                | -                | -         |     4.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           37 |     2520 | 2024-11-30 | ENTERPRISE Genesis                        | W   | 0.593      | -            | -                | -                | -         |     4.33 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           36 |     2537 | 2024-11-30 | GenOne                                    | W   | 0.592      | 0.371        | -                | 0.848 (0.186)    | -         |     8.43 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           35 |     2614 | 2024-11-28 | Dreams To Legends                         | W   | 0.580      | -            | -                | -                | -         |     3.61 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           34 |     2651 | 2024-11-28 | Tricked Esport                            | L   | 0.578      | -            | -                | -                | -         |    -8.70 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           33 |     2678 | 2024-11-27 | BC.Game Esports                           | L   | 0.572      | -            | -                | -                | -         |    -9.79 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           32 |     2760 | 2024-11-25 | Betclic Apogee Esports                    | W   | 0.558      | -            | -                | -                | -         |     8.67 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           31 |     2983 | 2024-11-22 | Viperio                                   | W   | 0.539      | -            | -                | -                | -         |     5.45 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           30 |     3129 | 2024-11-20 | Illuminar Gaming                          | W   | 0.524      | -            | -                | -                | -         |     7.16 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           29 |     3209 | 2024-11-18 | Leo Team                                  | L   | 0.512      | -            | -                | -                | -         |    -7.85 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           28 |     3354 | 2024-11-16 | HOTU                                      | W   | 0.497      | -            | -                | -                | -         |     4.37 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           27 |     3473 | 2024-11-14 | Illuminar Gaming                          | W   | 0.484      | -            | -                | -                | -         |     7.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           26 |     3538 | 2024-11-12 | FLuffy Gangsters                          | W   | 0.473      | -            | -                | -                | -         |     5.96 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           25 |     3615 | 2024-11-11 | BC.Game Esports                           | W   | 0.466      | -            | -                | -                | -         |     7.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           24 |     4059 | 2024-11-03 | Endpoint                                  | L   | 0.412      | -            | -                | -                | -         |    -7.75 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           23 |     4199 | 2024-11-01 | HOTU                                      | W   | 0.399      | -            | -                | -                | -         |     3.69 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           22 |     4318 | 2024-10-30 | Dynamo Eclot                              | L   | 0.386      | -            | -                | -                | -         |    -2.94 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           21 |     4522 | 2024-10-26 | TSM                                       | W   | 0.359      | -            | -                | -                | -         |     4.11 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           20 |     4543 | 2024-10-26 | Wild Lotus                                | L   | 0.358      | -            | -                | -                | -         |    -7.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           19 |     4635 | 2024-10-24 | KONO.ECF                                  | W   | 0.344      | 0.333        | 0.045 (0.005)    | -                | -         |     6.35 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           18 |     4684 | 2024-10-23 | Natus Vincere Junior                      | W   | 0.337      | 0.333        | 0.091 (0.010)    | -                | -         |     7.23 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           17 |     4716 | 2024-10-22 | Copenhagen Wolves (American organization) | W   | 0.330      | -            | -                | -                | -         |     5.60 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           16 |     4757 | 2024-10-21 | Illuminar Gaming                          | W   | 0.324      | -            | -                | -                | -         |     5.77 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           15 |     4812 | 2024-10-20 | Natus Vincere Junior                      | L   | 0.318      | -            | -                | -                | -         |    -3.01 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           14 |     4897 | 2024-10-18 | Copenhagen Wolves (American organization) | L   | 0.305      | -            | -                | -                | -         |    -4.46 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           13 |     5019 | 2024-10-16 | WOPA Esport                               | W   | 0.291      | 0.333        | 0.031 (0.003)    | -                | -         |     4.71 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           12 |     5150 | 2024-10-13 | AMKAL ESPORTS                             | L   | 0.271      | -            | -                | -                | -         |    -4.96 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           11 |     5238 | 2024-10-12 | Illuminar Gaming                          | L   | 0.264      | -            | -                | -                | -         |    -3.80 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           10 |     5444 | 2024-10-08 | WOPA Esport                               | W   | 0.237      | -            | -                | -                | -         |     3.75 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            9 |     5855 | 2024-10-01 | Los kogutos                               | L   | 0.192      | -            | -                | -                | -         |    -1.83 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            8 |     6508 | 2024-09-22 | AMKAL ESPORTS                             | W   | 0.133      | -            | -                | -                | -         |     1.69 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            7 |     6638 | 2024-09-20 | Partizan Esports                          | L   | 0.119      | -            | -                | -                | -         |    -0.72 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            6 |     6931 | 2024-09-15 | ARCRED                                    | W   | 0.085      | -            | -                | -                | -         |     1.02 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            5 |     7263 | 2024-09-10 | Tricked Esport                            | L   | 0.051      | -            | -                | -                | -         |    -0.82 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            4 |     7357 | 2024-09-08 | JANO Esports                              | W   | 0.038      | -            | -                | -                | -         |     0.73 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            3 |     7534 | 2024-09-06 | Alliance                                  | W   | 0.024      | -            | -                | -                | -         |     0.45 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            2 |     7623 | 2024-09-05 | Nexus Gaming                              | W   | 0.018      | -            | -                | -                | -         |     0.49 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            1 |     7665 | 2024-09-04 | Monte                                     | L   | 0.013      | -            | -                | -                | -         |    -0.16 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,566.94)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.704 | $3,000.00      | $2,112.50       |
| 2024-12-15 |      0.693 | $2,000.00      | $1,385.83       |
| 2024-12-15 |      0.692 | $3,500.00      | $2,422.78       |
| 2024-11-29 |      0.584 | $1,000.00      | $584.17         |
| 2024-10-24 |      0.344 | $6,000.00      | $2,061.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
