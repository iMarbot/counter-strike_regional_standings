### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Altekz, Cabbi, IceBerg, Lucky, Zyphon<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.9<br />
<br />
Final Rank Value (933.9) = Starting Rank Value (956.9) + Head To Head Adjustments (-23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.9
- 400 + ( ( 0.279 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 956.9


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
|           50 |      251 | 2025-02-20 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -11.21 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           49 |      353 | 2025-02-16 | Natus Vincere Junior                      | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.878 (0.381)    | 0 (0.000) |    16.40 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           48 |      427 | 2025-02-15 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.451 (0.196)    | 0 (0.000) |    13.90 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      519 | 2025-02-13 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -12.77 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      536 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | 0.016 (0.007)    | 1.000 (0.435)    | 0 (0.000) |    14.09 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      584 | 2025-02-10 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -15.00 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      638 | 2025-02-09 | OG                                        | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    17.71 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      773 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 1.000      | -            | -                | -                | -         |   -23.51 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      781 | 2025-02-07 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.67 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |      905 | 2025-02-05 | 9INE                                      | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.839 (0.364)    | 0 (0.000) |    16.55 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |      992 | 2025-02-04 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -14.79 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |     1012 | 2025-02-03 | Monte                                     | L   | 1.000      | -            | -                | -                | -         |   -16.48 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |     1041 | 2025-02-02 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -8.62 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |     1648 | 2024-12-15 | Chimera Esports                           | L   | 0.691      | -            | -                | -                | -         |   -11.39 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           36 |     1721 | 2024-12-14 | 9INE                                      | W   | 0.684      | 0.371        | 0.037 (0.009)    | 0.839 (0.213)    | 0 (0.000) |     9.72 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           35 |     1798 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.678      | -            | -                | -                | -         |    -8.99 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           34 |     1890 | 2024-12-11 | Chimera Esports                           | W   | 0.665      | 0.371        | -                | 0.595 (0.146)    | 0 (0.000) |     9.57 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           33 |     1910 | 2024-12-10 | GUN5 Esports                              | L   | 0.660      | -            | -                | -                | -         |   -10.52 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           32 |     1947 | 2024-12-09 | Aurora Gaming                             | L   | 0.653      | -            | -                | -                | -         |   -14.10 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           31 |     2092 | 2024-12-07 | Alliance                                  | W   | 0.638      | 0.371        | -                | 0.573 (0.136)    | -         |     7.48 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           30 |     2287 | 2024-12-03 | 9INE                                      | W   | 0.611      | 0.371        | 0.037 (0.008)    | 0.839 (0.190)    | -         |     7.82 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           29 |     2814 | 2024-11-24 | Team Spirit                               | L   | 0.551      | -            | -                | -                | -         |    -0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     2920 | 2024-11-22 | Virtus.pro                                | L   | 0.543      | -            | -                | -                | -         |    -0.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     3001 | 2024-11-21 | Eternal Fire                              | W   | 0.536      | 0.143        | 0.591 (0.045)    | -                | 1 (0.536) |    16.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3049 | 2024-11-21 | Astralis                                  | W   | 0.532      | 0.143        | 0.609 (0.046)    | -                | 1 (0.532) |    16.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3062 | 2024-11-20 | BIG                                       | L   | 0.530      | -            | -                | -                | -         |    -0.77 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3738 | 2024-11-09 | Dynamo Eclot                              | L   | 0.452      | -            | -                | -                | -         |    -4.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3810 | 2024-11-08 | 500                                       | L   | 0.444      | -            | -                | -                | -         |    -5.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3846 | 2024-11-07 | Endpoint                                  | W   | 0.439      | -            | -                | -                | -         |     4.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3850 | 2024-11-07 | OG                                        | W   | 0.439      | 0.384        | 0.062 (0.010)    | 1.000 (0.169)    | -         |     6.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3953 | 2024-11-05 | Rebels Gaming                             | W   | 0.425      | -            | -                | -                | -         |     3.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     4144 | 2024-11-02 | Wild Lotus                                | L   | 0.405      | -            | -                | -                | -         |    -8.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     4184 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.400      | -            | -                | -                | -         |    -8.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     4188 | 2024-11-01 | Insilio                                   | L   | 0.400      | -            | -                | -                | -         |   -10.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     4210 | 2024-11-01 | Los kogutos                               | W   | 0.398      | -            | -                | -                | -         |     5.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4387 | 2024-10-29 | GUN5 Esports                              | L   | 0.378      | -            | -                | -                | -         |    -6.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4626 | 2024-10-24 | Dynamo Eclot                              | W   | 0.345      | -            | -                | -                | -         |     1.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4928 | 2024-10-17 | 3DMAX                                     | L   | 0.299      | -            | -                | -                | -         |    -0.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4986 | 2024-10-16 | PARIVISION                                | W   | 0.293      | -            | -                | -                | -         |     2.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     5058 | 2024-10-15 | HEROIC                                    | L   | 0.286      | -            | -                | -                | -         |    -3.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     5235 | 2024-10-12 | Fire Flux Esports                         | W   | 0.264      | -            | -                | -                | -         |     3.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     6710 | 2024-09-19 | Monte                                     | L   | 0.111      | -            | -                | -                | -         |    -2.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     6835 | 2024-09-17 | BC.Game Esports                           | L   | 0.099      | -            | -                | -                | -         |    -1.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     6842 | 2024-09-17 | Wild Lotus                                | L   | 0.098      | -            | -                | -                | -         |    -2.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     6854 | 2024-09-17 | BC.Game Esports                           | W   | 0.098      | -            | -                | -                | -         |     1.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     6986 | 2024-09-14 | Rebels Gaming                             | L   | 0.079      | -            | -                | -                | -         |    -1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     7016 | 2024-09-14 | OG                                        | W   | 0.078      | -            | -                | -                | -         |     1.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     7140 | 2024-09-12 | TSM                                       | W   | 0.065      | -            | -                | -                | -         |     0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     7259 | 2024-09-10 | GamerLegion                               | W   | 0.051      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     7750 | 2024-09-03 | Nemiga Gaming                             | L   | 0.004      | -            | -                | -                | -         |    -0.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,483.61)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.704 | $1,000.00      | $704.17         |
| 2024-11-10 |      0.460 | $2,500.00      | $1,150.00       |
| 2024-10-20 |      0.319 | $7,000.00      | $2,232.22       |
| 2024-09-14 |      0.079 | $5,000.00      | $397.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
