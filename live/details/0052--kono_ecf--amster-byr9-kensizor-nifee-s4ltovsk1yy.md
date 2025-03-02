### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, byr9, kensizor, nifee, s4ltovsk1yy<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  963.7<br />
<br />
Final Rank Value (963.7) = Starting Rank Value (919.8) + Head To Head Adjustments (44.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.194[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.8
- 400 + ( ( 0.260 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 919.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |     1239 | 2024-12-30 | Dark Cloud Esports                        | W   | 0.792      | 0.333        | 0.038 (0.010)    | 0.828 (0.219)    | 0 (0.000) |     9.80 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           71 |     1261 | 2024-12-29 | Los kogutos                               | W   | 0.785      | 0.333        | 0.032 (0.008)    | -                | 0 (0.000) |    10.18 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           70 |     1301 | 2024-12-28 | Kubix Esports                             | W   | 0.779      | 0.333        | 0.045 (0.012)    | -                | 0 (0.000) |    11.02 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           69 |     1354 | 2024-12-25 | WOPA Esport                               | W   | 0.758      | 0.333        | 0.031 (0.008)    | 0.785 (0.198)    | 0 (0.000) |    10.14 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           68 |     1375 | 2024-12-23 | TEAM NEXT LEVEL                           | L   | 0.745      | -            | -                | -                | -         |   -13.14 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           67 |     1380 | 2024-12-23 | ENCE Academy                              | W   | 0.744      | -            | -                | -                | 0 (0.000) |     8.01 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           66 |     1384 | 2024-12-22 | Monte                                     | W   | 0.740      | 0.371        | 0.045 (0.012)    | 0.704 (0.193)    | 0 (0.000) |    12.59 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           65 |     1396 | 2024-12-22 | TEAM NEXT LEVEL                           | W   | 0.739      | -            | -                | -                | 0 (0.000) |    11.05 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           64 |     1406 | 2024-12-22 | Nexus Gaming                              | W   | 0.738      | 0.371        | 0.186 (0.051)    | 0.808 (0.221)    | 0 (0.000) |    15.67 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           63 |     1444 | 2024-12-21 | JANO Esports                              | W   | 0.733      | 0.371        | 0.022 (0.006)    | -                | 0 (0.000) |    10.35 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           62 |     1466 | 2024-12-21 | ADEPTS                                    | W   | 0.732      | -            | -                | -                | -         |     5.76 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           61 |     1483 | 2024-12-21 | WOPA Esport                               | L   | 0.731      | -            | -                | -                | -         |   -13.24 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           60 |     1501 | 2024-12-20 | TEAM NEXT LEVEL                           | L   | 0.727      | -            | -                | -                | -         |   -12.12 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           59 |     1528 | 2024-12-19 | Nexus Gaming                              | W   | 0.720      | 0.371        | 0.186 (0.050)    | 0.808 (0.216)    | -         |    16.01 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           58 |     1534 | 2024-12-19 | Astralis Talent                           | W   | 0.719      | 0.333        | -                | 0.733 (0.176)    | -         |     8.15 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           57 |     1546 | 2024-12-19 | Preasy Esport                             | W   | 0.718      | 0.333        | -                | 0.710 (0.170)    | -         |     8.00 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           56 |     1565 | 2024-12-17 | Lazer Cats                                | W   | 0.707      | -            | -                | -                | -         |     7.79 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           55 |     1568 | 2024-12-17 | Dark Cloud Esports                        | L   | 0.706      | -            | -                | -                | -         |   -11.66 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           54 |     1585 | 2024-12-16 | Monte                                     | W   | 0.699      | 0.371        | 0.045 (0.012)    | 0.704 (0.182)    | -         |    13.84 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           53 |     1597 | 2024-12-16 | GenOne                                    | W   | 0.698      | 0.333        | -                | 0.848 (0.197)    | -         |    10.48 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           52 |     1833 | 2024-12-12 | Astralis Talent                           | W   | 0.673      | 0.333        | -                | 0.733 (0.165)    | -         |     9.16 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           51 |     1844 | 2024-12-12 | Lilmix                                    | W   | 0.672      | -            | -                | -                | -         |     4.14 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           50 |     2004 | 2024-12-08 | GODSENT                                   | W   | 0.646      | -            | -                | -                | -         |     6.13 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           49 |     2024 | 2024-12-08 | GenOne                                    | L   | 0.644      | -            | -                | -                | -         |    -8.85 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           48 |     2430 | 2024-12-01 | BC.Game Esports                           | L   | 0.599      | -            | -                | -                | -         |    -7.90 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           47 |     2538 | 2024-11-30 | Betclic Apogee Esports                    | L   | 0.592      | -            | -                | -                | -         |    -8.10 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |     2598 | 2024-11-29 | BC.Game Esports                           | L   | 0.585      | -            | -                | -                | -         |    -8.56 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |     2701 | 2024-11-26 | ALTERNATE aTTaX                           | L   | 0.567      | -            | -                | -                | -         |    -7.13 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           44 |     2762 | 2024-11-25 | Preasy Esport                             | W   | 0.557      | -            | -                | -                | -         |     6.42 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |     2775 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.554      | -            | -                | -                | -         |    -9.04 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           42 |     2843 | 2024-11-23 | RUSTEC                                    | L   | 0.547      | -            | -                | -                | -         |   -13.65 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           41 |     2879 | 2024-11-23 | GenOne                                    | W   | 0.546      | -            | -                | -                | -         |     7.67 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |     2976 | 2024-11-22 | FLuffy Gangsters                          | L   | 0.539      | -            | -                | -                | -         |    -9.26 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           39 |     3015 | 2024-11-21 | Leo Team                                  | L   | 0.533      | -            | -                | -                | -         |    -8.55 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           38 |     3034 | 2024-11-21 | RUSTEC                                    | W   | 0.532      | -            | -                | -                | -         |     2.44 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           37 |     3385 | 2024-11-15 | Team Novaq                                | L   | 0.493      | -            | -                | -                | -         |    -3.25 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |     3433 | 2024-11-14 | Team Latvia                               | L   | 0.487      | -            | -                | -                | -         |   -12.96 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |     3442 | 2024-11-14 | Nexus Gaming                              | L   | 0.486      | -            | -                | -                | -         |    -4.11 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |     3453 | 2024-11-14 | GnG x Amazigh                             | W   | 0.486      | -            | -                | -                | 1 (0.486) |     0.83 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |     3870 | 2024-11-06 | Heimo Esports                             | W   | 0.434      | -            | -                | -                | -         |     4.04 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           32 |     3883 | 2024-11-06 | QUAZAR                                    | W   | 0.433      | -            | -                | -                | -         |     3.74 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           31 |     4033 | 2024-11-03 | Preasy Esport                             | L   | 0.414      | -            | -                | -                | -         |    -8.55 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |     4305 | 2024-10-30 | Fire Flux Esports                         | L   | 0.386      | -            | -                | -                | -         |    -6.56 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           29 |     4366 | 2024-10-29 | CYBERSHOKE Esports                        | W   | 0.380      | -            | -                | -                | -         |     4.71 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           28 |     4462 | 2024-10-27 | MOUZ NXT                                  | W   | 0.366      | -            | -                | -                | -         |     1.57 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           27 |     4635 | 2024-10-24 | Chimera Esports                           | L   | 0.344      | -            | -                | -                | -         |    -6.35 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     4712 | 2024-10-22 | Natus Vincere Junior                      | W   | 0.331      | 0.333        | 0.091 (0.010)    | -                | -         |     6.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     4736 | 2024-10-21 | Endpoint                                  | L   | 0.326      | -            | -                | -                | -         |    -7.17 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           24 |     4820 | 2024-10-20 | Copenhagen Wolves (American organization) | W   | 0.317      | -            | -                | -                | -         |     4.37 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     4906 | 2024-10-18 | GenOne                                    | L   | 0.304      | -            | -                | -                | -         |    -5.88 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     4946 | 2024-10-17 | Illuminar Gaming                          | W   | 0.298      | -            | -                | -                | -         |     4.26 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     5084 | 2024-10-15 | Heimo Esports                             | W   | 0.284      | -            | -                | -                | -         |     2.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     5094 | 2024-10-14 | ALASKA                                    | W   | 0.280      | -            | -                | -                | -         |     6.73 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           19 |     5119 | 2024-10-14 | Natus Vincere Junior                      | L   | 0.277      | -            | -                | -                | -         |    -3.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     5156 | 2024-10-13 | ADEPTS                                    | L   | 0.271      | -            | -                | -                | -         |    -6.82 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     5296 | 2024-10-10 | ENCE Academy                              | W   | 0.251      | -            | -                | -                | -         |     2.95 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     5371 | 2024-10-09 | Heimo Esports                             | W   | 0.244      | -            | -                | -                | -         |     2.21 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     5494 | 2024-10-07 | FAVBET Team                               | L   | 0.231      | -            | -                | -                | -         |    -4.45 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           14 |     5610 | 2024-10-05 | LOADING (French team)                     | W   | 0.218      | -            | -                | -                | -         |     0.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           13 |     5952 | 2024-09-29 | Leo Team                                  | L   | 0.180      | -            | -                | -                | -         |    -3.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           12 |     5970 | 2024-09-29 | TEAM NEXT LEVEL                           | W   | 0.178      | -            | -                | -                | -         |     2.34 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           11 |     6026 | 2024-09-28 | Iron Branch (Ukrainian team)              | W   | 0.173      | -            | -                | -                | -         |     0.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           10 |     6330 | 2024-09-25 | Los kogutos                               | L   | 0.150      | -            | -                | -                | -         |    -1.85 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            9 |     6593 | 2024-09-21 | Tricked Esport                            | L   | 0.124      | -            | -                | -                | -         |    -2.43 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            8 |     6850 | 2024-09-17 | Dynamo Eclot                              | L   | 0.098      | -            | -                | -                | -         |    -0.88 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            7 |     6896 | 2024-09-16 | Leo Team                                  | W   | 0.092      | -            | -                | -                | -         |     1.10 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            6 |     6945 | 2024-09-15 | Lazer Cats                                | L   | 0.085      | -            | -                | -                | -         |    -2.01 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            5 |     6958 | 2024-09-15 | Ex-ENTERPRISE esports                     | W   | 0.084      | -            | -                | -                | -         |     0.65 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            4 |     7036 | 2024-09-14 | Fragmatic                                 | W   | 0.078      | -            | -                | -                | -         |     0.20 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            3 |     7107 | 2024-09-13 | Preasy Esport                             | W   | 0.070      | -            | -                | -                | -         |     0.78 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            2 |     7215 | 2024-09-11 | Dynamo Eclot                              | L   | 0.057      | -            | -                | -                | -         |    -0.51 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            1 |     7526 | 2024-09-06 | ALASKA                                    | W   | 0.025      | -            | -                | -                | -         |     0.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,250.78)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.792 | $6,000.00      | $4,750.00       |
| 2024-12-25 |      0.758 | $6,000.00      | $4,549.58       |
| 2024-12-23 |      0.745 | $5,000.00      | $3,725.69       |
| 2024-12-22 |      0.739 | $1,196.99      | $885.11         |
| 2024-10-24 |      0.344 | $3,000.00      | $1,030.83       |
| 2024-09-29 |      0.180 | $971.82        | $174.66         |
| 2024-09-18 |      0.104 | $1,000.00      | $103.61         |
| 2024-09-15 |      0.086 | $362.53        | $31.29          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
