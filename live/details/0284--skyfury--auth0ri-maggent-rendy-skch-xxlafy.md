### Roster Details<br />
Team Name: SkyFury<br />
Roster: auth0ri, Maggent, rendY, skcH, xxlafy<br />
Global Rank: [284](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [194]( ../standings_europe.md)<br />
<br />
Final Rank Value:  659.2<br />
<br />
Final Rank Value (659.2) = Starting Rank Value (684.1) + Head To Head Adjustments (-24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.1
- 400 + ( ( 0.142 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 684.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1347 | 2024-12-26 | VOLT (European team)            | L   | 0.766      | -            | -                | -                | -         |   -10.42 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           25 |     1378 | 2024-12-23 | Infinite Gaming                 | W   | 0.744      | 0.333        | 0.000 (0.000)    | 0.059 (0.015)    | 0 (0.000) |     6.92 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           24 |     1400 | 2024-12-22 | C.S.D.E                         | L   | 0.739      | -            | -                | -                | -         |   -10.98 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           23 |     1411 | 2024-12-22 | Dragon Esports Club             | L   | 0.738      | -            | -                | -                | -         |   -11.58 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           22 |     1417 | 2024-12-22 | ROYALS                          | W   | 0.738      | 0.333        | 0.004 (0.001)    | 0.205 (0.050)    | 0 (0.000) |    11.64 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           21 |     1465 | 2024-12-21 | Fragmatic                       | W   | 0.732      | 0.143        | 0.000 (0.000)    | 0.069 (0.007)    | 0 (0.000) |     7.83 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           20 |     1479 | 2024-12-21 | CourageG                        | W   | 0.731      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.26 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           19 |     1519 | 2024-12-20 | VOLT (European team)            | L   | 0.725      | -            | -                | -                | -         |   -10.04 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           18 |     1531 | 2024-12-19 | NEVERMORE (Ukrainian team)      | W   | 0.720      | 0.303        | 0.010 (0.002)    | 0.911 (0.199)    | 0 (0.000) |    16.62 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           17 |     1560 | 2024-12-18 | Venom (Swedish team)            | W   | 0.711      | 0.303        | -                | 0.063 (0.014)    | 0 (0.000) |     6.70 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           16 |     1570 | 2024-12-17 | PLUSH                           | W   | 0.706      | -            | -                | -                | 0 (0.000) |     4.39 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           15 |     1644 | 2024-12-15 | Venom (Swedish team)            | L   | 0.691      | -            | -                | -                | -         |   -15.39 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           14 |     2126 | 2024-12-06 | C.S.D.E                         | L   | 0.633      | -            | -                | -                | -         |    -9.31 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           13 |     2327 | 2024-12-02 | Cerberus eSports (Russian team) | L   | 0.607      | -            | -                | -                | -         |   -11.78 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           12 |     2442 | 2024-12-01 | ROYALS                          | L   | 0.598      | -            | -                | -                | -         |    -9.17 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           11 |     2481 | 2024-11-30 | Rhyno Youngsters                | W   | 0.594      | 0.333        | 0.003 (0.001)    | 0.121 (0.024)    | 0 (0.000) |    10.20 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           10 |     2599 | 2024-11-29 | Dark Cloud Esports              | L   | 0.584      | -            | -                | -                | -         |    -5.02 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            9 |     2714 | 2024-11-26 | ALTERNATE aTTaX Evo             | W   | 0.567      | 0.333        | 0.001 (0.000)    | 0.184 (0.035)    | 0 (0.000) |     7.58 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            8 |     3017 | 2024-11-21 | Hypewrld                        | L   | 0.533      | -            | -                | -                | -         |    -7.16 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            7 |     3099 | 2024-11-20 | DEPO                            | L   | 0.527      | -            | -                | -                | -         |    -6.41 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            6 |     3104 | 2024-11-20 | KZ Esports                      | W   | 0.527      | 0.284        | 0.009 (0.001)    | 0.114 (0.017)    | 0 (0.000) |     8.64 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            5 |     4460 | 2024-10-27 | C.S.D.E                         | L   | 0.366      | -            | -                | -                | -         |    -5.85 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            4 |     4473 | 2024-10-27 | Podpivasi                       | W   | 0.365      | 0.143        | 0.000 (0.000)    | -                | -         |     2.98 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            3 |     5982 | 2024-09-29 | Leo Team                        | L   | 0.177      | -            | -                | -                | -         |    -1.69 | Maggent, rendY, skcH, svemyy, Зippoch |
|            2 |     6082 | 2024-09-28 | TEAM NEXT LEVEL                 | W   | 0.170      | 0.143        | 0.003 (0.000)    | 0.465 (0.011)    | -         |     2.80 | Maggent, rendY, skcH, svemyy, Зippoch |
|            1 |     7008 | 2024-09-14 | TEAM NEXT LEVEL                 | L   | 0.079      | -            | -                | -                | -         |    -0.70 | Maggent, rendY, skcH, svemyy, Зippoch |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,460.02)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $167.58        | $123.93         |
| 2024-12-21 |      0.731 | $500.00        | $365.42         |
| 2024-12-17 |      0.706 | $1,197.67      | $845.86         |
| 2024-10-27 |      0.366 | $193.05        | $70.72          |
| 2024-09-29 |      0.180 | $242.95        | $43.66          |
| 2024-09-15 |      0.086 | $120.84        | $10.43          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
