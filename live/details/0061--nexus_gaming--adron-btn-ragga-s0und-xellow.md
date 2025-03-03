### Roster Details<br />
Team Name: Nexus Gaming<br />
Roster: ADRON, BTN, ragga, s0und, XELLOW<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.1<br />
<br />
Final Rank Value (928.1) = Starting Rank Value (1190.0) + Head To Head Adjustments (-261.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.579[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.206[<sup>2</sup>](#table1)
- LAN Wins: 0.464[<sup>2</sup>](#table1)

The average of these factors is 0.395<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1190.0
- 400 + ( ( 0.395 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1190.0


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
|           83 |      265 | 2025-02-20 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -6.91 | ADRON, BTN, ragga, s0und, XELLOW     |
|           82 |      507 | 2025-02-14 | Partizan Esports                          | L   | 1.000      | -            | -                | -                | -         |   -12.21 | ADRON, BTN, ragga, s0und, XELLOW     |
|           81 |      528 | 2025-02-13 | Fire Flux Esports                         | W   | 1.000      | 0.435        | 0.008 (0.003)    | 1.000 (0.435)    | 0 (0.000) |    14.74 | ADRON, BTN, ragga, s0und, XELLOW     |
|           80 |      591 | 2025-02-10 | Hesta                                     | L   | 1.000      | -            | -                | -                | -         |   -21.79 | ADRON, BTN, ragga, s0und, XELLOW     |
|           79 |      604 | 2025-02-10 | Metizport                                 | L   | 1.000      | -            | -                | -                | -         |   -13.92 | ADRON, BTN, ragga, s0und, XELLOW     |
|           78 |      916 | 2025-02-05 | Dynamo Eclot                              | L   | 1.000      | -            | -                | -                | -         |   -12.19 | ADRON, BTN, ragga, s0und, XELLOW     |
|           77 |      926 | 2025-02-05 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -18.00 | ADRON, BTN, ragga, s0und, XELLOW     |
|           76 |     1411 | 2024-12-22 | Betclic Apogee Esports                    | L   | 0.731      | -            | -                | -                | -         |   -15.32 | ADRON, BTN, Ciocardau, XELLOW, zewts |
|           75 |     1418 | 2024-12-22 | KONO.ECF                                  | L   | 0.730      | -            | -                | -                | -         |   -15.58 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           74 |     1471 | 2024-12-21 | P0RTUGAL                                  | L   | 0.724      | -            | -                | -                | -         |   -17.70 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           73 |     1487 | 2024-12-21 | Copenhagen Wolves (American organization) | W   | 0.723      | 0.371        | 0.016 (0.004)    | 1.000 (0.268)    | 0 (0.000) |     6.93 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           72 |     1518 | 2024-12-20 | Fire Flux Esports                         | W   | 0.718      | 0.371        | -                | 1.000 (0.266)    | -         |     7.00 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           71 |     1540 | 2024-12-19 | KONO.ECF                                  | L   | 0.712      | -            | -                | -                | -         |   -15.88 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           70 |     1563 | 2024-12-18 | Insilio                                   | W   | 0.705      | 0.354        | -                | 0.500 (0.125)    | -         |     2.74 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           69 |     1567 | 2024-12-18 | Illuminar Gaming                          | W   | 0.704      | 0.354        | -                | 0.581 (0.145)    | -         |     4.61 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           68 |     1635 | 2024-12-15 | Aimclub                                   | L   | 0.684      | -            | -                | -                | -         |   -16.48 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           67 |     1713 | 2024-12-14 | Perfect Storm                             | W   | 0.678      | -            | -                | -                | 1 (0.678) |     2.21 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           66 |     1815 | 2024-12-13 | BC.Game Esports                           | L   | 0.670      | -            | -                | -                | -         |   -15.99 | ADRON, BTN, Ciocardau, s0und, XELLOW |
|           65 |     1897 | 2024-12-11 | Viperio                                   | L   | 0.657      | -            | -                | -                | -         |   -17.93 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           64 |     1969 | 2024-12-09 | Monte                                     | L   | 0.644      | -            | -                | -                | -         |   -14.53 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           63 |     2343 | 2024-12-02 | GenOne                                    | L   | 0.599      | -            | -                | -                | -         |   -15.31 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           62 |     2501 | 2024-11-30 | Infinite Gaming                           | W   | 0.585      | -            | -                | -                | -         |     0.57 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           61 |     2513 | 2024-11-30 | Theboyz                                   | W   | 0.585      | -            | -                | -                | -         |     1.19 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           60 |     2530 | 2024-11-30 | Perfect Storm                             | W   | 0.585      | -            | -                | -                | -         |     1.34 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           59 |     2535 | 2024-11-30 | JackBoyz                                  | W   | 0.584      | -            | -                | -                | -         |     1.27 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           58 |     2545 | 2024-11-30 | Lazer Cats                                | W   | 0.583      | -            | -                | -                | -         |     2.15 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           57 |     2646 | 2024-11-28 | FAVBET Team                               | L   | 0.572      | -            | -                | -                | -         |   -14.15 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           56 |     2715 | 2024-11-26 | UNiTY esports                             | W   | 0.559      | 0.372        | 0.025 (0.005)    | -                | -         |     2.94 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           55 |     2907 | 2024-11-23 | Haspers Team                              | W   | 0.537      | 0.372        | 0.013 (0.003)    | -                | -         |     1.43 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           54 |     2974 | 2024-11-22 | Endpoint                                  | W   | 0.531      | -            | -                | -                | -         |     1.78 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           53 |     2984 | 2024-11-22 | RUSTEC                                    | W   | 0.531      | -            | -                | -                | -         |     0.74 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           52 |     3037 | 2024-11-21 | Infinite Gaming                           | W   | 0.525      | -            | -                | -                | -         |     0.52 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           51 |     3058 | 2024-11-21 | ADEPTS                                    | W   | 0.524      | -            | -                | -                | -         |     0.93 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           50 |     3108 | 2024-11-20 | Passion UA                                | W   | 0.519      | 0.372        | 0.044 (0.009)    | 0.545 (0.105)    | -         |     5.08 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           49 |     3245 | 2024-11-17 | GTZ.ESPORTS                               | W   | 0.498      | 0.617        | 0.080 (0.025)    | 0.557 (0.171)    | 1 (0.498) |     9.03 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           48 |     3291 | 2024-11-17 | Metizport                                 | W   | 0.496      | 0.617        | 0.074 (0.023)    | 0.507 (0.155)    | 1 (0.496) |     7.49 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           47 |     3332 | 2024-11-16 | ALTERNATE aTTaX                           | W   | 0.491      | 0.617        | 0.021 (0.006)    | 0.552 (0.168)    | 1 (0.491) |     4.31 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           46 |     3404 | 2024-11-15 | Team Latvia                               | W   | 0.484      | -            | -                | -                | 1 (0.484) |     0.95 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           45 |     3444 | 2024-11-14 | GnG x Amazigh                             | W   | 0.478      | -            | -                | -                | 1 (0.478) |     0.30 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           44 |     3454 | 2024-11-14 | KONO.ECF                                  | W   | 0.478      | 0.617        | 0.046 (0.013)    | 0.747 (0.221)    | 1 (0.478) |     4.01 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           43 |     3464 | 2024-11-14 | Team Novaq                                | L   | 0.478      | -            | -                | -                | -         |    -6.98 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           42 |     3951 | 2024-11-05 | Heimo Esports                             | W   | 0.418      | -            | -                | -                | -         |     1.70 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           41 |     3962 | 2024-11-05 | TEAM NEXT LEVEL                           | W   | 0.418      | -            | -                | -                | -         |     1.25 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           40 |     4014 | 2024-11-04 | Fire Flux Esports                         | L   | 0.411      | -            | -                | -                | -         |    -9.84 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           39 |     4202 | 2024-11-01 | CYBERSHOKE Esports                        | L   | 0.392      | -            | -                | -                | -         |   -10.23 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           38 |     4477 | 2024-10-27 | HyperSpirit                               | W   | 0.358      | -            | -                | -                | 1 (0.358) |     0.83 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           37 |     4540 | 2024-10-26 | Johnny Speeds                             | L   | 0.350      | -            | -                | -                | -         |    -8.42 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           36 |     4631 | 2024-10-24 | FORZE Reload                              | L   | 0.338      | -            | -                | -                | -         |    -8.77 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           35 |     4675 | 2024-10-23 | K27                                       | W   | 0.331      | -            | -                | -                | -         |     2.41 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           34 |     4715 | 2024-10-22 | BC.Game Esports                           | W   | 0.324      | -            | -                | -                | -         |     1.72 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           33 |     4766 | 2024-10-21 | K27                                       | L   | 0.316      | -            | -                | -                | -         |    -7.60 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           32 |     4806 | 2024-10-20 | Kay Team                                  | W   | 0.311      | -            | -                | -                | -         |     0.32 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           31 |     4811 | 2024-10-20 | PORC CARTEL                               | W   | 0.310      | -            | -                | -                | -         |     0.48 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           30 |     4855 | 2024-10-19 | Los kogutos                               | W   | 0.304      | -            | -                | -                | -         |     2.88 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           29 |     4874 | 2024-10-19 | BC.Game Esports                           | L   | 0.302      | -            | -                | -                | -         |    -8.02 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           28 |     4897 | 2024-10-18 | HyperSpirit                               | W   | 0.298      | -            | -                | -                | -         |     0.62 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           27 |     4908 | 2024-10-18 | Virtuoso Squad                            | W   | 0.297      | -            | -                | -                | -         |     0.15 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           26 |     4946 | 2024-10-17 | RUSTEC                                    | L   | 0.291      | -            | -                | -                | -         |    -8.84 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           25 |     4954 | 2024-10-17 | FLuffy Gangsters                          | W   | 0.290      | -            | -                | -                | -         |     1.19 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           24 |     5033 | 2024-10-16 | Viperio                                   | W   | 0.282      | -            | -                | -                | -         |     0.91 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           23 |     5171 | 2024-10-13 | ECSTATIC                                  | L   | 0.262      | -            | -                | -                | -         |    -6.76 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           22 |     5223 | 2024-10-12 | THE GENTLEMEN ESPORTS                     | L   | 0.257      | -            | -                | -                | -         |    -7.51 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           21 |     5241 | 2024-10-12 | Ex-ESC Gaming                             | W   | 0.257      | -            | -                | -                | -         |     0.45 | ADRON, BTN, Ciocardau, ragga, XELLOW |
|           20 |     5543 | 2024-10-06 | Wild Lotus                                | L   | 0.217      | -            | -                | -                | -         |    -6.21 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           19 |     5803 | 2024-10-02 | Los kogutos                               | L   | 0.190      | -            | -                | -                | -         |    -4.38 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           18 |     6039 | 2024-09-28 | EYEBALLERS                                | L   | 0.165      | -            | -                | -                | -         |    -4.61 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           17 |     6083 | 2024-09-28 | Tricked Esport                            | W   | 0.163      | -            | -                | -                | -         |     0.67 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           16 |     6138 | 2024-09-27 | G2 Ares                                   | L   | 0.158      | -            | -                | -                | -         |    -4.67 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           15 |     6206 | 2024-09-26 | Team Space                                | W   | 0.151      | -            | -                | -                | -         |     0.11 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           14 |     6491 | 2024-09-23 | Zero Tenacity                             | L   | 0.130      | -            | -                | -                | -         |    -3.50 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           13 |     6589 | 2024-09-21 | 9Pandas                                   | W   | 0.118      | 0.435        | 0.085 (0.004)    | -                | -         |     0.90 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           12 |     6604 | 2024-09-21 | AMKAL ESPORTS                             | L   | 0.116      | -            | -                | -                | -         |    -3.34 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           11 |     6662 | 2024-09-20 | GenOne                                    | L   | 0.109      | -            | -                | -                | -         |    -3.02 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           10 |     6717 | 2024-09-19 | AMKAL ESPORTS                             | L   | 0.103      | -            | -                | -                | -         |    -2.98 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            9 |     6726 | 2024-09-19 | EYEBALLERS                                | W   | 0.102      | -            | -                | -                | -         |     0.33 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            8 |     6868 | 2024-09-17 | Lynn Vision Gaming                        | L   | 0.089      | -            | -                | -                | -         |    -2.40 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            7 |     6996 | 2024-09-14 | QUAZAR                                    | W   | 0.071      | -            | -                | -                | -         |     0.14 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            6 |     7083 | 2024-09-13 | Alliance                                  | W   | 0.065      | -            | -                | -                | -         |     0.33 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            5 |     7147 | 2024-09-12 | RUSH B (Russian team)                     | W   | 0.057      | -            | -                | -                | -         |     0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            4 |     7156 | 2024-09-12 | BOGATYRI                                  | W   | 0.056      | -            | -                | -                | -         |     0.02 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            3 |     7193 | 2024-09-11 | The Suspect                               | L   | 0.051      | -            | -                | -                | -         |    -1.51 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            2 |     7635 | 2024-09-05 | Chimera Esports                           | L   | 0.010      | -            | -                | -                | -         |    -0.27 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|            1 |     7664 | 2024-09-04 | Hyuga                                     | L   | 0.005      | -            | -                | -                | -         |    -0.15 | 7kick, BTN, Ciocardau, ragga, XELLOW |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,616.70)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-12-23 |      0.737 | $2,000.00      | $1,473.89       |
| 2024-12-15 |      0.684 | $7,878.57      | $5,391.35       |
| 2024-11-17 |      0.498 | $100,000.00    | $49,805.56      |
| 2024-10-27 |      0.358 | $5,399.86      | $1,932.57       |
| 2024-10-24 |      0.338 | $3,000.00      | $1,013.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
