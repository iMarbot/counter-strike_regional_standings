### Roster Details<br />
Team Name: Wild Lotus<br />
Roster: birdfromsky, Keoz, REDSTAR, smooya, Vegi<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  789.9<br />
<br />
Final Rank Value (789.9) = Starting Rank Value (740.4) + Head To Head Adjustments (49.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.4
- 400 + ( ( 0.170 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 740.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       41 | 2025-02-25 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -10.28 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           54 |       56 | 2025-02-24 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.49 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           53 |      133 | 2025-02-22 | Alliance                                  | L   | 1.000      | -            | -                | -                | -         |   -13.41 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           52 |      199 | 2025-02-21 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -11.27 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           51 |      210 | 2025-02-21 | GhoulsW                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.79 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           50 |      235 | 2025-02-20 | Nordix Esport                             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.51 | birdfromsky, Keoz, REDSTAR, smooya, Vegi      |
|           49 |     1106 | 2025-01-29 | Copenhagen Wolves (American organization) | W   | 0.993      | 0.143        | -                | 1.000 (0.142)    | 0 (0.000) |    18.39 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           48 |     1115 | 2025-01-28 | Zero Tenacity                             | W   | 0.987      | 0.143        | 0.028 (0.004)    | 0.692 (0.098)    | 0 (0.000) |    18.71 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           47 |     1119 | 2025-01-27 | AMKAL ESPORTS                             | L   | 0.980      | -            | -                | -                | -         |   -13.26 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           46 |     1774 | 2024-12-13 | AMKAL ESPORTS                             | L   | 0.680      | -            | -                | -                | -         |   -10.07 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           45 |     1986 | 2024-12-08 | 9INE                                      | W   | 0.647      | 0.435        | 0.037 (0.010)    | 0.839 (0.236)    | 0 (0.000) |    13.28 | Keoz, REDSTAR, reiko, sinnopsyy, smooya       |
|           44 |     2130 | 2024-12-06 | Endpoint                                  | W   | 0.633      | 0.435        | -                | 0.385 (0.106)    | 0 (0.000) |     8.50 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           43 |     2286 | 2024-12-03 | Metizport                                 | W   | 0.611      | 0.435        | 0.074 (0.020)    | 0.513 (0.136)    | 0 (0.000) |    15.94 | hAdji, Keoz, REDSTAR, sinnopsyy, smooya       |
|           42 |     3728 | 2024-11-09 | ENCE                                      | L   | 0.452      | -            | -                | -                | -         |    -2.90 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           41 |     3809 | 2024-11-08 | Dynamo Eclot                              | L   | 0.444      | -            | -                | -                | -         |    -2.47 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           40 |     3890 | 2024-11-06 | 9INE                                      | L   | 0.433      | -            | -                | -                | -         |    -6.83 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           39 |     3898 | 2024-11-06 | 9INE                                      | W   | 0.432      | -            | -                | -                | 0 (0.000) |     6.93 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           38 |     3949 | 2024-11-05 | Nemiga Gaming                             | L   | 0.426      | -            | -                | -                | -         |    -2.64 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           37 |     4011 | 2024-11-04 | Rebels Gaming                             | L   | 0.418      | -            | -                | -                | -         |    -7.73 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           36 |     4087 | 2024-11-03 | AMKAL ESPORTS                             | L   | 0.411      | -            | -                | -                | -         |    -6.41 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           35 |     4126 | 2024-11-02 | 500                                       | W   | 0.406      | 0.143        | 0.091 (0.005)    | 1.000 (0.058)    | 0 (0.000) |     9.88 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           34 |     4144 | 2024-11-02 | Sashi Esport                              | W   | 0.405      | -            | -                | -                | 0 (0.000) |     8.88 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           33 |     4153 | 2024-11-02 | Los kogutos                               | W   | 0.405      | -            | -                | -                | -         |     8.79 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           32 |     4204 | 2024-11-01 | Insilio                                   | L   | 0.399      | -            | -                | -                | -         |    -8.97 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           31 |     4213 | 2024-11-01 | Dynamo Eclot                              | L   | 0.398      | -            | -                | -                | -         |    -2.22 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           30 |     4319 | 2024-10-30 | Los kogutos                               | W   | 0.386      | 0.384        | 0.032 (0.005)    | 0.527 (0.078)    | -         |     8.56 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           29 |     4326 | 2024-10-30 | GUN5 Esports                              | W   | 0.385      | 0.371        | 0.102 (0.015)    | 0.515 (0.073)    | -         |     8.73 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           28 |     4543 | 2024-10-26 | Chimera Esports                           | W   | 0.358      | 0.371        | -                | 0.595 (0.079)    | -         |     7.06 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           27 |     4790 | 2024-10-20 | Johnny Speeds                             | W   | 0.319      | -            | -                | -                | -         |     7.07 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           26 |     5142 | 2024-10-13 | GUN5 Esports                              | L   | 0.272      | -            | -                | -                | -         |    -2.25 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           25 |     5531 | 2024-10-06 | Nexus Gaming                              | W   | 0.225      | 0.143        | 0.186 (0.006)    | -                | -         |     6.44 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           24 |     5793 | 2024-10-02 | Illuminar Gaming                          | L   | 0.198      | -            | -                | -                | -         |    -2.08 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           23 |     5882 | 2024-10-01 | Passion UA                                | L   | 0.190      | -            | -                | -                | -         |    -1.06 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           22 |     5966 | 2024-09-29 | Copenhagen Wolves (American organization) | L   | 0.178      | -            | -                | -                | -         |    -4.24 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           21 |     6058 | 2024-09-28 | Team Sampi                                | W   | 0.172      | -            | -                | -                | -         |     3.07 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           20 |     6072 | 2024-09-28 | Johnny Speeds                             | W   | 0.171      | -            | -                | -                | -         |     3.70 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           19 |     6118 | 2024-09-27 | ALTERNATE aTTaX                           | L   | 0.166      | -            | -                | -                | -         |    -1.40 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           18 |     6142 | 2024-09-27 | UNiTY esports                             | W   | 0.165      | -            | -                | -                | -         |     3.26 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           17 |     6185 | 2024-09-26 | ECSTATIC                                  | L   | 0.160      | -            | -                | -                | -         |    -1.59 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           16 |     6221 | 2024-09-26 | Aurora Gaming                             | L   | 0.158      | -            | -                | -                | -         |    -2.07 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           15 |     6370 | 2024-09-24 | Endpoint                                  | W   | 0.146      | -            | -                | -                | -         |     2.48 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           14 |     6393 | 2024-09-24 | Fnatic                                    | W   | 0.145      | 0.384        | 0.072 (0.004)    | -                | -         |     3.92 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           13 |     6413 | 2024-09-24 | ALTERNATE aTTaX                           | L   | 0.144      | -            | -                | -                | -         |    -1.20 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           12 |     6490 | 2024-09-23 | Metizport                                 | W   | 0.137      | 0.384        | 0.074 (0.004)    | -                | -         |     3.77 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           11 |     6624 | 2024-09-20 | 9Pandas                                   | L   | 0.120      | -            | -                | -                | -         |    -0.82 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|           10 |     6647 | 2024-09-20 | Dark Cloud Esports                        | W   | 0.118      | 0.371        | -                | 0.828 (0.036)    | -         |     2.33 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            9 |     6654 | 2024-09-20 | 9INE                                      | L   | 0.117      | -            | -                | -                | -         |    -1.76 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            8 |     6694 | 2024-09-19 | Team Sampi                                | W   | 0.113      | -            | -                | -                | -         |     2.09 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            7 |     6772 | 2024-09-18 | AMKAL ESPORTS                             | L   | 0.104      | -            | -                | -                | -         |    -1.40 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            6 |     6842 | 2024-09-17 | Sashi Esport                              | W   | 0.098      | -            | -                | -                | -         |     2.38 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            5 |     6853 | 2024-09-17 | GUN5 Esports                              | W   | 0.098      | 0.443        | 0.102 (0.004)    | -                | -         |     2.29 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            4 |     7191 | 2024-09-11 | EYEBALLERS                                | W   | 0.059      | -            | -                | -                | -         |     1.09 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            3 |     7211 | 2024-09-11 | Rebels Gaming                             | L   | 0.058      | -            | -                | -                | -         |    -0.93 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            2 |     7615 | 2024-09-05 | TEAM NEXT LEVEL                           | W   | 0.018      | -            | -                | -                | -         |     0.25 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |
|            1 |     7628 | 2024-09-05 | GamerLegion                               | W   | 0.017      | -            | -                | -                | -         |     0.24 | juanflatroo, Keoz, REDSTAR, sinnopsyy, smooya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($422.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-26 |      0.159 | $1,500.00      | $238.47         |
| 2024-09-24 |      0.145 | $1,000.00      | $144.72         |
| 2024-09-14 |      0.079 | $500.00        | $39.72          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
