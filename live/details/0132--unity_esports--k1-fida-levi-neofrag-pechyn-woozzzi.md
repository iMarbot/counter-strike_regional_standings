### Roster Details<br />
Team Name: UNiTY esports<br />
Roster: K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  781.5<br />
<br />
Final Rank Value (781.5) = Starting Rank Value (839.6) + Head To Head Adjustments (-58.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.098[<sup>2</sup>](#table1)
- LAN Wins: 0.107[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.6
- 400 + ( ( 0.220 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 839.6


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
|           63 |      723 | 2025-02-08 | Iberian Soul                              | L   | 1.000      | -            | -                | -                | -         |   -14.67 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           62 |      901 | 2025-02-05 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.57 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           61 |     1003 | 2025-02-04 | Iberian Soul                              | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.553 (0.079)    | 0 (0.000) |    16.02 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           60 |     1124 | 2025-01-27 | Ninjas in Pyjamas                         | L   | 0.978      | -            | -                | -                | -         |   -24.01 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           59 |     1412 | 2024-12-22 | 9INE                                      | L   | 0.738      | -            | -                | -                | -         |    -7.74 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           58 |     1529 | 2024-12-19 | Insilio                                   | W   | 0.720      | 0.354        | -                | 0.504 (0.129)    | 0 (0.000) |     7.47 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           57 |     1537 | 2024-12-19 | Illuminar Gaming                          | W   | 0.719      | 0.354        | 0.007 (0.002)    | 0.593 (0.151)    | 0 (0.000) |    10.92 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           56 |     1553 | 2024-12-18 | Insilio                                   | L   | 0.713      | -            | -                | -                | -         |   -15.06 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           55 |     1780 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.680      | -            | -                | -                | -         |   -11.23 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           54 |     2513 | 2024-11-30 | Partizan Esports                          | L   | 0.593      | -            | -                | -                | -         |    -4.28 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           53 |     2703 | 2024-11-26 | Nexus Gaming                              | L   | 0.567      | -            | -                | -                | -         |    -3.01 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           52 |     2795 | 2024-11-24 | Dynamo Eclot                              | L   | 0.552      | -            | -                | -                | -         |    -4.12 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           51 |     2875 | 2024-11-23 | Permitta Esports                          | L   | 0.546      | -            | -                | -                | -         |    -9.21 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           50 |     2908 | 2024-11-23 | Team Sampi                                | W   | 0.544      | -            | -                | -                | 1 (0.544) |     7.44 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           49 |     2968 | 2024-11-22 | BC.Game Esports                           | W   | 0.539      | 0.372        | 0.022 (0.004)    | 0.559 (0.112)    | 0 (0.000) |     8.26 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           48 |     3210 | 2024-11-18 | GamerLegion                               | L   | 0.511      | -            | -                | -                | -         |    -0.28 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           47 |     3250 | 2024-11-17 | SAW                                       | L   | 0.505      | -            | -                | -                | -         |    -1.02 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           46 |     3284 | 2024-11-16 | BetBoom Team                              | L   | 0.504      | -            | -                | -                | -         |    -4.05 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           45 |     3666 | 2024-11-10 | RUSTEC                                    | W   | 0.459      | -            | -                | -                | 0 (0.000) |     3.86 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           44 |     3668 | 2024-11-10 | RUSTEC                                    | W   | 0.459      | -            | -                | -                | 0 (0.000) |     2.53 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           43 |     3671 | 2024-11-10 | FLuffy Gangsters                          | W   | 0.459      | 0.372        | 0.014 (0.002)    | 0.925 (0.158)    | -         |     6.32 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           42 |     3832 | 2024-11-07 | Lazer Cats                                | L   | 0.440      | -            | -                | -                | -         |    -8.91 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           41 |     3878 | 2024-11-06 | TEAM NEXT LEVEL                           | W   | 0.433      | 0.372        | 0.039 (0.006)    | 0.508 (0.082)    | -         |     6.85 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           40 |     3884 | 2024-11-06 | Leo Team                                  | L   | 0.433      | -            | -                | -                | -         |    -6.86 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           39 |     4377 | 2024-10-29 | QUAZAR                                    | W   | 0.379      | -            | -                | -                | -         |     4.22 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           38 |     4410 | 2024-10-28 | Daystar                                   | L   | 0.374      | -            | -                | -                | -         |    -8.75 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           37 |     4627 | 2024-10-24 | HOTU                                      | L   | 0.345      | -            | -                | -                | -         |    -7.49 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           36 |     4727 | 2024-10-21 | Grindas                                   | W   | 0.326      | -            | -                | -                | -         |     1.42 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           35 |     4750 | 2024-10-21 | Johnny Speeds                             | L   | 0.325      | -            | -                | -                | -         |    -4.38 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           34 |     4778 | 2024-10-20 | Team Spirit Academy                       | W   | 0.319      | 0.372        | 0.068 (0.008)    | 0.714 (0.085)    | -         |     6.41 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           33 |     5023 | 2024-10-16 | WOPA Esport                               | L   | 0.290      | -            | -                | -                | -         |    -4.70 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           32 |     5115 | 2024-10-14 | 500                                       | L   | 0.278      | -            | -                | -                | -         |    -2.73 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           31 |     5264 | 2024-10-11 | 500                                       | L   | 0.259      | -            | -                | -                | -         |    -2.62 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           30 |     5458 | 2024-10-07 | Dynamo Eclot                              | W   | 0.233      | 0.143        | 0.127 (0.004)    | -                | -         |     5.64 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           29 |     5465 | 2024-10-07 | HOTU                                      | W   | 0.233      | 0.372        | -                | 0.777 (0.067)    | -         |     2.49 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           28 |     5495 | 2024-10-07 | Natus Vincere Junior                      | L   | 0.231      | -            | -                | -                | -         |    -2.50 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           27 |     5498 | 2024-10-07 | 9INE                                      | W   | 0.230      | -            | -                | -                | -         |     2.85 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           26 |     5538 | 2024-10-06 | Leo Team                                  | L   | 0.224      | -            | -                | -                | -         |    -3.68 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           25 |     5688 | 2024-10-04 | Preasy Esport                             | W   | 0.210      | 0.333        | -                | 0.710 (0.050)    | -         |     2.90 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           24 |     5770 | 2024-10-02 | FAVBET Team                               | W   | 0.199      | 0.384        | 0.032 (0.002)    | 0.814 (0.062)    | -         |     3.00 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           23 |     5794 | 2024-10-02 | Viperio                                   | W   | 0.198      | -            | -                | -                | -         |     2.31 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           22 |     5871 | 2024-10-01 | Partizan Esports                          | L   | 0.191      | -            | -                | -                | -         |    -1.26 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           21 |     5955 | 2024-09-29 | GardenGarage                              | W   | 0.179      | -            | -                | -                | -         |     2.08 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           20 |     6080 | 2024-09-28 | ALASKA                                    | W   | 0.170      | 0.333        | 0.030 (0.002)    | -                | -         |     4.54 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           19 |     6142 | 2024-09-27 | Wild Lotus                                | L   | 0.165      | -            | -                | -                | -         |    -3.26 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           18 |     6363 | 2024-09-24 | Kyoto (European mix-team)                 | L   | 0.146      | -            | -                | -                | -         |    -3.35 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           17 |     6380 | 2024-09-24 | Haspers Team                              | W   | 0.146      | -            | -                | -                | -         |     1.46 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           16 |     6412 | 2024-09-24 | Astralis Talent                           | W   | 0.144      | -            | -                | -                | -         |     1.86 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           15 |     6420 | 2024-09-24 | Dark Cloud Esports                        | W   | 0.144      | 0.371        | 0.038 (0.002)    | -                | -         |     2.22 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           14 |     6511 | 2024-09-22 | SINNERS Esports                           | W   | 0.133      | -            | -                | -                | 1 (0.133) |     2.54 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           13 |     6576 | 2024-09-21 | SINNERS Esports                           | W   | 0.126      | -            | -                | -                | 1 (0.126) |     2.43 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           12 |     6641 | 2024-09-20 | Team Sampi                                | W   | 0.118      | -            | -                | -                | 1 (0.118) |     1.71 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           11 |     6653 | 2024-09-20 | ALTERNATE aTTaX                           | L   | 0.117      | -            | -                | -                | -         |    -1.34 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           10 |     6811 | 2024-09-17 | Red Bottom Sky                            | W   | 0.100      | -            | -                | -                | -         |     0.25 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            9 |     6814 | 2024-09-17 | Haspers Team                              | W   | 0.100      | -            | -                | -                | -         |     0.64 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            8 |     7098 | 2024-09-13 | GameAgents                                | L   | 0.071      | -            | -                | -                | -         |    -1.57 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            7 |     7155 | 2024-09-12 | Ex-ENTERPRISE esports                     | L   | 0.064      | -            | -                | -                | -         |    -1.31 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            6 |     7316 | 2024-09-09 | Astralis Talent                           | W   | 0.044      | -            | -                | -                | -         |     0.59 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            5 |     7356 | 2024-09-08 | Sampi NEXT                                | W   | 0.038      | -            | -                | -                | -         |     0.16 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            4 |     7423 | 2024-09-07 | Team PeeP                                 | L   | 0.032      | -            | -                | -                | -         |    -0.89 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            3 |     7527 | 2024-09-06 | SINNERS Esports                           | L   | 0.025      | -            | -                | -                | -         |    -0.31 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            2 |     7593 | 2024-09-05 | Copenhagen Wolves (American organization) | L   | 0.019      | -            | -                | -                | -         |    -0.46 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            1 |     7610 | 2024-09-05 | Sampi NEXT                                | W   | 0.019      | -            | -                | -                | -         |     0.08 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,558.87)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $13,154.54     | $7,258.75       |
| 2024-10-08 |      0.237 | $1,000.00      | $237.08         |
| 2024-09-22 |      0.133 | $8,017.32      | $1,063.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
