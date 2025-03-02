### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: AcilioN, Beccie, Griller, Patti, Viggo<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  768.5<br />
<br />
Final Rank Value (768.5) = Starting Rank Value (812.1) + Head To Head Adjustments (-43.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.1
- 400 + ( ( 0.206 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 812.1


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
|           99 |       84 | 2025-02-23 | ARCRED                                    | L   | 1.000      | -            | -                | -                | -         |   -14.32 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           98 |       90 | 2025-02-23 | GardenGarage                              | W   | 1.000      | 0.143        | -                | 0.413 (0.059)    | 0 (0.000) |    14.85 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           97 |       97 | 2025-02-23 | AMKAL ESPORTS                             | W   | 1.000      | 0.143        | -                | 0.681 (0.097)    | 0 (0.000) |    16.20 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           96 |      131 | 2025-02-22 | Diamant Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.64 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           95 |      413 | 2025-02-15 | RUBY                                      | L   | 1.000      | -            | -                | -                | -         |   -16.81 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           94 |      458 | 2025-02-14 | AMKAL ESPORTS                             | W   | 1.000      | 0.143        | -                | 0.681 (0.097)    | 0 (0.000) |    17.08 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           93 |      769 | 2025-02-07 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -14.86 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           92 |      963 | 2025-02-04 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -21.26 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           91 |      978 | 2025-02-04 | 777 Esports                               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.15 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           90 |      987 | 2025-02-04 | Astralis Talent                           | W   | 1.000      | 0.143        | -                | 0.733 (0.105)    | 0 (0.000) |    15.41 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           89 |     1236 | 2024-12-30 | SemperFi Esports                          | W   | 0.794      | 0.284        | -                | 0.665 (0.150)    | 0 (0.000) |     6.51 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           88 |     1237 | 2024-12-30 | 777 Esports                               | W   | 0.793      | -            | -                | -                | 0 (0.000) |     8.81 | AcilioN, Beccie, Griller, Patti, Viggo     |
|           87 |     1287 | 2024-12-28 | Dark Cloud Esports                        | L   | 0.780      | -            | -                | -                | -         |    -8.62 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           86 |     1298 | 2024-12-28 | Copenhagen Wolves (American organization) | L   | 0.779      | -            | -                | -                | -         |    -7.96 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           85 |     1333 | 2024-12-27 | Dragon Esports Club                       | W   | 0.771      | 0.333        | 0.007 (0.002)    | 0.312 (0.080)    | -         |     9.95 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           84 |     1397 | 2024-12-22 | Doge Soldiers                             | W   | 0.739      | -            | -                | -                | -         |     4.94 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           83 |     1414 | 2024-12-22 | NEVERMORE (Ukrainian team)                | W   | 0.738      | 0.303        | 0.010 (0.002)    | 0.911 (0.204)    | -         |    13.28 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           82 |     1518 | 2024-12-20 | Astralis Talent                           | L   | 0.725      | -            | -                | -                | -         |   -10.33 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           81 |     1541 | 2024-12-19 | ADEPTS                                    | L   | 0.718      | -            | -                | -                | -         |   -13.78 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           80 |     1546 | 2024-12-19 | KONO.ECF                                  | L   | 0.718      | -            | -                | -                | -         |    -8.00 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           79 |     1980 | 2024-12-08 | RUSH B (Russian team)                     | L   | 0.647      | -            | -                | -                | -         |    -6.82 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           78 |     1984 | 2024-12-08 | EYEBALLERS                                | W   | 0.647      | 0.143        | 0.019 (0.002)    | -                | -         |    10.47 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           77 |     2321 | 2024-12-02 | Monte                                     | L   | 0.607      | -            | -                | -                | -         |    -5.84 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           76 |     2668 | 2024-11-27 | ADEPTS                                    | W   | 0.573      | 0.333        | -                | 0.292 (0.056)    | -         |     7.37 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           75 |     2679 | 2024-11-27 | GenOne                                    | L   | 0.572      | -            | -                | -                | -         |    -7.37 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           74 |     2726 | 2024-11-26 | GODSENT                                   | W   | 0.566      | -            | -                | -                | -         |     7.17 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           73 |     2762 | 2024-11-25 | KONO.ECF                                  | L   | 0.557      | -            | -                | -                | -         |    -6.42 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           72 |     2988 | 2024-11-22 | 777 Esports                               | W   | 0.538      | -            | -                | -                | -         |     6.34 | AcilioN, Beccie, Equip, Griller, Viggo     |
|           71 |     3057 | 2024-11-21 | Leo Team                                  | W   | 0.531      | 0.333        | 0.026 (0.005)    | 0.758 (0.134)    | -         |    11.16 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           70 |     3167 | 2024-11-19 | ADEPTS                                    | W   | 0.517      | -            | -                | -                | -         |     6.67 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           69 |     3411 | 2024-11-15 | BC.Game Esports                           | L   | 0.491      | -            | -                | -                | -         |    -5.46 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           68 |     3454 | 2024-11-14 | FLuffy Gangsters                          | L   | 0.486      | -            | -                | -                | -         |    -6.98 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           67 |     3584 | 2024-11-11 | Denial (Danish team)                      | L   | 0.467      | -            | -                | -                | -         |    -9.42 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           66 |     3594 | 2024-11-11 | Astralis Talent                           | L   | 0.467      | -            | -                | -                | -         |    -7.18 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           65 |     3606 | 2024-11-11 | XI Esport                                 | L   | 0.466      | -            | -                | -                | -         |    -9.32 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           64 |     3932 | 2024-11-05 | WOPA Esport                               | L   | 0.427      | -            | -                | -                | -         |    -5.42 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           63 |     3975 | 2024-11-04 | Copenhagen Wolves Academy                 | W   | 0.421      | -            | -                | -                | -         |     1.30 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           62 |     4003 | 2024-11-04 | Adventurers                               | L   | 0.419      | -            | -                | -                | -         |    -5.96 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           61 |     4016 | 2024-11-04 | Verdant                                   | L   | 0.418      | -            | -                | -                | -         |   -10.97 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           60 |     4033 | 2024-11-03 | KONO.ECF                                  | W   | 0.414      | 0.333        | 0.045 (0.006)    | 0.757 (0.104)    | -         |     8.55 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           59 |     4113 | 2024-11-02 | MASONIC                                   | W   | 0.407      | -            | -                | -                | 1 (0.407) |     4.19 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           58 |     4133 | 2024-11-02 | Natus Vincere Youth                       | W   | 0.406      | -            | -                | -                | -         |     2.07 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           57 |     4143 | 2024-11-02 | KILLBOX                                   | W   | 0.405      | -            | -                | -                | 1 (0.405) |     1.77 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           56 |     4247 | 2024-10-31 | GODSENT                                   | L   | 0.393      | -            | -                | -                | -         |    -8.06 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           55 |     4265 | 2024-10-31 | Illuminar Gaming                          | L   | 0.391      | -            | -                | -                | -         |    -5.24 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           54 |     4324 | 2024-10-30 | ZOTIX                                     | W   | 0.385      | -            | -                | -                | -         |     3.44 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           53 |     4419 | 2024-10-28 | XI Esport                                 | W   | 0.374      | -            | -                | -                | -         |     2.21 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           52 |     4431 | 2024-10-28 | MASONIC                                   | W   | 0.373      | -            | -                | -                | -         |     3.78 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           51 |     4683 | 2024-10-23 | ALTERNATE aTTaX                           | L   | 0.337      | -            | -                | -                | -         |    -3.58 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           50 |     4786 | 2024-10-20 | ARCRED                                    | L   | 0.319      | -            | -                | -                | -         |    -5.76 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           49 |     5468 | 2024-10-07 | XI Esport                                 | W   | 0.233      | -            | -                | -                | -         |     1.23 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           48 |     5472 | 2024-10-07 | WOPA Esport                               | L   | 0.233      | -            | -                | -                | -         |    -3.23 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           47 |     5482 | 2024-10-07 | Copenhagen Wolves Academy                 | W   | 0.233      | -            | -                | -                | -         |     0.70 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           46 |     5493 | 2024-10-07 | Johnny Speeds                             | L   | 0.231      | -            | -                | -                | -         |    -2.56 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           45 |     5627 | 2024-10-05 | Heimo Esports                             | L   | 0.217      | -            | -                | -                | -         |    -3.92 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           44 |     5688 | 2024-10-04 | UNiTY esports                             | L   | 0.210      | -            | -                | -                | -         |    -2.90 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           43 |     5728 | 2024-10-03 | GUN5 Esports                              | L   | 0.204      | -            | -                | -                | -         |    -2.14 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           42 |     5844 | 2024-10-01 | Iberian Soul                              | L   | 0.193      | -            | -                | -                | -         |    -2.83 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           41 |     5852 | 2024-10-01 | XI Esport                                 | W   | 0.192      | -            | -                | -                | -         |     1.98 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           40 |     5880 | 2024-10-01 | Natus Vincere Junior                      | W   | 0.190      | 0.333        | 0.091 (0.006)    | -                | -         |     4.26 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           39 |     5909 | 2024-09-30 | Astralis Talent                           | W   | 0.186      | -            | -                | -                | -         |     2.70 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           38 |     5917 | 2024-09-30 | LOADING (French team)                     | L   | 0.186      | -            | -                | -                | -         |    -4.90 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           37 |     5937 | 2024-09-30 | Ex-9INE Academy                           | W   | 0.184      | -            | -                | -                | -         |     1.37 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           36 |     5953 | 2024-09-29 | RUBY                                      | L   | 0.180      | -            | -                | -                | -         |    -3.55 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           35 |     5961 | 2024-09-29 | ALASKA                                    | W   | 0.179      | 0.333        | 0.030 (0.002)    | -                | -         |     4.88 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           34 |     6044 | 2024-09-28 | GODSENT                                   | L   | 0.172      | -            | -                | -                | -         |    -3.74 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           33 |     6089 | 2024-09-27 | Fire Flux Esports                         | L   | 0.168      | -            | -                | -                | -         |    -2.31 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           32 |     6098 | 2024-09-27 | Asian fetish                              | W   | 0.167      | -            | -                | -                | -         |     1.22 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           31 |     6105 | 2024-09-27 | REDPack Esports                           | W   | 0.167      | -            | -                | -                | -         |     1.42 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           30 |     6204 | 2024-09-26 | Partizan Esports                          | L   | 0.159      | -            | -                | -                | -         |    -0.88 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           29 |     6216 | 2024-09-26 | RUBY                                      | W   | 0.158      | -            | -                | -                | -         |     1.79 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           28 |     6223 | 2024-09-26 | GameAgents                                | W   | 0.158      | -            | -                | -                | -         |     1.71 | AcilioN, Beccie, BøghmagiC, Equip, Griller |
|           27 |     6414 | 2024-09-24 | Alliance                                  | W   | 0.144      | 0.333        | 0.015 (0.001)    | -                | -         |     2.85 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           26 |     6445 | 2024-09-23 | Denial (Danish team)                      | L   | 0.140      | -            | -                | -                | -         |    -3.15 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           25 |     6471 | 2024-09-23 | Viperio                                   | W   | 0.139      | -            | -                | -                | -         |     1.89 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           24 |     6491 | 2024-09-23 | ADEPTS                                    | L   | 0.137      | -            | -                | -                | -         |    -2.91 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           23 |     6513 | 2024-09-22 | FLuffy Gangsters                          | W   | 0.132      | 0.333        | 0.014 (0.001)    | -                | -         |     2.01 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           22 |     6528 | 2024-09-22 | Heimo Esports                             | L   | 0.131      | -            | -                | -                | -         |    -2.42 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           21 |     6537 | 2024-09-22 | Illuminar Gaming                          | L   | 0.130      | -            | -                | -                | -         |    -1.75 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           20 |     6564 | 2024-09-21 | LOADING (French team)                     | W   | 0.127      | -            | -                | -                | -         |     0.64 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           19 |     6597 | 2024-09-21 | ALASKA                                    | W   | 0.124      | 0.333        | 0.030 (0.001)    | -                | -         |     3.43 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           18 |     6621 | 2024-09-20 | ADEPTS                                    | W   | 0.120      | -            | -                | -                | -         |     1.24 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           17 |     6645 | 2024-09-20 | GenOne                                    | L   | 0.118      | -            | -                | -                | -         |    -1.71 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           16 |     6708 | 2024-09-19 | Natus Vincere Youth                       | W   | 0.111      | -            | -                | -                | -         |     0.51 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           15 |     6775 | 2024-09-18 | 9INE                                      | L   | 0.104      | -            | -                | -                | -         |    -1.86 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           14 |     6857 | 2024-09-17 | ROYALS                                    | L   | 0.097      | -            | -                | -                | -         |    -2.05 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           13 |     6890 | 2024-09-16 | MASONIC                                   | W   | 0.092      | -            | -                | -                | -         |     0.89 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           12 |     7107 | 2024-09-13 | KONO.ECF                                  | L   | 0.070      | -            | -                | -                | -         |    -0.78 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           11 |     7204 | 2024-09-11 | Leo Team                                  | L   | 0.058      | -            | -                | -                | -         |    -0.85 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|           10 |     7266 | 2024-09-10 | Viperio                                   | W   | 0.050      | -            | -                | -                | -         |     0.68 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            9 |     7306 | 2024-09-09 | Underrated                                | L   | 0.045      | -            | -                | -                | -         |    -0.94 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            8 |     7314 | 2024-09-09 | GameAgents                                | L   | 0.044      | -            | -                | -                | -         |    -0.94 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            7 |     7336 | 2024-09-08 | Betera Esports                            | W   | 0.040      | -            | -                | -                | -         |     0.50 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            6 |     7439 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.032      | -            | -                | -                | -         |    -0.31 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            5 |     7484 | 2024-09-07 | Ex-ENTERPRISE esports                     | L   | 0.030      | -            | -                | -                | -         |    -0.59 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            4 |     7515 | 2024-09-06 | G2 Ares                                   | W   | 0.026      | -            | -                | -                | -         |     0.27 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            3 |     7590 | 2024-09-05 | Revenant Esports                          | W   | 0.019      | -            | -                | -                | -         |     0.09 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            2 |     7683 | 2024-09-04 | ENCE Academy                              | L   | 0.011      | -            | -                | -                | -         |    -0.17 | AcilioN, Beccie, Equip, Griller, JBOEN     |
|            1 |     7759 | 2024-09-03 | Viperio                                   | W   | 0.004      | -            | -                | -                | -         |     0.05 | AcilioN, Beccie, Equip, Griller, JBOEN     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,004.58)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.794 | $2,000.00      | $1,587.27       |
| 2024-12-28 |      0.780 | $500.00        | $389.83         |
| 2024-11-14 |      0.487 | $1,000.00      | $486.81         |
| 2024-11-05 |      0.426 | $1,000.00      | $426.11         |
| 2024-11-02 |      0.407 | $1,415.01      | $576.03         |
| 2024-09-29 |      0.180 | $3,000.00      | $538.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
