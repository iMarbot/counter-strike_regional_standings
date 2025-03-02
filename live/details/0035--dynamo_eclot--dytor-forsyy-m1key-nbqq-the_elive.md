### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Dytor, forsyy, M1key, nbqq, The eLiVe<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1025.4<br />
<br />
Final Rank Value (1025.4) = Starting Rank Value (1086.4) + Head To Head Adjustments (-61.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.528[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.322[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1086.4
- 400 + ( ( 0.344 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1086.4


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
|           74 |      170 | 2025-02-22 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -14.62 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           73 |      248 | 2025-02-20 | Fnatic                                    | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.461 (0.200)    | 0 (0.000) |    17.17 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           72 |      485 | 2025-02-14 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -12.35 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           71 |      529 | 2025-02-12 | Team Spirit Academy                       | W   | 1.000      | 0.435        | 0.068 (0.030)    | 0.714 (0.310)    | 0 (0.000) |    14.99 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           70 |      697 | 2025-02-08 | NEVERMORE (Ukrainian team)                | L   | 1.000      | -            | -                | -                | -         |   -23.93 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           69 |      751 | 2025-02-07 | Ex-XI Esport                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.83 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           68 |      847 | 2025-02-06 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -20.95 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           67 |      904 | 2025-02-05 | Nexus Gaming                              | W   | 1.000      | 0.143        | 0.186 (0.027)    | 0.808 (0.115)    | -         |    12.11 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           66 |     1566 | 2024-12-17 | GUN5 Esports                              | L   | 0.707      | -            | -                | -                | -         |   -13.00 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           65 |     1584 | 2024-12-16 | Monte                                     | W   | 0.699      | -            | -                | -                | -         |     6.43 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           64 |     1692 | 2024-12-14 | ECSTATIC                                  | W   | 0.686      | 0.435        | 0.033 (0.010)    | 0.828 (0.247)    | -         |     7.15 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           63 |     1788 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.679      | -            | -                | -                | -         |   -11.62 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           62 |     1835 | 2024-12-12 | ECSTATIC                                  | W   | 0.673      | 0.435        | 0.033 (0.010)    | 0.828 (0.242)    | -         |     6.52 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           61 |     2795 | 2024-11-24 | UNiTY esports                             | W   | 0.552      | -            | -                | -                | 1 (0.552) |     4.12 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           60 |     2883 | 2024-11-23 | BRUTE                                     | W   | 0.546      | -            | -                | -                | 1 (0.546) |     2.21 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           59 |     3135 | 2024-11-19 | Fnatic                                    | L   | 0.523      | -            | -                | -                | -         |    -7.78 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           58 |     3176 | 2024-11-18 | HEROIC                                    | W   | 0.516      | 0.143        | 0.131 (0.010)    | -                | 1 (0.516) |     8.84 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           57 |     3219 | 2024-11-17 | SINNERS Esports                           | L   | 0.509      | -            | -                | -                | -         |   -10.82 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           56 |     3269 | 2024-11-17 | GamerLegion                               | W   | 0.504      | 0.143        | 0.127 (0.009)    | -                | 1 (0.504) |    15.09 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           55 |     3291 | 2024-11-16 | Team Falcons                              | L   | 0.503      | -            | -                | -                | -         |   -13.58 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           54 |     3613 | 2024-11-11 | BetBoom Team                              | L   | 0.466      | -            | -                | -                | -         |    -8.35 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           53 |     3631 | 2024-11-11 | 9Pandas                                   | L   | 0.464      | -            | -                | -                | -         |    -8.12 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           52 |     3653 | 2024-11-10 | 9Pandas                                   | L   | 0.460      | -            | -                | -                | -         |    -8.37 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           51 |     3670 | 2024-11-10 | SINNERS Esports                           | W   | 0.459      | -            | -                | -                | -         |     4.08 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           50 |     3683 | 2024-11-10 | Natus Vincere Junior                      | W   | 0.458      | 0.371        | 0.091 (0.015)    | 0.878 (0.149)    | -         |     5.86 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           49 |     3738 | 2024-11-09 | Sashi Esport                              | W   | 0.452      | 0.384        | -                | 0.503 (0.087)    | -         |     4.56 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           48 |     3755 | 2024-11-09 | Rebels Gaming                             | W   | 0.451      | -            | -                | -                | -         |     2.00 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           47 |     3801 | 2024-11-08 | AMKAL ESPORTS                             | W   | 0.446      | 0.384        | -                | 0.681 (0.117)    | -         |     2.50 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           46 |     3809 | 2024-11-08 | Wild Lotus                                | W   | 0.444      | -            | -                | -                | -         |     2.47 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           45 |     3852 | 2024-11-07 | 9Pandas                                   | L   | 0.438      | -            | -                | -                | -         |    -7.83 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           44 |     3903 | 2024-11-06 | Johnny Speeds                             | W   | 0.431      | -            | -                | -                | -         |     4.36 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           43 |     3957 | 2024-11-05 | SINNERS Esports                           | W   | 0.424      | -            | -                | -                | -         |     4.18 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           42 |     4022 | 2024-11-04 | GUN5 Esports                              | L   | 0.417      | -            | -                | -                | -         |    -8.75 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           41 |     4074 | 2024-11-03 | GUN5 Esports                              | W   | 0.412      | 0.371        | 0.102 (0.016)    | -                | -         |     4.39 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           40 |     4149 | 2024-11-02 | P0RTUGAL                                  | W   | 0.405      | -            | -                | -                | -         |     2.20 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           39 |     4213 | 2024-11-01 | Wild Lotus                                | W   | 0.398      | -            | -                | -                | -         |     2.22 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           38 |     4318 | 2024-10-30 | Chimera Esports                           | W   | 0.386      | 0.371        | -                | 0.595 (0.085)    | -         |     2.94 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           37 |     4439 | 2024-10-28 | Zero Tenacity                             | W   | 0.372      | 0.384        | -                | 0.692 (0.099)    | -         |     3.02 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           36 |     4561 | 2024-10-26 | GUN5 Esports                              | L   | 0.357      | -            | -                | -                | -         |    -7.48 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           35 |     4719 | 2024-10-21 | Dark Cloud Esports                        | W   | 0.327      | -            | -                | -                | -         |     2.09 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           34 |     4809 | 2024-10-20 | 9Pandas                                   | W   | 0.318      | 0.384        | 0.085 (0.010)    | -                | -         |     3.97 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           33 |     4950 | 2024-10-17 | Los kogutos                               | L   | 0.298      | -            | -                | -                | -         |    -5.80 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           32 |     5085 | 2024-10-15 | ALASKA                                    | L   | 0.284      | -            | -                | -                | -         |    -3.90 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           31 |     5109 | 2024-10-14 | GameAgents                                | W   | 0.279      | -            | -                | -                | -         |     0.96 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           30 |     5239 | 2024-10-12 | Leo Team                                  | W   | 0.264      | -            | -                | -                | -         |     1.87 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           29 |     5443 | 2024-10-08 | WW Team                                   | W   | 0.237      | -            | -                | -                | -         |     0.32 | Blytz, Dytor, forsyy, nbqq, realzen   |
|           28 |     5458 | 2024-10-07 | UNiTY esports                             | L   | 0.233      | -            | -                | -                | -         |    -5.64 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           27 |     5603 | 2024-10-05 | Team Sampi                                | W   | 0.219      | -            | -                | -                | 1 (0.219) |     1.29 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           26 |     5619 | 2024-10-05 | The Prodigies                             | W   | 0.217      | -            | -                | -                | 1 (0.217) |     0.35 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           25 |     5672 | 2024-10-04 | Team Sampi                                | L   | 0.212      | -            | -                | -                | -         |    -5.46 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           24 |     5726 | 2024-10-03 | The Prodigies                             | W   | 0.205      | -            | -                | -                | 1 (0.205) |     0.32 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           23 |     5729 | 2024-10-03 | 500                                       | L   | 0.204      | -            | -                | -                | -         |    -4.00 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           22 |     5850 | 2024-10-01 | Kubix Esports                             | L   | 0.193      | -            | -                | -                | -         |    -4.21 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           21 |     5853 | 2024-10-01 | Alliance                                  | W   | 0.192      | -            | -                | -                | -         |     1.56 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           20 |     5936 | 2024-09-30 | Monte                                     | W   | 0.184      | -            | -                | -                | -         |     1.64 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           19 |     6364 | 2024-09-24 | Devils.one                                | W   | 0.146      | -            | -                | -                | -         |     0.41 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           18 |     6384 | 2024-09-24 | GOSTIVAR                                  | W   | 0.146      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           17 |     6587 | 2024-09-21 | Team Sampi                                | L   | 0.125      | -            | -                | -                | -         |    -3.24 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           16 |     6631 | 2024-09-20 | SINNERS Esports                           | L   | 0.119      | -            | -                | -                | -         |    -2.69 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           15 |     6782 | 2024-09-18 | Natus Vincere Junior                      | L   | 0.104      | -            | -                | -                | -         |    -2.16 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           14 |     6850 | 2024-09-17 | KONO.ECF                                  | W   | 0.098      | -            | -                | -                | -         |     0.88 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           13 |     6902 | 2024-09-16 | Natus Vincere Junior                      | L   | 0.091      | -            | -                | -                | -         |    -1.92 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           12 |     6971 | 2024-09-14 | Illuminar Gaming                          | W   | 0.080      | -            | -                | -                | -         |     0.57 | Dytor, forsyy, kreaz, nbqq, NEOFRAG   |
|           11 |     7051 | 2024-09-14 | Leo Team                                  | W   | 0.077      | -            | -                | -                | -         |     0.48 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           10 |     7193 | 2024-09-11 | Copenhagen Wolves (American organization) | L   | 0.059      | -            | -                | -                | -         |    -1.71 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            9 |     7215 | 2024-09-11 | KONO.ECF                                  | W   | 0.057      | -            | -                | -                | -         |     0.51 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            8 |     7261 | 2024-09-10 | SINNERS Academy                           | W   | 0.051      | -            | -                | -                | -         |     0.20 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            7 |     7315 | 2024-09-09 | MOUZ NXT                                  | W   | 0.044      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            6 |     7347 | 2024-09-08 | BRUTE                                     | W   | 0.039      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            5 |     7368 | 2024-09-08 | Natus Vincere Junior                      | L   | 0.037      | -            | -                | -                | -         |    -0.78 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            4 |     7592 | 2024-09-05 | RUBY                                      | W   | 0.019      | -            | -                | -                | -         |     0.06 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            3 |     7602 | 2024-09-05 | BRUTE                                     | W   | 0.019      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            2 |     7688 | 2024-09-04 | SINNERS Academy                           | W   | 0.010      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            1 |     7735 | 2024-09-03 | K27                                       | L   | 0.006      | -            | -                | -                | -         |    -0.13 | Blytz, Dytor, forsyy, kreaz, nbqq     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,793.85)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $2,000.00      | $2,000.00       |
| 2025-02-15 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-12-17 |      0.707 | $10,000.00     | $7,066.67       |
| 2024-11-24 |      0.552 | $41,107.93     | $22,683.59      |
| 2024-11-12 |      0.473 | $1,000.00      | $472.62         |
| 2024-11-11 |      0.464 | $5,000.00      | $2,320.83       |
| 2024-11-10 |      0.460 | $7,500.00      | $3,450.00       |
| 2024-10-05 |      0.219 | $10,981.72     | $2,400.73       |
| 2024-09-22 |      0.133 | $668.11        | $88.59          |
| 2024-09-18 |      0.104 | $3,000.00      | $310.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
