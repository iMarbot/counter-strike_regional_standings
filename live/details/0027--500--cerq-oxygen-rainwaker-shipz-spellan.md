### Roster Details<br />
Team Name: 500<br />
Roster: CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1102.0<br />
<br />
Final Rank Value (1102.0) = Starting Rank Value (996.9) + Head To Head Adjustments (105.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.490[<sup>1</sup>](#table2)
- Bounty Collected: 0.406[<sup>2</sup>](#table1)
- Opponent Network: 0.299[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.299<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.9
- 400 + ( ( 0.299 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 996.9


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
|           81 |      362 | 2025-02-16 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -25.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           80 |      403 | 2025-02-15 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.082 (0.036)    | 0.768 (0.334)    | 0 (0.000) |    12.18 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           79 |      424 | 2025-02-15 | B8                                        | W   | 1.000      | 0.435        | 0.124 (0.054)    | 0.590 (0.256)    | 0 (0.000) |    15.86 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           78 |      475 | 2025-02-14 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -14.14 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           77 |      485 | 2025-02-14 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.127 (0.055)    | 0.703 (0.306)    | 0 (0.000) |    12.35 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           76 |      506 | 2025-02-13 | 9Pandas                                   | W   | 1.000      | 0.435        | 0.085 (0.037)    | 0.485 (0.211)    | 0 (0.000) |    13.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           75 |      515 | 2025-02-13 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |   -16.68 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           74 |      561 | 2025-02-11 | ALASKA                                    | W   | 1.000      | 0.435        | -                | 0.875 (0.380)    | 0 (0.000) |     7.45 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           73 |      635 | 2025-02-09 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.80 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           72 |      688 | 2025-02-08 | OG                                        | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    10.44 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           71 |      711 | 2025-02-08 | BIG                                       | W   | 1.000      | 0.143        | 0.246 (0.035)    | -                | 0 (0.000) |    27.49 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           70 |      805 | 2025-02-07 | BC.Game Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           69 |      848 | 2025-02-06 | SAW                                       | W   | 1.000      | 0.143        | 0.262 (0.037)    | -                | 0 (0.000) |    24.45 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           68 |      900 | 2025-02-05 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.43 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           67 |      906 | 2025-02-05 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -13.63 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           66 |      915 | 2025-02-05 | Eco Warriors                              | W   | 1.000      | -            | -                | -                | -         |     7.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           65 |      944 | 2025-02-04 | TEAM NEXT LEVEL                           | W   | 1.000      | -            | -                | -                | -         |     4.99 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           64 |      946 | 2025-02-04 | Fire Flux Esports                         | W   | 1.000      | -            | -                | -                | -         |    12.94 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           63 |      950 | 2025-02-04 | Monte                                     | W   | 1.000      | -            | -                | -                | -         |    13.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           62 |      976 | 2025-02-04 | Eternal Fire Academy                      | W   | 1.000      | -            | -                | -                | -         |     1.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           61 |     1025 | 2025-02-03 | 9INE                                      | W   | 1.000      | 0.435        | -                | 0.839 (0.364)    | -         |    14.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           60 |     1038 | 2025-02-02 | Betclic Apogee Esports                    | L   | 1.000      | -            | -                | -                | -         |   -18.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           59 |     1445 | 2024-12-21 | Betclic Apogee Esports                    | L   | 0.733      | -            | -                | -                | -         |   -15.65 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           58 |     1505 | 2024-12-20 | 9INE                                      | L   | 0.726      | -            | -                | -                | -         |   -14.04 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           57 |     1511 | 2024-12-20 | Ex-GODSENT                                | W   | 0.726      | -            | -                | -                | -         |     1.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           56 |     1520 | 2024-12-20 | JANO Esports                              | L   | 0.724      | -            | -                | -                | -         |   -16.86 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           55 |     1545 | 2024-12-19 | Copenhagen Wolves (American organization) | L   | 0.718      | -            | -                | -                | -         |   -15.99 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           54 |     1999 | 2024-12-08 | Leo Team                                  | W   | 0.646      | -            | -                | -                | -         |     6.26 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           53 |     2075 | 2024-12-07 | Copenhagen Wolves (American organization) | W   | 0.640      | 0.372        | -                | 1.000 (0.238)    | -         |     5.69 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           52 |     2129 | 2024-12-06 | Fire Flux Esports                         | W   | 0.633      | 0.372        | -                | 1.000 (0.236)    | -         |     6.91 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           51 |     2161 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.626      | 0.372        | -                | 1.000 (0.233)    | -         |     5.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           50 |     2216 | 2024-12-04 | ALTERNATE aTTaX                           | W   | 0.620      | -            | -                | -                | -         |     7.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           49 |     2262 | 2024-12-03 | Partizan Esports                          | W   | 0.613      | 0.372        | 0.082 (0.019)    | -                | -         |    10.79 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           48 |     2433 | 2024-12-01 | Team Spirit Academy                       | L   | 0.599      | -            | -                | -                | -         |   -10.89 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           47 |     2629 | 2024-11-28 | BC.Game Esports                           | W   | 0.580      | -            | -                | -                | -         |     5.59 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           46 |     2781 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.553      | -            | -                | -                | -         |   -12.87 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           45 |     2957 | 2024-11-22 | FAVBET Team                               | W   | 0.540      | -            | -                | -                | -         |     5.30 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           44 |     3101 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | W   | 0.527      | -            | -                | -                | -         |     2.39 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           43 |     3117 | 2024-11-20 | 1win                                      | L   | 0.526      | -            | -                | -                | -         |   -13.72 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           42 |     3154 | 2024-11-19 | Haspers Team                              | W   | 0.519      | -            | -                | -                | -         |     2.32 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           41 |     3161 | 2024-11-19 | K27                                       | W   | 0.519      | -            | -                | -                | -         |     5.07 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           40 |     3201 | 2024-11-18 | Endpoint                                  | W   | 0.513      | -            | -                | -                | -         |     3.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           39 |     3545 | 2024-11-12 | BetBoom Team                              | L   | 0.473      | -            | -                | -                | -         |    -7.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           38 |     3564 | 2024-11-12 | GUN5 Esports                              | W   | 0.471      | 0.384        | 0.102 (0.018)    | -                | -         |     6.01 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           37 |     3619 | 2024-11-11 | ENCE                                      | W   | 0.465      | 0.384        | 0.136 (0.024)    | -                | -         |     7.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           36 |     3675 | 2024-11-10 | 9Pandas                                   | W   | 0.458      | -            | -                | -                | -         |     7.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           35 |     3802 | 2024-11-08 | Nemiga Gaming                             | L   | 0.445      | -            | -                | -                | -         |    -6.44 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           34 |     3810 | 2024-11-08 | Sashi Esport                              | W   | 0.444      | -            | -                | -                | -         |     5.57 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           33 |     3851 | 2024-11-07 | Monte                                     | W   | 0.439      | -            | -                | -                | -         |     4.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           32 |     3858 | 2024-11-07 | SINNERS Esports                           | L   | 0.438      | -            | -                | -                | -         |    -8.92 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           31 |     3901 | 2024-11-06 | Passion UA                                | W   | 0.431      | -            | -                | -                | -         |     6.80 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           30 |     4015 | 2024-11-04 | Zero Tenacity                             | W   | 0.418      | -            | -                | -                | -         |     4.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           29 |     4126 | 2024-11-02 | Wild Lotus                                | L   | 0.406      | -            | -                | -                | -         |    -9.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           28 |     4244 | 2024-10-31 | GUN5 Esports                              | L   | 0.393      | -            | -                | -                | -         |    -7.67 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           27 |     4378 | 2024-10-29 | AMKAL ESPORTS                             | W   | 0.379      | -            | -                | -                | -         |     2.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           26 |     4423 | 2024-10-28 | Zero Tenacity                             | W   | 0.373      | -            | -                | -                | -         |     3.48 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           25 |     4437 | 2024-10-28 | OG                                        | W   | 0.372      | -            | -                | -                | -         |     4.53 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           24 |     4598 | 2024-10-25 | Kubix Esports                             | W   | 0.352      | -            | -                | -                | -         |     4.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           23 |     4625 | 2024-10-24 | Lazer Cats                                | W   | 0.345      | -            | -                | -                | -         |     1.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           22 |     4815 | 2024-10-20 | ECSTATIC                                  | W   | 0.318      | -            | -                | -                | -         |     3.38 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           21 |     4931 | 2024-10-17 | Leo Team                                  | W   | 0.299      | -            | -                | -                | -         |     2.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           20 |     5065 | 2024-10-15 | The Suspect                               | W   | 0.286      | -            | -                | -                | -         |     1.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           19 |     5115 | 2024-10-14 | UNiTY esports                             | W   | 0.278      | -            | -                | -                | -         |     2.73 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           18 |     5197 | 2024-10-12 | CYBERSHOKE Esports                        | W   | 0.266      | -            | -                | -                | -         |     2.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           17 |     5264 | 2024-10-11 | UNiTY esports                             | W   | 0.259      | -            | -                | -                | -         |     2.62 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           16 |     5370 | 2024-10-09 | HOTU                                      | W   | 0.244      | -            | -                | -                | -         |     1.45 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           15 |     5471 | 2024-10-07 | Daystar                                   | W   | 0.233      | -            | -                | -                | -         |     0.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           14 |     5579 | 2024-10-05 | Los kogutos                               | W   | 0.219      | -            | -                | -                | -         |     3.38 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           13 |     5663 | 2024-10-04 | ENCE Academy                              | L   | 0.213      | -            | -                | -                | -         |    -4.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           12 |     5729 | 2024-10-03 | Dynamo Eclot                              | W   | 0.204      | -            | -                | -                | -         |     4.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           11 |     5775 | 2024-10-02 | CYBERSHOKE Esports                        | W   | 0.199      | -            | -                | -                | -         |     2.03 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           10 |     5930 | 2024-09-30 | ALTERNATE aTTaX                           | W   | 0.184      | -            | -                | -                | -         |     2.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            9 |     5979 | 2024-09-29 | Insilio                                   | L   | 0.178      | -            | -                | -                | -         |    -4.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            8 |     6017 | 2024-09-28 | WinX                                      | L   | 0.173      | -            | -                | -                | -         |    -5.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            7 |     6032 | 2024-09-28 | FORZE Reload                              | W   | 0.173      | -            | -                | -                | -         |     1.68 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            6 |     6198 | 2024-09-26 | ARCRED                                    | L   | 0.159      | -            | -                | -                | -         |    -3.96 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            5 |     6276 | 2024-09-25 | TEAM NEXT LEVEL                           | W   | 0.153      | -            | -                | -                | -         |     0.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            4 |     7174 | 2024-09-11 | Daystar                                   | L   | 0.060      | -            | -                | -                | -         |    -1.65 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            3 |     7338 | 2024-09-08 | GameAgents                                | L   | 0.040      | -            | -                | -                | -         |    -1.13 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            2 |     7402 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.033      | -            | -                | -                | -         |    -0.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            1 |     7517 | 2024-09-06 | K27                                       | W   | 0.026      | -            | -                | -                | -         |     0.34 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,726.75)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-12-08 |      0.646 | $7,000.00      | $4,524.72       |
| 2024-11-12 |      0.473 | $3,500.00      | $1,654.16       |
| 2024-11-09 |      0.452 | $5,030.36      | $2,275.31       |
| 2024-10-05 |      0.218 | $1,250.00      | $272.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
