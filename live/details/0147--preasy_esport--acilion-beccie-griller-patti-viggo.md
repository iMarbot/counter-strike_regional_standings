### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: AcilioN, Beccie, Griller, Patti, Viggo<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
<br />
Final Rank Value:  765.6<br />
<br />
Final Rank Value (765.6) = Starting Rank Value (810.5) + Head To Head Adjustments (-44.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.093[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 810.5
- 400 + ( ( 0.205 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 810.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           98 |       99 | 2025-02-23 | ARCRED                                    | L   | 1.000      | -            | -                | -                | -         |   -14.25 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           97 |      105 | 2025-02-23 | GardenGarage                              | W   | 1.000      | 0.143        | -                | 0.408 (0.058)    | 0 (0.000) |    14.97 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           96 |      112 | 2025-02-23 | AMKAL ESPORTS                             | W   | 1.000      | 0.143        | -                | 0.674 (0.096)    | 0 (0.000) |    16.24 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           95 |      146 | 2025-02-22 | Diamant Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.70 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           94 |      425 | 2025-02-15 | RUBY                                      | L   | 1.000      | -            | -                | -                | -         |   -16.81 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           93 |      470 | 2025-02-14 | AMKAL ESPORTS                             | W   | 1.000      | 0.143        | -                | 0.674 (0.096)    | 0 (0.000) |    17.11 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           92 |      781 | 2025-02-07 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -14.72 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           91 |      975 | 2025-02-04 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -21.15 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           90 |      990 | 2025-02-04 | 777 Esports                               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           89 |      999 | 2025-02-04 | Astralis Talent                           | W   | 1.000      | 0.143        | -                | 0.724 (0.103)    | 0 (0.000) |    15.46 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           88 |     1248 | 2024-12-30 | SemperFi Esports                          | W   | 0.785      | 0.284        | -                | 0.666 (0.148)    | 0 (0.000) |     6.52 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           87 |     1249 | 2024-12-30 | 777 Esports                               | W   | 0.785      | -            | -                | -                | 0 (0.000) |     8.77 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           86 |     1299 | 2024-12-28 | Dark Cloud Esports                        | L   | 0.772      | -            | -                | -                | -         |    -8.47 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           85 |     1310 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.771      | -            | -                | -                | -         |    -7.81 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           84 |     1345 | 2024-12-27 | Dragon Esports Club                       | W   | 0.763      | 0.333        | 0.007 (0.002)    | 0.309 (0.079)    | -         |     9.96 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           83 |     1409 | 2024-12-22 | Doge Soldiers                             | W   | 0.731      | -            | -                | -                | -         |     4.97 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           82 |     1426 | 2024-12-22 | NEVERMORE (Ukrainian team)                | W   | 0.730      | 0.303        | 0.010 (0.002)    | 0.904 (0.200)    | -         |    13.24 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           81 |     1530 | 2024-12-20 | Astralis Talent                           | L   | 0.717      | -            | -                | -                | -         |   -10.17 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           80 |     1553 | 2024-12-19 | ADEPTS                                    | L   | 0.710      | -            | -                | -                | -         |   -14.89 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           79 |     1558 | 2024-12-19 | KONO.ECF                                  | L   | 0.709      | -            | -                | -                | -         |    -7.86 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           78 |     1992 | 2024-12-08 | RUSH B (Russian team)                     | L   | 0.639      | -            | -                | -                | -         |    -6.66 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           77 |     1996 | 2024-12-08 | EYEBALLERS                                | W   | 0.639      | 0.143        | 0.019 (0.002)    | -                | -         |    10.42 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           76 |     2333 | 2024-12-02 | Monte                                     | L   | 0.599      | -            | -                | -                | -         |    -5.74 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           75 |     2680 | 2024-11-27 | ADEPTS                                    | W   | 0.565      | 0.333        | -                | 0.287 (0.054)    | -         |     5.93 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           74 |     2691 | 2024-11-27 | GenOne                                    | L   | 0.563      | -            | -                | -                | -         |    -7.26 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           73 |     2738 | 2024-11-26 | GODSENT                                   | W   | 0.558      | -            | -                | -                | -         |     7.04 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           72 |     2774 | 2024-11-25 | KONO.ECF                                  | L   | 0.549      | -            | -                | -                | -         |    -6.32 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           71 |     3000 | 2024-11-22 | 777 Esports                               | W   | 0.530      | -            | -                | -                | -         |     6.26 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           70 |     3069 | 2024-11-21 | Leo Team                                  | W   | 0.523      | 0.333        | 0.026 (0.005)    | 0.748 (0.130)    | -         |    10.98 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           69 |     3179 | 2024-11-19 | ADEPTS                                    | W   | 0.509      | -            | -                | -                | -         |     5.22 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           68 |     3423 | 2024-11-15 | BC.Game Esports                           | L   | 0.483      | -            | -                | -                | -         |    -5.39 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           67 |     3466 | 2024-11-14 | FLuffy Gangsters                          | L   | 0.477      | -            | -                | -                | -         |    -6.89 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           66 |     3596 | 2024-11-11 | Denial (Danish team)                      | L   | 0.459      | -            | -                | -                | -         |    -9.26 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           65 |     3606 | 2024-11-11 | Astralis Talent                           | L   | 0.459      | -            | -                | -                | -         |    -7.08 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           64 |     3618 | 2024-11-11 | XI Esport                                 | L   | 0.458      | -            | -                | -                | -         |    -9.15 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           63 |     3944 | 2024-11-05 | WOPA Esport                               | L   | 0.418      | -            | -                | -                | -         |    -5.32 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           62 |     3987 | 2024-11-04 | Copenhagen Wolves Academy                 | W   | 0.412      | -            | -                | -                | -         |     1.28 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           61 |     4015 | 2024-11-04 | Adventurers                               | L   | 0.411      | -            | -                | -                | -         |    -5.89 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           60 |     4026 | 2024-11-04 | Verdant                                   | L   | 0.410      | -            | -                | -                | -         |   -10.75 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           59 |     4045 | 2024-11-03 | KONO.ECF                                  | W   | 0.406      | 0.333        | 0.046 (0.006)    | 0.747 (0.101)    | -         |     8.36 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           58 |     4125 | 2024-11-02 | MASONIC                                   | W   | 0.399      | -            | -                | -                | 1 (0.399) |     4.12 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           57 |     4145 | 2024-11-02 | Natus Vincere Youth                       | W   | 0.398      | -            | -                | -                | -         |     2.04 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           56 |     4155 | 2024-11-02 | KILLBOX                                   | W   | 0.397      | -            | -                | -                | 1 (0.397) |     1.74 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           55 |     4259 | 2024-10-31 | GODSENT                                   | L   | 0.385      | -            | -                | -                | -         |    -7.90 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           54 |     4277 | 2024-10-31 | Illuminar Gaming                          | L   | 0.383      | -            | -                | -                | -         |    -5.14 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           53 |     4336 | 2024-10-30 | ZOTIX                                     | W   | 0.377      | -            | -                | -                | -         |     3.39 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           52 |     4431 | 2024-10-28 | XI Esport                                 | W   | 0.365      | -            | -                | -                | -         |     2.16 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           51 |     4443 | 2024-10-28 | MASONIC                                   | W   | 0.365      | -            | -                | -                | -         |     3.71 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           50 |     4695 | 2024-10-23 | ALTERNATE aTTaX                           | L   | 0.329      | -            | -                | -                | -         |    -3.50 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           49 |     4798 | 2024-10-20 | ARCRED                                    | L   | 0.311      | -            | -                | -                | -         |    -5.60 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           48 |     5480 | 2024-10-07 | XI Esport                                 | W   | 0.225      | -            | -                | -                | -         |     1.19 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           47 |     5484 | 2024-10-07 | WOPA Esport                               | L   | 0.225      | -            | -                | -                | -         |    -3.12 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           46 |     5494 | 2024-10-07 | Copenhagen Wolves Academy                 | W   | 0.224      | -            | -                | -                | -         |     0.68 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           45 |     5505 | 2024-10-07 | Johnny Speeds                             | L   | 0.223      | -            | -                | -                | -         |    -2.48 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           44 |     5639 | 2024-10-05 | Heimo Esports                             | L   | 0.209      | -            | -                | -                | -         |    -3.77 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           43 |     5700 | 2024-10-04 | UNiTY esports                             | L   | 0.202      | -            | -                | -                | -         |    -2.80 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           42 |     5740 | 2024-10-03 | GUN5 Esports                              | L   | 0.196      | -            | -                | -                | -         |    -2.05 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           41 |     5856 | 2024-10-01 | Iberian Soul                              | L   | 0.185      | -            | -                | -                | -         |    -2.71 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           40 |     5864 | 2024-10-01 | XI Esport                                 | W   | 0.184      | -            | -                | -                | -         |     1.90 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           39 |     5892 | 2024-10-01 | Natus Vincere Junior                      | W   | 0.182      | 0.333        | 0.091 (0.006)    | -                | -         |     4.08 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           38 |     5921 | 2024-09-30 | Astralis Talent                           | W   | 0.178      | -            | -                | -                | -         |     2.58 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           37 |     5929 | 2024-09-30 | LOADING (French team)                     | L   | 0.177      | -            | -                | -                | -         |    -4.68 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           36 |     5949 | 2024-09-30 | Ex-9INE Academy                           | W   | 0.175      | -            | -                | -                | -         |     1.30 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           35 |     5965 | 2024-09-29 | RUBY                                      | L   | 0.171      | -            | -                | -                | -         |    -3.40 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           34 |     5973 | 2024-09-29 | ALASKA                                    | W   | 0.171      | 0.333        | 0.031 (0.002)    | -                | -         |     4.66 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           33 |     6056 | 2024-09-28 | GODSENT                                   | L   | 0.164      | -            | -                | -                | -         |    -3.56 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           32 |     6101 | 2024-09-27 | Fire Flux Esports                         | L   | 0.159      | -            | -                | -                | -         |    -2.19 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           31 |     6110 | 2024-09-27 | Asian fetish                              | W   | 0.159      | -            | -                | -                | -         |     1.17 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           30 |     6117 | 2024-09-27 | REDPack Esports                           | W   | 0.159      | -            | -                | -                | -         |     1.36 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           29 |     6216 | 2024-09-26 | Partizan Esports                          | L   | 0.151      | -            | -                | -                | -         |    -0.84 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           28 |     6228 | 2024-09-26 | RUBY                                      | W   | 0.150      | -            | -                | -                | -         |     1.70 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           27 |     6235 | 2024-09-26 | GameAgents                                | W   | 0.149      | -            | -                | -                | -         |     1.61 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           26 |     6426 | 2024-09-24 | Alliance                                  | W   | 0.136      | 0.333        | 0.015 (0.001)    | -                | -         |     2.69 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           25 |     6457 | 2024-09-23 | Denial (Danish team)                      | L   | 0.132      | -            | -                | -                | -         |    -2.96 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           24 |     6483 | 2024-09-23 | Viperio                                   | W   | 0.131      | -            | -                | -                | -         |     1.78 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           23 |     6503 | 2024-09-23 | ADEPTS                                    | L   | 0.129      | -            | -                | -                | -         |    -3.12 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           22 |     6525 | 2024-09-22 | FLuffy Gangsters                          | W   | 0.124      | 0.333        | 0.014 (0.001)    | -                | -         |     1.88 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           21 |     6540 | 2024-09-22 | Heimo Esports                             | L   | 0.123      | -            | -                | -                | -         |    -2.26 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           20 |     6549 | 2024-09-22 | Illuminar Gaming                          | L   | 0.122      | -            | -                | -                | -         |    -1.65 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           19 |     6576 | 2024-09-21 | LOADING (French team)                     | W   | 0.118      | -            | -                | -                | -         |     0.60 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           18 |     6609 | 2024-09-21 | ALASKA                                    | W   | 0.116      | 0.333        | 0.031 (0.001)    | -                | -         |     3.21 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           17 |     6633 | 2024-09-20 | ADEPTS                                    | W   | 0.112      | -            | -                | -                | -         |     0.81 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           16 |     6657 | 2024-09-20 | GenOne                                    | L   | 0.110      | -            | -                | -                | -         |    -1.60 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           15 |     6720 | 2024-09-19 | Natus Vincere Youth                       | W   | 0.103      | -            | -                | -                | -         |     0.47 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           14 |     6787 | 2024-09-18 | 9INE                                      | L   | 0.096      | -            | -                | -                | -         |    -1.72 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           13 |     6869 | 2024-09-17 | ROYALS                                    | L   | 0.089      | -            | -                | -                | -         |    -1.88 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           12 |     6902 | 2024-09-16 | MASONIC                                   | W   | 0.084      | -            | -                | -                | -         |     0.82 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           11 |     7119 | 2024-09-13 | KONO.ECF                                  | L   | 0.062      | -            | -                | -                | -         |    -0.69 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           10 |     7216 | 2024-09-11 | Leo Team                                  | L   | 0.050      | -            | -                | -                | -         |    -0.73 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            9 |     7278 | 2024-09-10 | Viperio                                   | W   | 0.042      | -            | -                | -                | -         |     0.57 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            8 |     7319 | 2024-09-09 | Underrated                                | L   | 0.037      | -            | -                | -                | -         |    -0.76 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            7 |     7326 | 2024-09-09 | GameAgents                                | L   | 0.036      | -            | -                | -                | -         |    -0.77 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            6 |     7348 | 2024-09-08 | Betera Esports                            | W   | 0.032      | -            | -                | -                | -         |     0.40 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            5 |     7451 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.024      | -            | -                | -                | -         |    -0.23 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            4 |     7496 | 2024-09-07 | Ex-ENTERPRISE esports                     | L   | 0.022      | -            | -                | -                | -         |    -0.43 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            3 |     7527 | 2024-09-06 | G2 Ares                                   | W   | 0.018      | -            | -                | -                | -         |     0.18 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            2 |     7602 | 2024-09-05 | Revenant Esports                          | W   | 0.011      | -            | -                | -                | -         |     0.05 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            1 |     7695 | 2024-09-04 | ENCE Academy                              | L   | 0.003      | -            | -                | -                | -         |    -0.04 | AcilioN, Beccie, Equip, Griller, JBOEN     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,931.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.785 | $2,000.00      | $1,570.88       |
| 2024-12-28 |      0.771 | $500.00        | $385.73         |
| 2024-11-14 |      0.479 | $1,000.00      | $478.61         |
| 2024-11-05 |      0.418 | $1,000.00      | $417.92         |
| 2024-11-02 |      0.399 | $1,415.01      | $564.43         |
| 2024-09-29 |      0.171 | $3,000.00      | $513.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
