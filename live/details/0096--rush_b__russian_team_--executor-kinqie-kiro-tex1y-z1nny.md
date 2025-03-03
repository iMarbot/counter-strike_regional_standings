### Roster Details<br />
Team Name: RUSH B (Russian team)<br />
Roster: executor, kinqie, KIRO, tex1y, z1Nny<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  863.7<br />
<br />
Final Rank Value (863.7) = Starting Rank Value (893.2) + Head To Head Adjustments (-29.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.159[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.2
- 400 + ( ( 0.247 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 893.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |       21 | 2025-02-28 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -17.59 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           60 |       29 | 2025-02-27 | ALASKA                          | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.867 (0.124)    | 0 (0.000) |    15.72 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           59 |       38 | 2025-02-26 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -17.82 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           58 |       73 | 2025-02-24 | PARIVISION                      | L   | 1.000      | -            | -                | -                | -         |   -17.70 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           57 |      109 | 2025-02-23 | ESC Gaming                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.31 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           56 |      175 | 2025-02-22 | Rebels Gaming                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.97 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           55 |      193 | 2025-02-21 | Fire Flux Esports               | L   | 1.000      | -            | -                | -                | -         |   -14.74 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           54 |      218 | 2025-02-21 | Astralis Talent                 | L   | 1.000      | -            | -                | -                | -         |   -22.70 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           53 |      249 | 2025-02-20 | Benched                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.00 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           52 |      276 | 2025-02-18 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -14.82 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           51 |      319 | 2025-02-17 | Fnatic                          | L   | 1.000      | -            | -                | -                | -         |   -10.47 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           50 |      428 | 2025-02-15 | KONO.ECF                        | L   | 1.000      | -            | -                | -                | -         |   -25.06 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           49 |      477 | 2025-02-14 | QUAZAR                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           48 |      493 | 2025-02-14 | GTZ.ESPORTS                     | W   | 1.000      | 0.435        | 0.080 (0.035)    | 0.557 (0.242)    | 0 (0.000) |    19.92 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           47 |      596 | 2025-02-10 | Sashi Esport                    | W   | 1.000      | 0.435        | 0.013 (0.006)    | 0.499 (0.217)    | 0 (0.000) |    14.99 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           46 |      645 | 2025-02-09 | OG                              | W   | 1.000      | 0.143        | 0.062 (0.009)    | 1.000 (0.143)    | 0 (0.000) |    16.85 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           45 |      714 | 2025-02-08 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -13.71 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           44 |      724 | 2025-02-08 | Zero Tenacity                   | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.684 (0.098)    | -         |    12.16 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           43 |      774 | 2025-02-07 | Heimo Esports                   | W   | 1.000      | 0.143        | -                | 0.651 (0.093)    | -         |     8.94 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           42 |      923 | 2025-02-05 | Adventurers                     | W   | 1.000      | 0.143        | 0.016 (0.002)    | -                | -         |    10.87 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           41 |      953 | 2025-02-04 | Zero Tenacity                   | L   | 1.000      | -            | -                | -                | -         |   -17.89 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           40 |      978 | 2025-02-04 | Monte                           | L   | 1.000      | -            | -                | -                | -         |   -15.12 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           39 |     1395 | 2024-12-22 | Zero Tenacity                   | W   | 0.732      | 0.143        | 0.028 (0.003)    | 0.684 (0.072)    | -         |    10.80 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           38 |     1413 | 2024-12-22 | P0RTUGAL                        | L   | 0.731      | -            | -                | -                | -         |   -14.35 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           37 |     1470 | 2024-12-21 | JANO Esports                    | W   | 0.724      | 0.143        | 0.022 (0.002)    | -                | -         |     9.18 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           36 |     1634 | 2024-12-15 | FORZE Reload                    | W   | 0.685      | 0.143        | 0.026 (0.003)    | 0.552 (0.054)    | 1 (0.685) |    10.10 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           35 |     1725 | 2024-12-14 | K27                             | W   | 0.676      | 0.143        | -                | 0.769 (0.074)    | 1 (0.676) |     9.57 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           34 |     1985 | 2024-12-08 | 0to100                          | W   | 0.639      | -            | -                | -                | -         |     6.61 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           33 |     1992 | 2024-12-08 | Preasy Esport                   | W   | 0.639      | 0.143        | -                | 0.701 (0.064)    | -         |     6.66 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           32 |     2009 | 2024-12-08 | Aimclub                         | W   | 0.638      | -            | -                | -                | -         |     1.23 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           31 |     2422 | 2024-12-01 | Zero Tenacity                   | L   | 0.592      | -            | -                | -                | -         |    -9.58 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           30 |     2433 | 2024-12-01 | EYEBALLERS                      | W   | 0.592      | -            | -                | -                | -         |     6.84 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           29 |     2810 | 2024-11-24 | Premdesant                      | W   | 0.543      | -            | -                | -                | -         |     4.07 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           28 |     3259 | 2024-11-17 | INDINDA                         | W   | 0.497      | -            | -                | -                | -         |     1.84 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           27 |     3273 | 2024-11-17 | LEON Esports                    | L   | 0.497      | -            | -                | -                | -         |   -10.88 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           26 |     3287 | 2024-11-17 | XP Academy                      | W   | 0.496      | -            | -                | -                | -         |     2.49 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           25 |     3752 | 2024-11-09 | Nuclear TigeRES                 | W   | 0.443      | -            | -                | -                | -         |     6.12 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           24 |     3759 | 2024-11-09 | VOID GAMING (Russian team)      | W   | 0.443      | -            | -                | -                | -         |     1.15 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           23 |     4052 | 2024-11-03 | ARCRED                          | L   | 0.405      | -            | -                | -                | -         |    -8.35 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           22 |     4135 | 2024-11-02 | 1win                            | W   | 0.398      | -            | -                | -                | -         |     4.04 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           21 |     4198 | 2024-11-01 | Nuclear TigeRES                 | W   | 0.392      | -            | -                | -                | -         |     5.37 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           20 |     4481 | 2024-10-27 | K27                             | W   | 0.358      | -            | -                | -                | -         |     5.93 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           19 |     4519 | 2024-10-26 | ECSTATIC                        | L   | 0.351      | -            | -                | -                | -         |    -5.55 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           18 |     4636 | 2024-10-24 | NewBALLS                        | W   | 0.337      | -            | -                | -                | -         |     2.38 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           17 |     4757 | 2024-10-21 | ARCRED                          | L   | 0.317      | -            | -                | -                | -         |    -6.81 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           16 |     4781 | 2024-10-20 | Wu-Tang Clan                    | L   | 0.312      | -            | -                | -                | -         |    -8.80 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           15 |     4794 | 2024-10-20 | GenOne                          | W   | 0.311      | -            | -                | -                | -         |     4.13 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           14 |     4870 | 2024-10-19 | GTZ.ESPORTS                     | W   | 0.303      | 0.143        | 0.080 (0.003)    | -                | -         |     8.12 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           13 |     5167 | 2024-10-13 | FAVBET Team                     | L   | 0.263      | -            | -                | -                | -         |    -4.62 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           12 |     6277 | 2024-09-25 | Fire Flux Esports               | L   | 0.146      | -            | -                | -                | -         |    -2.56 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           11 |     6458 | 2024-09-23 | Asian fetish                    | W   | 0.132      | -            | -                | -                | -         |     0.66 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           10 |     6568 | 2024-09-21 | Freesunshine                    | W   | 0.119      | -            | -                | -                | -         |     0.51 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            9 |     6575 | 2024-09-21 | Cerberus eSports (Russian team) | W   | 0.118      | -            | -                | -                | -         |     0.60 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            8 |     7022 | 2024-09-14 | ARCRED                          | L   | 0.070      | -            | -                | -                | -         |    -1.51 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            7 |     7055 | 2024-09-14 | Devils.one                      | L   | 0.069      | -            | -                | -                | -         |    -1.74 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            6 |     7147 | 2024-09-12 | Nexus Gaming                    | L   | 0.057      | -            | -                | -                | -         |    -0.29 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            5 |     7433 | 2024-09-07 | FLuffy Gangsters                | W   | 0.024      | -            | -                | -                | -         |     0.28 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            4 |     7450 | 2024-09-07 | Partizan Esports                | W   | 0.024      | -            | -                | -                | -         |     0.56 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            3 |     7503 | 2024-09-06 | Asian fetish                    | W   | 0.019      | -            | -                | -                | -         |     0.05 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            2 |     7513 | 2024-09-06 | ZEROvariant                     | W   | 0.018      | -            | -                | -                | -         |     0.03 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            1 |     7616 | 2024-09-05 | HOTU                            | L   | 0.011      | -            | -                | -                | -         |    -0.24 | executor, Gospadarov, kinqie, KIRO, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,128.22)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $2,607.56      | $1,909.68       |
| 2024-12-15 |      0.685 | $7,263.25      | $4,972.64       |
| 2024-11-03 |      0.405 | $5,108.69      | $2,069.73       |
| 2024-09-23 |      0.132 | $1,300.00      | $171.35         |
| 2024-09-07 |      0.024 | $200.00        | $4.83           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
