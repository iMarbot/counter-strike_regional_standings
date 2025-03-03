### Roster Details<br />
Team Name: Tricked Esport<br />
Roster: Nodios, Queenix, roeJ, salazar, valde<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.9<br />
<br />
Final Rank Value (861.9) = Starting Rank Value (830.5) + Head To Head Adjustments (31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.404[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.134[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 830.5
- 400 + ( ( 0.215 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 830.5


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
|           72 |       19 | 2025-03-01 | ECSTATIC                                  | L   | 1.000      | -            | -                | -                | -         |   -15.54 | Nodios, Queenix, roeJ, salazar, valde    |
|           71 |       25 | 2025-02-28 | ESC Gaming                                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.26 | Nodios, Queenix, roeJ, salazar, valde    |
|           70 |       60 | 2025-02-25 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.54 | Nodios, Queenix, roeJ, salazar, valde    |
|           69 |       77 | 2025-02-24 | OG                                        | L   | 1.000      | -            | -                | -                | -         |   -10.19 | Nodios, Queenix, roeJ, salazar, valde    |
|           68 |      194 | 2025-02-21 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -12.63 | Leakz, niko, Queenix, salazar, valde     |
|           67 |      212 | 2025-02-21 | Dark Cloud Esports                        | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.819 (0.117)    | 0 (0.000) |    15.06 | Leakz, niko, Queenix, salazar, valde     |
|           66 |      223 | 2025-02-21 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    15.44 | Leakz, niko, Queenix, salazar, valde     |
|           65 |      240 | 2025-02-20 | Viperio                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | Leakz, niko, Queenix, salazar, valde     |
|           64 |     1012 | 2025-02-04 | Wildcard Academy                          | L   | 1.000      | -            | -                | -                | -         |   -27.10 | Leakz, Nodios, Queenix, salazar, valde   |
|           63 |     1971 | 2024-12-09 | Betclic Apogee Esports                    | L   | 0.643      | -            | -                | -                | -         |   -10.07 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           62 |     2107 | 2024-12-07 | Fire Flux Esports                         | L   | 0.629      | -            | -                | -                | -         |    -8.99 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           61 |     2171 | 2024-12-05 | Chimera Esports                           | L   | 0.618      | -            | -                | -                | -         |   -10.17 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           60 |     2188 | 2024-12-05 | Team Sampi                                | W   | 0.616      | -            | -                | -                | 0 (0.000) |     6.76 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           59 |     2239 | 2024-12-04 | Iberian Soul                              | L   | 0.610      | -            | -                | -                | -         |   -10.59 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           58 |     2450 | 2024-12-01 | Iberian Soul                              | L   | 0.590      | -            | -                | -                | -         |   -10.80 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           57 |     2524 | 2024-11-30 | Betclic Apogee Esports                    | W   | 0.585      | 0.354        | -                | 0.513 (0.106)    | 0 (0.000) |     8.90 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           56 |     2602 | 2024-11-29 | Natus Vincere Junior                      | W   | 0.578      | 0.354        | 0.091 (0.019)    | 0.865 (0.177)    | 0 (0.000) |    11.56 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           55 |     2614 | 2024-11-29 | BC.Game Esports                           | L   | 0.576      | -            | -                | -                | -         |    -9.85 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |     2637 | 2024-11-28 | GUN5 Esports                              | W   | 0.572      | 0.354        | 0.103 (0.021)    | -                | 0 (0.000) |    10.27 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           53 |     2663 | 2024-11-28 | Chimera Esports                           | W   | 0.569      | 0.333        | 0.026 (0.005)    | 0.586 (0.111)    | 0 (0.000) |     8.57 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |     2674 | 2024-11-27 | Betclic Apogee Esports                    | L   | 0.565      | -            | -                | -                | -         |    -9.01 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           51 |     2678 | 2024-11-27 | Iberian Soul                              | W   | 0.565      | 0.354        | 0.015 (0.003)    | 0.551 (0.110)    | -         |     8.26 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           50 |     2694 | 2024-11-27 | Betclic Apogee Esports                    | W   | 0.563      | -            | -                | -                | -         |     8.88 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           49 |     2732 | 2024-11-26 | Iberian Soul                              | L   | 0.559      | -            | -                | -                | -         |    -9.65 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           48 |     2751 | 2024-11-26 | Leo Team                                  | W   | 0.556      | 0.333        | 0.026 (0.005)    | 0.748 (0.139)    | -         |     8.93 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           47 |     2762 | 2024-11-25 | Fire Flux Esports                         | W   | 0.552      | 0.333        | -                | 1.000 (0.184)    | -         |    10.01 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           46 |     2825 | 2024-11-24 | Viperio                                   | W   | 0.543      | -            | -                | -                | -         |     5.42 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           45 |     3008 | 2024-11-22 | Betclic Apogee Esports                    | L   | 0.529      | -            | -                | -                | -         |    -8.29 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           44 |     3215 | 2024-11-18 | GenOne                                    | W   | 0.504      | 0.333        | -                | 0.837 (0.141)    | -         |     7.53 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           43 |     3568 | 2024-11-12 | G2 Ares                                   | W   | 0.463      | -            | -                | -                | -         |     4.05 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           42 |     3660 | 2024-11-10 | Zero Tenacity                             | L   | 0.452      | -            | -                | -                | -         |    -6.83 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           41 |     3736 | 2024-11-09 | 9Pandas                                   | L   | 0.444      | -            | -                | -                | -         |    -4.12 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           40 |     3859 | 2024-11-07 | AMKAL ESPORTS                             | W   | 0.431      | 0.384        | 0.017 (0.003)    | -                | -         |     5.65 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           39 |     3866 | 2024-11-07 | 9INE                                      | W   | 0.430      | -            | -                | -                | -         |     5.51 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           38 |     4084 | 2024-11-03 | 9Pandas                                   | L   | 0.403      | -            | -                | -                | -         |    -3.92 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           37 |     4218 | 2024-11-01 | HOTU                                      | W   | 0.390      | 0.384        | -                | 0.768 (0.115)    | -         |     3.55 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           36 |     4261 | 2024-10-31 | ECSTATIC                                  | L   | 0.385      | -            | -                | -                | -         |    -5.61 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           35 |     4374 | 2024-10-29 | Johnny Speeds                             | W   | 0.372      | 0.333        | 0.039 (0.005)    | -                | -         |     6.86 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           34 |     4385 | 2024-10-29 | Endpoint                                  | W   | 0.371      | -            | -                | -                | -         |     4.91 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           33 |     4457 | 2024-10-28 | Rebels Gaming                             | W   | 0.363      | -            | -                | -                | -         |     3.80 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           32 |     4484 | 2024-10-27 | AMKAL ESPORTS                             | W   | 0.357      | -            | -                | -                | -         |     4.73 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           31 |     4558 | 2024-10-26 | Natus Vincere Junior                      | L   | 0.349      | -            | -                | -                | -         |    -3.54 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           30 |     4693 | 2024-10-23 | Dynamo Eclot                              | W   | 0.330      | -            | -                | -                | -         |     2.94 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           29 |     4815 | 2024-10-20 | FAVBET Team                               | L   | 0.310      | -            | -                | -                | -         |    -4.95 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           28 |     4860 | 2024-10-19 | 9INE                                      | W   | 0.304      | -            | -                | -                | -         |     3.84 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           27 |     5095 | 2024-10-15 | GUN5 Esports                              | W   | 0.275      | 0.384        | 0.103 (0.011)    | -                | -         |     5.53 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           26 |     5222 | 2024-10-12 | GTZ.ESPORTS                               | W   | 0.257      | 0.143        | 0.080 (0.003)    | -                | -         |     7.26 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           25 |     5280 | 2024-10-11 | HOTU                                      | W   | 0.250      | -            | -                | -                | -         |     2.77 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           24 |     5305 | 2024-10-10 | CYBERSHOKE Esports                        | W   | 0.243      | -            | -                | -                | -         |     4.15 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           23 |     5638 | 2024-10-05 | Team Sampi                                | W   | 0.209      | -            | -                | -                | -         |     3.12 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           22 |     5790 | 2024-10-02 | ENCE Academy                              | L   | 0.190      | -            | -                | -                | -         |    -3.18 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           21 |     5812 | 2024-10-02 | HOTU                                      | L   | 0.189      | -            | -                | -                | -         |    -3.79 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           20 |     5817 | 2024-10-02 | TSM                                       | L   | 0.189      | -            | -                | -                | -         |    -3.60 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           19 |     5943 | 2024-09-30 | Johnny Speeds                             | W   | 0.176      | -            | -                | -                | -         |     3.23 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           18 |     6083 | 2024-09-28 | Nexus Gaming                              | L   | 0.163      | -            | -                | -                | -         |    -0.67 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           17 |     6096 | 2024-09-27 | Passion UA                                | L   | 0.162      | -            | -                | -                | -         |    -1.29 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           16 |     6209 | 2024-09-26 | GameAgents                                | L   | 0.151      | -            | -                | -                | -         |    -3.31 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           15 |     6237 | 2024-09-26 | Los kogutos                               | W   | 0.149      | -            | -                | -                | -         |     3.35 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           14 |     6291 | 2024-09-25 | Zero Tenacity                             | W   | 0.145      | -            | -                | -                | -         |     2.53 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           13 |     6325 | 2024-09-25 | TSM                                       | L   | 0.143      | -            | -                | -                | -         |    -2.77 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           12 |     6605 | 2024-09-21 | KONO.ECF                                  | W   | 0.116      | -            | -                | -                | -         |     2.27 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           11 |     6967 | 2024-09-15 | GamerLegion                               | L   | 0.076      | -            | -                | -                | -         |    -1.62 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           10 |     7062 | 2024-09-14 | ECSTATIC                                  | W   | 0.069      | -            | -                | -                | -         |     1.24 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            9 |     7114 | 2024-09-13 | Cloud9                                    | W   | 0.063      | -            | -                | -                | -         |     1.16 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            8 |     7275 | 2024-09-10 | Chimera Esports                           | W   | 0.042      | -            | -                | -                | -         |     0.69 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            7 |     7321 | 2024-09-09 | FAVBET Team                               | L   | 0.037      | -            | -                | -                | -         |    -0.56 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            6 |     7424 | 2024-09-07 | Team Spirit Academy                       | L   | 0.025      | -            | -                | -                | -         |    -0.30 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            5 |     7512 | 2024-09-06 | Passion UA                                | L   | 0.018      | -            | -                | -                | -         |    -0.14 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            4 |     7624 | 2024-09-05 | BetBoom Team                              | L   | 0.010      | -            | -                | -                | -         |    -0.08 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            3 |     7638 | 2024-09-05 | Team Sampi                                | L   | 0.009      | -            | -                | -                | -         |    -0.16 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            2 |     7641 | 2024-09-05 | Revenant Esports                          | W   | 0.009      | -            | -                | -                | -         |     0.04 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            1 |     7689 | 2024-09-04 | Rhyno Esports                             | W   | 0.003      | -            | -                | -                | -         |     0.03 | kraghen, nicoodoz, Nodios, Queenix, roeJ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,059.94)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.585 | $12,000.00     | $7,018.33       |
| 2024-11-29 |      0.576 | $3,000.00      | $1,727.92       |
| 2024-11-27 |      0.564 | $1,000.00      | $563.89         |
| 2024-11-12 |      0.464 | $500.00        | $232.21         |
| 2024-11-10 |      0.452 | $2,500.00      | $1,129.51       |
| 2024-09-15 |      0.078 | $5,000.00      | $388.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
