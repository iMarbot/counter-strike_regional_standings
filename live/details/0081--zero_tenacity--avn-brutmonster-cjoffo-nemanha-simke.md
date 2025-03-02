### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [81](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  880.5<br />
<br />
Final Rank Value (880.5) = Starting Rank Value (868.5) + Head To Head Adjustments (12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.319[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.5
- 400 + ( ( 0.235 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 868.5


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
|           70 |      560 | 2025-02-11 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |      583 | 2025-02-10 | NEVERMORE (Ukrainian team)                | W   | 1.000      | 0.143        | -                | 0.911 (0.130)    | 0 (0.000) |    14.46 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |      593 | 2025-02-10 | HEROIC                                    | L   | 1.000      | -            | -                | -                | -         |    -5.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |      659 | 2025-02-08 | Little Red Door                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |      675 | 2025-02-08 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -7.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |      680 | 2025-02-08 | ENCE                                      | W   | 1.000      | 0.143        | 0.136 (0.019)    | -                | 0 (0.000) |    22.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |      692 | 2025-02-08 | FORZE Reload                              | W   | 1.000      | 0.143        | 0.026 (0.004)    | 0.559 (0.080)    | 0 (0.000) |    17.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |      712 | 2025-02-08 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -12.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |      746 | 2025-02-07 | Arch Esports                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |      877 | 2025-02-05 | KONO.ECF                                  | L   | 1.000      | -            | -                | -                | -         |   -22.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |      941 | 2025-02-04 | RUSH B (Russian team)                     | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.921 (0.132)    | 0 (0.000) |    17.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1002 | 2025-02-04 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -24.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1010 | 2025-02-04 | Superior Esports                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1115 | 2025-01-28 | Wild Lotus                                | L   | 0.987      | -            | -                | -                | -         |   -18.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1123 | 2025-01-27 | Adventurers                               | W   | 0.979      | -            | -                | -                | 0 (0.000) |    12.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1125 | 2025-01-26 | AMKAL ESPORTS                             | L   | 0.973      | -            | -                | -                | -         |   -17.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1383 | 2024-12-22 | RUSH B (Russian team)                     | L   | 0.740      | -            | -                | -                | -         |   -10.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1387 | 2024-12-22 | Metizport                                 | L   | 0.740      | -            | -                | -                | -         |    -7.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1440 | 2024-12-21 | Alliance                                  | W   | 0.733      | -            | -                | -                | -         |    10.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1707 | 2024-12-14 | ECSTATIC                                  | L   | 0.685      | -            | -                | -                | -         |   -10.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1832 | 2024-12-12 | AMKAL ESPORTS                             | W   | 0.673      | 0.435        | -                | 0.681 (0.199)    | -         |     8.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     2399 | 2024-12-01 | FORZE Reload                              | W   | 0.600      | -            | -                | -                | -         |     9.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2410 | 2024-12-01 | RUSH B (Russian team)                     | W   | 0.600      | 0.143        | -                | 0.921 (0.079)    | -         |     9.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2424 | 2024-12-01 | Los kogutos                               | W   | 0.600      | -            | -                | -                | -         |     1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2872 | 2024-11-23 | ENCE                                      | L   | 0.546      | -            | -                | -                | -         |    -5.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     3225 | 2024-11-17 | 0to100                                    | W   | 0.507      | -            | -                | -                | 1 (0.507) |     5.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     3347 | 2024-11-16 | Juggernauts                               | W   | 0.498      | -            | -                | -                | 1 (0.498) |     3.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     3597 | 2024-11-11 | Ninjas in Pyjamas                         | L   | 0.467      | -            | -                | -                | -         |    -7.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     3648 | 2024-11-10 | Tricked Esport                            | W   | 0.460      | 0.384        | 0.033 (0.006)    | 0.696 (0.123)    | -         |     6.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     3714 | 2024-11-09 | GUN5 Esports                              | W   | 0.453      | 0.143        | 0.102 (0.007)    | -                | -         |     8.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     3805 | 2024-11-08 | Johnny Speeds                             | W   | 0.445      | 0.384        | 0.039 (0.007)    | -                | -         |     8.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     3899 | 2024-11-06 | HOTU                                      | W   | 0.432      | 0.384        | -                | 0.777 (0.129)    | -         |     3.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     4015 | 2024-11-04 | 500                                       | L   | 0.418      | -            | -                | -                | -         |    -4.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     4134 | 2024-11-02 | Los kogutos                               | W   | 0.406      | 0.384        | 0.032 (0.005)    | 0.527 (0.082)    | -         |     7.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     4380 | 2024-10-29 | OG                                        | L   | 0.379      | -            | -                | -                | -         |    -4.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     4423 | 2024-10-28 | 500                                       | L   | 0.373      | -            | -                | -                | -         |    -3.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     4439 | 2024-10-28 | Dynamo Eclot                              | L   | 0.372      | -            | -                | -                | -         |    -3.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     4443 | 2024-10-28 | Wu-Tang Clan                              | W   | 0.371      | -            | -                | -                | -         |     1.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     5059 | 2024-10-15 | 9Pandas                                   | L   | 0.286      | -            | -                | -                | -         |    -3.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     5300 | 2024-10-10 | Aurora Gaming                             | L   | 0.250      | -            | -                | -                | -         |    -4.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     5491 | 2024-10-07 | ECSTATIC                                  | W   | 0.232      | 0.435        | 0.033 (0.003)    | 0.828 (0.083)    | -         |     3.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     5524 | 2024-10-06 | MADNESS (Kosovar team)                    | W   | 0.226      | -            | -                | -                | -         |     0.95 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     5601 | 2024-10-05 | Team Spirit Academy                       | L   | 0.219      | -            | -                | -                | -         |    -2.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     5869 | 2024-10-01 | FAVBET Team                               | W   | 0.191      | 0.435        | -                | 0.814 (0.068)    | -         |     2.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     6279 | 2024-09-25 | Tricked Esport                            | L   | 0.153      | -            | -                | -                | -         |    -2.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     6311 | 2024-09-25 | 3DMAX                                     | L   | 0.151      | -            | -                | -                | -         |    -0.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     6417 | 2024-09-24 | 3DMAX                                     | L   | 0.144      | -            | -                | -                | -         |    -0.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     6465 | 2024-09-23 | SINNERS Esports                           | W   | 0.140      | -            | -                | -                | -         |     2.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     6479 | 2024-09-23 | Nexus Gaming                              | W   | 0.138      | 0.435        | 0.186 (0.011)    | -                | -         |     3.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     6529 | 2024-09-22 | Copenhagen Wolves (American organization) | L   | 0.131      | -            | -                | -                | -         |    -3.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     6702 | 2024-09-19 | FAVBET Team                               | W   | 0.112      | -            | -                | -                | -         |     1.65 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     6779 | 2024-09-18 | Monte                                     | L   | 0.104      | -            | -                | -                | -         |    -1.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     6817 | 2024-09-17 | Sampi NEXT                                | L   | 0.100      | -            | -                | -                | -         |    -2.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     6883 | 2024-09-16 | ECSTATIC                                  | W   | 0.093      | -            | -                | -                | -         |     1.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     6999 | 2024-09-14 | GamerLegion                               | L   | 0.079      | -            | -                | -                | -         |    -1.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     7041 | 2024-09-14 | Rebels Gaming                             | L   | 0.077      | -            | -                | -                | -         |    -1.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     7093 | 2024-09-13 | 3DMAX                                     | W   | 0.072      | 0.384        | 0.295 (0.008)    | -                | -         |     2.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     7139 | 2024-09-12 | EYEBALLERS                                | W   | 0.065      | -            | -                | -                | -         |     0.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     7194 | 2024-09-11 | Metizport                                 | W   | 0.058      | -            | -                | -                | -         |     1.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     7228 | 2024-09-10 | Devils.one                                | L   | 0.054      | -            | -                | -                | -         |    -1.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     7237 | 2024-09-10 | Ins (Polish team)                         | W   | 0.053      | -            | -                | -                | -         |     0.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     7313 | 2024-09-09 | Metizport                                 | W   | 0.044      | -            | -                | -                | -         |     1.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     7355 | 2024-09-08 | B8                                        | L   | 0.038      | -            | -                | -                | -         |    -0.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     7405 | 2024-09-07 | Nemiga Gaming                             | W   | 0.033      | -            | -                | -                | -         |     0.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     7451 | 2024-09-07 | Cloud9                                    | L   | 0.032      | -            | -                | -                | -         |    -0.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     7537 | 2024-09-06 | Young Ninjas                              | W   | 0.024      | -            | -                | -                | -         |     0.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     7601 | 2024-09-05 | Alliance                                  | W   | 0.019      | -            | -                | -                | -         |     0.32 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     7676 | 2024-09-04 | ECSTATIC                                  | W   | 0.012      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     7686 | 2024-09-04 | SINNERS Esports                           | W   | 0.010      | -            | -                | -                | -         |     0.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     7746 | 2024-09-03 | TEAM NEXT LEVEL                           | W   | 0.005      | -            | -                | -                | -         |     0.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,333.20)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $2,000.00      | $1,385.83       |
| 2024-11-24 |      0.552 | $1,864.89      | $1,029.83       |
| 2024-11-17 |      0.507 | $7,908.47      | $4,007.51       |
| 2024-11-12 |      0.473 | $1,000.00      | $472.62         |
| 2024-10-20 |      0.319 | $5,000.00      | $1,594.44       |
| 2024-09-26 |      0.159 | $1,000.00      | $158.98         |
| 2024-09-15 |      0.086 | $2,000.00      | $171.62         |
| 2024-09-14 |      0.079 | $2,000.00      | $158.89         |
| 2024-09-08 |      0.039 | $5,000.00      | $195.83         |
| 2024-09-07 |      0.032 | $5,000.00      | $157.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
