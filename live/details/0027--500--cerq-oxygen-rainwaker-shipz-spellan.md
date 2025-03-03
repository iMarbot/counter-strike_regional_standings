### Roster Details<br />
Team Name: 500<br />
Roster: CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1101.1<br />
<br />
Final Rank Value (1101.1) = Starting Rank Value (997.4) + Head To Head Adjustments (103.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.492[<sup>1</sup>](#table2)
- Bounty Collected: 0.406[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.299<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.4
- 400 + ( ( 0.299 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 997.4


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
|           81 |      374 | 2025-02-16 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -25.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           80 |      415 | 2025-02-15 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.083 (0.036)    | 0.757 (0.329)    | 0 (0.000) |    12.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           79 |      436 | 2025-02-15 | B8                                        | W   | 1.000      | 0.435        | 0.126 (0.055)    | 0.586 (0.254)    | 0 (0.000) |    15.81 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           78 |      487 | 2025-02-14 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -14.12 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           77 |      497 | 2025-02-14 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.128 (0.056)    | 0.692 (0.301)    | 0 (0.000) |    12.31 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           76 |      518 | 2025-02-13 | 9Pandas                                   | W   | 1.000      | 0.435        | 0.085 (0.037)    | 0.477 (0.207)    | 0 (0.000) |    13.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           75 |      527 | 2025-02-13 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |   -16.75 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           74 |      573 | 2025-02-11 | ALASKA                                    | W   | 1.000      | 0.435        | -                | 0.867 (0.377)    | 0 (0.000) |     7.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           73 |      647 | 2025-02-09 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.79 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           72 |      700 | 2025-02-08 | OG                                        | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    10.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           71 |      723 | 2025-02-08 | BIG                                       | W   | 1.000      | 0.143        | 0.248 (0.035)    | -                | 0 (0.000) |    27.50 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           70 |      817 | 2025-02-07 | BC.Game Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           69 |      860 | 2025-02-06 | SAW                                       | W   | 1.000      | 0.143        | 0.266 (0.038)    | -                | 0 (0.000) |    24.48 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           68 |      912 | 2025-02-05 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.44 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           67 |      918 | 2025-02-05 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -13.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           66 |      927 | 2025-02-05 | Eco Warriors                              | W   | 1.000      | -            | -                | -                | -         |     7.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           65 |      956 | 2025-02-04 | TEAM NEXT LEVEL                           | W   | 1.000      | -            | -                | -                | -         |     5.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           64 |      958 | 2025-02-04 | Fire Flux Esports                         | W   | 1.000      | -            | -                | -                | -         |    12.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           63 |      962 | 2025-02-04 | Monte                                     | W   | 1.000      | -            | -                | -                | -         |    13.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           62 |      988 | 2025-02-04 | Eternal Fire Academy                      | W   | 1.000      | -            | -                | -                | -         |     1.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           61 |     1037 | 2025-02-03 | 9INE                                      | W   | 1.000      | 0.435        | -                | 0.837 (0.364)    | -         |    13.97 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           60 |     1050 | 2025-02-02 | Betclic Apogee Esports                    | L   | 1.000      | -            | -                | -                | -         |   -18.86 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           59 |     1457 | 2024-12-21 | Betclic Apogee Esports                    | L   | 0.725      | -            | -                | -                | -         |   -15.50 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           58 |     1517 | 2024-12-20 | 9INE                                      | L   | 0.718      | -            | -                | -                | -         |   -13.91 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           57 |     1523 | 2024-12-20 | Ex-GODSENT                                | W   | 0.717      | -            | -                | -                | -         |     1.54 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           56 |     1532 | 2024-12-20 | JANO Esports                              | L   | 0.716      | -            | -                | -                | -         |   -16.65 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           55 |     1557 | 2024-12-19 | Copenhagen Wolves (American organization) | L   | 0.709      | -            | -                | -                | -         |   -15.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           54 |     2011 | 2024-12-08 | Leo Team                                  | W   | 0.638      | -            | -                | -                | -         |     6.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           53 |     2087 | 2024-12-07 | Copenhagen Wolves (American organization) | W   | 0.632      | 0.372        | -                | 1.000 (0.235)    | -         |     5.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           52 |     2141 | 2024-12-06 | Fire Flux Esports                         | W   | 0.625      | 0.372        | -                | 1.000 (0.233)    | -         |     6.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           51 |     2173 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.618      | 0.372        | -                | 1.000 (0.230)    | -         |     5.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           50 |     2228 | 2024-12-04 | ALTERNATE aTTaX                           | W   | 0.612      | -            | -                | -                | -         |     7.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           49 |     2274 | 2024-12-03 | Partizan Esports                          | W   | 0.605      | 0.372        | 0.083 (0.019)    | -                | -         |    10.62 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           48 |     2445 | 2024-12-01 | Team Spirit Academy                       | L   | 0.591      | -            | -                | -                | -         |   -10.81 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           47 |     2641 | 2024-11-28 | BC.Game Esports                           | W   | 0.572      | -            | -                | -                | -         |     5.49 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           46 |     2793 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.545      | -            | -                | -                | -         |   -12.69 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           45 |     2969 | 2024-11-22 | FAVBET Team                               | W   | 0.532      | -            | -                | -                | -         |     5.19 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           44 |     3113 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | W   | 0.518      | -            | -                | -                | -         |     2.34 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           43 |     3129 | 2024-11-20 | 1win                                      | L   | 0.518      | -            | -                | -                | -         |   -13.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           42 |     3166 | 2024-11-19 | Haspers Team                              | W   | 0.511      | -            | -                | -                | -         |     2.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           41 |     3173 | 2024-11-19 | K27                                       | W   | 0.511      | -            | -                | -                | -         |     5.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           40 |     3213 | 2024-11-18 | Endpoint                                  | W   | 0.505      | -            | -                | -                | -         |     3.27 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           39 |     3557 | 2024-11-12 | BetBoom Team                              | L   | 0.464      | -            | -                | -                | -         |    -7.41 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           38 |     3576 | 2024-11-12 | GUN5 Esports                              | W   | 0.463      | 0.384        | 0.103 (0.018)    | -                | -         |     5.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           37 |     3631 | 2024-11-11 | ENCE                                      | W   | 0.457      | 0.384        | 0.136 (0.024)    | -                | -         |     7.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           36 |     3687 | 2024-11-10 | 9Pandas                                   | W   | 0.450      | -            | -                | -                | -         |     7.34 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           35 |     3814 | 2024-11-08 | Nemiga Gaming                             | L   | 0.437      | -            | -                | -                | -         |    -6.39 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           34 |     3822 | 2024-11-08 | Sashi Esport                              | W   | 0.436      | -            | -                | -                | -         |     5.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           33 |     3863 | 2024-11-07 | Monte                                     | W   | 0.430      | -            | -                | -                | -         |     4.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           32 |     3870 | 2024-11-07 | SINNERS Esports                           | L   | 0.429      | -            | -                | -                | -         |    -8.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           31 |     3913 | 2024-11-06 | Passion UA                                | W   | 0.423      | -            | -                | -                | -         |     6.64 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           30 |     4025 | 2024-11-04 | Zero Tenacity                             | W   | 0.410      | -            | -                | -                | -         |     3.93 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           29 |     4138 | 2024-11-02 | Wild Lotus                                | L   | 0.398      | -            | -                | -                | -         |    -9.73 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           28 |     4256 | 2024-10-31 | GUN5 Esports                              | L   | 0.385      | -            | -                | -                | -         |    -7.53 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           27 |     4390 | 2024-10-29 | AMKAL ESPORTS                             | W   | 0.371      | -            | -                | -                | -         |     2.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           26 |     4435 | 2024-10-28 | Zero Tenacity                             | W   | 0.365      | -            | -                | -                | -         |     3.37 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           25 |     4449 | 2024-10-28 | OG                                        | W   | 0.364      | -            | -                | -                | -         |     4.41 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           24 |     4610 | 2024-10-25 | Kubix Esports                             | W   | 0.344      | -            | -                | -                | -         |     4.34 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           23 |     4637 | 2024-10-24 | Lazer Cats                                | W   | 0.337      | -            | -                | -                | -         |     1.72 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           22 |     4827 | 2024-10-20 | ECSTATIC                                  | W   | 0.309      | -            | -                | -                | -         |     3.27 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           21 |     4943 | 2024-10-17 | Leo Team                                  | W   | 0.291      | -            | -                | -                | -         |     2.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           20 |     5077 | 2024-10-15 | The Suspect                               | W   | 0.278      | -            | -                | -                | -         |     1.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           19 |     5127 | 2024-10-14 | UNiTY esports                             | W   | 0.270      | -            | -                | -                | -         |     2.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           18 |     5209 | 2024-10-12 | CYBERSHOKE Esports                        | W   | 0.258      | -            | -                | -                | -         |     2.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           17 |     5276 | 2024-10-11 | UNiTY esports                             | W   | 0.250      | -            | -                | -                | -         |     2.50 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           16 |     5382 | 2024-10-09 | HOTU                                      | W   | 0.235      | -            | -                | -                | -         |     1.39 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           15 |     5483 | 2024-10-07 | Daystar                                   | W   | 0.225      | -            | -                | -                | -         |     0.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           14 |     5591 | 2024-10-05 | Los kogutos                               | W   | 0.211      | -            | -                | -                | -         |     3.22 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           13 |     5675 | 2024-10-04 | ENCE Academy                              | L   | 0.205      | -            | -                | -                | -         |    -4.71 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           12 |     5741 | 2024-10-03 | Dynamo Eclot                              | W   | 0.196      | -            | -                | -                | -         |     3.81 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           11 |     5787 | 2024-10-02 | CYBERSHOKE Esports                        | W   | 0.190      | -            | -                | -                | -         |     1.94 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           10 |     5942 | 2024-09-30 | ALTERNATE aTTaX                           | W   | 0.176      | -            | -                | -                | -         |     2.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            9 |     5991 | 2024-09-29 | Insilio                                   | L   | 0.169      | -            | -                | -                | -         |    -4.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            8 |     6029 | 2024-09-28 | WinX                                      | L   | 0.165      | -            | -                | -                | -         |    -4.87 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            7 |     6044 | 2024-09-28 | FORZE Reload                              | W   | 0.164      | -            | -                | -                | -         |     1.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            6 |     6210 | 2024-09-26 | ARCRED                                    | L   | 0.151      | -            | -                | -                | -         |    -3.77 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            5 |     6288 | 2024-09-25 | TEAM NEXT LEVEL                           | W   | 0.145      | -            | -                | -                | -         |     0.73 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            4 |     7186 | 2024-09-11 | Daystar                                   | L   | 0.052      | -            | -                | -                | -         |    -1.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            3 |     7350 | 2024-09-08 | GameAgents                                | L   | 0.032      | -            | -                | -                | -         |    -0.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            2 |     7414 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.025      | -            | -                | -                | -         |    -0.44 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            1 |     7529 | 2024-09-06 | K27                                       | W   | 0.018      | -            | -                | -                | -         |     0.23 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,589.25)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-12-08 |      0.638 | $7,000.00      | $4,467.36       |
| 2024-11-12 |      0.464 | $3,500.00      | $1,625.47       |
| 2024-11-09 |      0.444 | $5,030.36      | $2,234.09       |
| 2024-10-05 |      0.210 | $1,250.00      | $262.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
