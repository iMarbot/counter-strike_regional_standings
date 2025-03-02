### Roster Details<br />
Team Name: Los kogutos<br />
Roster: maaryy, mASKED, Melavi, tein, tomiko<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.0<br />
<br />
Final Rank Value (837.0) = Starting Rank Value (1014.2) + Head To Head Adjustments (-177.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.447[<sup>2</sup>](#table1)

The average of these factors is 0.307<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1014.2
- 400 + ( ( 0.307 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1014.2


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
|           87 |     1212 | 2025-01-08 | EYEBALLERS                                | L   | 0.853      | -            | -                | -                | -         |   -15.44 | maaryy, mASKED, Melavi, tein, tomiko |
|           86 |     1214 | 2025-01-07 | Insilio                                   | L   | 0.847      | -            | -                | -                | -         |   -18.33 | maaryy, mASKED, Melavi, tein, tomiko |
|           85 |     1221 | 2025-01-05 | BadGuys                                   | W   | 0.832      | 0.417        | -                | 0.281 (0.098)    | -         |     6.26 | maaryy, mASKED, Melavi, tein, tomiko |
|           84 |     1226 | 2025-01-03 | FLuffy Gangsters                          | L   | 0.820      | -            | -                | -                | -         |   -13.49 | maaryy, mASKED, Melavi, tein, tomiko |
|           83 |     1261 | 2024-12-29 | KONO.ECF                                  | L   | 0.785      | -            | -                | -                | -         |   -10.18 | kRaSnaL, maaryy, mASKED, mhL, tomiko |
|           82 |     1306 | 2024-12-28 | VOLT (European team)                      | W   | 0.778      | -            | -                | -                | -         |     6.94 | kRaSnaL, maaryy, mASKED, mhL, tomiko |
|           81 |     2866 | 2024-11-23 | HyperSpirit                               | L   | 0.546      | -            | -                | -                | -         |   -13.60 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           80 |     2969 | 2024-11-22 | ROUNDS                                    | L   | 0.539      | -            | -                | -                | -         |   -15.44 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           79 |     3038 | 2024-11-21 | 1win                                      | W   | 0.532      | 0.372        | -                | 0.329 (0.065)    | -         |     5.15 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           78 |     3105 | 2024-11-20 | Ex-Soul's Heart Esport                    | W   | 0.527      | -            | -                | -                | -         |     2.80 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           77 |     3115 | 2024-11-20 | TEAM NEXT LEVEL                           | W   | 0.526      | 0.372        | -                | 0.465 (0.091)    | -         |     3.77 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           76 |     3331 | 2024-11-16 | Partizan Esports                          | L   | 0.499      | -            | -                | -                | -         |    -4.47 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           75 |     3396 | 2024-11-15 | Mindfreak (Australian team)               | W   | 0.492      | -            | -                | -                | 1 (0.492) |     4.02 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           74 |     3410 | 2024-11-15 | PCIFIC Espor                              | W   | 0.491      | 0.617        | -                | 0.254 (0.077)    | 1 (0.491) |     5.22 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           73 |     3423 | 2024-11-14 | Metizport                                 | L   | 0.487      | -            | -                | -                | -         |    -4.06 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           72 |     3505 | 2024-11-13 | Homyno                                    | W   | 0.479      | 0.617        | -                | 0.192 (0.057)    | 1 (0.479) |     3.99 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           71 |     3508 | 2024-11-13 | Team Norway                               | W   | 0.479      | -            | -                | -                | 1 (0.479) |     2.54 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           70 |     3804 | 2024-11-08 | Rebels Gaming                             | L   | 0.445      | -            | -                | -                | -         |    -9.99 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           69 |     3871 | 2024-11-06 | PCIFIC Espor                              | W   | 0.434      | -            | -                | -                | -         |     4.59 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           68 |     3902 | 2024-11-06 | SINNERS Esports                           | W   | 0.431      | 0.371        | 0.027 (0.004)    | 0.451 (0.072)    | -         |     7.37 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           67 |     3933 | 2024-11-05 | OG                                        | L   | 0.427      | -            | -                | -                | -         |    -6.23 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           66 |     3955 | 2024-11-05 | 9Pandas                                   | L   | 0.425      | -            | -                | -                | -         |    -4.63 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           65 |     4064 | 2024-11-03 | Soul's Heart Esport                       | L   | 0.412      | -            | -                | -                | -         |   -11.56 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           64 |     4086 | 2024-11-03 | Team Sampi                                | W   | 0.411      | -            | -                | -                | -         |     4.62 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           63 |     4134 | 2024-11-02 | Zero Tenacity                             | L   | 0.406      | -            | -                | -                | -         |    -7.38 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           62 |     4153 | 2024-11-02 | Wild Lotus                                | L   | 0.405      | -            | -                | -                | -         |    -8.79 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           61 |     4210 | 2024-11-01 | Sashi Esport                              | L   | 0.398      | -            | -                | -                | -         |    -5.85 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           60 |     4319 | 2024-10-30 | Wild Lotus                                | L   | 0.386      | -            | -                | -                | -         |    -8.56 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           59 |     4376 | 2024-10-29 | Partizan Esports                          | L   | 0.379      | -            | -                | -                | -         |    -3.82 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           58 |     4463 | 2024-10-27 | Illuminar Gaming                          | W   | 0.366      | -            | -                | -                | 1 (0.366) |     4.71 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           57 |     4474 | 2024-10-27 | Passion UA                                | W   | 0.365      | -            | -                | -                | 1 (0.365) |     7.33 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           56 |     4508 | 2024-10-26 | Illuminar Gaming                          | L   | 0.359      | -            | -                | -                | -         |    -6.65 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           55 |     4533 | 2024-10-26 | Ex-ENTERPRISE esports                     | L   | 0.358      | -            | -                | -                | -         |    -8.66 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           54 |     4545 | 2024-10-26 | AgenciUSB                                 | W   | 0.358      | -            | -                | -                | 1 (0.358) |     0.86 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           53 |     4606 | 2024-10-25 | Team Sampi                                | L   | 0.351      | -            | -                | -                | -         |    -7.68 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           52 |     4664 | 2024-10-23 | GODSENT                                   | L   | 0.339      | -            | -                | -                | -         |    -8.98 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           51 |     4674 | 2024-10-23 | Ex-9INE Academy                           | W   | 0.339      | -            | -                | -                | -         |     1.20 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           50 |     4709 | 2024-10-22 | Lausanne-Sport Esports                    | L   | 0.332      | -            | -                | -                | -         |    -9.53 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           49 |     4741 | 2024-10-21 | Haspers Team                              | L   | 0.326      | -            | -                | -                | -         |    -8.39 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           48 |     4843 | 2024-10-19 | Nexus Gaming                              | L   | 0.312      | -            | -                | -                | -         |    -2.98 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           47 |     4950 | 2024-10-17 | Dynamo Eclot                              | W   | 0.298      | 0.384        | 0.127 (0.015)    | 0.703 (0.080)    | -         |     5.80 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           46 |     5006 | 2024-10-16 | The Suspect                               | L   | 0.292      | -            | -                | -                | -         |    -7.48 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           45 |     5092 | 2024-10-14 | GardenGarage                              | W   | 0.280      | -            | -                | -                | -         |     1.84 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           44 |     5162 | 2024-10-12 | MYinsanity                                | W   | 0.270      | -            | -                | -                | 1 (0.270) |     1.20 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           43 |     5180 | 2024-10-12 | Lausanne-Sport Esports                    | W   | 0.267      | -            | -                | -                | 1 (0.267) |     0.73 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           42 |     5187 | 2024-10-12 | Ins (Polish team)                         | W   | 0.267      | -            | -                | -                | -         |     1.36 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           41 |     5188 | 2024-10-12 | Ex-Soul's Heart Esport                    | L   | 0.266      | -            | -                | -                | -         |    -7.36 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           40 |     5217 | 2024-10-12 | Addicted Esports Swiss                    | W   | 0.265      | -            | -                | -                | 1 (0.265) |     0.31 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           39 |     5237 | 2024-10-12 | Team Sampi                                | W   | 0.264      | -            | -                | -                | -         |     2.25 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           38 |     5275 | 2024-10-10 | 500 Rush                                  | W   | 0.253      | -            | -                | -                | -         |     1.11 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           37 |     5280 | 2024-10-10 | Ins (Polish team)                         | W   | 0.253      | -            | -                | -                | -         |     1.21 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           36 |     5288 | 2024-10-10 | GUN5 Esports                              | W   | 0.252      | 0.384        | 0.102 (0.010)    | -                | -         |     3.60 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           35 |     5579 | 2024-10-05 | 500                                       | L   | 0.219      | -            | -                | -                | -         |    -3.38 | bnox, maaryy, Markoś, mASKED, tomiko |
|           34 |     5607 | 2024-10-05 | Passion UA                                | L   | 0.218      | -            | -                | -                | -         |    -2.90 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           33 |     5689 | 2024-10-04 | G2 Ares                                   | L   | 0.210      | -            | -                | -                | -         |    -5.58 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           32 |     5715 | 2024-10-03 | SINNERS Esports                           | W   | 0.207      | 0.435        | 0.027 (0.002)    | -                | -         |     2.58 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           31 |     5725 | 2024-10-03 | ENCE Academy                              | L   | 0.205      | -            | -                | -                | -         |    -4.75 | bnox, maaryy, Markoś, mASKED, tomiko |
|           30 |     5777 | 2024-10-02 | GUN5 Esports                              | L   | 0.199      | -            | -                | -                | -         |    -3.65 | bnox, maaryy, Markoś, mASKED, tomiko |
|           29 |     5791 | 2024-10-02 | Nexus Gaming                              | W   | 0.198      | 0.333        | 0.186 (0.012)    | 0.808 (0.053)    | -         |     4.55 | bnox, maaryy, Markoś, mASKED, tomiko |
|           28 |     5803 | 2024-10-02 | Adventurers                               | L   | 0.197      | -            | -                | -                | -         |    -4.74 | bnox, maaryy, Markoś, mASKED, tomiko |
|           27 |     5855 | 2024-10-01 | Chimera Esports                           | W   | 0.192      | -            | -                | -                | -         |     1.83 | bnox, maaryy, Markoś, mASKED, tomiko |
|           26 |     5878 | 2024-10-01 | Johnny Speeds                             | W   | 0.190      | 0.384        | 0.039 (0.003)    | -                | -         |     2.18 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           25 |     5922 | 2024-09-30 | CYBERSHOKE Esports                        | W   | 0.185      | 0.435        | -                | 1.000 (0.080)    | -         |     1.91 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           24 |     5969 | 2024-09-29 | FAVBET Team                               | L   | 0.178      | -            | -                | -                | -         |    -4.00 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           23 |     5971 | 2024-09-29 | Devils.one                                | L   | 0.178      | -            | -                | -                | -         |    -4.87 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           22 |     6060 | 2024-09-28 | Monte                                     | W   | 0.172      | 0.435        | 0.045 (0.003)    | 0.704 (0.052)    | -         |     2.11 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           21 |     6225 | 2024-09-26 | Tricked Esport                            | L   | 0.158      | -            | -                | -                | -         |    -3.55 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           20 |     6296 | 2024-09-25 | TALON                                     | W   | 0.152      | -            | -                | -                | -         |     0.38 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           19 |     6330 | 2024-09-25 | KONO.ECF                                  | W   | 0.150      | 0.371        | 0.045 (0.003)    | -                | -         |     1.85 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           18 |     6366 | 2024-09-24 | Kubix Esports                             | L   | 0.146      | -            | -                | -                | -         |    -2.71 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           17 |     6381 | 2024-09-24 | Dark Cloud Esports                        | W   | 0.146      | -            | -                | -                | -         |     1.31 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           16 |     6415 | 2024-09-24 | AMKAL ESPORTS                             | L   | 0.144      | -            | -                | -                | -         |    -3.55 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           15 |     6446 | 2024-09-23 | Ex-ENTERPRISE esports                     | L   | 0.140      | -            | -                | -                | -         |    -3.66 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           14 |     6461 | 2024-09-23 | GardenGarage                              | W   | 0.140      | -            | -                | -                | -         |     0.87 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           13 |     6558 | 2024-09-21 | U Neptuna                                 | W   | 0.127      | -            | -                | -                | -         |     0.13 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           12 |     6584 | 2024-09-21 | ECSTATIC                                  | L   | 0.125      | -            | -                | -                | -         |    -2.64 | bnox, maaryy, Markoś, mASKED, tomiko |
|           11 |     6600 | 2024-09-21 | TSM                                       | L   | 0.124      | -            | -                | -                | -         |    -3.16 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|           10 |     6652 | 2024-09-20 | Insilio                                   | L   | 0.117      | -            | -                | -                | -         |    -3.15 | bnox, maaryy, Markoś, mASKED, tomiko |
|            9 |     6768 | 2024-09-18 | CYBERSHOKE Esports                        | L   | 0.105      | -            | -                | -                | -         |    -2.95 | bnox, maaryy, Markoś, mASKED, tomiko |
|            8 |     6894 | 2024-09-16 | 9Pandas                                   | W   | 0.092      | 0.435        | 0.085 (0.003)    | -                | -         |     1.31 | bnox, maaryy, Markoś, mASKED, tomiko |
|            7 |     6948 | 2024-09-15 | Partizan Esports                          | W   | 0.084      | 0.384        | 0.082 (0.003)    | -                | -         |     1.64 | bnox, maaryy, Markoś, mASKED, tomiko |
|            6 |     7359 | 2024-09-08 | Team Spirit Academy                       | L   | 0.038      | -            | -                | -                | -         |    -0.75 | bnox, DGL, maaryy, mASKED, tomiko    |
|            5 |     7473 | 2024-09-07 | Copenhagen Wolves (American organization) | L   | 0.031      | -            | -                | -                | -         |    -0.91 | bnox, DGL, maaryy, mASKED, tomiko    |
|            4 |     7533 | 2024-09-06 | Team Space                                | W   | 0.024      | -            | -                | -                | -         |     0.04 | bnox, maaryy, Markoś, mASKED, tomiko |
|            3 |     7575 | 2024-09-05 | Nemiga Gaming                             | L   | 0.020      | -            | -                | -                | -         |    -0.31 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|            2 |     7745 | 2024-09-03 | Team Space                                | W   | 0.005      | -            | -                | -                | -         |     0.01 | bnox, fr3nd, maaryy, mASKED, tomiko  |
|            1 |     7758 | 2024-09-03 | Team Spirit Academy                       | W   | 0.004      | -            | -                | -                | -         |     0.04 | bnox, DGL, maaryy, mASKED, tomiko    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,786.53)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.792 | $1,000.00      | $791.67         |
| 2024-11-17 |      0.506 | $12,500.00     | $6,328.13       |
| 2024-10-27 |      0.366 | $4,979.65      | $1,823.10       |
| 2024-10-26 |      0.360 | $248.98        | $89.51          |
| 2024-10-12 |      0.270 | $2,916.41      | $787.43         |
| 2024-10-06 |      0.226 | $2,000.00      | $452.92         |
| 2024-10-03 |      0.206 | $2,500.00      | $513.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
