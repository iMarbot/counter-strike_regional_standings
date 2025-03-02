### Roster Details<br />
Team Name: GenOne<br />
Roster: Brooxsy, devoduvek, drac, JACKZ, Kursy<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  844.4<br />
<br />
Final Rank Value (844.4) = Starting Rank Value (831.9) + Head To Head Adjustments (12.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.9
- 400 + ( ( 0.216 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 831.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           87 |      288 | 2025-02-17 | Hesta                                     | L   | 1.000      | -            | -                | -                | -         |   -17.11 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           86 |      298 | 2025-02-17 | Bad News Eagles                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.32 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           85 |      328 | 2025-02-16 | WOPA Esport                               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.12 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           84 |     1201 | 2025-01-10 | 9Pandas                                   | L   | 0.865      | -            | -                | -                | -         |    -6.56 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           83 |     1210 | 2025-01-09 | ECSTATIC                                  | W   | 0.858      | 0.417        | 0.033 (0.012)    | 0.828 (0.296)    | 0 (0.000) |    15.57 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           82 |     1215 | 2025-01-07 | ECSTATIC                                  | W   | 0.846      | 0.417        | 0.033 (0.012)    | 0.828 (0.292)    | 0 (0.000) |    16.39 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           81 |     1256 | 2024-12-29 | Wu-Tang Clan                              | W   | 0.786      | -            | -                | -                | 0 (0.000) |     7.74 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           80 |     1284 | 2024-12-28 | BadGuys                                   | L   | 0.780      | -            | -                | -                | -         |   -17.50 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           79 |     1597 | 2024-12-16 | KONO.ECF                                  | L   | 0.698      | -            | -                | -                | -         |   -10.48 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           78 |     1632 | 2024-12-15 | Betera Esports                            | L   | 0.692      | -            | -                | -                | -         |   -13.30 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           77 |     1804 | 2024-12-13 | Illuminar Gaming                          | L   | 0.678      | -            | -                | -                | -         |   -11.45 | Brooxsy, devoduvek, drac, Kursy, Revol    |
|           76 |     1849 | 2024-12-12 | WOPA Esport                               | L   | 0.671      | -            | -                | -                | -         |   -11.48 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           75 |     1933 | 2024-12-10 | AMKAL ESPORTS                             | L   | 0.658      | -            | -                | -                | -         |   -12.25 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           74 |     1956 | 2024-12-09 | FORZE Reload                              | W   | 0.652      | 0.333        | 0.026 (0.006)    | -                | 0 (0.000) |    10.29 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           73 |     1963 | 2024-12-09 | Chimera Esports                           | L   | 0.651      | -            | -                | -                | -         |    -9.40 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           72 |     2024 | 2024-12-08 | KONO.ECF                                  | W   | 0.644      | 0.333        | 0.045 (0.010)    | 0.757 (0.163)    | 0 (0.000) |     8.85 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           71 |     2177 | 2024-12-05 | BC.Game Esports                           | L   | 0.624      | -            | -                | -                | -         |    -9.97 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           70 |     2201 | 2024-12-04 | Fire Flux Esports                         | L   | 0.620      | -            | -                | -                | -         |    -9.08 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           69 |     2233 | 2024-12-04 | BC.Game Esports                           | W   | 0.618      | 0.371        | 0.022 (0.005)    | -                | 0 (0.000) |     9.29 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           68 |     2258 | 2024-12-03 | Nuclear TigeRES                           | W   | 0.614      | -            | -                | -                | 0 (0.000) |     7.58 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           67 |     2288 | 2024-12-03 | BC.Game Esports                           | W   | 0.611      | -            | -                | -                | 0 (0.000) |     9.92 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           66 |     2331 | 2024-12-02 | Nexus Gaming                              | W   | 0.607      | 0.372        | 0.186 (0.042)    | 0.808 (0.183)    | -         |    15.50 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           65 |     2446 | 2024-12-01 | Dark Cloud Esports                        | W   | 0.598      | 0.333        | 0.038 (0.008)    | 0.828 (0.165)    | -         |     9.56 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           64 |     2519 | 2024-11-30 | 1win                                      | W   | 0.593      | -            | -                | -                | -         |     7.74 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           63 |     2537 | 2024-11-30 | Chimera Esports                           | L   | 0.592      | -            | -                | -                | -         |    -8.43 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           62 |     2650 | 2024-11-28 | Astralis Talent                           | W   | 0.578      | 0.333        | -                | 0.733 (0.141)    | -         |     8.06 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           61 |     2679 | 2024-11-27 | Preasy Esport                             | W   | 0.572      | 0.333        | -                | 0.710 (0.135)    | -         |     7.37 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           60 |     2724 | 2024-11-26 | Kubix Esports                             | L   | 0.566      | -            | -                | -                | -         |    -6.62 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           59 |     2759 | 2024-11-25 | Leo Team                                  | W   | 0.558      | 0.333        | 0.026 (0.005)    | 0.758 (0.141)    | -         |    10.59 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           58 |     2800 | 2024-11-24 | Astralis Talent                           | L   | 0.552      | -            | -                | -                | -         |    -9.45 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           57 |     2879 | 2024-11-23 | KONO.ECF                                  | L   | 0.546      | -            | -                | -                | -         |    -7.67 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           56 |     2902 | 2024-11-23 | BC.Game Esports                           | L   | 0.545      | -            | -                | -                | -         |    -9.03 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           55 |     2967 | 2024-11-22 | Ex-RUBY                                   | W   | 0.539      | -            | -                | -                | -         |     2.74 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           54 |     3021 | 2024-11-21 | Leo Team                                  | L   | 0.533      | -            | -                | -                | -         |    -7.84 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           53 |     3059 | 2024-11-21 | G2 Ares                                   | W   | 0.531      | -            | -                | -                | -         |     5.05 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           52 |     3108 | 2024-11-20 | Haspers Team                              | W   | 0.526      | -            | -                | -                | -         |     5.06 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           51 |     3124 | 2024-11-20 | RUSTEC                                    | L   | 0.526      | -            | -                | -                | -         |   -13.83 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           50 |     3156 | 2024-11-19 | ALASKA                                    | W   | 0.519      | 0.372        | 0.030 (0.006)    | 0.875 (0.169)    | -         |    11.57 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           49 |     3194 | 2024-11-18 | Poslednii3ae3d                            | W   | 0.513      | -            | -                | -                | -         |     3.56 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           48 |     3203 | 2024-11-18 | Tricked Esport                            | L   | 0.513      | -            | -                | -                | -         |    -7.65 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           47 |     3336 | 2024-11-16 | AMKAL ESPORTS                             | L   | 0.498      | -            | -                | -                | -         |    -9.02 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           46 |     3376 | 2024-11-15 | Alliance                                  | W   | 0.493      | -            | -                | -                | -         |     8.55 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           45 |     3404 | 2024-11-15 | Leo Team                                  | L   | 0.492      | -            | -                | -                | -         |    -7.50 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           44 |     3431 | 2024-11-14 | Fire Flux Esports                         | L   | 0.487      | -            | -                | -                | -         |    -6.60 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           43 |     3464 | 2024-11-14 | Astralis Talent                           | W   | 0.485      | -            | -                | -                | -         |     6.09 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           42 |     3502 | 2024-11-13 | Alliance                                  | W   | 0.479      | -            | -                | -                | -         |     8.27 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           41 |     3522 | 2024-11-13 | Viperio                                   | W   | 0.477      | -            | -                | -                | -         |     5.31 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           40 |     3563 | 2024-11-12 | WOPA Esport                               | W   | 0.471      | 0.333        | 0.031 (0.005)    | -                | -         |     7.63 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           39 |     3604 | 2024-11-11 | Team Spirit Academy                       | L   | 0.466      | -            | -                | -                | -         |    -5.30 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           38 |     3635 | 2024-11-11 | Illuminar Gaming                          | W   | 0.464      | -            | -                | -                | -         |     7.59 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           37 |     3682 | 2024-11-10 | Dark Cloud Esports                        | L   | 0.458      | -            | -                | -                | -         |    -7.27 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           36 |     3725 | 2024-11-09 | Monte                                     | L   | 0.453      | -            | -                | -                | -         |    -5.72 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           35 |     3781 | 2024-11-08 | FLuffy Gangsters                          | W   | 0.447      | 0.354        | -                | 0.925 (0.146)    | -         |     6.07 | Brooxsy, devoduvek, drac, Kursy, Kyojin   |
|           34 |     3803 | 2024-11-08 | 777 Esports                               | W   | 0.445      | -            | -                | -                | -         |     4.01 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           33 |     3848 | 2024-11-07 | Heimo Esports                             | W   | 0.439      | -            | -                | -                | -         |     5.26 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           32 |     3887 | 2024-11-06 | Endpoint                                  | W   | 0.433      | -            | -                | -                | -         |     5.98 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           31 |     3904 | 2024-11-06 | Leo Team                                  | L   | 0.431      | -            | -                | -                | -         |    -6.83 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           30 |     4085 | 2024-11-03 | Lazer Cats                                | L   | 0.411      | -            | -                | -                | -         |    -8.36 | Brooxsy, devoduvek, drac, Kursy, MaThZ    |
|           29 |     4148 | 2024-11-02 | 777 Esports                               | W   | 0.405      | -            | -                | -                | -         |     3.61 | Brooxsy, devoduvek, drac, Kursy, MaThZ    |
|           28 |     4660 | 2024-10-23 | Copenhagen Wolves (American organization) | W   | 0.339      | -            | -                | -                | -         |     5.81 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           27 |     4723 | 2024-10-21 | Fire Flux Esports                         | L   | 0.326      | -            | -                | -                | -         |    -4.45 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           26 |     4751 | 2024-10-21 | Anonymo Esports                           | W   | 0.325      | -            | -                | -                | -         |     1.70 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           25 |     4782 | 2024-10-20 | RUSH B (Russian team)                     | L   | 0.319      | -            | -                | -                | -         |    -4.27 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           24 |     4906 | 2024-10-18 | KONO.ECF                                  | W   | 0.304      | -            | -                | -                | -         |     5.88 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           23 |     4981 | 2024-10-16 | PCIFIC Espor                              | W   | 0.293      | -            | -                | -                | -         |     3.84 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           22 |     5007 | 2024-10-16 | Monte                                     | L   | 0.292      | -            | -                | -                | -         |    -3.61 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           21 |     5117 | 2024-10-14 | ENCE Academy                              | W   | 0.278      | -            | -                | -                | -         |     4.22 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           20 |     5203 | 2024-10-12 | Ex-9INE Academy                           | W   | 0.266      | -            | -                | -                | -         |     1.77 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           19 |     5271 | 2024-10-11 | Astralis Talent                           | L   | 0.257      | -            | -                | -                | -         |    -4.82 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           18 |     5287 | 2024-10-10 | GamerLegion Academy                       | W   | 0.252      | -            | -                | -                | -         |     1.30 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           17 |     5299 | 2024-10-10 | Natus Vincere Junior                      | L   | 0.250      | -            | -                | -                | -         |    -2.46 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           16 |     5487 | 2024-10-07 | Monte                                     | L   | 0.232      | -            | -                | -                | -         |    -2.88 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           15 |     5496 | 2024-10-07 | Leo Team                                  | L   | 0.231      | -            | -                | -                | -         |    -3.60 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           14 |     5580 | 2024-10-05 | TEAM NEXT LEVEL                           | W   | 0.219      | -            | -                | -                | -         |     3.63 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           13 |     5774 | 2024-10-02 | Lazer Cats                                | W   | 0.199      | -            | -                | -                | -         |     2.18 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           12 |     6148 | 2024-09-27 | ROYALS                                    | L   | 0.165      | -            | -                | -                | -         |    -3.61 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           11 |     6219 | 2024-09-26 | Partizan Esports                          | W   | 0.158      | -            | -                | -                | -         |     4.01 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|           10 |     6234 | 2024-09-26 | ROYALS                                    | L   | 0.157      | -            | -                | -                | -         |    -3.46 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            9 |     6525 | 2024-09-22 | Leo Team                                  | W   | 0.131      | -            | -                | -                | -         |     2.06 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            8 |     6645 | 2024-09-20 | Preasy Esport                             | W   | 0.118      | -            | -                | -                | -         |     1.71 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            7 |     6650 | 2024-09-20 | Nexus Gaming                              | W   | 0.117      | -            | -                | -                | -         |     3.25 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            6 |     6683 | 2024-09-19 | Natus Vincere Youth                       | W   | 0.113      | -            | -                | -                | -         |     0.46 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            5 |     6713 | 2024-09-19 | HOTU                                      | L   | 0.111      | -            | -                | -                | -         |    -2.22 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            4 |     6780 | 2024-09-18 | LOADING (French team)                     | W   | 0.104      | -            | -                | -                | -         |     0.47 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            3 |     6900 | 2024-09-16 | ROYALS                                    | W   | 0.091      | -            | -                | -                | -         |     0.87 | Brooxsy, devoduvek, drac, JACKZ, Kursy    |
|            2 |     7352 | 2024-09-08 | Ex-9INE Academy                           | L   | 0.039      | -            | -                | -                | -         |    -0.95 | Brooxsy, devoduvek, drac, Kursy, unshaarK |
|            1 |     7675 | 2024-09-04 | Viperio                                   | W   | 0.012      | -            | -                | -                | -         |     0.15 | Brooxsy, devoduvek, drac, Kursy, SHOGU    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,174.24)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.646 | $750.00        | $484.79         |
| 2024-12-05 |      0.624 | $3,000.00      | $1,872.50       |
| 2024-11-17 |      0.505 | $1,000.00      | $505.14         |
| 2024-11-10 |      0.460 | $1,000.00      | $459.72         |
| 2024-10-08 |      0.239 | $1,500.00      | $358.33         |
| 2024-09-27 |      0.165 | $3,000.00      | $493.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
