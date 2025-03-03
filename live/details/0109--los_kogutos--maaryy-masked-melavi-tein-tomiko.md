### Roster Details<br />
Team Name: Los kogutos<br />
Roster: maaryy, mASKED, Melavi, tein, tomiko<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  836.5<br />
<br />
Final Rank Value (836.5) = Starting Rank Value (1009.1) + Head To Head Adjustments (-172.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.439[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1009.1
- 400 + ( ( 0.304 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1009.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           85 |     1224 | 2025-01-08 | EYEBALLERS                                | L   | 0.844      | -            | -                | -                | -         |   -15.29 | maaryy, mASKED, Melavi, tein, tomiko |
|           84 |     1226 | 2025-01-07 | Insilio                                   | L   | 0.838      | -            | -                | -                | -         |   -18.23 | maaryy, mASKED, Melavi, tein, tomiko |
|           83 |     1233 | 2025-01-05 | BadGuys                                   | W   | 0.824      | 0.417        | -                | 0.279 (0.096)    | -         |     6.18 | maaryy, mASKED, Melavi, tein, tomiko |
|           82 |     1238 | 2025-01-03 | FLuffy Gangsters                          | L   | 0.812      | -            | -                | -                | -         |   -13.44 | maaryy, mASKED, Melavi, tein, tomiko |
|           81 |     1273 | 2024-12-29 | KONO.ECF                                  | L   | 0.777      | -            | -                | -                | -         |   -10.15 | kRaSnaL, maaryy, mASKED, mhL, tomiko |
|           80 |     1318 | 2024-12-28 | VOLT (European team)                      | W   | 0.770      | -            | -                | -                | -         |     6.88 | kRaSnaL, maaryy, mASKED, mhL, tomiko |
|           79 |     2878 | 2024-11-23 | HyperSpirit                               | L   | 0.538      | -            | -                | -                | -         |   -13.39 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           78 |     2981 | 2024-11-22 | ROUNDS                                    | L   | 0.531      | -            | -                | -                | -         |   -15.21 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           77 |     3050 | 2024-11-21 | 1win                                      | W   | 0.524      | 0.372        | -                | 0.326 (0.064)    | -         |     5.07 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           76 |     3117 | 2024-11-20 | Ex-Soul's Heart Esport                    | W   | 0.518      | -            | -                | -                | -         |     2.76 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           75 |     3127 | 2024-11-20 | TEAM NEXT LEVEL                           | W   | 0.518      | 0.372        | -                | 0.464 (0.089)    | -         |     3.72 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           74 |     3343 | 2024-11-16 | Partizan Esports                          | L   | 0.490      | -            | -                | -                | -         |    -4.41 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           73 |     3408 | 2024-11-15 | Mindfreak (Australian team)               | W   | 0.484      | -            | -                | -                | 1 (0.484) |     3.95 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           72 |     3422 | 2024-11-15 | PCIFIC Espor                              | W   | 0.483      | 0.617        | -                | 0.251 (0.075)    | 1 (0.483) |     5.13 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           71 |     3435 | 2024-11-14 | Metizport                                 | L   | 0.479      | -            | -                | -                | -         |    -4.03 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           70 |     3517 | 2024-11-13 | Homyno                                    | W   | 0.471      | 0.617        | -                | 0.189 (0.055)    | 1 (0.471) |     3.95 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           69 |     3520 | 2024-11-13 | Team Norway                               | W   | 0.470      | -            | -                | -                | 1 (0.470) |     2.49 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           68 |     3816 | 2024-11-08 | Rebels Gaming                             | L   | 0.437      | -            | -                | -                | -         |    -9.83 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           67 |     3883 | 2024-11-06 | PCIFIC Espor                              | W   | 0.425      | -            | -                | -                | -         |     4.50 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           66 |     3914 | 2024-11-06 | SINNERS Esports                           | W   | 0.423      | 0.371        | 0.027 (0.004)    | 0.446 (0.070)    | -         |     7.20 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           65 |     3945 | 2024-11-05 | OG                                        | L   | 0.418      | -            | -                | -                | -         |    -6.12 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           64 |     3967 | 2024-11-05 | 9Pandas                                   | L   | 0.417      | -            | -                | -                | -         |    -4.57 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           63 |     4076 | 2024-11-03 | Soul's Heart Esport                       | L   | 0.404      | -            | -                | -                | -         |   -11.33 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           62 |     4098 | 2024-11-03 | Team Sampi                                | W   | 0.403      | -            | -                | -                | -         |     4.49 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           61 |     4146 | 2024-11-02 | Zero Tenacity                             | L   | 0.398      | -            | -                | -                | -         |    -7.25 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           60 |     4165 | 2024-11-02 | Wild Lotus                                | L   | 0.396      | -            | -                | -                | -         |    -8.65 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           59 |     4222 | 2024-11-01 | Sashi Esport                              | L   | 0.390      | -            | -                | -                | -         |    -5.73 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           58 |     4331 | 2024-10-30 | Wild Lotus                                | L   | 0.378      | -            | -                | -                | -         |    -8.40 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           57 |     4388 | 2024-10-29 | Partizan Esports                          | L   | 0.371      | -            | -                | -                | -         |    -3.74 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           56 |     4475 | 2024-10-27 | Illuminar Gaming                          | W   | 0.358      | -            | -                | -                | 1 (0.358) |     4.59 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           55 |     4486 | 2024-10-27 | Passion UA                                | W   | 0.357      | -            | -                | -                | 1 (0.357) |     7.16 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           54 |     4520 | 2024-10-26 | Illuminar Gaming                          | L   | 0.351      | -            | -                | -                | -         |    -6.52 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           53 |     4545 | 2024-10-26 | Ex-ENTERPRISE esports                     | L   | 0.350      | -            | -                | -                | -         |    -8.46 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           52 |     4557 | 2024-10-26 | AgenciUSB                                 | W   | 0.350      | -            | -                | -                | 1 (0.350) |     0.85 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           51 |     4618 | 2024-10-25 | Team Sampi                                | L   | 0.343      | -            | -                | -                | -         |    -7.51 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           50 |     4676 | 2024-10-23 | GODSENT                                   | L   | 0.331      | -            | -                | -                | -         |    -8.76 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           49 |     4686 | 2024-10-23 | Ex-9INE Academy                           | W   | 0.331      | -            | -                | -                | -         |     1.17 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           48 |     4721 | 2024-10-22 | Lausanne-Sport Esports                    | L   | 0.324      | -            | -                | -                | -         |    -9.29 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           47 |     4753 | 2024-10-21 | Haspers Team                              | L   | 0.318      | -            | -                | -                | -         |    -8.16 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           46 |     4855 | 2024-10-19 | Nexus Gaming                              | L   | 0.304      | -            | -                | -                | -         |    -2.88 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           45 |     4962 | 2024-10-17 | Dynamo Eclot                              | W   | 0.290      | 0.384        | 0.128 (0.014)    | 0.692 (0.077)    | -         |     5.65 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           44 |     5018 | 2024-10-16 | The Suspect                               | L   | 0.284      | -            | -                | -                | -         |    -7.25 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           43 |     5104 | 2024-10-14 | GardenGarage                              | W   | 0.272      | -            | -                | -                | -         |     1.80 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           42 |     5174 | 2024-10-12 | MYinsanity                                | W   | 0.262      | -            | -                | -                | 1 (0.262) |     1.18 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           41 |     5192 | 2024-10-12 | Lausanne-Sport Esports                    | W   | 0.259      | -            | -                | -                | 1 (0.259) |     0.71 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           40 |     5199 | 2024-10-12 | Ins (Polish team)                         | W   | 0.258      | -            | -                | -                | -         |     1.33 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           39 |     5200 | 2024-10-12 | Ex-Soul's Heart Esport                    | L   | 0.258      | -            | -                | -                | -         |    -7.13 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           38 |     5229 | 2024-10-12 | Addicted Esports Swiss                    | W   | 0.257      | -            | -                | -                | 1 (0.257) |     0.30 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           37 |     5249 | 2024-10-12 | Team Sampi                                | W   | 0.256      | -            | -                | -                | -         |     2.17 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           36 |     5287 | 2024-10-10 | 500 Rush                                  | W   | 0.245      | -            | -                | -                | -         |     1.09 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           35 |     5292 | 2024-10-10 | Ins (Polish team)                         | W   | 0.245      | -            | -                | -                | -         |     1.19 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           34 |     5300 | 2024-10-10 | GUN5 Esports                              | W   | 0.244      | 0.384        | 0.103 (0.010)    | -                | -         |     3.49 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           33 |     5591 | 2024-10-05 | 500                                       | L   | 0.211      | -            | -                | -                | -         |    -3.22 | bnox, maaryy, Markoś, mASKED, tomiko |
|           32 |     5619 | 2024-10-05 | Passion UA                                | L   | 0.210      | -            | -                | -                | -         |    -2.78 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           31 |     5701 | 2024-10-04 | G2 Ares                                   | L   | 0.202      | -            | -                | -                | -         |    -5.35 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           30 |     5727 | 2024-10-03 | SINNERS Esports                           | W   | 0.198      | 0.435        | 0.027 (0.002)    | -                | -         |     2.48 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           29 |     5737 | 2024-10-03 | ENCE Academy                              | L   | 0.197      | -            | -                | -                | -         |    -4.54 | bnox, maaryy, Markoś, mASKED, tomiko |
|           28 |     5789 | 2024-10-02 | GUN5 Esports                              | L   | 0.190      | -            | -                | -                | -         |    -3.48 | bnox, maaryy, Markoś, mASKED, tomiko |
|           27 |     5803 | 2024-10-02 | Nexus Gaming                              | W   | 0.190      | 0.333        | 0.187 (0.012)    | 0.795 (0.050)    | -         |     4.38 | bnox, maaryy, Markoś, mASKED, tomiko |
|           26 |     5815 | 2024-10-02 | Adventurers                               | L   | 0.189      | -            | -                | -                | -         |    -4.53 | bnox, maaryy, Markoś, mASKED, tomiko |
|           25 |     5867 | 2024-10-01 | Chimera Esports                           | W   | 0.184      | -            | -                | -                | -         |     1.76 | bnox, maaryy, Markoś, mASKED, tomiko |
|           24 |     5890 | 2024-10-01 | Johnny Speeds                             | W   | 0.182      | 0.384        | 0.039 (0.003)    | -                | -         |     2.09 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           23 |     5934 | 2024-09-30 | CYBERSHOKE Esports                        | W   | 0.177      | 0.435        | -                | 1.000 (0.077)    | -         |     1.84 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           22 |     5981 | 2024-09-29 | FAVBET Team                               | L   | 0.170      | -            | -                | -                | -         |    -3.80 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           21 |     5983 | 2024-09-29 | Devils.one                                | L   | 0.170      | -            | -                | -                | -         |    -4.64 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           20 |     6072 | 2024-09-28 | Monte                                     | W   | 0.163      | 0.435        | 0.045 (0.003)    | 0.696 (0.049)    | -         |     2.02 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           19 |     6237 | 2024-09-26 | Tricked Esport                            | L   | 0.149      | -            | -                | -                | -         |    -3.35 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           18 |     6308 | 2024-09-25 | TALON                                     | W   | 0.144      | -            | -                | -                | -         |     0.36 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           17 |     6342 | 2024-09-25 | KONO.ECF                                  | W   | 0.142      | 0.371        | 0.046 (0.002)    | -                | -         |     1.76 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           16 |     6378 | 2024-09-24 | Kubix Esports                             | L   | 0.138      | -            | -                | -                | -         |    -2.55 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           15 |     6393 | 2024-09-24 | Dark Cloud Esports                        | W   | 0.138      | -            | -                | -                | -         |     1.26 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           14 |     6427 | 2024-09-24 | AMKAL ESPORTS                             | L   | 0.136      | -            | -                | -                | -         |    -3.34 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           13 |     6459 | 2024-09-23 | Ex-ENTERPRISE esports                     | L   | 0.132      | -            | -                | -                | -         |    -3.44 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           12 |     6474 | 2024-09-23 | GardenGarage                              | W   | 0.132      | -            | -                | -                | -         |     0.83 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           11 |     6570 | 2024-09-21 | U Neptuna                                 | W   | 0.119      | -            | -                | -                | -         |     0.13 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           10 |     6596 | 2024-09-21 | ECSTATIC                                  | L   | 0.117      | -            | -                | -                | -         |    -2.45 | bnox, maaryy, Markoś, mASKED, tomiko |
|            9 |     6612 | 2024-09-21 | TSM                                       | L   | 0.115      | -            | -                | -                | -         |    -2.94 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|            8 |     6664 | 2024-09-20 | Insilio                                   | L   | 0.109      | -            | -                | -                | -         |    -2.93 | bnox, maaryy, Markoś, mASKED, tomiko |
|            7 |     6780 | 2024-09-18 | CYBERSHOKE Esports                        | L   | 0.097      | -            | -                | -                | -         |    -2.72 | bnox, maaryy, Markoś, mASKED, tomiko |
|            6 |     6906 | 2024-09-16 | 9Pandas                                   | W   | 0.084      | 0.435        | 0.085 (0.003)    | -                | -         |     1.21 | bnox, maaryy, Markoś, mASKED, tomiko |
|            5 |     6960 | 2024-09-15 | Partizan Esports                          | W   | 0.076      | 0.384        | 0.083 (0.002)    | -                | -         |     1.49 | bnox, maaryy, Markoś, mASKED, tomiko |
|            4 |     7371 | 2024-09-08 | Team Spirit Academy                       | L   | 0.030      | -            | -                | -                | -         |    -0.58 | bnox, DGL, maaryy, mASKED, tomiko    |
|            3 |     7485 | 2024-09-07 | Copenhagen Wolves (American organization) | L   | 0.023      | -            | -                | -                | -         |    -0.67 | bnox, DGL, maaryy, mASKED, tomiko    |
|            2 |     7545 | 2024-09-06 | Team Space                                | W   | 0.016      | -            | -                | -                | -         |     0.03 | bnox, maaryy, Markoś, mASKED, tomiko |
|            1 |     7587 | 2024-09-05 | Nemiga Gaming                             | L   | 0.012      | -            | -                | -                | -         |    -0.18 | bnox, fr3nd, maaryy, mASKED, tomiko  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,572.28)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $1,000.00      | $783.47         |
| 2024-11-17 |      0.498 | $12,500.00     | $6,225.69       |
| 2024-10-27 |      0.358 | $4,979.65      | $1,782.30       |
| 2024-10-26 |      0.351 | $248.98        | $87.47          |
| 2024-10-12 |      0.262 | $2,916.41      | $763.53         |
| 2024-10-06 |      0.218 | $2,000.00      | $436.53         |
| 2024-10-03 |      0.197 | $2,500.00      | $493.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
