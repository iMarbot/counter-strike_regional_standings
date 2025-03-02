### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, ropz, ZywOo<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1952.2<br />
<br />
Final Rank Value (1952.2) = Starting Rank Value (1914.1) + Head To Head Adjustments (38.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.721[<sup>2</sup>](#table1)
- Opponent Network: 0.390[<sup>2</sup>](#table1)
- LAN Wins: 0.921[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1914.1
- 400 + ( ( 0.758 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1914.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      631 | 2025-02-09 | Team Spirit  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.663 (0.663)    | 1 (1.000) |    17.29 | apEX, flameZ, mezii, ropz, ZywOo  |
|           29 |      708 | 2025-02-08 | The MongolZ  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.579 (0.579)    | 1 (1.000) |    16.19 | apEX, flameZ, mezii, ropz, ZywOo  |
|           28 |      955 | 2025-02-04 | Virtus.pro   | W   | 1.000      | 1.000        | 0.268 (0.268)    | 0.439 (0.439)    | 1 (1.000) |     5.28 | apEX, flameZ, mezii, ropz, ZywOo  |
|           27 |     1031 | 2025-02-02 | FaZe Clan    | W   | 1.000      | 1.000        | 0.744 (0.744)    | 0.482 (0.482)    | 1 (1.000) |    14.09 | apEX, flameZ, mezii, ropz, ZywOo  |
|           26 |     1064 | 2025-02-01 | 3DMAX        | W   | 1.000      | 1.000        | 0.295 (0.295)    | 0.535 (0.535)    | 1 (1.000) |     4.22 | apEX, flameZ, mezii, ropz, ZywOo  |
|           25 |     1140 | 2025-01-24 | Eternal Fire | L   | 0.959      | -            | -                | -                | -         |   -17.55 | apEX, flameZ, mezii, ropz, ZywOo  |
|           24 |     1149 | 2025-01-19 | Virtus.pro   | W   | 0.927      | 0.363        | 0.268 (0.090)    | -                | -         |     4.07 | apEX, flameZ, mezii, ropz, ZywOo  |
|           23 |     1181 | 2025-01-15 | Metizport    | W   | 0.900      | 0.363        | -                | 0.513 (0.168)    | -         |     0.22 | apEX, flameZ, mezii, ropz, ZywOo  |
|           22 |     1805 | 2024-12-13 | FaZe Clan    | L   | 0.678      | -            | -                | -                | -         |   -11.46 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     2144 | 2024-12-05 | MIBR         | W   | 0.630      | 1.000        | 0.141 (0.089)    | 0.471 (0.297)    | 1 (0.630) |     1.21 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     2181 | 2024-12-05 | FURIA        | W   | 0.624      | 1.000        | -                | 0.384 (0.240)    | 1 (0.624) |     1.48 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     2188 | 2024-12-04 | GamerLegion  | W   | 0.623      | 1.000        | 0.127 (0.079)    | 0.493 (0.307)    | 1 (0.623) |     2.56 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     3211 | 2024-11-18 | FaZe Clan    | W   | 0.511      | -            | -                | -                | 1 (0.511) |     7.81 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     3265 | 2024-11-17 | BetBoom Team | W   | 0.505      | -            | -                | -                | 1 (0.505) |     0.12 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     3297 | 2024-11-16 | GamerLegion  | W   | 0.503      | -            | -                | -                | -         |     2.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     4158 | 2024-11-02 | G2 Esports   | L   | 0.404      | -            | -                | -                | -         |    -8.12 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           14 |     4215 | 2024-11-01 | MOUZ         | W   | 0.397      | 1.000        | 1.000 (0.397)    | 0.473 (0.188)    | -         |     7.55 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           13 |     4259 | 2024-10-31 | Team Liquid  | W   | 0.391      | -            | -                | -                | -         |     1.30 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           12 |     4322 | 2024-10-30 | Team Spirit  | L   | 0.385      | -            | -                | -                | -         |    -4.74 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           11 |     5248 | 2024-10-11 | MOUZ         | L   | 0.260      | -            | -                | -                | -         |    -3.20 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     5343 | 2024-10-09 | Team Falcons | L   | 0.246      | -            | -                | -                | -         |    -3.85 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     5425 | 2024-10-08 | The MongolZ  | W   | 0.239      | 0.624        | 1.000 (0.149)    | -                | -         |     4.04 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     5478 | 2024-10-07 | 9z Team      | W   | 0.233      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     6047 | 2024-09-28 | G2 Esports   | L   | 0.172      | -            | -                | -                | -         |    -3.57 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     6181 | 2024-09-26 | Team Liquid  | W   | 0.160      | -            | -                | -                | -         |     0.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     6294 | 2024-09-25 | Astralis     | W   | 0.152      | -            | -                | -                | -         |     1.96 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     6693 | 2024-09-19 | Eternal Fire | L   | 0.113      | -            | -                | -                | -         |    -1.91 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     6924 | 2024-09-15 | Team Liquid  | W   | 0.086      | -            | -                | -                | -         |     0.27 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     7137 | 2024-09-12 | FURIA        | W   | 0.065      | -            | -                | -                | -         |     0.13 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     7203 | 2024-09-11 | ATOX Esports | W   | 0.058      | -            | -                | -                | -         |     0.02 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($483,763.75)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-01-26 |      0.973 | $3,750.00      | $3,646.88       |
| 2024-12-15 |      0.691 | $45,000.00     | $31,092.71      |
| 2024-11-03 |      0.411 | $85,000.00     | $34,920.83      |
| 2024-10-13 |      0.273 | $10,000.00     | $2,727.78       |
| 2024-09-29 |      0.179 | $40,000.00     | $7,144.44       |
| 2024-09-22 |      0.132 | $32,000.00     | $4,231.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
