### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  735.8<br />
<br />
Final Rank Value (735.8) = Starting Rank Value (775.8) + Head To Head Adjustments (-40.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.287[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.188<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.8
- 400 + ( ( 0.188 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 775.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |     1854 | 2024-12-12 | ENCE                                      | L   | 0.663      | -            | -                | -                | -         |    -3.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |     1882 | 2024-12-11 | Fire Flux Esports                         | L   | 0.659      | -            | -                | -                | -         |    -5.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |     1891 | 2024-12-11 | Iberian Soul                              | W   | 0.658      | 0.435        | 0.015 (0.004)    | 0.551 (0.157)    | 0 (0.000) |    14.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |     1928 | 2024-12-10 | JiJieHao                                  | L   | 0.652      | -            | -                | -                | -         |   -12.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |     1962 | 2024-12-09 | CYBERSHOKE Esports                        | W   | 0.645      | 0.435        | 0.011 (0.003)    | 1.000 (0.280)    | 0 (0.000) |    13.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |     2023 | 2024-12-08 | Insilio                                   | L   | 0.637      | -            | -                | -                | -         |   -11.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |     2142 | 2024-12-06 | Wild Lotus                                | L   | 0.624      | -            | -                | -                | -         |    -8.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |     2151 | 2024-12-06 | Illuminar Gaming                          | L   | 0.623      | -            | -                | -                | -         |    -7.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |     2233 | 2024-12-04 | Fire Flux Esports                         | W   | 0.611      | 0.435        | 0.008 (0.002)    | 1.000 (0.266)    | 0 (0.000) |    13.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |     2361 | 2024-12-02 | TSM                                       | L   | 0.597      | -            | -                | -                | -         |    -9.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |     2800 | 2024-11-24 | Fire Flux Esports                         | W   | 0.544      | 0.333        | 0.008 (0.001)    | 1.000 (0.181)    | 0 (0.000) |    12.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |     2890 | 2024-11-23 | PCIFIC Espor                              | W   | 0.538      | -            | -                | -                | 0 (0.000) |     8.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |     2913 | 2024-11-23 | Viperio                                   | L   | 0.537      | -            | -                | -                | -         |    -8.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |     2974 | 2024-11-22 | Nexus Gaming                              | L   | 0.531      | -            | -                | -                | -         |    -1.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |     2985 | 2024-11-22 | Haspers Team                              | L   | 0.531      | -            | -                | -                | -         |    -9.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |     3062 | 2024-11-21 | Astralis Talent                           | L   | 0.523      | -            | -                | -                | -         |    -7.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     3097 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | L   | 0.519      | -            | -                | -                | -         |    -9.58 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     3177 | 2024-11-19 | Illuminar Gaming                          | L   | 0.510      | -            | -                | -                | -         |    -6.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     3195 | 2024-11-18 | CYBERSHOKE Esports                        | L   | 0.505      | -            | -                | -                | -         |    -6.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     3213 | 2024-11-18 | 500                                       | L   | 0.505      | -            | -                | -                | -         |    -3.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     3244 | 2024-11-17 | Reveal (German team)                      | W   | 0.498      | -            | -                | -                | 0 (0.000) |     5.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     3289 | 2024-11-17 | Heimo Esports                             | W   | 0.496      | 0.333        | -                | 0.651 (0.108)    | 0 (0.000) |     6.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     3528 | 2024-11-13 | Astralis Talent                           | L   | 0.469      | -            | -                | -                | -         |    -7.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     3553 | 2024-11-12 | 1win                                      | L   | 0.465      | -            | -                | -                | -         |    -7.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     3650 | 2024-11-10 | TRAXXXMANIA                               | W   | 0.452      | -            | -                | -                | 0 (0.000) |     5.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     3674 | 2024-11-10 | ROYALS                                    | W   | 0.452      | -            | -                | -                | 0 (0.000) |     5.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     3858 | 2024-11-07 | Sashi Esport                              | L   | 0.431      | -            | -                | -                | -         |    -3.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     3889 | 2024-11-06 | XP Academy                                | W   | 0.425      | -            | -                | -                | 0 (0.000) |     3.41 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     3899 | 2024-11-06 | GenOne                                    | L   | 0.425      | -            | -                | -                | -         |    -5.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     3909 | 2024-11-06 | FAVBET Team                               | L   | 0.424      | -            | -                | -                | -         |    -5.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     4071 | 2024-11-03 | Chimera Esports                           | W   | 0.404      | 0.384        | 0.026 (0.004)    | 0.586 (0.091)    | -         |     7.58 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     4151 | 2024-11-02 | 9Pandas                                   | L   | 0.398      | -            | -                | -                | -         |    -2.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     4167 | 2024-11-02 | Rebels Gaming                             | L   | 0.396      | -            | -                | -                | -         |    -7.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     4215 | 2024-11-01 | SINNERS Esports                           | L   | 0.391      | -            | -                | -                | -         |    -4.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     4363 | 2024-10-29 | Johnny Speeds                             | L   | 0.372      | -            | -                | -                | -         |    -4.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     4373 | 2024-10-29 | Rare Atom                                 | W   | 0.372      | 0.333        | 0.063 (0.008)    | 0.578 (0.072)    | -         |     8.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     4385 | 2024-10-29 | Tricked Esport                            | L   | 0.371      | -            | -                | -                | -         |    -4.91 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     4447 | 2024-10-28 | Viperio                                   | W   | 0.365      | -            | -                | -                | -         |     4.68 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     4489 | 2024-10-27 | Rebels Gaming                             | W   | 0.357      | 0.371        | 0.009 (0.001)    | -                | -         |     4.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     4641 | 2024-10-24 | NewBALLS                                  | W   | 0.336      | -            | -                | -                | -         |     3.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     4679 | 2024-10-23 | Permitta Esports                          | W   | 0.331      | 0.372        | 0.013 (0.002)    | 0.487 (0.060)    | -         |     5.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     4688 | 2024-10-23 | Illuminar Gaming                          | W   | 0.330      | 0.372        | -                | 0.581 (0.071)    | -         |     6.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     4748 | 2024-10-21 | KONO.ECF                                  | W   | 0.318      | 0.372        | 0.046 (0.005)    | 0.747 (0.088)    | -         |     6.97 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     4812 | 2024-10-20 | AMKAL ESPORTS                             | L   | 0.310      | -            | -                | -                | -         |    -4.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     5275 | 2024-10-11 | ARCRED                                    | W   | 0.250      | 0.384        | 0.018 (0.002)    | -                | -         |     3.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     6167 | 2024-09-27 | WW Team                                   | L   | 0.156      | -            | -                | -                | -         |    -3.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           11 |     6302 | 2024-09-25 | Aurora Gaming                             | L   | 0.145      | -            | -                | -                | -         |    -2.02 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           10 |     6316 | 2024-09-25 | Copenhagen Wolves (American organization) | L   | 0.143      | -            | -                | -                | -         |    -3.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            9 |     6382 | 2024-09-24 | Wild Lotus                                | L   | 0.138      | -            | -                | -                | -         |    -2.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            8 |     6637 | 2024-09-20 | CYBERSHOKE Esports                        | W   | 0.111      | -            | -                | -                | -         |     2.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            7 |     6769 | 2024-09-18 | Insilio                                   | W   | 0.098      | -            | -                | -                | -         |     1.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            6 |     6910 | 2024-09-16 | FAVBET Team                               | L   | 0.083      | -            | -                | -                | -         |    -1.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            5 |     6956 | 2024-09-15 | Nexus Gaming                              | W   | 0.076      | -            | -                | -                | -         |     0.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            4 |     7297 | 2024-09-09 | Natus Vincere Junior                      | L   | 0.038      | -            | -                | -                | -         |    -0.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            3 |     7434 | 2024-09-07 | Copenhagen Wolves (American organization) | W   | 0.024      | -            | -                | -                | -         |     0.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            2 |     7531 | 2024-09-06 | GamerLegion                               | L   | 0.017      | -            | -                | -                | -         |    -0.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            1 |     7606 | 2024-09-05 | GamerLegion Academy                       | W   | 0.011      | -            | -                | -                | -         |     0.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,867.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $5,000.00      | $2,721.53       |
| 2024-09-21 |      0.117 | $1,250.00      | $146.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
