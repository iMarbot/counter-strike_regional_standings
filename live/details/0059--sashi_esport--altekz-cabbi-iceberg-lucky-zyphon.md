### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Altekz, Cabbi, IceBerg, Lucky, Zyphon<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  932.4<br />
<br />
Final Rank Value (932.4) = Starting Rank Value (955.5) + Head To Head Adjustments (-23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.347[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.264[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 955.5
- 400 + ( ( 0.278 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 955.5


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
|           49 |      263 | 2025-02-20 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -11.25 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           48 |      365 | 2025-02-16 | Natus Vincere Junior                      | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.865 (0.376)    | 0 (0.000) |    16.37 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      439 | 2025-02-15 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.446 (0.194)    | 0 (0.000) |    13.89 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      531 | 2025-02-13 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -12.84 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      548 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | 0.016 (0.007)    | 1.000 (0.435)    | 0 (0.000) |    14.09 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      596 | 2025-02-10 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -14.99 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      650 | 2025-02-09 | OG                                        | W   | 1.000      | 0.435        | 0.062 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    17.72 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      785 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 1.000      | -            | -                | -                | -         |   -23.48 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |      793 | 2025-02-07 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.70 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |      917 | 2025-02-05 | 9INE                                      | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.837 (0.364)    | 0 (0.000) |    16.55 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |     1004 | 2025-02-04 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -14.81 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |     1024 | 2025-02-03 | Monte                                     | L   | 1.000      | -            | -                | -                | -         |   -16.53 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |     1053 | 2025-02-02 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -8.64 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           36 |     1660 | 2024-12-15 | Chimera Esports                           | L   | 0.683      | -            | -                | -                | -         |   -11.31 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           35 |     1733 | 2024-12-14 | 9INE                                      | W   | 0.676      | 0.371        | 0.037 (0.009)    | 0.837 (0.210)    | 0 (0.000) |     9.60 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           34 |     1810 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.670      | -            | -                | -                | -         |    -8.92 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           33 |     1902 | 2024-12-11 | Chimera Esports                           | W   | 0.657      | 0.371        | -                | 0.586 (0.143)    | 0 (0.000) |     9.41 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           32 |     1922 | 2024-12-10 | GUN5 Esports                              | L   | 0.652      | -            | -                | -                | -         |   -10.41 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           31 |     1959 | 2024-12-09 | Aurora Gaming                             | L   | 0.645      | -            | -                | -                | -         |   -13.93 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           30 |     2104 | 2024-12-07 | Alliance                                  | W   | 0.630      | 0.371        | -                | 0.570 (0.133)    | -         |     7.40 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           29 |     2299 | 2024-12-03 | 9INE                                      | W   | 0.603      | 0.371        | 0.037 (0.008)    | 0.837 (0.187)    | -         |     7.72 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           28 |     2826 | 2024-11-24 | Team Spirit                               | L   | 0.542      | -            | -                | -                | -         |    -0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     2932 | 2024-11-22 | Virtus.pro                                | L   | 0.535      | -            | -                | -                | -         |    -0.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3013 | 2024-11-21 | Eternal Fire                              | W   | 0.528      | 0.143        | 0.599 (0.045)    | -                | 1 (0.528) |    16.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3061 | 2024-11-21 | Astralis                                  | W   | 0.524      | 0.143        | 0.619 (0.046)    | -                | 1 (0.524) |    16.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3074 | 2024-11-20 | BIG                                       | L   | 0.522      | -            | -                | -                | -         |    -0.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3750 | 2024-11-09 | Dynamo Eclot                              | L   | 0.444      | -            | -                | -                | -         |    -4.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3822 | 2024-11-08 | 500                                       | L   | 0.436      | -            | -                | -                | -         |    -5.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3858 | 2024-11-07 | Endpoint                                  | W   | 0.431      | -            | -                | -                | -         |     3.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3862 | 2024-11-07 | OG                                        | W   | 0.430      | 0.384        | 0.062 (0.010)    | 1.000 (0.165)    | -         |     6.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3965 | 2024-11-05 | Rebels Gaming                             | W   | 0.417      | -            | -                | -                | -         |     3.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     4156 | 2024-11-02 | Wild Lotus                                | L   | 0.397      | -            | -                | -                | -         |    -8.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     4196 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.392      | -            | -                | -                | -         |    -8.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     4200 | 2024-11-01 | Insilio                                   | L   | 0.392      | -            | -                | -                | -         |   -10.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4222 | 2024-11-01 | Los kogutos                               | W   | 0.390      | -            | -                | -                | -         |     5.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4399 | 2024-10-29 | GUN5 Esports                              | L   | 0.369      | -            | -                | -                | -         |    -6.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4638 | 2024-10-24 | Dynamo Eclot                              | W   | 0.337      | -            | -                | -                | -         |     1.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4940 | 2024-10-17 | 3DMAX                                     | L   | 0.291      | -            | -                | -                | -         |    -0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4998 | 2024-10-16 | PARIVISION                                | W   | 0.285      | -            | -                | -                | -         |     2.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     5070 | 2024-10-15 | HEROIC                                    | L   | 0.278      | -            | -                | -                | -         |    -2.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     5247 | 2024-10-12 | Fire Flux Esports                         | W   | 0.256      | -            | -                | -                | -         |     3.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     6722 | 2024-09-19 | Monte                                     | L   | 0.103      | -            | -                | -                | -         |    -2.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     6847 | 2024-09-17 | BC.Game Esports                           | L   | 0.091      | -            | -                | -                | -         |    -1.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     6854 | 2024-09-17 | Wild Lotus                                | L   | 0.090      | -            | -                | -                | -         |    -2.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     6866 | 2024-09-17 | BC.Game Esports                           | W   | 0.089      | -            | -                | -                | -         |     1.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     6998 | 2024-09-14 | Rebels Gaming                             | L   | 0.071      | -            | -                | -                | -         |    -1.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     7028 | 2024-09-14 | OG                                        | W   | 0.070      | -            | -                | -                | -         |     0.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     7152 | 2024-09-12 | TSM                                       | W   | 0.057      | -            | -                | -                | -         |     0.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     7271 | 2024-09-10 | GamerLegion                               | W   | 0.043      | -            | -                | -                | -         |     0.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,356.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.696 | $1,000.00      | $695.97         |
| 2024-11-10 |      0.452 | $2,500.00      | $1,129.51       |
| 2024-10-20 |      0.311 | $7,000.00      | $2,174.86       |
| 2024-09-14 |      0.071 | $5,000.00      | $356.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
