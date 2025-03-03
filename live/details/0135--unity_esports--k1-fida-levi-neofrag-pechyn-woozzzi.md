### Roster Details<br />
Team Name: UNiTY esports<br />
Roster: K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  779.7<br />
<br />
Final Rank Value (779.7) = Starting Rank Value (836.5) + Head To Head Adjustments (-56.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.104[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.5
- 400 + ( ( 0.218 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 836.5


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
|           63 |      735 | 2025-02-08 | Iberian Soul                              | L   | 1.000      | -            | -                | -                | -         |   -14.65 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           62 |      913 | 2025-02-05 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.55 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           61 |     1015 | 2025-02-04 | Iberian Soul                              | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.551 (0.079)    | 0 (0.000) |    16.05 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           60 |     1136 | 2025-01-27 | Ninjas in Pyjamas                         | L   | 0.970      | -            | -                | -                | -         |   -23.76 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           59 |     1424 | 2024-12-22 | 9INE                                      | L   | 0.730      | -            | -                | -                | -         |    -7.64 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           58 |     1541 | 2024-12-19 | Insilio                                   | W   | 0.712      | 0.354        | -                | 0.500 (0.126)    | 0 (0.000) |     7.38 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           57 |     1549 | 2024-12-19 | Illuminar Gaming                          | W   | 0.711      | 0.354        | 0.007 (0.002)    | 0.581 (0.146)    | 0 (0.000) |    10.80 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           56 |     1565 | 2024-12-18 | Insilio                                   | L   | 0.704      | -            | -                | -                | -         |   -14.90 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           55 |     1792 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.672      | -            | -                | -                | -         |   -11.05 | K1-FiDa, Levi, NEOFRAG, Pechyn, woozzzi |
|           54 |     2525 | 2024-11-30 | Partizan Esports                          | L   | 0.585      | -            | -                | -                | -         |    -4.21 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           53 |     2715 | 2024-11-26 | Nexus Gaming                              | L   | 0.559      | -            | -                | -                | -         |    -2.94 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           52 |     2807 | 2024-11-24 | Dynamo Eclot                              | L   | 0.544      | -            | -                | -                | -         |    -4.04 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           51 |     2887 | 2024-11-23 | Permitta Esports                          | L   | 0.538      | -            | -                | -                | -         |    -9.06 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           50 |     2920 | 2024-11-23 | Team Sampi                                | W   | 0.536      | -            | -                | -                | 1 (0.536) |     7.33 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           49 |     2980 | 2024-11-22 | BC.Game Esports                           | W   | 0.531      | 0.372        | 0.022 (0.004)    | 0.551 (0.109)    | 0 (0.000) |     8.17 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           48 |     3222 | 2024-11-18 | GamerLegion                               | L   | 0.503      | -            | -                | -                | -         |    -0.27 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           47 |     3262 | 2024-11-17 | SAW                                       | L   | 0.497      | -            | -                | -                | -         |    -0.99 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           46 |     3296 | 2024-11-16 | BetBoom Team                              | L   | 0.496      | -            | -                | -                | -         |    -3.97 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           45 |     3678 | 2024-11-10 | RUSTEC                                    | W   | 0.451      | -            | -                | -                | 0 (0.000) |     3.83 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           44 |     3680 | 2024-11-10 | RUSTEC                                    | W   | 0.451      | -            | -                | -                | 0 (0.000) |     2.50 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           43 |     3683 | 2024-11-10 | FLuffy Gangsters                          | W   | 0.451      | 0.372        | 0.014 (0.002)    | 0.909 (0.153)    | -         |     6.21 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           42 |     3844 | 2024-11-07 | Lazer Cats                                | L   | 0.432      | -            | -                | -                | -         |    -8.72 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           41 |     3890 | 2024-11-06 | TEAM NEXT LEVEL                           | W   | 0.425      | 0.372        | 0.040 (0.006)    | 0.500 (0.079)    | -         |     6.75 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           40 |     3896 | 2024-11-06 | Leo Team                                  | L   | 0.425      | -            | -                | -                | -         |    -6.71 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           39 |     4389 | 2024-10-29 | QUAZAR                                    | W   | 0.371      | -            | -                | -                | -         |     4.15 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           38 |     4422 | 2024-10-28 | Daystar                                   | L   | 0.365      | -            | -                | -                | -         |    -8.56 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           37 |     4639 | 2024-10-24 | HOTU                                      | L   | 0.337      | -            | -                | -                | -         |    -7.28 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           36 |     4739 | 2024-10-21 | Grindas                                   | W   | 0.318      | -            | -                | -                | -         |     1.40 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           35 |     4762 | 2024-10-21 | Johnny Speeds                             | L   | 0.317      | -            | -                | -                | -         |    -4.26 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           34 |     4790 | 2024-10-20 | Team Spirit Academy                       | W   | 0.311      | 0.372        | 0.068 (0.008)    | 0.702 (0.081)    | -         |     6.24 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           33 |     5035 | 2024-10-16 | WOPA Esport                               | L   | 0.282      | -            | -                | -                | -         |    -4.54 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           32 |     5127 | 2024-10-14 | 500                                       | L   | 0.270      | -            | -                | -                | -         |    -2.61 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           31 |     5276 | 2024-10-11 | 500                                       | L   | 0.250      | -            | -                | -                | -         |    -2.50 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           30 |     5470 | 2024-10-07 | Dynamo Eclot                              | W   | 0.225      | 0.143        | 0.128 (0.004)    | -                | -         |     5.46 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           29 |     5477 | 2024-10-07 | HOTU                                      | W   | 0.225      | 0.372        | -                | 0.768 (0.064)    | -         |     2.42 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           28 |     5507 | 2024-10-07 | Natus Vincere Junior                      | L   | 0.223      | -            | -                | -                | -         |    -2.40 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           27 |     5510 | 2024-10-07 | 9INE                                      | W   | 0.222      | -            | -                | -                | -         |     2.75 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           26 |     5550 | 2024-10-06 | Leo Team                                  | L   | 0.216      | -            | -                | -                | -         |    -3.53 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           25 |     5700 | 2024-10-04 | Preasy Esport                             | W   | 0.202      | 0.333        | -                | 0.701 (0.047)    | -         |     2.80 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           24 |     5782 | 2024-10-02 | FAVBET Team                               | W   | 0.191      | 0.384        | 0.031 (0.002)    | 0.801 (0.059)    | -         |     2.89 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           23 |     5806 | 2024-10-02 | Viperio                                   | W   | 0.189      | -            | -                | -                | -         |     2.23 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           22 |     5883 | 2024-10-01 | Partizan Esports                          | L   | 0.183      | -            | -                | -                | -         |    -1.20 | blogg1s, K1-FiDa, Levi, NEOFRAG, Pechyn |
|           21 |     5967 | 2024-09-29 | GardenGarage                              | W   | 0.171      | -            | -                | -                | -         |     2.01 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           20 |     6092 | 2024-09-28 | ALASKA                                    | W   | 0.162      | 0.333        | 0.031 (0.002)    | -                | -         |     4.33 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           19 |     6154 | 2024-09-27 | Wild Lotus                                | L   | 0.157      | -            | -                | -                | -         |    -3.10 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           18 |     6375 | 2024-09-24 | Kyoto (European mix-team)                 | L   | 0.138      | -            | -                | -                | -         |    -3.15 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           17 |     6392 | 2024-09-24 | Haspers Team                              | W   | 0.138      | -            | -                | -                | -         |     1.39 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           16 |     6424 | 2024-09-24 | Astralis Talent                           | W   | 0.136      | -            | -                | -                | -         |     1.76 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           15 |     6432 | 2024-09-24 | Dark Cloud Esports                        | W   | 0.135      | 0.371        | 0.039 (0.002)    | -                | -         |     2.11 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           14 |     6523 | 2024-09-22 | SINNERS Esports                           | W   | 0.124      | -            | -                | -                | 1 (0.124) |     2.38 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           13 |     6588 | 2024-09-21 | SINNERS Esports                           | W   | 0.118      | -            | -                | -                | 1 (0.118) |     2.27 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           12 |     6653 | 2024-09-20 | Team Sampi                                | W   | 0.110      | -            | -                | -                | 1 (0.110) |     1.59 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           11 |     6665 | 2024-09-20 | ALTERNATE aTTaX                           | L   | 0.109      | -            | -                | -                | -         |    -1.25 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|           10 |     6823 | 2024-09-17 | Red Bottom Sky                            | W   | 0.092      | -            | -                | -                | -         |     0.24 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            9 |     6826 | 2024-09-17 | Haspers Team                              | W   | 0.092      | -            | -                | -                | -         |     0.59 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            8 |     7110 | 2024-09-13 | GameAgents                                | L   | 0.063      | -            | -                | -                | -         |    -1.39 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            7 |     7167 | 2024-09-12 | Ex-ENTERPRISE esports                     | L   | 0.055      | -            | -                | -                | -         |    -1.14 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            6 |     7328 | 2024-09-09 | Astralis Talent                           | W   | 0.036      | -            | -                | -                | -         |     0.48 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            5 |     7368 | 2024-09-08 | Sampi NEXT                                | W   | 0.030      | -            | -                | -                | -         |     0.13 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            4 |     7435 | 2024-09-07 | Team PeeP                                 | L   | 0.024      | -            | -                | -                | -         |    -0.66 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            3 |     7539 | 2024-09-06 | SINNERS Esports                           | L   | 0.017      | -            | -                | -                | -         |    -0.21 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            2 |     7605 | 2024-09-05 | Copenhagen Wolves (American organization) | L   | 0.011      | -            | -                | -                | -         |    -0.26 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |
|            1 |     7622 | 2024-09-05 | Sampi NEXT                                | W   | 0.010      | -            | -                | -                | -         |     0.04 | blogg1s, K1-FiDa, Levi, M1key, Pechyn   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,377.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $13,154.54     | $7,150.95       |
| 2024-10-08 |      0.229 | $1,000.00      | $228.89         |
| 2024-09-22 |      0.124 | $8,017.32      | $997.34         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
