### Roster Details<br />
Team Name: GamerLegion<br />
Roster: PR, REZ, sl3nd, Tauson, ztr<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1583.9<br />
<br />
Final Rank Value (1583.9) = Starting Rank Value (1585.7) + Head To Head Adjustments (-1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.528[<sup>1</sup>](#table2)
- Bounty Collected: 0.630[<sup>2</sup>](#table1)
- Opponent Network: 0.347[<sup>2</sup>](#table1)
- LAN Wins: 0.870[<sup>2</sup>](#table1)

The average of these factors is 0.594<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1585.7
- 400 + ( ( 0.594 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1585.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      581 | 2025-02-10 | Metizport       | W   | 1.000      | 0.143        | 0.074 (0.011)    | 0.513 (0.073)    | -         |     1.23 | PR, REZ, sl3nd, Tauson, ztr      |
|           28 |      594 | 2025-02-10 | Hesta           | W   | 1.000      | 0.143        | -                | 0.656 (0.094)    | -         |     0.37 | PR, REZ, sl3nd, Tauson, ztr      |
|           27 |      717 | 2025-02-08 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |   -31.15 | PR, REZ, sl3nd, Tauson, ztr      |
|           26 |      942 | 2025-02-04 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -3.73 | PR, REZ, sl3nd, Tauson, ztr      |
|           25 |      996 | 2025-02-04 | Astralis        | W   | 1.000      | 1.000        | 0.609 (0.609)    | 0.787 (0.787)    | 1 (1.000) |    22.11 | PR, REZ, sl3nd, Tauson, ztr      |
|           24 |     1026 | 2025-02-03 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |    -3.77 | PR, REZ, sl3nd, Tauson, ztr      |
|           23 |     1054 | 2025-02-01 | MOUZ            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.473 (0.473)    | 1 (1.000) |    27.30 | PR, REZ, sl3nd, Tauson, ztr      |
|           22 |     1101 | 2025-01-30 | PaiN Gaming     | W   | 0.998      | 1.000        | 0.318 (0.317)    | 0.555 (0.555)    | 1 (0.998) |    17.28 | PR, REZ, sl3nd, Tauson, ztr      |
|           21 |     1110 | 2025-01-29 | SAW             | W   | 0.992      | 1.000        | 0.262 (0.260)    | 0.329 (0.326)    | 1 (0.992) |     6.00 | PR, REZ, sl3nd, Tauson, ztr      |
|           20 |     1176 | 2025-01-17 | PaiN Gaming     | L   | 0.911      | -            | -                | -                | -         |   -13.76 | PR, REZ, sl3nd, Tauson, ztr      |
|           19 |     2102 | 2024-12-06 | Natus Vincere   | L   | 0.637      | -            | -                | -                | -         |    -6.39 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           18 |     2145 | 2024-12-05 | Wildcard        | W   | 0.630      | 1.000        | 0.176 (0.111)    | 0.428 (0.270)    | 1 (0.630) |     4.34 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           17 |     2180 | 2024-12-05 | Team Liquid     | L   | 0.624      | -            | -                | -                | -         |   -11.18 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           16 |     2188 | 2024-12-04 | Team Vitality   | L   | 0.623      | -            | -                | -                | -         |    -2.56 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           15 |     2361 | 2024-12-02 | Passion UA      | W   | 0.604      | 1.000        | 0.044 (0.027)    | 0.557 (0.336)    | 1 (0.604) |     0.93 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           14 |     2447 | 2024-12-01 | The MongolZ     | L   | 0.597      | -            | -                | -                | -         |    -2.28 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           13 |     2534 | 2024-11-30 | PaiN Gaming     | W   | 0.592      | 1.000        | 0.318 (0.188)    | 0.555 (0.329)    | 1 (0.592) |     9.69 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           12 |     2564 | 2024-11-29 | FURIA           | W   | 0.589      | 1.000        | 0.094 (0.055)    | 0.384 (0.226)    | 1 (0.589) |     6.11 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           11 |     3127 | 2024-11-20 | BetBoom Team    | W   | 0.525      | -            | -                | -                | 1 (0.525) |     0.90 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           10 |     3130 | 2024-11-20 | SINNERS Esports | W   | 0.524      | -            | -                | -                | 1 (0.524) |     0.46 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            9 |     3168 | 2024-11-19 | Team Falcons    | W   | 0.517      | -            | -                | -                | -         |     0.17 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            8 |     3210 | 2024-11-18 | UNiTY esports   | W   | 0.511      | -            | -                | -                | -         |     0.28 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            7 |     3269 | 2024-11-17 | Dynamo Eclot    | L   | 0.504      | -            | -                | -                | -         |   -15.09 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            6 |     3297 | 2024-11-16 | Team Vitality   | L   | 0.503      | -            | -                | -                | -         |    -2.19 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            5 |     5259 | 2024-10-11 | GUN5 Esports    | L   | 0.259      | -            | -                | -                | -         |    -7.95 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            4 |     5509 | 2024-10-06 | Passion UA      | W   | 0.226      | -            | -                | -                | -         |     0.34 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            3 |     5526 | 2024-10-06 | 9Pandas         | W   | 0.225      | -            | -                | -                | -         |     0.23 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            2 |     5567 | 2024-10-05 | B8              | W   | 0.220      | 0.435        | 0.124 (0.012)    | -                | -         |     0.48 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            1 |     5657 | 2024-10-04 | Adventurers     | W   | 0.213      | -            | -                | -                | -         |     0.08 | FL4MUS, sl3nd, Tauson, volt, ztr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,801.06)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-10-06 |      0.226 | $22,000.00     | $4,982.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
