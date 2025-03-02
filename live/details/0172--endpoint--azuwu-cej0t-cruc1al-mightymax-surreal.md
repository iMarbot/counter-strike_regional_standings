### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [127]( ../standings_europe.md)<br />
<br />
Final Rank Value:  736.8<br />
<br />
Final Rank Value (736.8) = Starting Rank Value (776.9) + Head To Head Adjustments (-40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.288[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.9
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 776.9


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
|           58 |     1842 | 2024-12-12 | ENCE                                      | L   | 0.672      | -            | -                | -                | -         |    -3.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           57 |     1870 | 2024-12-11 | Fire Flux Esports                         | L   | 0.667      | -            | -                | -                | -         |    -5.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |     1879 | 2024-12-11 | Iberian Soul                              | W   | 0.666      | 0.435        | 0.015 (0.004)    | 0.553 (0.160)    | 0 (0.000) |    14.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |     1916 | 2024-12-10 | JiJieHao                                  | L   | 0.660      | -            | -                | -                | -         |   -12.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |     1950 | 2024-12-09 | CYBERSHOKE Esports                        | W   | 0.653      | 0.435        | 0.011 (0.003)    | 1.000 (0.284)    | 0 (0.000) |    13.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |     2011 | 2024-12-08 | Insilio                                   | L   | 0.645      | -            | -                | -                | -         |   -11.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |     2130 | 2024-12-06 | Wild Lotus                                | L   | 0.633      | -            | -                | -                | -         |    -8.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |     2139 | 2024-12-06 | Illuminar Gaming                          | L   | 0.631      | -            | -                | -                | -         |    -8.02 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |     2221 | 2024-12-04 | Fire Flux Esports                         | W   | 0.619      | 0.435        | 0.008 (0.002)    | 1.000 (0.269)    | 0 (0.000) |    14.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |     2349 | 2024-12-02 | TSM                                       | L   | 0.605      | -            | -                | -                | -         |    -9.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |     2788 | 2024-11-24 | Fire Flux Esports                         | W   | 0.552      | 0.333        | 0.008 (0.001)    | 1.000 (0.184)    | 0 (0.000) |    13.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |     2878 | 2024-11-23 | PCIFIC Espor                              | W   | 0.546      | -            | -                | -                | 0 (0.000) |     8.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |     2901 | 2024-11-23 | Viperio                                   | L   | 0.545      | -            | -                | -                | -         |    -8.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |     2962 | 2024-11-22 | Nexus Gaming                              | L   | 0.540      | -            | -                | -                | -         |    -1.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |     2973 | 2024-11-22 | Haspers Team                              | L   | 0.539      | -            | -                | -                | -         |    -9.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |     3050 | 2024-11-21 | Astralis Talent                           | L   | 0.532      | -            | -                | -                | -         |    -7.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |     3085 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | L   | 0.527      | -            | -                | -                | -         |    -9.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     3165 | 2024-11-19 | Illuminar Gaming                          | L   | 0.518      | -            | -                | -                | -         |    -6.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     3183 | 2024-11-18 | CYBERSHOKE Esports                        | L   | 0.514      | -            | -                | -                | -         |    -6.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     3201 | 2024-11-18 | 500                                       | L   | 0.513      | -            | -                | -                | -         |    -3.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     3232 | 2024-11-17 | Reveal (German team)                      | W   | 0.506      | -            | -                | -                | 0 (0.000) |     5.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     3277 | 2024-11-17 | Heimo Esports                             | W   | 0.504      | 0.333        | -                | 0.658 (0.111)    | 0 (0.000) |     6.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     3516 | 2024-11-13 | Astralis Talent                           | L   | 0.477      | -            | -                | -                | -         |    -7.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     3541 | 2024-11-12 | 1win                                      | L   | 0.473      | -            | -                | -                | -         |    -7.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     3638 | 2024-11-10 | TRAXXXMANIA                               | W   | 0.461      | -            | -                | -                | 0 (0.000) |     5.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     3662 | 2024-11-10 | ROYALS                                    | W   | 0.460      | -            | -                | -                | 0 (0.000) |     5.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     3846 | 2024-11-07 | Sashi Esport                              | L   | 0.439      | -            | -                | -                | -         |    -4.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     3877 | 2024-11-06 | XP Academy                                | W   | 0.433      | -            | -                | -                | 0 (0.000) |     3.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     3887 | 2024-11-06 | GenOne                                    | L   | 0.433      | -            | -                | -                | -         |    -5.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     3897 | 2024-11-06 | FAVBET Team                               | L   | 0.432      | -            | -                | -                | -         |    -5.43 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     4059 | 2024-11-03 | Chimera Esports                           | W   | 0.412      | 0.384        | 0.025 (0.004)    | 0.595 (0.094)    | -         |     7.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     4139 | 2024-11-02 | 9Pandas                                   | L   | 0.406      | -            | -                | -                | -         |    -2.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     4155 | 2024-11-02 | Rebels Gaming                             | L   | 0.404      | -            | -                | -                | -         |    -7.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     4203 | 2024-11-01 | SINNERS Esports                           | L   | 0.399      | -            | -                | -                | -         |    -4.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     4351 | 2024-10-29 | Johnny Speeds                             | L   | 0.381      | -            | -                | -                | -         |    -4.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     4361 | 2024-10-29 | Rare Atom                                 | W   | 0.380      | 0.333        | 0.063 (0.008)    | 0.581 (0.073)    | -         |     8.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     4373 | 2024-10-29 | Tricked Esport                            | L   | 0.379      | -            | -                | -                | -         |    -5.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     4435 | 2024-10-28 | Viperio                                   | W   | 0.373      | -            | -                | -                | -         |     4.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     4477 | 2024-10-27 | Rebels Gaming                             | W   | 0.365      | 0.371        | 0.009 (0.001)    | -                | -         |     4.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     4629 | 2024-10-24 | NewBALLS                                  | W   | 0.344      | -            | -                | -                | -         |     3.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     4667 | 2024-10-23 | Permitta Esports                          | W   | 0.339      | 0.372        | 0.013 (0.002)    | 0.494 (0.062)    | -         |     5.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     4676 | 2024-10-23 | Illuminar Gaming                          | W   | 0.339      | 0.372        | -                | 0.593 (0.075)    | -         |     6.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     4736 | 2024-10-21 | KONO.ECF                                  | W   | 0.326      | 0.372        | 0.045 (0.006)    | 0.757 (0.092)    | -         |     7.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     4800 | 2024-10-20 | AMKAL ESPORTS                             | L   | 0.319      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     5263 | 2024-10-11 | ARCRED                                    | W   | 0.259      | 0.384        | 0.018 (0.002)    | -                | -         |     3.89 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     6155 | 2024-09-27 | WW Team                                   | L   | 0.164      | -            | -                | -                | -         |    -4.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     6290 | 2024-09-25 | Aurora Gaming                             | L   | 0.153      | -            | -                | -                | -         |    -2.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           11 |     6304 | 2024-09-25 | Copenhagen Wolves (American organization) | L   | 0.151      | -            | -                | -                | -         |    -3.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           10 |     6370 | 2024-09-24 | Wild Lotus                                | L   | 0.146      | -            | -                | -                | -         |    -2.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            9 |     6625 | 2024-09-20 | CYBERSHOKE Esports                        | W   | 0.120      | -            | -                | -                | -         |     2.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            8 |     6757 | 2024-09-18 | Insilio                                   | W   | 0.106      | -            | -                | -                | -         |     1.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            7 |     6898 | 2024-09-16 | FAVBET Team                               | L   | 0.092      | -            | -                | -                | -         |    -1.17 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            6 |     6944 | 2024-09-15 | Nexus Gaming                              | W   | 0.085      | -            | -                | -                | -         |     0.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            5 |     7285 | 2024-09-09 | Natus Vincere Junior                      | L   | 0.047      | -            | -                | -                | -         |    -0.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            4 |     7422 | 2024-09-07 | Copenhagen Wolves (American organization) | W   | 0.032      | -            | -                | -                | -         |     0.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            3 |     7519 | 2024-09-06 | GamerLegion                               | L   | 0.026      | -            | -                | -                | -         |    -0.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            2 |     7594 | 2024-09-05 | GamerLegion Academy                       | W   | 0.019      | -            | -                | -                | -         |     0.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|            1 |     7731 | 2024-09-03 | Dark Cloud Esports                        | W   | 0.006      | -            | -                | -                | -         |     0.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,918.75)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $5,000.00      | $2,762.50       |
| 2024-09-21 |      0.125 | $1,250.00      | $156.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
