### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, byr9, kensizor, nifee, s4ltovsk1yy<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  960.7<br />
<br />
Final Rank Value (960.7) = Starting Rank Value (917.9) + Head To Head Adjustments (42.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.9
- 400 + ( ( 0.259 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 917.9


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
|           72 |     1251 | 2024-12-30 | Dark Cloud Esports                        | W   | 0.783      | 0.333        | 0.039 (0.010)    | 0.819 (0.214)    | 0 (0.000) |     9.73 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           71 |     1273 | 2024-12-29 | Los kogutos                               | W   | 0.777      | 0.333        | 0.032 (0.008)    | -                | 0 (0.000) |    10.15 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           70 |     1313 | 2024-12-28 | Kubix Esports                             | W   | 0.770      | 0.333        | 0.045 (0.012)    | -                | 0 (0.000) |    10.95 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           69 |     1366 | 2024-12-25 | WOPA Esport                               | W   | 0.750      | 0.333        | 0.032 (0.008)    | 0.777 (0.194)    | 0 (0.000) |    10.05 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           68 |     1387 | 2024-12-23 | TEAM NEXT LEVEL                           | L   | 0.737      | -            | -                | -                | -         |   -12.96 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           67 |     1392 | 2024-12-23 | ENCE Academy                              | W   | 0.736      | -            | -                | -                | 0 (0.000) |     7.97 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           66 |     1396 | 2024-12-22 | Monte                                     | W   | 0.732      | 0.371        | 0.045 (0.012)    | 0.696 (0.189)    | 0 (0.000) |    12.46 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           65 |     1408 | 2024-12-22 | TEAM NEXT LEVEL                           | W   | 0.731      | -            | -                | -                | 0 (0.000) |    10.97 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           64 |     1418 | 2024-12-22 | Nexus Gaming                              | W   | 0.730      | 0.371        | 0.187 (0.051)    | 0.795 (0.215)    | 0 (0.000) |    15.58 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           63 |     1456 | 2024-12-21 | JANO Esports                              | W   | 0.725      | 0.371        | 0.022 (0.006)    | -                | 0 (0.000) |    10.32 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           62 |     1478 | 2024-12-21 | ADEPTS                                    | W   | 0.724      | -            | -                | -                | -         |     4.72 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           61 |     1495 | 2024-12-21 | WOPA Esport                               | L   | 0.723      | -            | -                | -                | -         |   -13.07 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           60 |     1513 | 2024-12-20 | TEAM NEXT LEVEL                           | L   | 0.719      | -            | -                | -                | -         |   -11.98 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           59 |     1540 | 2024-12-19 | Nexus Gaming                              | W   | 0.712      | 0.371        | 0.187 (0.049)    | 0.795 (0.210)    | -         |    15.88 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           58 |     1546 | 2024-12-19 | Astralis Talent                           | W   | 0.711      | 0.333        | -                | 0.724 (0.172)    | -         |     8.03 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           57 |     1558 | 2024-12-19 | Preasy Esport                             | W   | 0.709      | 0.333        | -                | 0.701 (0.166)    | -         |     7.86 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           56 |     1577 | 2024-12-17 | Lazer Cats                                | W   | 0.699      | -            | -                | -                | -         |     7.70 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           55 |     1580 | 2024-12-17 | Dark Cloud Esports                        | L   | 0.698      | -            | -                | -                | -         |   -11.54 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           54 |     1597 | 2024-12-16 | Monte                                     | W   | 0.691      | 0.371        | 0.045 (0.011)    | 0.696 (0.178)    | -         |    13.63 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           53 |     1609 | 2024-12-16 | GenOne                                    | W   | 0.689      | 0.333        | -                | 0.837 (0.192)    | -         |    10.35 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           52 |     1845 | 2024-12-12 | Astralis Talent                           | W   | 0.665      | 0.333        | -                | 0.724 (0.161)    | -         |     8.99 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           51 |     1856 | 2024-12-12 | Lilmix                                    | W   | 0.663      | -            | -                | -                | -         |     4.10 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           50 |     2016 | 2024-12-08 | GODSENT                                   | W   | 0.638      | -            | -                | -                | -         |     6.02 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           49 |     2036 | 2024-12-08 | GenOne                                    | L   | 0.636      | -            | -                | -                | -         |    -8.77 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           48 |     2442 | 2024-12-01 | BC.Game Esports                           | L   | 0.591      | -            | -                | -                | -         |    -7.82 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           47 |     2550 | 2024-11-30 | Betclic Apogee Esports                    | L   | 0.583      | -            | -                | -                | -         |    -8.00 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |     2610 | 2024-11-29 | BC.Game Esports                           | L   | 0.577      | -            | -                | -                | -         |    -8.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |     2713 | 2024-11-26 | ALTERNATE aTTaX                           | L   | 0.559      | -            | -                | -                | -         |    -7.05 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           44 |     2774 | 2024-11-25 | Preasy Esport                             | W   | 0.549      | -            | -                | -                | -         |     6.32 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |     2787 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.545      | -            | -                | -                | -         |    -8.90 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           42 |     2855 | 2024-11-23 | RUSTEC                                    | L   | 0.538      | -            | -                | -                | -         |   -13.42 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           41 |     2891 | 2024-11-23 | GenOne                                    | W   | 0.538      | -            | -                | -                | -         |     7.55 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |     2988 | 2024-11-22 | FLuffy Gangsters                          | L   | 0.531      | -            | -                | -                | -         |    -9.15 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           39 |     3027 | 2024-11-21 | Leo Team                                  | L   | 0.525      | -            | -                | -                | -         |    -8.44 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           38 |     3046 | 2024-11-21 | RUSTEC                                    | W   | 0.524      | -            | -                | -                | -         |     2.41 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           37 |     3397 | 2024-11-15 | Team Novaq                                | L   | 0.485      | -            | -                | -                | -         |    -3.23 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |     3445 | 2024-11-14 | Team Latvia                               | L   | 0.478      | -            | -                | -                | -         |   -12.73 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |     3454 | 2024-11-14 | Nexus Gaming                              | L   | 0.478      | -            | -                | -                | -         |    -4.01 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |     3465 | 2024-11-14 | GnG x Amazigh                             | W   | 0.478      | -            | -                | -                | 1 (0.478) |     0.83 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |     3882 | 2024-11-06 | Heimo Esports                             | W   | 0.425      | -            | -                | -                | -         |     3.96 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           32 |     3895 | 2024-11-06 | QUAZAR                                    | W   | 0.425      | -            | -                | -                | -         |     3.67 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           31 |     4045 | 2024-11-03 | Preasy Esport                             | L   | 0.406      | -            | -                | -                | -         |    -8.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |     4317 | 2024-10-30 | Fire Flux Esports                         | L   | 0.378      | -            | -                | -                | -         |    -6.43 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           29 |     4378 | 2024-10-29 | CYBERSHOKE Esports                        | W   | 0.372      | -            | -                | -                | -         |     4.65 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           28 |     4474 | 2024-10-27 | MOUZ NXT                                  | W   | 0.358      | -            | -                | -                | -         |     1.54 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           27 |     4647 | 2024-10-24 | Chimera Esports                           | L   | 0.335      | -            | -                | -                | -         |    -6.20 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     4725 | 2024-10-22 | Natus Vincere Junior                      | W   | 0.323      | 0.333        | 0.091 (0.010)    | -                | -         |     6.15 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     4748 | 2024-10-21 | Endpoint                                  | L   | 0.318      | -            | -                | -                | -         |    -6.97 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           24 |     4834 | 2024-10-20 | Copenhagen Wolves (American organization) | W   | 0.309      | -            | -                | -                | -         |     4.27 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     4918 | 2024-10-18 | GenOne                                    | L   | 0.295      | -            | -                | -                | -         |    -5.72 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     4958 | 2024-10-17 | Illuminar Gaming                          | W   | 0.290      | -            | -                | -                | -         |     4.13 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     5097 | 2024-10-15 | Heimo Esports                             | W   | 0.275      | -            | -                | -                | -         |     2.52 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     5106 | 2024-10-14 | ALASKA                                    | W   | 0.272      | -            | -                | -                | -         |     6.56 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           19 |     5130 | 2024-10-14 | Natus Vincere Junior                      | L   | 0.269      | -            | -                | -                | -         |    -3.48 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     5168 | 2024-10-13 | ADEPTS                                    | L   | 0.263      | -            | -                | -                | -         |    -7.12 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     5307 | 2024-10-10 | ENCE Academy                              | W   | 0.243      | -            | -                | -                | -         |     2.87 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     5383 | 2024-10-09 | Heimo Esports                             | W   | 0.235      | -            | -                | -                | -         |     2.14 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     5506 | 2024-10-07 | FAVBET Team                               | L   | 0.223      | -            | -                | -                | -         |    -4.29 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           14 |     5622 | 2024-10-05 | LOADING (French team)                     | W   | 0.210      | -            | -                | -                | -         |     0.67 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           13 |     5964 | 2024-09-29 | Leo Team                                  | L   | 0.172      | -            | -                | -                | -         |    -3.30 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           12 |     5982 | 2024-09-29 | TEAM NEXT LEVEL                           | W   | 0.170      | -            | -                | -                | -         |     2.23 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           11 |     6038 | 2024-09-28 | Iron Branch (Ukrainian team)              | W   | 0.165      | -            | -                | -                | -         |     0.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           10 |     6342 | 2024-09-25 | Los kogutos                               | L   | 0.142      | -            | -                | -                | -         |    -1.76 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            9 |     6605 | 2024-09-21 | Tricked Esport                            | L   | 0.116      | -            | -                | -                | -         |    -2.27 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            8 |     6862 | 2024-09-17 | Dynamo Eclot                              | L   | 0.089      | -            | -                | -                | -         |    -0.81 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            7 |     6908 | 2024-09-16 | Leo Team                                  | W   | 0.084      | -            | -                | -                | -         |     1.01 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            6 |     6957 | 2024-09-15 | Lazer Cats                                | L   | 0.076      | -            | -                | -                | -         |    -1.81 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            5 |     6970 | 2024-09-15 | Ex-ENTERPRISE esports                     | W   | 0.075      | -            | -                | -                | -         |     0.59 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            4 |     7048 | 2024-09-14 | Fragmatic                                 | W   | 0.070      | -            | -                | -                | -         |     0.18 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            3 |     7119 | 2024-09-13 | Preasy Esport                             | W   | 0.062      | -            | -                | -                | -         |     0.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            2 |     7227 | 2024-09-11 | Dynamo Eclot                              | L   | 0.049      | -            | -                | -                | -         |    -0.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            1 |     7538 | 2024-09-06 | ALASKA                                    | W   | 0.017      | -            | -                | -                | -         |     0.43 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,057.95)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.783 | $6,000.00      | $4,700.83       |
| 2024-12-25 |      0.750 | $6,000.00      | $4,500.42       |
| 2024-12-23 |      0.737 | $5,000.00      | $3,684.72       |
| 2024-12-22 |      0.731 | $1,196.99      | $875.30         |
| 2024-10-24 |      0.335 | $3,000.00      | $1,006.25       |
| 2024-09-29 |      0.172 | $971.82        | $166.69         |
| 2024-09-18 |      0.095 | $1,000.00      | $95.42          |
| 2024-09-15 |      0.078 | $362.53        | $28.32          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
