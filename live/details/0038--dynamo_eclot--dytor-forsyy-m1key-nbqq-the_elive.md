### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Dytor, forsyy, M1key, nbqq, The eLiVe<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1023.6<br />
<br />
Final Rank Value (1023.6) = Starting Rank Value (1083.1) + Head To Head Adjustments (-59.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.528[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.316[<sup>2</sup>](#table1)

The average of these factors is 0.341<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1083.1
- 400 + ( ( 0.341 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1083.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |      182 | 2025-02-22 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -14.65 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           72 |      260 | 2025-02-20 | Fnatic                                    | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.459 (0.200)    | 0 (0.000) |    17.14 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           71 |      497 | 2025-02-14 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -12.31 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           70 |      541 | 2025-02-12 | Team Spirit Academy                       | W   | 1.000      | 0.435        | 0.068 (0.030)    | 0.702 (0.305)    | 0 (0.000) |    14.92 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           69 |      709 | 2025-02-08 | NEVERMORE (Ukrainian team)                | L   | 1.000      | -            | -                | -                | -         |   -23.90 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           68 |      763 | 2025-02-07 | Ex-XI Esport                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.84 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           67 |      859 | 2025-02-06 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -20.95 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           66 |      916 | 2025-02-05 | Nexus Gaming                              | W   | 1.000      | 0.143        | 0.187 (0.027)    | 0.795 (0.114)    | -         |    12.19 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           65 |     1578 | 2024-12-17 | GUN5 Esports                              | L   | 0.698      | -            | -                | -                | -         |   -12.86 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           64 |     1596 | 2024-12-16 | Monte                                     | W   | 0.691      | -            | -                | -                | -         |     6.33 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           63 |     1704 | 2024-12-14 | ECSTATIC                                  | W   | 0.678      | 0.435        | 0.033 (0.010)    | 0.820 (0.242)    | -         |     7.05 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           62 |     1800 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.671      | -            | -                | -                | -         |   -11.51 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           61 |     1847 | 2024-12-12 | ECSTATIC                                  | W   | 0.665      | 0.435        | 0.033 (0.010)    | 0.820 (0.237)    | -         |     6.43 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           60 |     2807 | 2024-11-24 | UNiTY esports                             | W   | 0.544      | -            | -                | -                | 1 (0.544) |     4.04 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           59 |     2895 | 2024-11-23 | BRUTE                                     | W   | 0.538      | -            | -                | -                | 1 (0.538) |     2.19 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           58 |     3147 | 2024-11-19 | Fnatic                                    | L   | 0.515      | -            | -                | -                | -         |    -7.68 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           57 |     3188 | 2024-11-18 | HEROIC                                    | W   | 0.507      | 0.143        | 0.131 (0.010)    | -                | 1 (0.507) |     8.66 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           56 |     3231 | 2024-11-17 | SINNERS Esports                           | L   | 0.501      | -            | -                | -                | -         |   -10.65 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           55 |     3281 | 2024-11-17 | GamerLegion                               | W   | 0.496      | 0.143        | 0.129 (0.009)    | -                | 1 (0.496) |    14.84 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           54 |     3303 | 2024-11-16 | Team Falcons                              | L   | 0.495      | -            | -                | -                | -         |   -13.37 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           53 |     3625 | 2024-11-11 | BetBoom Team                              | L   | 0.458      | -            | -                | -                | -         |    -8.20 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           52 |     3643 | 2024-11-11 | 9Pandas                                   | L   | 0.456      | -            | -                | -                | -         |    -7.98 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           51 |     3665 | 2024-11-10 | 9Pandas                                   | L   | 0.452      | -            | -                | -                | -         |    -8.23 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           50 |     3682 | 2024-11-10 | SINNERS Esports                           | W   | 0.451      | -            | -                | -                | -         |     4.02 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           49 |     3695 | 2024-11-10 | Natus Vincere Junior                      | W   | 0.449      | 0.371        | 0.091 (0.015)    | 0.865 (0.144)    | -         |     5.74 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           48 |     3750 | 2024-11-09 | Sashi Esport                              | W   | 0.444      | 0.384        | -                | 0.499 (0.085)    | -         |     4.50 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           47 |     3767 | 2024-11-09 | Rebels Gaming                             | W   | 0.443      | -            | -                | -                | -         |     1.96 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           46 |     3813 | 2024-11-08 | AMKAL ESPORTS                             | W   | 0.437      | 0.384        | -                | 0.674 (0.113)    | -         |     2.45 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           45 |     3821 | 2024-11-08 | Wild Lotus                                | W   | 0.436      | -            | -                | -                | -         |     2.41 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           44 |     3864 | 2024-11-07 | 9Pandas                                   | L   | 0.430      | -            | -                | -                | -         |    -7.70 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           43 |     3915 | 2024-11-06 | Johnny Speeds                             | W   | 0.423      | -            | -                | -                | -         |     4.26 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           42 |     3969 | 2024-11-05 | SINNERS Esports                           | W   | 0.416      | -            | -                | -                | -         |     4.10 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           41 |     4034 | 2024-11-04 | GUN5 Esports                              | L   | 0.409      | -            | -                | -                | -         |    -8.57 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           40 |     4086 | 2024-11-03 | GUN5 Esports                              | W   | 0.403      | 0.371        | 0.103 (0.015)    | -                | -         |     4.31 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           39 |     4161 | 2024-11-02 | P0RTUGAL                                  | W   | 0.397      | -            | -                | -                | -         |     2.17 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           38 |     4225 | 2024-11-01 | Wild Lotus                                | W   | 0.389      | -            | -                | -                | -         |     2.16 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           37 |     4330 | 2024-10-30 | Chimera Esports                           | W   | 0.378      | 0.371        | -                | 0.586 (0.082)    | -         |     2.88 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           36 |     4451 | 2024-10-28 | Zero Tenacity                             | W   | 0.364      | 0.384        | -                | 0.684 (0.096)    | -         |     2.94 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           35 |     4573 | 2024-10-26 | GUN5 Esports                              | L   | 0.349      | -            | -                | -                | -         |    -7.30 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           34 |     4731 | 2024-10-21 | Dark Cloud Esports                        | W   | 0.318      | -            | -                | -                | -         |     2.06 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           33 |     4821 | 2024-10-20 | 9Pandas                                   | W   | 0.310      | 0.384        | 0.085 (0.010)    | -                | -         |     3.87 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           32 |     4962 | 2024-10-17 | Los kogutos                               | L   | 0.290      | -            | -                | -                | -         |    -5.65 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           31 |     5096 | 2024-10-15 | ALASKA                                    | L   | 0.275      | -            | -                | -                | -         |    -3.75 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           30 |     5121 | 2024-10-14 | GameAgents                                | W   | 0.270      | -            | -                | -                | -         |     0.92 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           29 |     5250 | 2024-10-12 | Leo Team                                  | W   | 0.256      | -            | -                | -                | -         |     1.81 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           28 |     5455 | 2024-10-08 | WW Team                                   | W   | 0.229      | -            | -                | -                | -         |     0.31 | Blytz, Dytor, forsyy, nbqq, realzen   |
|           27 |     5470 | 2024-10-07 | UNiTY esports                             | L   | 0.225      | -            | -                | -                | -         |    -5.46 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           26 |     5611 | 2024-10-05 | Team Sampi                                | W   | 0.210      | -            | -                | -                | 1 (0.210) |     1.24 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           25 |     5631 | 2024-10-05 | The Prodigies                             | W   | 0.209      | -            | -                | -                | 1 (0.209) |     0.34 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           24 |     5684 | 2024-10-04 | Team Sampi                                | L   | 0.204      | -            | -                | -                | -         |    -5.25 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           23 |     5738 | 2024-10-03 | The Prodigies                             | W   | 0.197      | -            | -                | -                | 1 (0.197) |     0.31 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           22 |     5741 | 2024-10-03 | 500                                       | L   | 0.196      | -            | -                | -                | -         |    -3.81 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           21 |     5862 | 2024-10-01 | Kubix Esports                             | L   | 0.184      | -            | -                | -                | -         |    -4.02 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           20 |     5865 | 2024-10-01 | Alliance                                  | W   | 0.184      | -            | -                | -                | -         |     1.51 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           19 |     5948 | 2024-09-30 | Monte                                     | W   | 0.175      | -            | -                | -                | -         |     1.58 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           18 |     6376 | 2024-09-24 | Devils.one                                | W   | 0.138      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           17 |     6396 | 2024-09-24 | GOSTIVAR                                  | W   | 0.138      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           16 |     6599 | 2024-09-21 | Team Sampi                                | L   | 0.117      | -            | -                | -                | -         |    -3.03 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           15 |     6643 | 2024-09-20 | SINNERS Esports                           | L   | 0.111      | -            | -                | -                | -         |    -2.50 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           14 |     6794 | 2024-09-18 | Natus Vincere Junior                      | L   | 0.095      | -            | -                | -                | -         |    -1.99 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           13 |     6862 | 2024-09-17 | KONO.ECF                                  | W   | 0.089      | -            | -                | -                | -         |     0.81 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           12 |     6914 | 2024-09-16 | Natus Vincere Junior                      | L   | 0.083      | -            | -                | -                | -         |    -1.74 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           11 |     6983 | 2024-09-14 | Illuminar Gaming                          | W   | 0.072      | -            | -                | -                | -         |     0.51 | Dytor, forsyy, kreaz, nbqq, NEOFRAG   |
|           10 |     7063 | 2024-09-14 | Leo Team                                  | W   | 0.069      | -            | -                | -                | -         |     0.43 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            9 |     7205 | 2024-09-11 | Copenhagen Wolves (American organization) | L   | 0.050      | -            | -                | -                | -         |    -1.47 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            8 |     7227 | 2024-09-11 | KONO.ECF                                  | W   | 0.049      | -            | -                | -                | -         |     0.44 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            7 |     7273 | 2024-09-10 | SINNERS Academy                           | W   | 0.043      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            6 |     7327 | 2024-09-09 | MOUZ NXT                                  | W   | 0.036      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            5 |     7359 | 2024-09-08 | BRUTE                                     | W   | 0.031      | -            | -                | -                | -         |     0.11 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            4 |     7380 | 2024-09-08 | Natus Vincere Junior                      | L   | 0.029      | -            | -                | -                | -         |    -0.61 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            3 |     7604 | 2024-09-05 | RUBY                                      | W   | 0.011      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            2 |     7614 | 2024-09-05 | BRUTE                                     | W   | 0.011      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            1 |     7700 | 2024-09-04 | SINNERS Academy                           | W   | 0.002      | -            | -                | -                | -         |     0.01 | Blytz, Dytor, forsyy, kreaz, nbqq     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,144.38)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $2,000.00      | $2,000.00       |
| 2025-02-15 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-12-17 |      0.698 | $10,000.00     | $6,984.72       |
| 2024-11-24 |      0.544 | $41,107.93     | $22,346.73      |
| 2024-11-12 |      0.464 | $1,000.00      | $464.42         |
| 2024-11-11 |      0.456 | $5,000.00      | $2,279.86       |
| 2024-11-10 |      0.452 | $7,500.00      | $3,388.54       |
| 2024-10-05 |      0.210 | $10,981.72     | $2,310.74       |
| 2024-09-22 |      0.124 | $668.11        | $83.11          |
| 2024-09-18 |      0.095 | $3,000.00      | $286.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
