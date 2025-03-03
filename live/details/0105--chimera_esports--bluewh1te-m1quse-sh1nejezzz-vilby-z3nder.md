### Roster Details<br />
Team Name: Chimera Esports<br />
Roster: bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.4<br />
<br />
Final Rank Value (840.4) = Starting Rank Value (839.3) + Head To Head Adjustments (1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.3
- 400 + ( ( 0.220 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 839.3


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
|           60 |      154 | 2025-02-22 | MASONIC                                   | L   | 1.000      | -            | -                | -                | -         |   -24.00 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           59 |      502 | 2025-02-14 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -15.30 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           58 |      542 | 2025-02-12 | ECSTATIC                                  | L   | 1.000      | -            | -                | -                | -         |   -16.45 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           57 |      565 | 2025-02-11 | Natus Vincere Junior                      | L   | 1.000      | -            | -                | -                | -         |   -13.43 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           56 |     1021 | 2025-02-04 | K27                                       | L   | 1.000      | -            | -                | -                | -         |   -19.14 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           55 |     1151 | 2025-01-24 | ALASKA                                    | L   | 0.951      | -            | -                | -                | -         |   -15.85 | bluewh1te, m1QUSE, sh1nejezzz, VILBy, z3ndeR |
|           54 |     1606 | 2024-12-16 | GUN5 Esports                              | L   | 0.690      | -            | -                | -                | -         |   -10.56 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           53 |     1642 | 2024-12-15 | LEON Esports                              | W   | 0.684      | -            | -                | -                | 0 (0.000) |     5.94 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           52 |     1660 | 2024-12-15 | Sashi Esport                              | W   | 0.683      | 0.371        | 0.013 (0.003)    | 0.499 (0.126)    | 0 (0.000) |    11.31 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           51 |     1720 | 2024-12-14 | Iberian Soul                              | W   | 0.677      | 0.371        | 0.015 (0.004)    | 0.551 (0.138)    | 0 (0.000) |     8.42 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           50 |     1731 | 2024-12-14 | Team Spirit Academy                       | L   | 0.676      | -            | -                | -                | -         |    -9.67 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           49 |     1850 | 2024-12-12 | GUN5 Esports                              | W   | 0.664      | 0.435        | 0.103 (0.030)    | 0.505 (0.146)    | 0 (0.000) |    11.48 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           48 |     1853 | 2024-12-12 | Betclic Apogee Esports                    | W   | 0.664      | 0.371        | -                | 0.513 (0.126)    | 0 (0.000) |     9.14 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           47 |     1902 | 2024-12-11 | Sashi Esport                              | L   | 0.657      | -            | -                | -                | -         |    -9.41 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           46 |     1944 | 2024-12-10 | Metizport                                 | W   | 0.650      | 0.435        | 0.074 (0.021)    | 0.507 (0.143)    | 0 (0.000) |    14.13 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           45 |     1975 | 2024-12-09 | GenOne                                    | W   | 0.643      | 0.371        | 0.012 (0.003)    | 0.837 (0.199)    | 0 (0.000) |     9.30 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           44 |     2076 | 2024-12-07 | ECSTATIC                                  | W   | 0.632      | 0.435        | 0.033 (0.009)    | 0.820 (0.225)    | 0 (0.000) |     9.56 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           43 |     2144 | 2024-12-06 | LEON Esports                              | W   | 0.624      | -            | -                | -                | 0 (0.000) |     7.02 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           42 |     2171 | 2024-12-05 | Tricked Esport                            | W   | 0.618      | 0.435        | 0.034 (0.009)    | 0.687 (0.184)    | 0 (0.000) |    10.17 | bl1x1, bluewh1te, m1QUSE, Pumpkin66, VILBy   |
|           41 |     2214 | 2024-12-04 | AMKAL ESPORTS                             | W   | 0.612      | 0.333        | -                | 0.674 (0.138)    | -         |     8.18 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           40 |     2235 | 2024-12-04 | GUN5 Esports                              | L   | 0.610      | -            | -                | -                | -         |    -7.61 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           39 |     2244 | 2024-12-04 | 9INE                                      | L   | 0.609      | -            | -                | -                | -         |    -9.28 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           38 |     2278 | 2024-12-03 | ZennoX                                    | W   | 0.605      | -            | -                | -                | -         |     4.18 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           37 |     2532 | 2024-11-30 | ENTERPRISE Genesis                        | W   | 0.585      | -            | -                | -                | -         |     4.30 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           36 |     2549 | 2024-11-30 | GenOne                                    | W   | 0.583      | 0.371        | -                | 0.837 (0.181)    | -         |     8.32 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           35 |     2626 | 2024-11-28 | Dreams To Legends                         | W   | 0.572      | -            | -                | -                | -         |     3.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           34 |     2663 | 2024-11-28 | Tricked Esport                            | L   | 0.569      | -            | -                | -                | -         |    -8.57 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           33 |     2690 | 2024-11-27 | BC.Game Esports                           | L   | 0.563      | -            | -                | -                | -         |    -9.63 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           32 |     2772 | 2024-11-25 | Betclic Apogee Esports                    | W   | 0.550      | -            | -                | -                | -         |     8.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           31 |     2995 | 2024-11-22 | Viperio                                   | W   | 0.530      | -            | -                | -                | -         |     5.37 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           30 |     3141 | 2024-11-20 | Illuminar Gaming                          | W   | 0.516      | -            | -                | -                | -         |     7.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           29 |     3221 | 2024-11-18 | Leo Team                                  | L   | 0.503      | -            | -                | -                | -         |    -7.73 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           28 |     3366 | 2024-11-16 | HOTU                                      | W   | 0.489      | -            | -                | -                | -         |     4.33 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           27 |     3485 | 2024-11-14 | Illuminar Gaming                          | W   | 0.476      | -            | -                | -                | -         |     7.08 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           26 |     3550 | 2024-11-12 | FLuffy Gangsters                          | W   | 0.465      | -            | -                | -                | -         |     5.86 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           25 |     3627 | 2024-11-11 | BC.Game Esports                           | W   | 0.458      | -            | -                | -                | -         |     6.96 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           24 |     4071 | 2024-11-03 | Endpoint                                  | L   | 0.404      | -            | -                | -                | -         |    -7.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           23 |     4211 | 2024-11-01 | HOTU                                      | W   | 0.391      | -            | -                | -                | -         |     3.63 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           22 |     4330 | 2024-10-30 | Dynamo Eclot                              | L   | 0.378      | -            | -                | -                | -         |    -2.88 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           21 |     4534 | 2024-10-26 | TSM                                       | W   | 0.350      | -            | -                | -                | -         |     4.01 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           20 |     4555 | 2024-10-26 | Wild Lotus                                | L   | 0.350      | -            | -                | -                | -         |    -6.91 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           19 |     4647 | 2024-10-24 | KONO.ECF                                  | W   | 0.335      | 0.333        | 0.046 (0.005)    | -                | -         |     6.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           18 |     4696 | 2024-10-23 | Natus Vincere Junior                      | W   | 0.329      | 0.333        | 0.091 (0.010)    | -                | -         |     7.04 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           17 |     4729 | 2024-10-22 | Copenhagen Wolves (American organization) | W   | 0.322      | -            | -                | -                | -         |     5.47 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           16 |     4769 | 2024-10-21 | Illuminar Gaming                          | W   | 0.315      | -            | -                | -                | -         |     5.61 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           15 |     4825 | 2024-10-20 | Natus Vincere Junior                      | L   | 0.309      | -            | -                | -                | -         |    -2.95 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           14 |     4909 | 2024-10-18 | Copenhagen Wolves (American organization) | L   | 0.297      | -            | -                | -                | -         |    -4.33 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           13 |     5031 | 2024-10-16 | WOPA Esport                               | W   | 0.283      | 0.333        | 0.032 (0.003)    | -                | -         |     4.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           12 |     5162 | 2024-10-13 | AMKAL ESPORTS                             | L   | 0.263      | -            | -                | -                | -         |    -4.82 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           11 |     5252 | 2024-10-12 | Illuminar Gaming                          | L   | 0.256      | -            | -                | -                | -         |    -3.70 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|           10 |     5456 | 2024-10-08 | WOPA Esport                               | W   | 0.229      | -            | -                | -                | -         |     3.63 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            9 |     5867 | 2024-10-01 | Los kogutos                               | L   | 0.184      | -            | -                | -                | -         |    -1.76 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            8 |     6520 | 2024-09-22 | AMKAL ESPORTS                             | W   | 0.125      | -            | -                | -                | -         |     1.59 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            7 |     6650 | 2024-09-20 | Partizan Esports                          | L   | 0.110      | -            | -                | -                | -         |    -0.67 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            6 |     6943 | 2024-09-15 | ARCRED                                    | W   | 0.077      | -            | -                | -                | -         |     0.93 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            5 |     7275 | 2024-09-10 | Tricked Esport                            | L   | 0.042      | -            | -                | -                | -         |    -0.69 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            4 |     7369 | 2024-09-08 | JANO Esports                              | W   | 0.030      | -            | -                | -                | -         |     0.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            3 |     7546 | 2024-09-06 | Alliance                                  | W   | 0.016      | -            | -                | -                | -         |     0.30 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            2 |     7635 | 2024-09-05 | Nexus Gaming                              | W   | 0.010      | -            | -                | -                | -         |     0.27 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |
|            1 |     7677 | 2024-09-04 | Monte                                     | L   | 0.005      | -            | -                | -                | -         |    -0.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,439.93)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.696 | $3,000.00      | $2,087.92       |
| 2024-12-15 |      0.685 | $2,000.00      | $1,369.44       |
| 2024-12-15 |      0.684 | $3,500.00      | $2,394.10       |
| 2024-11-29 |      0.576 | $1,000.00      | $575.97         |
| 2024-10-24 |      0.335 | $6,000.00      | $2,012.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
