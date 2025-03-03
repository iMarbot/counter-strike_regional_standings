### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  878.3<br />
<br />
Final Rank Value (878.3) = Starting Rank Value (866.2) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.2
- 400 + ( ( 0.233 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 866.2


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
|           69 |      572 | 2025-02-11 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |      595 | 2025-02-10 | NEVERMORE (Ukrainian team)                | W   | 1.000      | 0.143        | -                | 0.904 (0.129)    | 0 (0.000) |    14.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |      605 | 2025-02-10 | HEROIC                                    | L   | 1.000      | -            | -                | -                | -         |    -5.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |      671 | 2025-02-08 | Little Red Door                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |      687 | 2025-02-08 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -7.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |      692 | 2025-02-08 | ENCE                                      | W   | 1.000      | 0.143        | 0.136 (0.019)    | -                | 0 (0.000) |    22.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |      704 | 2025-02-08 | FORZE Reload                              | W   | 1.000      | 0.143        | 0.026 (0.004)    | 0.552 (0.079)    | 0 (0.000) |    17.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |      724 | 2025-02-08 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -12.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |      758 | 2025-02-07 | Arch Esports                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |      889 | 2025-02-05 | KONO.ECF                                  | L   | 1.000      | -            | -                | -                | -         |   -22.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |      953 | 2025-02-04 | RUSH B (Russian team)                     | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.915 (0.131)    | 0 (0.000) |    17.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1014 | 2025-02-04 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -24.28 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1022 | 2025-02-04 | Superior Esports                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1127 | 2025-01-28 | Wild Lotus                                | L   | 0.979      | -            | -                | -                | -         |   -18.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1135 | 2025-01-27 | Adventurers                               | W   | 0.970      | -            | -                | -                | 0 (0.000) |    12.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1137 | 2025-01-26 | AMKAL ESPORTS                             | L   | 0.965      | -            | -                | -                | -         |   -17.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1395 | 2024-12-22 | RUSH B (Russian team)                     | L   | 0.732      | -            | -                | -                | -         |   -10.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1399 | 2024-12-22 | Metizport                                 | L   | 0.732      | -            | -                | -                | -         |    -7.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1452 | 2024-12-21 | Alliance                                  | W   | 0.725      | -            | -                | -                | -         |    10.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1719 | 2024-12-14 | ECSTATIC                                  | L   | 0.677      | -            | -                | -                | -         |   -10.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1844 | 2024-12-12 | AMKAL ESPORTS                             | W   | 0.665      | 0.435        | -                | 0.674 (0.195)    | -         |     8.76 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2411 | 2024-12-01 | FORZE Reload                              | W   | 0.592      | -            | -                | -                | -         |     8.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2422 | 2024-12-01 | RUSH B (Russian team)                     | W   | 0.592      | 0.143        | -                | 0.915 (0.077)    | -         |     9.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2436 | 2024-12-01 | Los kogutos                               | W   | 0.591      | -            | -                | -                | -         |     1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2884 | 2024-11-23 | ENCE                                      | L   | 0.538      | -            | -                | -                | -         |    -5.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     3237 | 2024-11-17 | 0to100                                    | W   | 0.499      | -            | -                | -                | 1 (0.499) |     5.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     3359 | 2024-11-16 | Juggernauts                               | W   | 0.489      | -            | -                | -                | 1 (0.489) |     3.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     3609 | 2024-11-11 | Ninjas in Pyjamas                         | L   | 0.459      | -            | -                | -                | -         |    -7.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     3660 | 2024-11-10 | Tricked Esport                            | W   | 0.452      | 0.384        | 0.034 (0.006)    | 0.687 (0.119)    | -         |     6.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     3726 | 2024-11-09 | GUN5 Esports                              | W   | 0.445      | 0.143        | 0.103 (0.007)    | -                | -         |     8.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     3817 | 2024-11-08 | Johnny Speeds                             | W   | 0.437      | 0.384        | 0.039 (0.007)    | -                | -         |     8.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     3911 | 2024-11-06 | HOTU                                      | W   | 0.423      | 0.384        | -                | 0.768 (0.125)    | -         |     3.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     4025 | 2024-11-04 | 500                                       | L   | 0.410      | -            | -                | -                | -         |    -3.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     4146 | 2024-11-02 | Los kogutos                               | W   | 0.398      | 0.384        | 0.032 (0.005)    | 0.515 (0.079)    | -         |     7.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     4392 | 2024-10-29 | OG                                        | L   | 0.371      | -            | -                | -                | -         |    -4.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     4435 | 2024-10-28 | 500                                       | L   | 0.365      | -            | -                | -                | -         |    -3.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     4451 | 2024-10-28 | Dynamo Eclot                              | L   | 0.364      | -            | -                | -                | -         |    -2.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     4455 | 2024-10-28 | Wu-Tang Clan                              | W   | 0.363      | -            | -                | -                | -         |     1.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     5071 | 2024-10-15 | 9Pandas                                   | L   | 0.278      | -            | -                | -                | -         |    -3.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     5312 | 2024-10-10 | Aurora Gaming                             | L   | 0.242      | -            | -                | -                | -         |    -4.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     5503 | 2024-10-07 | ECSTATIC                                  | W   | 0.223      | 0.435        | 0.033 (0.003)    | 0.820 (0.080)    | -         |     3.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     5536 | 2024-10-06 | MADNESS (Kosovar team)                    | W   | 0.217      | -            | -                | -                | -         |     0.94 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     5609 | 2024-10-05 | Team Spirit Academy                       | L   | 0.210      | -            | -                | -                | -         |    -2.77 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     5881 | 2024-10-01 | FAVBET Team                               | W   | 0.183      | 0.435        | -                | 0.801 (0.064)    | -         |     2.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     6291 | 2024-09-25 | Tricked Esport                            | L   | 0.145      | -            | -                | -                | -         |    -2.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     6323 | 2024-09-25 | 3DMAX                                     | L   | 0.143      | -            | -                | -                | -         |    -0.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     6429 | 2024-09-24 | 3DMAX                                     | L   | 0.135      | -            | -                | -                | -         |    -0.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     6477 | 2024-09-23 | SINNERS Esports                           | W   | 0.131      | -            | -                | -                | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     6491 | 2024-09-23 | Nexus Gaming                              | W   | 0.130      | 0.435        | 0.187 (0.011)    | -                | -         |     3.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     6541 | 2024-09-22 | Copenhagen Wolves (American organization) | L   | 0.123      | -            | -                | -                | -         |    -3.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     6714 | 2024-09-19 | FAVBET Team                               | W   | 0.104      | -            | -                | -                | -         |     1.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     6791 | 2024-09-18 | Monte                                     | L   | 0.096      | -            | -                | -                | -         |    -1.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     6829 | 2024-09-17 | Sampi NEXT                                | L   | 0.092      | -            | -                | -                | -         |    -2.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     6895 | 2024-09-16 | ECSTATIC                                  | W   | 0.085      | -            | -                | -                | -         |     1.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     7011 | 2024-09-14 | GamerLegion                               | L   | 0.071      | -            | -                | -                | -         |    -1.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     7053 | 2024-09-14 | Rebels Gaming                             | L   | 0.069      | -            | -                | -                | -         |    -1.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     7105 | 2024-09-13 | 3DMAX                                     | W   | 0.063      | 0.384        | 0.298 (0.007)    | -                | -         |     1.97 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     7151 | 2024-09-12 | EYEBALLERS                                | W   | 0.057      | -            | -                | -                | -         |     0.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     7206 | 2024-09-11 | Metizport                                 | W   | 0.050      | -            | -                | -                | -         |     1.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     7240 | 2024-09-10 | Devils.one                                | L   | 0.045      | -            | -                | -                | -         |    -1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     7249 | 2024-09-10 | Ins (Polish team)                         | W   | 0.045      | -            | -                | -                | -         |     0.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     7325 | 2024-09-09 | Metizport                                 | W   | 0.036      | -            | -                | -                | -         |     0.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     7367 | 2024-09-08 | B8                                        | L   | 0.030      | -            | -                | -                | -         |    -0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     7417 | 2024-09-07 | Nemiga Gaming                             | W   | 0.025      | -            | -                | -                | -         |     0.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     7463 | 2024-09-07 | Cloud9                                    | L   | 0.023      | -            | -                | -                | -         |    -0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     7549 | 2024-09-06 | Young Ninjas                              | W   | 0.016      | -            | -                | -                | -         |     0.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     7613 | 2024-09-05 | Alliance                                  | W   | 0.011      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     7688 | 2024-09-04 | ECSTATIC                                  | W   | 0.004      | -            | -                | -                | -         |     0.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     7698 | 2024-09-04 | SINNERS Esports                           | W   | 0.002      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,064.64)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $2,000.00      | $1,369.44       |
| 2024-11-24 |      0.544 | $1,864.89      | $1,014.55       |
| 2024-11-17 |      0.499 | $7,908.47      | $3,942.70       |
| 2024-11-12 |      0.464 | $1,000.00      | $464.42         |
| 2024-10-20 |      0.311 | $5,000.00      | $1,553.47       |
| 2024-09-26 |      0.151 | $1,000.00      | $150.79         |
| 2024-09-15 |      0.078 | $2,000.00      | $155.23         |
| 2024-09-14 |      0.071 | $2,000.00      | $142.50         |
| 2024-09-08 |      0.031 | $5,000.00      | $154.86         |
| 2024-09-07 |      0.023 | $5,000.00      | $116.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
