### Roster Details<br />
Team Name: Lazer Cats<br />
Roster: Magic, MAGILA, nikitea, Templ, yab0ku-<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [137]( ../standings_europe.md)<br />
<br />
Final Rank Value:  717.4<br />
<br />
Final Rank Value (717.4) = Starting Rank Value (720.2) + Head To Head Adjustments (-2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 720.2
- 400 + ( ( 0.160 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 720.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |      462 | 2025-02-14 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -17.43 | Magic, MAGILA, nikitea, Templ, yab0ku-  |
|           53 |     1447 | 2024-12-21 | Copenhagen Wolves (American organization) | L   | 0.733      | -            | -                | -                | -         |    -7.22 | Magic, nikitea, remorse, Templ, yab0ku- |
|           52 |     1467 | 2024-12-21 | Dragon Esports Club                       | W   | 0.732      | 0.303        | 0.007 (0.001)    | 0.312 (0.069)    | 0 (0.000) |     9.36 | Magic, nikitea, remorse, Templ, yab0ku- |
|           51 |     1481 | 2024-12-21 | Copenhagen Wolves (American organization) | L   | 0.731      | -            | -                | -                | -         |    -6.72 | Magic, nikitea, remorse, Templ, yab0ku- |
|           50 |     1552 | 2024-12-18 | Monte                                     | L   | 0.713      | -            | -                | -                | -         |    -5.43 | Magic, nikitea, remorse, Templ, yab0ku- |
|           49 |     1565 | 2024-12-17 | KONO.ECF                                  | L   | 0.707      | -            | -                | -                | -         |    -7.79 | Magic, nikitea, remorse, Templ, yab0ku- |
|           48 |     2533 | 2024-11-30 | Nexus Gaming                              | L   | 0.592      | -            | -                | -                | -         |    -2.19 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           47 |     2669 | 2024-11-27 | Partizan Esports                          | L   | 0.573      | -            | -                | -                | -         |    -2.73 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           46 |     2949 | 2024-11-22 | RUSTEC                                    | W   | 0.540      | 0.372        | -                | 0.217 (0.044)    | 0 (0.000) |     4.49 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           45 |     2984 | 2024-11-22 | Hawks (Argentinian team)                  | L   | 0.538      | -            | -                | -                | -         |   -13.72 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           44 |     3012 | 2024-11-21 | FLuffy Gangsters                          | L   | 0.533      | -            | -                | -                | -         |    -6.78 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           43 |     3045 | 2024-11-21 | Team Spirit Academy                       | L   | 0.532      | -            | -                | -                | -         |    -4.46 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           42 |     3084 | 2024-11-20 | QUAZAR                                    | W   | 0.527      | 0.372        | 0.005 (0.001)    | 0.257 (0.051)    | 0 (0.000) |     7.59 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           41 |     3107 | 2024-11-20 | Ins (Polish team)                         | W   | 0.527      | 0.278        | 0.004 (0.001)    | 0.280 (0.041)    | 0 (0.000) |     6.79 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           40 |     3163 | 2024-11-19 | Copenhagen Wolves (American organization) | L   | 0.518      | -            | -                | -                | -         |    -6.21 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           39 |     3202 | 2024-11-18 | Ins (Polish team)                         | W   | 0.513      | 0.278        | 0.004 (0.001)    | 0.280 (0.040)    | 0 (0.000) |     6.61 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           38 |     3228 | 2024-11-17 | Nuclear TigeRES                           | W   | 0.507      | 0.372        | 0.004 (0.001)    | 0.586 (0.111)    | 0 (0.000) |     9.24 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           37 |     3310 | 2024-11-16 | GamerLegion Academy                       | W   | 0.500      | -            | -                | -                | 0 (0.000) |     4.46 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           36 |     3370 | 2024-11-15 | Kay Team                                  | W   | 0.494      | -            | -                | -                | 0 (0.000) |     3.11 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           35 |     3450 | 2024-11-14 | Mission Possible                          | W   | 0.486      | -            | -                | -                | 0 (0.000) |     4.02 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           34 |     3723 | 2024-11-09 | G2 Ares                                   | W   | 0.453      | -            | -                | -                | 0 (0.000) |     6.30 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           33 |     3787 | 2024-11-08 | Leo Team                                  | L   | 0.447      | -            | -                | -                | -         |    -5.05 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           32 |     3832 | 2024-11-07 | UNiTY esports                             | W   | 0.440      | 0.372        | 0.025 (0.004)    | 0.412 (0.068)    | -         |     8.91 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           31 |     3936 | 2024-11-05 | ENCE Prospects                            | W   | 0.427      | -            | -                | -                | -         |     1.78 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           30 |     3982 | 2024-11-04 | PCIFIC Espor                              | L   | 0.420      | -            | -                | -                | -         |    -5.93 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           29 |     4010 | 2024-11-04 | Monte                                     | L   | 0.418      | -            | -                | -                | -         |    -3.71 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           28 |     4085 | 2024-11-03 | GenOne                                    | W   | 0.411      | 0.333        | 0.012 (0.002)    | 0.848 (0.116)    | -         |     8.36 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           27 |     4114 | 2024-11-02 | Poslednii3ae3d                            | W   | 0.407      | -            | -                | -                | -         |     4.68 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           26 |     4256 | 2024-10-31 | Astralis Talent                           | W   | 0.392      | 0.333        | -                | 0.733 (0.096)    | -         |     6.58 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           25 |     4289 | 2024-10-30 | RUSTEC                                    | W   | 0.387      | -            | -                | -                | -         |     5.54 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           24 |     4311 | 2024-10-30 | TEAM NEXT LEVEL                           | W   | 0.386      | 0.333        | 0.039 (0.005)    | 0.508 (0.065)    | -         |     8.44 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           23 |     4578 | 2024-10-25 | Grindas                                   | L   | 0.353      | -            | -                | -                | -         |    -8.18 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           22 |     4625 | 2024-10-24 | 500                                       | L   | 0.345      | -            | -                | -                | -         |    -1.78 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           21 |     4785 | 2024-10-20 | The Suspect                               | L   | 0.319      | -            | -                | -                | -         |    -4.83 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           20 |     5774 | 2024-10-02 | GenOne                                    | L   | 0.199      | -            | -                | -                | -         |    -2.18 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           19 |     6048 | 2024-09-28 | TEAM NEXT LEVEL                           | L   | 0.172      | -            | -                | -                | -         |    -1.77 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           18 |     6152 | 2024-09-27 | ENCE Academy                              | L   | 0.164      | -            | -                | -                | -         |    -2.01 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           17 |     6201 | 2024-09-26 | Astralis Talent                           | L   | 0.159      | -            | -                | -                | -         |    -2.18 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           16 |     6270 | 2024-09-25 | Johnny Speeds                             | W   | 0.154      | 0.143        | 0.039 (0.001)    | -                | -         |     3.50 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           15 |     6389 | 2024-09-24 | Astralis Talent                           | W   | 0.146      | -            | -                | -                | -         |     2.63 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           14 |     6474 | 2024-09-23 | PCIFIC Espor                              | W   | 0.139      | -            | -                | -                | -         |     2.51 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           13 |     6486 | 2024-09-23 | Leo Team                                  | L   | 0.138      | -            | -                | -                | -         |    -1.52 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           12 |     6578 | 2024-09-21 | THE GENTLEMEN ESPORTS                     | L   | 0.126      | -            | -                | -                | -         |    -2.14 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           11 |     6746 | 2024-09-18 | QUAZAR                                    | W   | 0.107      | -            | -                | -                | -         |     1.62 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           10 |     6895 | 2024-09-16 | Team Kosovo                               | W   | 0.092      | -            | -                | -                | -         |     0.90 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            9 |     6922 | 2024-09-15 | Passion UA                                | L   | 0.086      | -            | -                | -                | -         |    -0.41 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            8 |     6945 | 2024-09-15 | KONO.ECF                                  | W   | 0.085      | 0.143        | 0.045 (0.001)    | -                | -         |     2.01 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            7 |     7049 | 2024-09-14 | FAVBET Team                               | L   | 0.077      | -            | -                | -                | -         |    -0.82 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            6 |     7090 | 2024-09-13 | Infinite Gaming                           | W   | 0.072      | -            | -                | -                | -         |     0.73 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            5 |     7301 | 2024-09-09 | NOM Esports                               | W   | 0.046      | -            | -                | -                | -         |     0.21 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            4 |     7447 | 2024-09-07 | AgenciUSB                                 | W   | 0.032      | -            | -                | -                | -         |     0.14 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            3 |     7458 | 2024-09-07 | Haspers Team                              | W   | 0.031      | -            | -                | -                | -         |     0.33 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            2 |     7481 | 2024-09-07 | 500 Rush                                  | L   | 0.030      | -            | -                | -                | -         |    -0.58 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            1 |     7666 | 2024-09-04 | Lays                                      | W   | 0.013      | -            | -                | -                | -         |     0.06 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,837.83)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-20 |      0.527 | $1,500.00      | $789.79         |
| 2024-11-10 |      0.460 | $500.00        | $229.86         |
| 2024-11-05 |      0.426 | $1,000.00      | $426.11         |
| 2024-09-29 |      0.180 | $60.74         | $10.92          |
| 2024-09-21 |      0.126 | $2,200.00      | $276.83         |
| 2024-09-15 |      0.086 | $1,208.44      | $104.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
