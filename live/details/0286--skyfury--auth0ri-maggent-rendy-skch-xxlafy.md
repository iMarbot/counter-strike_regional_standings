### Roster Details<br />
Team Name: SkyFury<br />
Roster: auth0ri, Maggent, rendY, skcH, xxlafy<br />
Global Rank: [286](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [193]( ../standings_europe.md)<br />
<br />
Final Rank Value:  659.2<br />
<br />
Final Rank Value (659.2) = Starting Rank Value (684.0) + Head To Head Adjustments (-24.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.0
- 400 + ( ( 0.142 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 684.0


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
|           26 |     1359 | 2024-12-26 | VOLT (European team)            | L   | 0.758      | -            | -                | -                | -         |   -10.32 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           25 |     1390 | 2024-12-23 | Infinite Gaming                 | W   | 0.736      | 0.333        | 0.000 (0.000)    | 0.059 (0.014)    | 0 (0.000) |     6.81 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           24 |     1412 | 2024-12-22 | C.S.D.E                         | L   | 0.731      | -            | -                | -                | -         |   -10.86 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           23 |     1423 | 2024-12-22 | Dragon Esports Club             | L   | 0.730      | -            | -                | -                | -         |   -11.45 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           22 |     1429 | 2024-12-22 | ROYALS                          | W   | 0.730      | 0.333        | 0.004 (0.001)    | 0.200 (0.049)    | 0 (0.000) |    11.48 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           21 |     1477 | 2024-12-21 | Fragmatic                       | W   | 0.724      | 0.143        | 0.000 (0.000)    | 0.068 (0.007)    | 0 (0.000) |     7.73 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           20 |     1491 | 2024-12-21 | CourageG                        | W   | 0.723      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.22 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           19 |     1531 | 2024-12-20 | VOLT (European team)            | L   | 0.717      | -            | -                | -                | -         |    -9.94 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           18 |     1543 | 2024-12-19 | NEVERMORE (Ukrainian team)      | W   | 0.712      | 0.303        | 0.010 (0.002)    | 0.904 (0.195)    | 0 (0.000) |    16.40 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           17 |     1572 | 2024-12-18 | Venom (Swedish team)            | W   | 0.703      | 0.303        | -                | 0.062 (0.013)    | 0 (0.000) |     6.63 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           16 |     1582 | 2024-12-17 | PLUSH                           | W   | 0.698      | -            | -                | -                | 0 (0.000) |     4.33 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           15 |     1656 | 2024-12-15 | Venom (Swedish team)            | L   | 0.683      | -            | -                | -                | -         |   -15.21 | auth0ri, Maggent, rendY, skcH, xxlafy |
|           14 |     2138 | 2024-12-06 | C.S.D.E                         | L   | 0.625      | -            | -                | -                | -         |    -9.20 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           13 |     2339 | 2024-12-02 | Cerberus eSports (Russian team) | L   | 0.599      | -            | -                | -                | -         |   -11.62 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           12 |     2454 | 2024-12-01 | ROYALS                          | L   | 0.590      | -            | -                | -                | -         |    -9.08 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           11 |     2493 | 2024-11-30 | Rhyno Youngsters                | W   | 0.586      | 0.333        | 0.003 (0.001)    | 0.118 (0.023)    | 0 (0.000) |    10.06 | 3ippoch, Maggent, rendY, skcH, svemyy |
|           10 |     2611 | 2024-11-29 | Dark Cloud Esports              | L   | 0.576      | -            | -                | -                | -         |    -4.96 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            9 |     2726 | 2024-11-26 | ALTERNATE aTTaX Evo             | W   | 0.559      | 0.333        | 0.001 (0.000)    | 0.178 (0.033)    | 0 (0.000) |     7.46 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            8 |     3029 | 2024-11-21 | Hypewrld                        | L   | 0.525      | -            | -                | -                | -         |    -7.05 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            7 |     3111 | 2024-11-20 | DEPO                            | L   | 0.519      | -            | -                | -                | -         |    -6.37 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            6 |     3116 | 2024-11-20 | KZ Esports                      | W   | 0.518      | 0.284        | 0.009 (0.001)    | 0.112 (0.017)    | 0 (0.000) |     8.51 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            5 |     4472 | 2024-10-27 | C.S.D.E                         | L   | 0.358      | -            | -                | -                | -         |    -5.71 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            4 |     4485 | 2024-10-27 | Podpivasi                       | W   | 0.357      | 0.143        | 0.000 (0.000)    | -                | -         |     2.92 | 3ippoch, Maggent, rendY, skcH, svemyy |
|            3 |     5994 | 2024-09-29 | Leo Team                        | L   | 0.169      | -            | -                | -                | -         |    -1.62 | Maggent, rendY, skcH, svemyy, Зippoch |
|            2 |     6094 | 2024-09-28 | TEAM NEXT LEVEL                 | W   | 0.162      | 0.143        | 0.003 (0.000)    | 0.464 (0.011)    | -         |     2.66 | Maggent, rendY, skcH, svemyy, Зippoch |
|            1 |     7020 | 2024-09-14 | TEAM NEXT LEVEL                 | L   | 0.070      | -            | -                | -                | -         |    -0.63 | Maggent, rendY, skcH, svemyy, Зippoch |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,440.17)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.731 | $167.58        | $122.56         |
| 2024-12-21 |      0.723 | $500.00        | $361.32         |
| 2024-12-17 |      0.698 | $1,197.67      | $836.04         |
| 2024-10-27 |      0.358 | $193.05        | $69.14          |
| 2024-09-29 |      0.172 | $242.95        | $41.67          |
| 2024-09-15 |      0.078 | $120.84        | $9.44           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
