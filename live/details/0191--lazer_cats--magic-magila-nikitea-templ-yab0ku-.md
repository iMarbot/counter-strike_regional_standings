### Roster Details<br />
Team Name: Lazer Cats<br />
Roster: Magic, MAGILA, nikitea, Templ, yab0ku-<br />
Global Rank: [191](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [137]( ../standings_europe.md)<br />
<br />
Final Rank Value:  715.9<br />
<br />
Final Rank Value (715.9) = Starting Rank Value (719.1) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.1
- 400 + ( ( 0.160 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 719.1


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
|           54 |      474 | 2025-02-14 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -17.40 | Magic, MAGILA, nikitea, Templ, yab0ku-  |
|           53 |     1459 | 2024-12-21 | Copenhagen Wolves (American organization) | L   | 0.725      | -            | -                | -                | -         |    -7.14 | Magic, nikitea, remorse, Templ, yab0ku- |
|           52 |     1479 | 2024-12-21 | Dragon Esports Club                       | W   | 0.723      | 0.303        | 0.007 (0.001)    | 0.309 (0.068)    | 0 (0.000) |     9.30 | Magic, nikitea, remorse, Templ, yab0ku- |
|           51 |     1493 | 2024-12-21 | Copenhagen Wolves (American organization) | L   | 0.723      | -            | -                | -                | -         |    -6.66 | Magic, nikitea, remorse, Templ, yab0ku- |
|           50 |     1564 | 2024-12-18 | Monte                                     | L   | 0.705      | -            | -                | -                | -         |    -5.40 | Magic, nikitea, remorse, Templ, yab0ku- |
|           49 |     1577 | 2024-12-17 | KONO.ECF                                  | L   | 0.699      | -            | -                | -                | -         |    -7.70 | Magic, nikitea, remorse, Templ, yab0ku- |
|           48 |     2545 | 2024-11-30 | Nexus Gaming                              | L   | 0.583      | -            | -                | -                | -         |    -2.15 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           47 |     2681 | 2024-11-27 | Partizan Esports                          | L   | 0.565      | -            | -                | -                | -         |    -2.69 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           46 |     2961 | 2024-11-22 | RUSTEC                                    | W   | 0.532      | 0.372        | -                | 0.216 (0.043)    | 0 (0.000) |     4.43 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           45 |     2996 | 2024-11-22 | Hawks (Argentinian team)                  | L   | 0.530      | -            | -                | -                | -         |   -13.49 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           44 |     3024 | 2024-11-21 | FLuffy Gangsters                          | L   | 0.525      | -            | -                | -                | -         |    -6.68 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           43 |     3057 | 2024-11-21 | Team Spirit Academy                       | L   | 0.524      | -            | -                | -                | -         |    -4.41 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           42 |     3096 | 2024-11-20 | QUAZAR                                    | W   | 0.519      | 0.372        | 0.005 (0.001)    | 0.251 (0.048)    | 0 (0.000) |     7.48 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           41 |     3119 | 2024-11-20 | Ins (Polish team)                         | W   | 0.518      | 0.278        | 0.004 (0.001)    | 0.274 (0.039)    | 0 (0.000) |     6.70 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           40 |     3175 | 2024-11-19 | Copenhagen Wolves (American organization) | L   | 0.510      | -            | -                | -                | -         |    -6.09 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           39 |     3214 | 2024-11-18 | Ins (Polish team)                         | W   | 0.505      | 0.278        | 0.004 (0.001)    | -                | 0 (0.000) |     6.53 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           38 |     3240 | 2024-11-17 | Nuclear TigeRES                           | W   | 0.498      | 0.372        | 0.004 (0.001)    | 0.580 (0.108)    | 0 (0.000) |     9.14 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           37 |     3322 | 2024-11-16 | GamerLegion Academy                       | W   | 0.492      | -            | -                | -                | 0 (0.000) |     4.38 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           36 |     3382 | 2024-11-15 | Kay Team                                  | W   | 0.485      | -            | -                | -                | 0 (0.000) |     3.07 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           35 |     3462 | 2024-11-14 | Mission Possible                          | W   | 0.478      | 0.278        | -                | 0.292 (0.039)    | 0 (0.000) |     3.96 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           34 |     3735 | 2024-11-09 | G2 Ares                                   | W   | 0.444      | -            | -                | -                | 0 (0.000) |     6.20 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           33 |     3799 | 2024-11-08 | Leo Team                                  | L   | 0.438      | -            | -                | -                | -         |    -4.96 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           32 |     3844 | 2024-11-07 | UNiTY esports                             | W   | 0.432      | 0.372        | 0.025 (0.004)    | 0.403 (0.065)    | -         |     8.72 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           31 |     3948 | 2024-11-05 | ENCE Prospects                            | W   | 0.418      | -            | -                | -                | -         |     1.76 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           30 |     3994 | 2024-11-04 | PCIFIC Espor                              | L   | 0.412      | -            | -                | -                | -         |    -5.80 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           29 |     4022 | 2024-11-04 | Monte                                     | L   | 0.410      | -            | -                | -                | -         |    -3.64 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           28 |     4097 | 2024-11-03 | GenOne                                    | W   | 0.403      | 0.333        | 0.012 (0.002)    | 0.837 (0.112)    | -         |     8.18 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           27 |     4126 | 2024-11-02 | Poslednii3ae3d                            | W   | 0.398      | -            | -                | -                | -         |     4.61 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           26 |     4268 | 2024-10-31 | Astralis Talent                           | W   | 0.384      | 0.333        | -                | 0.724 (0.093)    | -         |     6.46 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           25 |     4301 | 2024-10-30 | RUSTEC                                    | W   | 0.379      | -            | -                | -                | -         |     5.44 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           24 |     4323 | 2024-10-30 | TEAM NEXT LEVEL                           | W   | 0.378      | 0.333        | 0.040 (0.005)    | 0.500 (0.063)    | -         |     8.26 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           23 |     4590 | 2024-10-25 | Grindas                                   | L   | 0.345      | -            | -                | -                | -         |    -7.98 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           22 |     4637 | 2024-10-24 | 500                                       | L   | 0.337      | -            | -                | -                | -         |    -1.72 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           21 |     4797 | 2024-10-20 | The Suspect                               | L   | 0.311      | -            | -                | -                | -         |    -4.71 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           20 |     5786 | 2024-10-02 | GenOne                                    | L   | 0.191      | -            | -                | -                | -         |    -2.10 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           19 |     6060 | 2024-09-28 | TEAM NEXT LEVEL                           | L   | 0.164      | -            | -                | -                | -         |    -1.69 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           18 |     6164 | 2024-09-27 | ENCE Academy                              | L   | 0.156      | -            | -                | -                | -         |    -1.90 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           17 |     6213 | 2024-09-26 | Astralis Talent                           | L   | 0.151      | -            | -                | -                | -         |    -2.06 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           16 |     6282 | 2024-09-25 | Johnny Speeds                             | W   | 0.145      | 0.143        | 0.039 (0.001)    | -                | -         |     3.31 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           15 |     6401 | 2024-09-24 | Astralis Talent                           | W   | 0.137      | -            | -                | -                | -         |     2.48 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           14 |     6486 | 2024-09-23 | PCIFIC Espor                              | W   | 0.131      | -            | -                | -                | -         |     2.36 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           13 |     6498 | 2024-09-23 | Leo Team                                  | L   | 0.129      | -            | -                | -                | -         |    -1.43 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           12 |     6590 | 2024-09-21 | THE GENTLEMEN ESPORTS                     | L   | 0.118      | -            | -                | -                | -         |    -2.00 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           11 |     6758 | 2024-09-18 | QUAZAR                                    | W   | 0.098      | -            | -                | -                | -         |     1.49 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|           10 |     6907 | 2024-09-16 | Team Kosovo                               | W   | 0.084      | -            | -                | -                | -         |     0.82 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            9 |     6934 | 2024-09-15 | Passion UA                                | L   | 0.078      | -            | -                | -                | -         |    -0.37 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            8 |     6957 | 2024-09-15 | KONO.ECF                                  | W   | 0.076      | 0.143        | 0.046 (0.000)    | -                | -         |     1.81 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            7 |     7061 | 2024-09-14 | FAVBET Team                               | L   | 0.069      | -            | -                | -                | -         |    -0.73 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            6 |     7102 | 2024-09-13 | Infinite Gaming                           | W   | 0.064      | -            | -                | -                | -         |     0.65 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            5 |     7313 | 2024-09-09 | NOM Esports                               | W   | 0.038      | -            | -                | -                | -         |     0.17 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            4 |     7459 | 2024-09-07 | AgenciUSB                                 | W   | 0.023      | -            | -                | -                | -         |     0.11 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            3 |     7470 | 2024-09-07 | Haspers Team                              | W   | 0.023      | -            | -                | -                | -         |     0.24 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            2 |     7493 | 2024-09-07 | 500 Rush                                  | L   | 0.022      | -            | -                | -                | -         |    -0.42 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |
|            1 |     7678 | 2024-09-04 | Lays                                      | W   | 0.005      | -            | -                | -                | -         |     0.02 | 7oX1C, Magic, nikitea, Templ, yab0ku-   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,784.81)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-20 |      0.518 | $1,500.00      | $777.50         |
| 2024-11-10 |      0.452 | $500.00        | $225.76         |
| 2024-11-05 |      0.418 | $1,000.00      | $417.92         |
| 2024-09-29 |      0.172 | $60.74         | $10.42          |
| 2024-09-21 |      0.118 | $2,200.00      | $258.81         |
| 2024-09-15 |      0.078 | $1,208.44      | $94.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
