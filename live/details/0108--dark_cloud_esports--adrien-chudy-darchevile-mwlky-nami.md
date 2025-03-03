### Roster Details<br />
Team Name: Dark Cloud Esports<br />
Roster: AdrieN, chudy, darchevile, mwlky, Nami<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.3<br />
<br />
Final Rank Value (837.3) = Starting Rank Value (840.1) + Head To Head Adjustments (-2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.415[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.1
- 400 + ( ( 0.220 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 840.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |      162 | 2025-02-22 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -15.37 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           74 |      212 | 2025-02-21 | Tricked Esport                            | L   | 1.000      | -            | -                | -                | -         |   -15.06 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           73 |      224 | 2025-02-21 | 1win                                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.61 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           72 |      251 | 2025-02-20 | SEight                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.27 | AdrieN, chudy, darchevile, mwlky, Nami   |
|           71 |     1235 | 2025-01-04 | Insilio                                   | L   | 0.818      | -            | -                | -                | -         |   -18.40 | chudy, darchevile, Enzo, Michat, Nami    |
|           70 |     1251 | 2024-12-30 | KONO.ECF                                  | L   | 0.783      | -            | -                | -                | -         |    -9.73 | Bambosh, chudy, darchevile, Melavi, Nami |
|           69 |     1269 | 2024-12-29 | Copenhagen Wolves (American organization) | W   | 0.777      | 0.333        | 0.016 (0.004)    | 1.000 (0.259)    | 0 (0.000) |    13.26 | Bambosh, chudy, darchevile, Melavi, Nami |
|           68 |     1276 | 2024-12-29 | BRUTE                                     | W   | 0.776      | -            | -                | -                | 0 (0.000) |     7.07 | chudy, darchevile, Michat, Nami, next1me |
|           67 |     1299 | 2024-12-28 | Preasy Esport                             | W   | 0.772      | 0.333        | 0.012 (0.003)    | 0.701 (0.180)    | 0 (0.000) |     8.47 | Bambosh, chudy, darchevile, Melavi, Nami |
|           66 |     1349 | 2024-12-27 | 9INE                                      | L   | 0.763      | -            | -                | -                | -         |    -8.57 | chudy, darchevile, Enzo, Michat, Nami    |
|           65 |     1355 | 2024-12-26 | M1Z                                       | W   | 0.759      | -            | -                | -                | 0 (0.000) |     1.97 | Bambosh, chudy, darchevile, Enzo, Nami   |
|           64 |     1356 | 2024-12-26 | BRUTE                                     | W   | 0.758      | -            | -                | -                | 0 (0.000) |     7.36 | Bambosh, chudy, darchevile, Enzo, Nami   |
|           63 |     1482 | 2024-12-21 | Astralis Talent                           | L   | 0.723      | -            | -                | -                | -         |   -13.91 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           62 |     1494 | 2024-12-21 | VOLT (European team)                      | W   | 0.723      | -            | -                | -                | 0 (0.000) |     6.93 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           61 |     1516 | 2024-12-20 | Monte                                     | L   | 0.718      | -            | -                | -                | -         |    -7.97 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           60 |     1522 | 2024-12-20 | XI Esport                                 | W   | 0.717      | -            | -                | -                | 0 (0.000) |     6.51 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           59 |     1533 | 2024-12-20 | ALASKA                                    | L   | 0.716      | -            | -                | -                | -         |    -9.74 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           58 |     1539 | 2024-12-19 | FLuffy Gangsters                          | W   | 0.712      | 0.333        | 0.014 (0.003)    | 0.909 (0.216)    | 0 (0.000) |    10.72 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           57 |     1548 | 2024-12-19 | Wu-Tang Clan                              | W   | 0.711      | -            | -                | -                | -         |     6.18 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           56 |     1580 | 2024-12-17 | KONO.ECF                                  | W   | 0.698      | 0.333        | 0.046 (0.011)    | 0.747 (0.174)    | -         |    11.54 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           55 |     1595 | 2024-12-16 | Viperio                                   | W   | 0.691      | -            | -                | -                | -         |     8.49 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           54 |     1637 | 2024-12-15 | ENCE Academy                              | W   | 0.684      | 0.333        | -                | 0.649 (0.148)    | -         |    10.01 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           53 |     1654 | 2024-12-15 | JANO Esports                              | W   | 0.683      | 0.333        | 0.022 (0.005)    | -                | -         |    11.99 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           52 |     1789 | 2024-12-13 | Heimo Esports                             | L   | 0.672      | -            | -                | -                | -         |   -13.40 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           51 |     1836 | 2024-12-12 | ADEPTS                                    | W   | 0.666      | -            | -                | -                | -         |     4.99 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           50 |     1908 | 2024-12-11 | FORZE Reload                              | L   | 0.656      | -            | -                | -                | -         |    -9.00 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           49 |     1966 | 2024-12-09 | ENCE Academy                              | W   | 0.644      | 0.333        | -                | 0.649 (0.139)    | -         |     9.31 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           48 |     1974 | 2024-12-09 | AMKAL ESPORTS                             | L   | 0.643      | -            | -                | -                | -         |   -10.86 | Bambosh, chudy2k, darchevile, Enzo, Nami |
|           47 |     2292 | 2024-12-03 | Illuminar Gaming                          | L   | 0.603      | -            | -                | -                | -         |    -9.86 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           46 |     2355 | 2024-12-02 | Chroma                                    | L   | 0.598      | -            | -                | -                | -         |   -13.27 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           45 |     2363 | 2024-12-02 | Betclic Apogee Esports                    | W   | 0.597      | 0.333        | 0.012 (0.002)    | -                | -         |    10.65 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           44 |     2458 | 2024-12-01 | GenOne                                    | L   | 0.589      | -            | -                | -                | -         |    -9.46 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           43 |     2599 | 2024-11-29 | BC.Game Esports                           | L   | 0.578      | -            | -                | -                | -         |    -8.34 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           42 |     2611 | 2024-11-29 | SkyFury                                   | W   | 0.576      | -            | -                | -                | -         |     4.96 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           41 |     2656 | 2024-11-28 | Illuminar Gaming                          | L   | 0.571      | -            | -                | -                | -         |   -10.09 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           40 |     2660 | 2024-11-28 | ENCE Academy                              | W   | 0.570      | -            | -                | -                | -         |     7.41 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           39 |     2688 | 2024-11-27 | Fragmatic                                 | W   | 0.564      | -            | -                | -                | -         |     2.90 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           38 |     2693 | 2024-11-27 | WOPA Esport                               | W   | 0.563      | 0.333        | 0.032 (0.006)    | 0.777 (0.146)    | -         |     8.60 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           37 |     2773 | 2024-11-25 | FORZE Reload                              | L   | 0.550      | -            | -                | -                | -         |    -8.29 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           36 |     2815 | 2024-11-24 | Heimo Esports                             | W   | 0.543      | -            | -                | -                | -         |     5.42 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           35 |     2844 | 2024-11-23 | Viperio                                   | W   | 0.539      | -            | -                | -                | -         |     5.89 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           34 |     2954 | 2024-11-22 | FLuffy Gangsters                          | W   | 0.532      | 0.333        | 0.014 (0.002)    | 0.909 (0.161)    | -         |     8.69 | CheDzik, chudy2k, darchevile, Enzo, Nami |
|           33 |     3140 | 2024-11-20 | WOPA Esport                               | L   | 0.517      | -            | -                | -                | -         |    -8.44 | chudy2k, darchevile, Enzo, Melavi, Nami  |
|           32 |     3264 | 2024-11-17 | Leo Team                                  | L   | 0.497      | -            | -                | -                | -         |    -7.36 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           31 |     3341 | 2024-11-16 | Kubix Esports                             | L   | 0.491      | -            | -                | -                | -         |    -6.03 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           30 |     3489 | 2024-11-14 | Leo Team                                  | W   | 0.476      | 0.333        | 0.026 (0.004)    | -                | -         |     7.75 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           29 |     3582 | 2024-11-12 | Astralis Talent                           | W   | 0.463      | -            | -                | -                | -         |     6.02 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           28 |     3694 | 2024-11-10 | GenOne                                    | W   | 0.449      | 0.333        | -                | 0.837 (0.125)    | -         |     7.10 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           27 |     4012 | 2024-11-04 | Haspers Team                              | W   | 0.412      | -            | -                | -                | -         |     4.44 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           26 |     4100 | 2024-11-03 | Copenhagen Wolves (American organization) | W   | 0.403      | 0.333        | 0.016 (0.002)    | 1.000 (0.134)    | -         |     6.77 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           25 |     4339 | 2024-10-30 | Lilmix                                    | W   | 0.377      | -            | -                | -                | -         |     3.21 | chudy2k, darchevile, Enzo, Ex1st, Nami   |
|           24 |     4381 | 2024-10-29 | Illuminar Gaming                          | W   | 0.372      | -            | -                | -                | -         |     6.62 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           23 |     4731 | 2024-10-21 | Dynamo Eclot                              | L   | 0.318      | -            | -                | -                | -         |    -2.06 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           22 |     5473 | 2024-10-07 | Mission Possible                          | L   | 0.225      | -            | -                | -                | -         |    -5.94 | chudy2k, darchevile, michat, Nami, yvro  |
|           21 |     5495 | 2024-10-07 | Error404                                  | W   | 0.224      | -            | -                | -                | -         |     0.61 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           20 |     5814 | 2024-10-02 | Illuminar Gaming                          | L   | 0.189      | -            | -                | -                | -         |    -2.59 | chudy2k, darchevile, Enzo, morelz, Nami  |
|           19 |     6046 | 2024-09-28 | Tibian Soldiers                           | W   | 0.164      | -            | -                | -                | -         |     0.44 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           18 |     6129 | 2024-09-27 | Haspers Team                              | L   | 0.158      | -            | -                | -                | -         |    -3.29 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           17 |     6171 | 2024-09-27 | The Suspect                               | L   | 0.155      | -            | -                | -                | -         |    -3.16 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           16 |     6247 | 2024-09-26 | AMKAL ESPORTS                             | L   | 0.149      | -            | -                | -                | -         |    -2.74 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           15 |     6372 | 2024-09-24 | GameAgents                                | W   | 0.138      | -            | -                | -                | -         |     1.34 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           14 |     6393 | 2024-09-24 | Los kogutos                               | L   | 0.138      | -            | -                | -                | -         |    -1.26 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           13 |     6432 | 2024-09-24 | UNiTY esports                             | L   | 0.135      | -            | -                | -                | -         |    -2.11 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           12 |     6465 | 2024-09-23 | Ex-Soul's Heart Esport                    | L   | 0.132      | -            | -                | -                | -         |    -3.16 | chudy2k, darchevile, Melavi, Nami, yvro  |
|           11 |     6492 | 2024-09-23 | WOPA Esport                               | W   | 0.130      | -            | -                | -                | -         |     2.16 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           10 |     6659 | 2024-09-20 | Wild Lotus                                | L   | 0.109      | -            | -                | -                | -         |    -2.18 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            9 |     6820 | 2024-09-17 | Ins (Polish team)                         | W   | 0.092      | -            | -                | -                | -         |     0.81 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            8 |     6837 | 2024-09-17 | WiLD MultiGaming                          | W   | 0.092      | -            | -                | -                | -         |     0.63 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            7 |     7333 | 2024-09-09 | Astralis Talent                           | L   | 0.035      | -            | -                | -                | -         |    -0.65 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            6 |     7372 | 2024-09-08 | SINNERS Academy                           | L   | 0.030      | -            | -                | -                | -         |    -0.60 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            5 |     7416 | 2024-09-07 | Daystar                                   | L   | 0.025      | -            | -                | -                | -         |    -0.59 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            4 |     7636 | 2024-09-05 | ADEPTS                                    | L   | 0.009      | -            | -                | -                | -         |    -0.24 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            3 |     7658 | 2024-09-04 | Iuhop (Russian team)                      | L   | 0.005      | -            | -                | -                | -         |    -0.14 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            2 |     7673 | 2024-09-04 | Cerberus eSports (Russian team)           | W   | 0.005      | -            | -                | -                | -         |     0.03 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            1 |     7690 | 2024-09-04 | Natus Vincere Junior                      | L   | 0.003      | -            | -                | -                | -         |    -0.03 | chudy2k, darchevile, Enzo, Nami, yvro    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,759.20)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $2,000.00      | $1,566.94       |
| 2024-12-21 |      0.724 | $1,000.00      | $723.89         |
| 2024-12-21 |      0.723 | $2,700.00      | $1,951.13       |
| 2024-12-03 |      0.605 | $500.00        | $302.50         |
| 2024-11-17 |      0.497 | $3,000.00      | $1,490.83       |
| 2024-11-16 |      0.491 | $13,708.02     | $6,723.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
