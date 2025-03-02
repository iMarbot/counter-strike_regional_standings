### Roster Details<br />
Team Name: Tricked Esport<br />
Roster: Nodios, Queenix, roeJ, salazar, valde<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  863.7<br />
<br />
Final Rank Value (863.7) = Starting Rank Value (831.5) + Head To Head Adjustments (32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.404[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 831.5
- 400 + ( ( 0.216 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 831.5


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
|           73 |        4 | 2025-03-01 | ECSTATIC                                  | L   | 1.000      | -            | -                | -                | -         |   -15.54 | Nodios, Queenix, roeJ, salazar, valde    |
|           72 |       10 | 2025-02-28 | ESC Gaming                                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.25 | Nodios, Queenix, roeJ, salazar, valde    |
|           71 |       45 | 2025-02-25 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.51 | Nodios, Queenix, roeJ, salazar, valde    |
|           70 |       62 | 2025-02-24 | OG                                        | L   | 1.000      | -            | -                | -                | -         |   -10.22 | Nodios, Queenix, roeJ, salazar, valde    |
|           69 |      182 | 2025-02-21 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -12.65 | Leakz, niko, Queenix, salazar, valde     |
|           68 |      200 | 2025-02-21 | Dark Cloud Esports                        | W   | 1.000      | 0.143        | 0.038 (0.005)    | 0.828 (0.118)    | 0 (0.000) |    15.05 | Leakz, niko, Queenix, salazar, valde     |
|           67 |      211 | 2025-02-21 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    15.41 | Leakz, niko, Queenix, salazar, valde     |
|           66 |      228 | 2025-02-20 | Viperio                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | Leakz, niko, Queenix, salazar, valde     |
|           65 |     1000 | 2025-02-04 | Wildcard Academy                          | L   | 1.000      | -            | -                | -                | -         |   -27.14 | Leakz, Nodios, Queenix, salazar, valde   |
|           64 |     1959 | 2024-12-09 | Betclic Apogee Esports                    | L   | 0.652      | -            | -                | -                | -         |   -10.22 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           63 |     2095 | 2024-12-07 | Fire Flux Esports                         | L   | 0.637      | -            | -                | -                | -         |    -9.09 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           62 |     2159 | 2024-12-05 | Chimera Esports                           | L   | 0.626      | -            | -                | -                | -         |   -10.30 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           61 |     2176 | 2024-12-05 | Team Sampi                                | W   | 0.624      | 0.371        | 0.012 (0.003)    | -                | 0 (0.000) |     6.86 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           60 |     2227 | 2024-12-04 | Iberian Soul                              | L   | 0.618      | -            | -                | -                | -         |   -10.75 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           59 |     2438 | 2024-12-01 | Iberian Soul                              | L   | 0.598      | -            | -                | -                | -         |   -10.97 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           58 |     2512 | 2024-11-30 | Betclic Apogee Esports                    | W   | 0.593      | 0.354        | -                | 0.515 (0.108)    | 0 (0.000) |     9.00 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           57 |     2590 | 2024-11-29 | Natus Vincere Junior                      | W   | 0.586      | 0.354        | 0.091 (0.019)    | 0.878 (0.182)    | 0 (0.000) |    11.73 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           56 |     2602 | 2024-11-29 | BC.Game Esports                           | L   | 0.584      | -            | -                | -                | -         |   -10.01 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           55 |     2625 | 2024-11-28 | GUN5 Esports                              | W   | 0.580      | 0.354        | 0.102 (0.021)    | -                | 0 (0.000) |    10.40 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |     2651 | 2024-11-28 | Chimera Esports                           | W   | 0.578      | 0.333        | 0.025 (0.005)    | 0.595 (0.114)    | 0 (0.000) |     8.70 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           53 |     2662 | 2024-11-27 | Betclic Apogee Esports                    | L   | 0.573      | -            | -                | -                | -         |    -9.16 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |     2666 | 2024-11-27 | Iberian Soul                              | W   | 0.573      | 0.354        | 0.015 (0.003)    | 0.553 (0.112)    | -         |     8.36 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           51 |     2682 | 2024-11-27 | Betclic Apogee Esports                    | W   | 0.571      | -            | -                | -                | -         |     8.98 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           50 |     2720 | 2024-11-26 | Iberian Soul                              | L   | 0.567      | -            | -                | -                | -         |    -9.82 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           49 |     2739 | 2024-11-26 | Leo Team                                  | W   | 0.564      | 0.333        | 0.026 (0.005)    | 0.758 (0.143)    | -         |     9.07 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           48 |     2750 | 2024-11-25 | Fire Flux Esports                         | W   | 0.560      | 0.333        | -                | 1.000 (0.187)    | -         |    10.18 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           47 |     2813 | 2024-11-24 | Viperio                                   | W   | 0.551      | -            | -                | -                | -         |     5.51 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           46 |     2996 | 2024-11-22 | Betclic Apogee Esports                    | L   | 0.537      | -            | -                | -                | -         |    -8.44 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           45 |     3203 | 2024-11-18 | GenOne                                    | W   | 0.513      | 0.333        | -                | 0.848 (0.145)    | -         |     7.65 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           44 |     3556 | 2024-11-12 | G2 Ares                                   | W   | 0.472      | -            | -                | -                | -         |     4.11 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           43 |     3648 | 2024-11-10 | Zero Tenacity                             | L   | 0.460      | -            | -                | -                | -         |    -6.93 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           42 |     3724 | 2024-11-09 | 9Pandas                                   | L   | 0.453      | -            | -                | -                | -         |    -4.19 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           41 |     3847 | 2024-11-07 | AMKAL ESPORTS                             | W   | 0.439      | -            | -                | -                | -         |     5.75 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           40 |     3854 | 2024-11-07 | 9INE                                      | W   | 0.438      | -            | -                | -                | -         |     5.64 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           39 |     4072 | 2024-11-03 | 9Pandas                                   | L   | 0.412      | -            | -                | -                | -         |    -3.99 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           38 |     4206 | 2024-11-01 | HOTU                                      | W   | 0.398      | 0.384        | -                | 0.777 (0.119)    | -         |     3.61 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           37 |     4249 | 2024-10-31 | ECSTATIC                                  | L   | 0.393      | -            | -                | -                | -         |    -5.72 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           36 |     4362 | 2024-10-29 | Johnny Speeds                             | W   | 0.380      | 0.333        | 0.039 (0.005)    | -                | -         |     7.04 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           35 |     4373 | 2024-10-29 | Endpoint                                  | W   | 0.379      | -            | -                | -                | -         |     5.01 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           34 |     4445 | 2024-10-28 | Rebels Gaming                             | W   | 0.371      | -            | -                | -                | -         |     3.88 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           33 |     4472 | 2024-10-27 | AMKAL ESPORTS                             | W   | 0.366      | -            | -                | -                | -         |     4.85 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           32 |     4546 | 2024-10-26 | Natus Vincere Junior                      | L   | 0.358      | -            | -                | -                | -         |    -3.62 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           31 |     4681 | 2024-10-23 | Dynamo Eclot                              | W   | 0.338      | -            | -                | -                | -         |     3.00 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           30 |     4803 | 2024-10-20 | FAVBET Team                               | L   | 0.319      | -            | -                | -                | -         |    -5.08 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           29 |     4848 | 2024-10-19 | 9INE                                      | W   | 0.312      | -            | -                | -                | -         |     3.97 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           28 |     5083 | 2024-10-15 | GUN5 Esports                              | W   | 0.284      | 0.384        | 0.102 (0.011)    | -                | -         |     5.70 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           27 |     5210 | 2024-10-12 | GTZ.ESPORTS                               | W   | 0.265      | 0.143        | 0.080 (0.003)    | -                | -         |     7.50 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           26 |     5268 | 2024-10-11 | HOTU                                      | W   | 0.258      | -            | -                | -                | -         |     2.86 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           25 |     5293 | 2024-10-10 | CYBERSHOKE Esports                        | W   | 0.251      | -            | -                | -                | -         |     4.28 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           24 |     5626 | 2024-10-05 | Team Sampi                                | W   | 0.217      | -            | -                | -                | -         |     3.26 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           23 |     5778 | 2024-10-02 | ENCE Academy                              | L   | 0.199      | -            | -                | -                | -         |    -3.33 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           22 |     5800 | 2024-10-02 | HOTU                                      | L   | 0.197      | -            | -                | -                | -         |    -3.96 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           21 |     5805 | 2024-10-02 | TSM                                       | L   | 0.197      | -            | -                | -                | -         |    -3.75 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           20 |     5931 | 2024-09-30 | Johnny Speeds                             | W   | 0.184      | -            | -                | -                | -         |     3.38 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           19 |     6071 | 2024-09-28 | Nexus Gaming                              | L   | 0.171      | -            | -                | -                | -         |    -0.70 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           18 |     6084 | 2024-09-27 | Passion UA                                | L   | 0.170      | -            | -                | -                | -         |    -1.35 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           17 |     6197 | 2024-09-26 | GameAgents                                | L   | 0.159      | -            | -                | -                | -         |    -3.48 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           16 |     6225 | 2024-09-26 | Los kogutos                               | W   | 0.158      | -            | -                | -                | -         |     3.55 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           15 |     6279 | 2024-09-25 | Zero Tenacity                             | W   | 0.153      | -            | -                | -                | -         |     2.69 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           14 |     6313 | 2024-09-25 | TSM                                       | L   | 0.151      | -            | -                | -                | -         |    -2.92 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           13 |     6593 | 2024-09-21 | KONO.ECF                                  | W   | 0.124      | -            | -                | -                | -         |     2.43 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           12 |     6955 | 2024-09-15 | GamerLegion                               | L   | 0.084      | -            | -                | -                | -         |    -1.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           11 |     7050 | 2024-09-14 | ECSTATIC                                  | W   | 0.077      | -            | -                | -                | -         |     1.39 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           10 |     7102 | 2024-09-13 | Cloud9                                    | W   | 0.071      | -            | -                | -                | -         |     1.31 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            9 |     7263 | 2024-09-10 | Chimera Esports                           | W   | 0.051      | -            | -                | -                | -         |     0.82 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            8 |     7309 | 2024-09-09 | FAVBET Team                               | L   | 0.045      | -            | -                | -                | -         |    -0.69 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            7 |     7412 | 2024-09-07 | Team Spirit Academy                       | L   | 0.033      | -            | -                | -                | -         |    -0.39 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            6 |     7500 | 2024-09-06 | Passion UA                                | L   | 0.026      | -            | -                | -                | -         |    -0.20 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            5 |     7612 | 2024-09-05 | BetBoom Team                              | L   | 0.019      | -            | -                | -                | -         |    -0.15 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            4 |     7626 | 2024-09-05 | Team Sampi                                | L   | 0.018      | -            | -                | -                | -         |    -0.29 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            3 |     7629 | 2024-09-05 | Revenant Esports                          | W   | 0.017      | -            | -                | -                | -         |     0.07 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            2 |     7677 | 2024-09-04 | Rhyno Esports                             | W   | 0.011      | -            | -                | -                | -         |     0.10 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            1 |     7753 | 2024-09-03 | SINNERS Esports                           | W   | 0.004      | -            | -                | -                | -         |     0.08 | kraghen, nicoodoz, Nodios, Queenix, roeJ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,256.61)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.593 | $12,000.00     | $7,116.67       |
| 2024-11-29 |      0.584 | $3,000.00      | $1,752.50       |
| 2024-11-27 |      0.572 | $1,000.00      | $572.08         |
| 2024-11-12 |      0.473 | $500.00        | $236.31         |
| 2024-11-10 |      0.460 | $2,500.00      | $1,150.00       |
| 2024-09-15 |      0.086 | $5,000.00      | $429.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
