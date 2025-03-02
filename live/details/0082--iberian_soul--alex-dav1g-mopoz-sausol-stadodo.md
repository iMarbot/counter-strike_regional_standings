### Roster Details<br />
Team Name: Iberian Soul<br />
Roster: alex, dav1g, mopoz, sausol, stadodo<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  877.6<br />
<br />
Final Rank Value (877.6) = Starting Rank Value (836.7) + Head To Head Adjustments (40.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.058[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.7
- 400 + ( ( 0.219 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 836.7


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
|           45 |        1 | 2025-03-01 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.36 | alex, dav1g, mopoz, sausol, stadodo   |
|           44 |        8 | 2025-02-28 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    18.69 | alex, dav1g, mopoz, sausol, stadodo   |
|           43 |       37 | 2025-02-25 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -15.77 | alex, dav1g, mopoz, sausol, stadodo   |
|           42 |       55 | 2025-02-24 | OG                                        | W   | 1.000      | 0.143        | 0.062 (0.009)    | 1.000 (0.143)    | 0 (0.000) |    21.80 | alex, dav1g, mopoz, sausol, stadodo   |
|           41 |       57 | 2025-02-24 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    20.13 | alex, dav1g, mopoz, sausol, stadodo   |
|           40 |      106 | 2025-02-23 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.55 | alex, dav1g, mopoz, sausol, stadodo   |
|           39 |      249 | 2025-02-20 | ECSTATIC                                  | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.828 (0.118)    | 0 (0.000) |    18.19 | alex, dav1g, mopoz, sausol, stadodo   |
|           38 |      261 | 2025-02-19 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |    -8.20 | alex, dav1g, mopoz, sausol, stadodo   |
|           37 |      460 | 2025-02-14 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -19.67 | alex, dav1g, mopoz, sausol, stadodo   |
|           36 |      637 | 2025-02-09 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -12.15 | alex, dav1g, mopoz, sausol, stadodo   |
|           35 |      723 | 2025-02-08 | UNiTY esports                             | W   | 1.000      | 0.143        | 0.025 (0.004)    | -                | 0 (0.000) |    14.67 | alex, dav1g, mopoz, sausol, stadodo   |
|           34 |      774 | 2025-02-07 | Team Novaq                                | L   | 1.000      | -            | -                | -                | -         |    -4.78 | alex, dav1g, mopoz, sausol, stadodo   |
|           33 |      922 | 2025-02-05 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.85 | alex, dav1g, mopoz, sausol, stadodo   |
|           32 |     1003 | 2025-02-04 | UNiTY esports                             | L   | 1.000      | -            | -                | -                | -         |   -16.02 | alex, dav1g, mopoz, sausol, stadodo   |
|           31 |     1134 | 2025-01-25 | ECSTATIC                                  | L   | 0.965      | -            | -                | -                | -         |   -12.99 | alex, dav1g, mopoz, sausol, stadodo   |
|           30 |     1141 | 2025-01-24 | KONO.ECF                                  | L   | 0.959      | -            | -                | -                | -         |   -22.15 | alex, dav1g, mopoz, sausol, stadodo   |
|           29 |     1708 | 2024-12-14 | Chimera Esports                           | L   | 0.685      | -            | -                | -                | -         |    -8.49 | adamS, dav1g, mopoz, sausol, stadodo  |
|           28 |     1810 | 2024-12-13 | GUN5 Esports                              | L   | 0.677      | -            | -                | -                | -         |    -7.83 | adamS, dav1g, mopoz, sausol, stadodo  |
|           27 |     1879 | 2024-12-11 | Endpoint                                  | L   | 0.666      | -            | -                | -                | -         |   -14.46 | adamS, dav1g, mopoz, sausol, stadodo  |
|           26 |     1923 | 2024-12-10 | Team Spirit Academy                       | L   | 0.660      | -            | -                | -                | -         |    -8.63 | adamS, dav1g, mopoz, sausol, stadodo  |
|           25 |     1931 | 2024-12-10 | TSM                                       | W   | 0.658      | -            | -                | -                | 0 (0.000) |     6.99 | adamS, dav1g, mopoz, sausol, stadodo  |
|           24 |     2082 | 2024-12-07 | FAVBET Team                               | W   | 0.639      | 0.435        | 0.032 (0.009)    | 0.814 (0.226)    | -         |    10.44 | adamS, dav1g, mopoz, sausol, stadodo  |
|           23 |     2135 | 2024-12-06 | 9INE                                      | L   | 0.632      | -            | -                | -                | -         |    -9.24 | adamS, dav1g, mopoz, sausol, stadodo  |
|           22 |     2167 | 2024-12-05 | Betclic Apogee Esports                    | W   | 0.625      | 0.371        | 0.012 (0.003)    | 0.515 (0.119)    | -         |    10.07 | adamS, dav1g, mopoz, sausol, stadodo  |
|           21 |     2227 | 2024-12-04 | Tricked Esport                            | W   | 0.618      | 0.435        | 0.033 (0.009)    | 0.696 (0.187)    | -         |    10.75 | adamS, dav1g, mopoz, sausol, stadodo  |
|           20 |     2438 | 2024-12-01 | Tricked Esport                            | W   | 0.598      | 0.371        | 0.033 (0.007)    | 0.696 (0.154)    | -         |    10.97 | adamS, dav1g, mopoz, sausol, stadodo  |
|           19 |     2636 | 2024-11-28 | GUN5 Esports                              | L   | 0.580      | -            | -                | -                | -         |    -6.86 | adamS, dav1g, mopoz, sausol, stadodo  |
|           18 |     2666 | 2024-11-27 | Tricked Esport                            | L   | 0.573      | -            | -                | -                | -         |    -8.36 | adamS, dav1g, mopoz, sausol, stadodo  |
|           17 |     2674 | 2024-11-27 | TEAM NEXT LEVEL                           | W   | 0.572      | 0.333        | 0.039 (0.008)    | -                | -         |     9.08 | adamS, dav1g, mopoz, sausol, stadodo  |
|           16 |     2720 | 2024-11-26 | Tricked Esport                            | W   | 0.567      | 0.333        | 0.033 (0.006)    | 0.696 (0.131)    | -         |     9.82 | adamS, dav1g, mopoz, sausol, stadodo  |
|           15 |     2758 | 2024-11-25 | 9INE                                      | W   | 0.559      | -            | -                | -                | -         |     7.58 | adamS, dav1g, mopoz, sausol, stadodo  |
|           14 |     2867 | 2024-11-23 | ENCE Academy                              | W   | 0.546      | 0.333        | -                | 0.655 (0.119)    | -         |     7.67 | adamS, dav1g, mopoz, sausol, stadodo  |
|           13 |     2970 | 2024-11-22 | JANO Esports                              | W   | 0.539      | 0.333        | 0.022 (0.004)    | -                | -         |    10.60 | adamS, dav1g, mopoz, sausol, stadodo  |
|           12 |     3120 | 2024-11-20 | ENCE Academy                              | L   | 0.526      | -            | -                | -                | -         |    -8.98 | adamS, dav1g, mopoz, sausol, stadodo  |
|           11 |     3244 | 2024-11-17 | Rhyno Esports                             | L   | 0.506      | -            | -                | -                | -         |    -7.10 | adamS, dav1g, deLonge, mopoz, stadodo |
|           10 |     3321 | 2024-11-16 | GOOFYBOYZ                                 | W   | 0.499      | -            | -                | -                | 1 (0.499) |     6.55 | adamS, dav1g, deLonge, mopoz, stadodo |
|            9 |     4280 | 2024-10-30 | ECSTATIC                                  | L   | 0.387      | -            | -                | -                | -         |    -5.23 | adamS, dav1g, JUST, mopoz, stadodo    |
|            8 |     4303 | 2024-10-30 | Illuminar Gaming                          | W   | 0.386      | -            | -                | -                | -         |     6.47 | adamS, dav1g, JUST, mopoz, stadodo    |
|            7 |     4317 | 2024-10-30 | Metizport                                 | L   | 0.386      | -            | -                | -                | -         |    -2.38 | adamS, dav1g, JUST, mopoz, stadodo    |
|            6 |     5616 | 2024-10-05 | Rhyno Esports                             | L   | 0.218      | -            | -                | -                | -         |    -4.74 | adamS, dav1g, JUST, mopoz, stadodo    |
|            5 |     5769 | 2024-10-02 | Natus Vincere Junior                      | L   | 0.200      | -            | -                | -                | -         |    -2.06 | adamS, dav1g, JUST, mopoz, stadodo    |
|            4 |     5844 | 2024-10-01 | Preasy Esport                             | W   | 0.193      | -            | -                | -                | -         |     2.83 | adamS, dav1g, JUST, mopoz, stadodo    |
|            3 |     7498 | 2024-09-06 | Wildcard                                  | L   | 0.026      | -            | -                | -                | -         |    -0.04 | adamS, dav1g, JUST, mopoz, stadodo    |
|            2 |     7620 | 2024-09-05 | The MongolZ                               | L   | 0.018      | -            | -                | -                | -         |    -0.00 | adamS, dav1g, JUST, mopoz, stadodo    |
|            1 |     7722 | 2024-09-03 | G2 Esports                                | L   | 0.006      | -            | -                | -                | -         |    -0.00 | adamS, dav1g, JUST, mopoz, stadodo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,169.55)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-27 |      0.572 | $5,000.00      | $2,860.42       |
| 2024-11-17 |      0.506 | $3,163.39      | $1,599.27       |
| 2024-10-06 |      0.225 | $1,098.17      | $247.09         |
| 2024-09-22 |      0.132 | $3,500.00      | $462.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
