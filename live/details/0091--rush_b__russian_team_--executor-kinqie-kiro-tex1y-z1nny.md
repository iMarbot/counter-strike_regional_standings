### Roster Details<br />
Team Name: RUSH B (Russian team)<br />
Roster: executor, kinqie, KIRO, tex1y, z1Nny<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  864.9<br />
<br />
Final Rank Value (864.9) = Starting Rank Value (893.6) + Head To Head Adjustments (-28.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.119[<sup>2</sup>](#table1)
- LAN Wins: 0.161[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.6
- 400 + ( ( 0.247 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 893.6


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
|           61 |        6 | 2025-02-28 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -17.56 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           60 |       14 | 2025-02-27 | ALASKA                          | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.875 (0.125)    | 0 (0.000) |    15.63 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           59 |       23 | 2025-02-26 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -17.79 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           58 |       58 | 2025-02-24 | PARIVISION                      | L   | 1.000      | -            | -                | -                | -         |   -17.74 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           57 |       94 | 2025-02-23 | ESC Gaming                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.30 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           56 |      163 | 2025-02-22 | Rebels Gaming                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.98 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           55 |      181 | 2025-02-21 | Fire Flux Esports               | L   | 1.000      | -            | -                | -                | -         |   -14.72 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           54 |      206 | 2025-02-21 | Astralis Talent                 | L   | 1.000      | -            | -                | -                | -         |   -22.66 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           53 |      237 | 2025-02-20 | Benched                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.97 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           52 |      264 | 2025-02-18 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -14.79 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           51 |      307 | 2025-02-17 | Fnatic                          | L   | 1.000      | -            | -                | -                | -         |   -10.43 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           50 |      416 | 2025-02-15 | KONO.ECF                        | L   | 1.000      | -            | -                | -                | -         |   -25.06 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           49 |      465 | 2025-02-14 | QUAZAR                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.36 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           48 |      481 | 2025-02-14 | GTZ.ESPORTS                     | W   | 1.000      | 0.435        | 0.080 (0.035)    | 0.563 (0.245)    | 0 (0.000) |    19.91 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           47 |      584 | 2025-02-10 | Sashi Esport                    | W   | 1.000      | 0.435        | 0.013 (0.006)    | 0.503 (0.218)    | 0 (0.000) |    15.00 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           46 |      633 | 2025-02-09 | OG                              | W   | 1.000      | 0.143        | 0.062 (0.009)    | 1.000 (0.143)    | 0 (0.000) |    16.84 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           45 |      702 | 2025-02-08 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -13.67 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           44 |      712 | 2025-02-08 | Zero Tenacity                   | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.692 (0.099)    | -         |    12.21 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           43 |      762 | 2025-02-07 | Heimo Esports                   | W   | 1.000      | 0.143        | -                | 0.658 (0.094)    | -         |     9.01 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           42 |      911 | 2025-02-05 | Adventurers                     | W   | 1.000      | 0.143        | 0.017 (0.002)    | -                | -         |    10.94 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           41 |      941 | 2025-02-04 | Zero Tenacity                   | L   | 1.000      | -            | -                | -                | -         |   -17.82 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           40 |      966 | 2025-02-04 | Monte                           | L   | 1.000      | -            | -                | -                | -         |   -15.05 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           39 |     1383 | 2024-12-22 | Zero Tenacity                   | W   | 0.740      | 0.143        | 0.028 (0.003)    | 0.692 (0.073)    | -         |    10.99 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           38 |     1401 | 2024-12-22 | P0RTUGAL                        | L   | 0.739      | -            | -                | -                | -         |   -14.51 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           37 |     1458 | 2024-12-21 | JANO Esports                    | W   | 0.732      | 0.143        | 0.022 (0.002)    | -                | -         |     9.26 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           36 |     1622 | 2024-12-15 | FORZE Reload                    | W   | 0.693      | 0.143        | 0.026 (0.003)    | 0.559 (0.055)    | 1 (0.693) |    10.25 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           35 |     1713 | 2024-12-14 | K27                             | W   | 0.685      | 0.143        | -                | 0.776 (0.076)    | 1 (0.685) |     9.65 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           34 |     1973 | 2024-12-08 | 0to100                          | W   | 0.647      | -            | -                | -                | -         |     6.70 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           33 |     1980 | 2024-12-08 | Preasy Esport                   | W   | 0.647      | 0.143        | -                | 0.710 (0.066)    | -         |     6.82 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           32 |     1997 | 2024-12-08 | Aimclub                         | W   | 0.647      | -            | -                | -                | -         |     1.24 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           31 |     2410 | 2024-12-01 | Zero Tenacity                   | L   | 0.600      | -            | -                | -                | -         |    -9.64 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           30 |     2421 | 2024-12-01 | EYEBALLERS                      | W   | 0.600      | -            | -                | -                | -         |     6.93 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           29 |     2798 | 2024-11-24 | Premdesant                      | W   | 0.552      | -            | -                | -                | -         |     4.13 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           28 |     3247 | 2024-11-17 | INDINDA                         | W   | 0.505      | -            | -                | -                | -         |     1.88 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           27 |     3261 | 2024-11-17 | LEON Esports                    | L   | 0.505      | -            | -                | -                | -         |   -11.07 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           26 |     3275 | 2024-11-17 | XP Academy                      | W   | 0.504      | -            | -                | -                | -         |     2.55 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           25 |     3740 | 2024-11-09 | Nuclear TigeRES                 | W   | 0.452      | -            | -                | -                | -         |     6.23 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           24 |     3747 | 2024-11-09 | VOID GAMING (Russian team)      | W   | 0.451      | -            | -                | -                | -         |     1.17 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           23 |     4040 | 2024-11-03 | ARCRED                          | L   | 0.413      | -            | -                | -                | -         |    -8.51 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           22 |     4123 | 2024-11-02 | 1win                            | W   | 0.407      | -            | -                | -                | -         |     4.14 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           21 |     4186 | 2024-11-01 | Nuclear TigeRES                 | W   | 0.400      | -            | -                | -                | -         |     5.48 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           20 |     4469 | 2024-10-27 | K27                             | W   | 0.366      | -            | -                | -                | -         |     6.05 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           19 |     4507 | 2024-10-26 | ECSTATIC                        | L   | 0.359      | -            | -                | -                | -         |    -5.66 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           18 |     4624 | 2024-10-24 | NewBALLS                        | W   | 0.345      | -            | -                | -                | -         |     2.44 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           17 |     4745 | 2024-10-21 | ARCRED                          | L   | 0.325      | -            | -                | -                | -         |    -6.98 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           16 |     4769 | 2024-10-20 | Wu-Tang Clan                    | L   | 0.320      | -            | -                | -                | -         |    -9.04 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           15 |     4782 | 2024-10-20 | GenOne                          | W   | 0.319      | -            | -                | -                | -         |     4.27 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           14 |     4858 | 2024-10-19 | GTZ.ESPORTS                     | W   | 0.311      | 0.143        | 0.080 (0.004)    | -                | -         |     8.35 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           13 |     5155 | 2024-10-13 | FAVBET Team                     | L   | 0.271      | -            | -                | -                | -         |    -4.74 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           12 |     6265 | 2024-09-25 | Fire Flux Esports               | L   | 0.154      | -            | -                | -                | -         |    -2.69 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           11 |     6447 | 2024-09-23 | Asian fetish                    | W   | 0.140      | -            | -                | -                | -         |     0.70 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           10 |     6556 | 2024-09-21 | Freesunshine                    | W   | 0.127      | -            | -                | -                | -         |     0.55 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            9 |     6563 | 2024-09-21 | Cerberus eSports (Russian team) | W   | 0.127      | -            | -                | -                | -         |     0.64 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            8 |     7010 | 2024-09-14 | ARCRED                          | L   | 0.078      | -            | -                | -                | -         |    -1.69 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            7 |     7043 | 2024-09-14 | Devils.one                      | L   | 0.077      | -            | -                | -                | -         |    -1.94 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            6 |     7135 | 2024-09-12 | Nexus Gaming                    | L   | 0.066      | -            | -                | -                | -         |    -0.33 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            5 |     7421 | 2024-09-07 | FLuffy Gangsters                | W   | 0.032      | -            | -                | -                | -         |     0.37 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            4 |     7438 | 2024-09-07 | Partizan Esports                | W   | 0.032      | -            | -                | -                | -         |     0.76 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            3 |     7491 | 2024-09-06 | Asian fetish                    | W   | 0.027      | -            | -                | -                | -         |     0.07 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            2 |     7501 | 2024-09-06 | ZEROvariant                     | W   | 0.026      | -            | -                | -                | -         |     0.05 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            1 |     7604 | 2024-09-05 | HOTU                            | L   | 0.019      | -            | -                | -                | -         |    -0.42 | executor, Gospadarov, kinqie, KIRO, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,263.26)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.741 | $2,607.56      | $1,931.04       |
| 2024-12-15 |      0.693 | $7,263.25      | $5,032.15       |
| 2024-11-03 |      0.413 | $5,108.69      | $2,111.59       |
| 2024-09-23 |      0.140 | $1,300.00      | $182.00         |
| 2024-09-07 |      0.032 | $200.00        | $6.47           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
