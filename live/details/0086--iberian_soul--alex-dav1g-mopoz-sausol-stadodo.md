### Roster Details<br />
Team Name: Iberian Soul<br />
Roster: alex, dav1g, mopoz, sausol, stadodo<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  876.3<br />
<br />
Final Rank Value (876.3) = Starting Rank Value (835.6) + Head To Head Adjustments (40.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 835.6
- 400 + ( ( 0.218 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 835.6


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
|           44 |       16 | 2025-03-01 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.38 | alex, dav1g, mopoz, sausol, stadodo   |
|           43 |       23 | 2025-02-28 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    18.67 | alex, dav1g, mopoz, sausol, stadodo   |
|           42 |       52 | 2025-02-25 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -15.76 | alex, dav1g, mopoz, sausol, stadodo   |
|           41 |       70 | 2025-02-24 | OG                                        | W   | 1.000      | 0.143        | 0.062 (0.009)    | 1.000 (0.143)    | 0 (0.000) |    21.81 | alex, dav1g, mopoz, sausol, stadodo   |
|           40 |       72 | 2025-02-24 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    20.12 | alex, dav1g, mopoz, sausol, stadodo   |
|           39 |      121 | 2025-02-23 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.57 | alex, dav1g, mopoz, sausol, stadodo   |
|           38 |      261 | 2025-02-20 | ECSTATIC                                  | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.820 (0.117)    | 0 (0.000) |    18.17 | alex, dav1g, mopoz, sausol, stadodo   |
|           37 |      273 | 2025-02-19 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |    -8.21 | alex, dav1g, mopoz, sausol, stadodo   |
|           36 |      472 | 2025-02-14 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -19.68 | alex, dav1g, mopoz, sausol, stadodo   |
|           35 |      649 | 2025-02-09 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -12.15 | alex, dav1g, mopoz, sausol, stadodo   |
|           34 |      735 | 2025-02-08 | UNiTY esports                             | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | 0 (0.000) |    14.65 | alex, dav1g, mopoz, sausol, stadodo   |
|           33 |      786 | 2025-02-07 | Team Novaq                                | L   | 1.000      | -            | -                | -                | -         |    -4.83 | alex, dav1g, mopoz, sausol, stadodo   |
|           32 |      934 | 2025-02-05 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.87 | alex, dav1g, mopoz, sausol, stadodo   |
|           31 |     1015 | 2025-02-04 | UNiTY esports                             | L   | 1.000      | -            | -                | -                | -         |   -16.05 | alex, dav1g, mopoz, sausol, stadodo   |
|           30 |     1146 | 2025-01-25 | ECSTATIC                                  | L   | 0.957      | -            | -                | -                | -         |   -12.91 | alex, dav1g, mopoz, sausol, stadodo   |
|           29 |     1153 | 2025-01-24 | KONO.ECF                                  | L   | 0.950      | -            | -                | -                | -         |   -21.96 | alex, dav1g, mopoz, sausol, stadodo   |
|           28 |     1720 | 2024-12-14 | Chimera Esports                           | L   | 0.677      | -            | -                | -                | -         |    -8.42 | adamS, dav1g, mopoz, sausol, stadodo  |
|           27 |     1822 | 2024-12-13 | GUN5 Esports                              | L   | 0.669      | -            | -                | -                | -         |    -7.75 | adamS, dav1g, mopoz, sausol, stadodo  |
|           26 |     1891 | 2024-12-11 | Endpoint                                  | L   | 0.658      | -            | -                | -                | -         |   -14.26 | adamS, dav1g, mopoz, sausol, stadodo  |
|           25 |     1935 | 2024-12-10 | Team Spirit Academy                       | L   | 0.651      | -            | -                | -                | -         |    -8.56 | adamS, dav1g, mopoz, sausol, stadodo  |
|           24 |     1943 | 2024-12-10 | TSM                                       | W   | 0.650      | -            | -                | -                | 0 (0.000) |     6.89 | adamS, dav1g, mopoz, sausol, stadodo  |
|           23 |     2094 | 2024-12-07 | FAVBET Team                               | W   | 0.631      | 0.435        | 0.031 (0.009)    | 0.801 (0.220)    | -         |    10.29 | adamS, dav1g, mopoz, sausol, stadodo  |
|           22 |     2147 | 2024-12-06 | 9INE                                      | L   | 0.623      | -            | -                | -                | -         |    -9.10 | adamS, dav1g, mopoz, sausol, stadodo  |
|           21 |     2179 | 2024-12-05 | Betclic Apogee Esports                    | W   | 0.617      | 0.371        | 0.012 (0.003)    | 0.513 (0.117)    | -         |     9.95 | adamS, dav1g, mopoz, sausol, stadodo  |
|           20 |     2239 | 2024-12-04 | Tricked Esport                            | W   | 0.610      | 0.435        | 0.034 (0.009)    | 0.687 (0.182)    | -         |    10.59 | adamS, dav1g, mopoz, sausol, stadodo  |
|           19 |     2450 | 2024-12-01 | Tricked Esport                            | W   | 0.590      | 0.371        | 0.034 (0.007)    | 0.687 (0.150)    | -         |    10.80 | adamS, dav1g, mopoz, sausol, stadodo  |
|           18 |     2648 | 2024-11-28 | GUN5 Esports                              | L   | 0.571      | -            | -                | -                | -         |    -6.77 | adamS, dav1g, mopoz, sausol, stadodo  |
|           17 |     2678 | 2024-11-27 | Tricked Esport                            | L   | 0.565      | -            | -                | -                | -         |    -8.26 | adamS, dav1g, mopoz, sausol, stadodo  |
|           16 |     2686 | 2024-11-27 | TEAM NEXT LEVEL                           | W   | 0.564      | 0.333        | 0.040 (0.007)    | -                | -         |     8.95 | adamS, dav1g, mopoz, sausol, stadodo  |
|           15 |     2732 | 2024-11-26 | Tricked Esport                            | W   | 0.559      | 0.333        | 0.034 (0.006)    | 0.687 (0.128)    | -         |     9.65 | adamS, dav1g, mopoz, sausol, stadodo  |
|           14 |     2770 | 2024-11-25 | 9INE                                      | W   | 0.551      | -            | -                | -                | -         |     7.42 | adamS, dav1g, mopoz, sausol, stadodo  |
|           13 |     2879 | 2024-11-23 | ENCE Academy                              | W   | 0.538      | 0.333        | -                | 0.649 (0.116)    | -         |     7.59 | adamS, dav1g, mopoz, sausol, stadodo  |
|           12 |     2982 | 2024-11-22 | JANO Esports                              | W   | 0.531      | 0.333        | 0.022 (0.004)    | -                | -         |    10.47 | adamS, dav1g, mopoz, sausol, stadodo  |
|           11 |     3132 | 2024-11-20 | ENCE Academy                              | L   | 0.518      | -            | -                | -                | -         |    -8.82 | adamS, dav1g, mopoz, sausol, stadodo  |
|           10 |     3256 | 2024-11-17 | Rhyno Esports                             | L   | 0.497      | -            | -                | -                | -         |    -7.02 | adamS, dav1g, deLonge, mopoz, stadodo |
|            9 |     3333 | 2024-11-16 | GOOFYBOYZ                                 | W   | 0.491      | -            | -                | -                | 1 (0.491) |     6.45 | adamS, dav1g, deLonge, mopoz, stadodo |
|            8 |     4292 | 2024-10-30 | ECSTATIC                                  | L   | 0.379      | -            | -                | -                | -         |    -5.13 | adamS, dav1g, JUST, mopoz, stadodo    |
|            7 |     4315 | 2024-10-30 | Illuminar Gaming                          | W   | 0.378      | -            | -                | -                | -         |     6.31 | adamS, dav1g, JUST, mopoz, stadodo    |
|            6 |     4329 | 2024-10-30 | Metizport                                 | L   | 0.378      | -            | -                | -                | -         |    -2.35 | adamS, dav1g, JUST, mopoz, stadodo    |
|            5 |     5628 | 2024-10-05 | Rhyno Esports                             | L   | 0.209      | -            | -                | -                | -         |    -4.57 | adamS, dav1g, JUST, mopoz, stadodo    |
|            4 |     5781 | 2024-10-02 | Natus Vincere Junior                      | L   | 0.191      | -            | -                | -                | -         |    -1.98 | adamS, dav1g, JUST, mopoz, stadodo    |
|            3 |     5856 | 2024-10-01 | Preasy Esport                             | W   | 0.185      | -            | -                | -                | -         |     2.71 | adamS, dav1g, JUST, mopoz, stadodo    |
|            2 |     7510 | 2024-09-06 | Wildcard                                  | L   | 0.018      | -            | -                | -                | -         |    -0.03 | adamS, dav1g, JUST, mopoz, stadodo    |
|            1 |     7632 | 2024-09-05 | The MongolZ                               | L   | 0.010      | -            | -                | -                | -         |    -0.00 | adamS, dav1g, JUST, mopoz, stadodo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,064.98)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-27 |      0.564 | $5,000.00      | $2,819.44       |
| 2024-11-17 |      0.497 | $3,163.39      | $1,573.35       |
| 2024-10-06 |      0.217 | $1,098.17      | $238.09         |
| 2024-09-22 |      0.124 | $3,500.00      | $434.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
