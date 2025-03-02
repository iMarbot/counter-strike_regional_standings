### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, FreeZe, hyped, PerX, prosus<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.0<br />
<br />
Final Rank Value (929.0) = Starting Rank Value (936.7) + Head To Head Adjustments (-7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.373[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.285[<sup>2</sup>](#table1)

The average of these factors is 0.269<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 936.7
- 400 + ( ( 0.269 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 936.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           66 |     1792 | 2024-12-13 | 9INE                                      | L   | 0.679      | -            | -                | -                | -         |   -11.19 | ArroW, FreeZe, hyped, PerX, prosus |
|           65 |     2216 | 2024-12-04 | 500                                       | L   | 0.620      | -            | -                | -                | -         |    -7.60 | ArroW, FreeZe, hyped, PerX, prosus |
|           64 |     2268 | 2024-12-03 | FAVBET Team                               | W   | 0.613      | 0.372        | 0.032 (0.007)    | 0.814 (0.186)    | 0 (0.000) |     8.29 | ArroW, FreeZe, hyped, PerX, prosus |
|           63 |     2322 | 2024-12-02 | GameAgents                                | W   | 0.607      | -            | -                | -                | 0 (0.000) |     2.84 | ArroW, FreeZe, hyped, PerX, prosus |
|           62 |     2407 | 2024-12-01 | Viperio                                   | W   | 0.600      | 0.372        | -                | 0.411 (0.092)    | 0 (0.000) |     4.71 | ArroW, FreeZe, hyped, PerX, prosus |
|           61 |     2633 | 2024-11-28 | Leo Team                                  | L   | 0.580      | -            | -                | -                | -         |   -10.47 | ArroW, FreeZe, hyped, PerX, prosus |
|           60 |     2701 | 2024-11-26 | KONO.ECF                                  | W   | 0.567      | 0.372        | 0.045 (0.010)    | 0.757 (0.160)    | 0 (0.000) |     7.13 | ArroW, FreeZe, hyped, PerX, prosus |
|           59 |     2787 | 2024-11-24 | Underrated                                | W   | 0.552      | 0.372        | -                | 0.271 (0.056)    | 0 (0.000) |     3.12 | ArroW, FreeZe, hyped, PerX, prosus |
|           58 |     2966 | 2024-11-22 | RUSTEC                                    | W   | 0.539      | -            | -                | -                | -         |     2.77 | ArroW, FreeZe, hyped, PerX, prosus |
|           57 |     2975 | 2024-11-22 | PCIFIC Espor                              | W   | 0.539      | 0.372        | 0.004 (0.001)    | -                | -         |     4.67 | ArroW, FreeZe, hyped, PerX, prosus |
|           56 |     3024 | 2024-11-21 | Kay Team                                  | W   | 0.533      | -            | -                | -                | -         |     1.33 | ArroW, FreeZe, hyped, PerX, prosus |
|           55 |     3320 | 2024-11-16 | Nexus Gaming                              | L   | 0.500      | -            | -                | -                | -         |    -4.43 | ArroW, faveN, FreeZe, hyped, PerX  |
|           54 |     3383 | 2024-11-15 | Team Hungary                              | W   | 0.493      | -            | -                | -                | 1 (0.493) |     5.14 | ArroW, faveN, FreeZe, hyped, PerX  |
|           53 |     3395 | 2024-11-15 | GTZ.ESPORTS                               | W   | 0.492      | 0.617        | 0.080 (0.024)    | 0.563 (0.171)    | 1 (0.492) |    12.40 | ArroW, faveN, FreeZe, hyped, PerX  |
|           52 |     3456 | 2024-11-14 | MAFE MA3LOM                               | W   | 0.486      | -            | -                | -                | 1 (0.486) |     1.52 | ArroW, faveN, FreeZe, hyped, PerX  |
|           51 |     3461 | 2024-11-14 | Team Kosovo                               | W   | 0.485      | -            | -                | -                | 1 (0.485) |     2.00 | ArroW, faveN, FreeZe, hyped, PerX  |
|           50 |     3468 | 2024-11-14 | Team Chile                                | W   | 0.485      | -            | -                | -                | 1 (0.485) |     1.73 | ArroW, faveN, FreeZe, hyped, PerX  |
|           49 |     4046 | 2024-11-03 | Permitta Esports                          | L   | 0.413      | -            | -                | -                | -         |    -8.41 | ArroW, awzek, FreeZe, hyped, PerX  |
|           48 |     4125 | 2024-11-02 | BIG                                       | L   | 0.406      | -            | -                | -                | -         |    -0.50 | ArroW, awzek, FreeZe, hyped, PerX  |
|           47 |     4180 | 2024-11-01 | Permitta Esports                          | W   | 0.400      | -            | -                | -                | -         |     4.38 | ArroW, awzek, FreeZe, hyped, PerX  |
|           46 |     4196 | 2024-11-01 | HyperSpirit                               | W   | 0.399      | -            | -                | -                | -         |     2.49 | ArroW, FreeZe, hyped, PerX, prosus |
|           45 |     4294 | 2024-10-30 | XPERION NXT                               | W   | 0.387      | -            | -                | -                | -         |     2.30 | ArroW, awzek, FreeZe, hyped, PerX  |
|           44 |     4301 | 2024-10-30 | Ex-Soul's Heart Esport                    | W   | 0.387      | -            | -                | -                | -         |     2.19 | ArroW, FreeZe, hyped, PerX, prosus |
|           43 |     4312 | 2024-10-30 | ADEPTS                                    | L   | 0.386      | -            | -                | -                | -         |    -9.67 | ArroW, FreeZe, hyped, PerX, prosus |
|           42 |     4424 | 2024-10-28 | ROUNDS                                    | W   | 0.373      | -            | -                | -                | -         |     1.22 | ArroW, FreeZe, hyped, PerX, prosus |
|           41 |     4440 | 2024-10-28 | BIG                                       | L   | 0.372      | -            | -                | -                | -         |    -0.45 | ArroW, awzek, FreeZe, hyped, PerX  |
|           40 |     4599 | 2024-10-25 | Passion UA                                | L   | 0.352      | -            | -                | -                | -         |    -3.82 | ArroW, FreeZe, hyped, PerX, prosus |
|           39 |     4633 | 2024-10-24 | Dynamo Eclot                              | L   | 0.344      | -            | -                | -                | -         |    -8.62 | ArroW, awzek, FreeZe, PerX, Rulz   |
|           38 |     4668 | 2024-10-23 | Sissi State Punks                         | W   | 0.339      | -            | -                | -                | -         |     1.54 | ArroW, awzek, FreeZe, hyped, PerX  |
|           37 |     4678 | 2024-10-23 | ALASKA                                    | W   | 0.339      | 0.372        | 0.030 (0.004)    | 0.875 (0.110)    | -         |     7.82 | ArroW, FreeZe, hyped, PerX, prosus |
|           36 |     4683 | 2024-10-23 | Preasy Esport                             | W   | 0.337      | 0.384        | 0.012 (0.002)    | 0.710 (0.092)    | -         |     3.58 | ArroW, awzek, FreeZe, hyped, PerX  |
|           35 |     5071 | 2024-10-15 | QUAZAR                                    | L   | 0.285      | -            | -                | -                | -         |    -6.88 | ArroW, FreeZe, hyped, PerX, prosus |
|           34 |     5079 | 2024-10-15 | HOTU                                      | L   | 0.284      | -            | -                | -                | -         |    -6.87 | ArroW, awzek, FreeZe, hyped, PerX  |
|           33 |     5097 | 2024-10-14 | Permitta Esports                          | W   | 0.280      | -            | -                | -                | -         |     2.97 | ArroW, awzek, FreeZe, hyped, PerX  |
|           32 |     5101 | 2024-10-14 | GTZ.ESPORTS                               | W   | 0.279      | 0.372        | 0.080 (0.008)    | 0.563 (0.059)    | -         |     7.42 | ArroW, FreeZe, hyped, PerX, prosus |
|           31 |     5335 | 2024-10-09 | Fire Flux Esports                         | L   | 0.246      | -            | -                | -                | -         |    -4.43 | ArroW, FreeZe, hyped, PerX, prosus |
|           30 |     5345 | 2024-10-09 | TEAM NEXT LEVEL                           | W   | 0.246      | -            | -                | -                | -         |     1.74 | ArroW, FreeZe, hyped, PerX, prosus |
|           29 |     5439 | 2024-10-08 | Monte                                     | W   | 0.238      | 0.384        | 0.045 (0.004)    | 0.704 (0.064)    | -         |     3.77 | ArroW, awzek, FreeZe, hyped, PerX  |
|           28 |     5441 | 2024-10-08 | Metizport                                 | L   | 0.237      | -            | -                | -                | -         |    -2.08 | ArroW, awzek, FreeZe, hyped, PerX  |
|           27 |     5484 | 2024-10-07 | GUN5 Esports                              | L   | 0.232      | -            | -                | -                | -         |    -3.44 | ArroW, awzek, FreeZe, hyped, PerX  |
|           26 |     5581 | 2024-10-05 | Passion UA                                | L   | 0.219      | -            | -                | -                | -         |    -2.33 | ArroW, awzek, FreeZe, hyped, PerX  |
|           25 |     5719 | 2024-10-03 | TSM                                       | W   | 0.206      | 0.435        | 0.009 (0.001)    | -                | -         |     1.91 | ArroW, awzek, FreeZe, hyped, PerX  |
|           24 |     5727 | 2024-10-03 | B8                                        | L   | 0.205      | -            | -                | -                | -         |    -1.59 | ArroW, awzek, FreeZe, hyped, PerX  |
|           23 |     5773 | 2024-10-02 | SNOGARD Dragons                           | W   | 0.199      | -            | -                | -                | -         |     0.86 | ArroW, awzek, FreeZe, hyped, PerX  |
|           22 |     5848 | 2024-10-01 | Copenhagen Wolves (American organization) | W   | 0.193      | -            | -                | -                | -         |     0.72 | ArroW, awzek, FreeZe, hyped, PerX  |
|           21 |     5868 | 2024-10-01 | 9INE                                      | L   | 0.191      | -            | -                | -                | -         |    -4.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|           20 |     5881 | 2024-10-01 | HOTU                                      | W   | 0.190      | 0.435        | -                | 0.777 (0.064)    | -         |     1.57 | ArroW, awzek, FreeZe, hyped, PerX  |
|           19 |     5914 | 2024-09-30 | Adventurers                               | L   | 0.186      | -            | -                | -                | -         |    -4.06 | ArroW, awzek, FreeZe, hyped, PerX  |
|           18 |     5930 | 2024-09-30 | 500                                       | L   | 0.184      | -            | -                | -                | -         |    -2.46 | ArroW, awzek, FreeZe, hyped, PerX  |
|           17 |     5939 | 2024-09-30 | Illuminar Gaming                          | L   | 0.184      | -            | -                | -                | -         |    -3.42 | ArroW, awzek, FreeZe, hyped, PerX  |
|           16 |     5988 | 2024-09-29 | GameAgents                                | L   | 0.177      | -            | -                | -                | -         |    -4.38 | ArroW, awzek, FreeZe, hyped, PerX  |
|           15 |     6118 | 2024-09-27 | Wild Lotus                                | W   | 0.166      | -            | -                | -                | -         |     1.40 | ArroW, awzek, FreeZe, hyped, PerX  |
|           14 |     6285 | 2024-09-25 | Rhyno Esports                             | W   | 0.153      | -            | -                | -                | -         |     0.93 | ArroW, awzek, FreeZe, hyped, PerX  |
|           13 |     6413 | 2024-09-24 | Wild Lotus                                | W   | 0.144      | -            | -                | -                | -         |     1.20 | ArroW, awzek, FreeZe, hyped, PerX  |
|           12 |     6455 | 2024-09-23 | Regnum4Games                              | W   | 0.140      | -            | -                | -                | -         |     0.68 | ArroW, awzek, FreeZe, hyped, PerX  |
|           11 |     6482 | 2024-09-23 | Team Spirit Academy                       | L   | 0.138      | -            | -                | -                | -         |    -2.26 | ArroW, awzek, FreeZe, hyped, PerX  |
|           10 |     6594 | 2024-09-21 | FAVBET Team                               | L   | 0.124      | -            | -                | -                | -         |    -2.46 | ArroW, awzek, FreeZe, hyped, PerX  |
|            9 |     6653 | 2024-09-20 | UNiTY esports                             | W   | 0.117      | 0.371        | 0.025 (0.001)    | -                | -         |     1.34 | ArroW, awzek, FreeZe, hyped, PerX  |
|            8 |     6707 | 2024-09-19 | The Suspect                               | W   | 0.111      | -            | -                | -                | -         |     0.84 | ArroW, awzek, FreeZe, hyped, PerX  |
|            7 |     6751 | 2024-09-18 | ESports Cologne                           | W   | 0.106      | -            | -                | -                | -         |     0.23 | ArroW, awzek, FreeZe, hyped, PerX  |
|            6 |     6956 | 2024-09-15 | Monte                                     | L   | 0.084      | -            | -                | -                | -         |    -1.40 | ArroW, awzek, FreeZe, hyped, PerX  |
|            5 |     7252 | 2024-09-10 | TSM                                       | L   | 0.052      | -            | -                | -                | -         |    -1.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|            4 |     7298 | 2024-09-09 | MYinsanity                                | W   | 0.046      | -            | -                | -                | -         |     0.25 | ArroW, awzek, FreeZe, hyped, PerX  |
|            3 |     7599 | 2024-09-05 | FAVBET Team                               | W   | 0.019      | -            | -                | -                | -         |     0.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|            2 |     7625 | 2024-09-05 | Cloud9                                    | L   | 0.018      | -            | -                | -                | -         |    -0.31 | ArroW, awzek, FreeZe, hyped, PerX  |
|            1 |     7685 | 2024-09-04 | GameAgents                                | W   | 0.011      | -            | -                | -                | -         |     0.04 | ArroW, awzek, FreeZe, hyped, PerX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,032.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.686 | $262.62        | $180.28         |
| 2024-12-08 |      0.646 | $750.00        | $484.79         |
| 2024-11-17 |      0.506 | $12,500.00     | $6,328.13       |
| 2024-09-14 |      0.079 | $500.00        | $39.72          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
