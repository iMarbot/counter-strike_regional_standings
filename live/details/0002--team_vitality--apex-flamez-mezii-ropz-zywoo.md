### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, ropz, ZywOo<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1952.0<br />
<br />
Final Rank Value (1952.0) = Starting Rank Value (1913.1) + Head To Head Adjustments (38.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.722[<sup>2</sup>](#table1)
- Opponent Network: 0.384[<sup>2</sup>](#table1)
- LAN Wins: 0.919[<sup>2</sup>](#table1)

The average of these factors is 0.756<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1913.1
- 400 + ( ( 0.756 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1913.1


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
|           30 |      643 | 2025-02-09 | Team Spirit  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.658 (0.658)    | 1 (1.000) |    17.30 | apEX, flameZ, mezii, ropz, ZywOo  |
|           29 |      720 | 2025-02-08 | The MongolZ  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.574 (0.574)    | 1 (1.000) |    16.19 | apEX, flameZ, mezii, ropz, ZywOo  |
|           28 |      967 | 2025-02-04 | Virtus.pro   | W   | 1.000      | 1.000        | 0.272 (0.272)    | 0.436 (0.436)    | 1 (1.000) |     5.32 | apEX, flameZ, mezii, ropz, ZywOo  |
|           27 |     1043 | 2025-02-02 | FaZe Clan    | W   | 1.000      | 1.000        | 0.753 (0.753)    | 0.478 (0.478)    | 1 (1.000) |    14.19 | apEX, flameZ, mezii, ropz, ZywOo  |
|           26 |     1076 | 2025-02-01 | 3DMAX        | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.528 (0.528)    | 1 (1.000) |     4.22 | apEX, flameZ, mezii, ropz, ZywOo  |
|           25 |     1152 | 2025-01-24 | Eternal Fire | L   | 0.951      | -            | -                | -                | -         |   -17.27 | apEX, flameZ, mezii, ropz, ZywOo  |
|           24 |     1161 | 2025-01-19 | Virtus.pro   | W   | 0.918      | 0.363        | 0.272 (0.091)    | -                | -         |     4.08 | apEX, flameZ, mezii, ropz, ZywOo  |
|           23 |     1193 | 2025-01-15 | Metizport    | W   | 0.892      | 0.363        | -                | 0.507 (0.164)    | -         |     0.21 | apEX, flameZ, mezii, ropz, ZywOo  |
|           22 |     1817 | 2024-12-13 | FaZe Clan    | L   | 0.670      | -            | -                | -                | -         |   -11.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|           21 |     2156 | 2024-12-05 | MIBR         | W   | 0.622      | 1.000        | 0.142 (0.088)    | 0.465 (0.289)    | 1 (0.622) |     1.19 | apEX, flameZ, mezii, Spinx, ZywOo |
|           20 |     2193 | 2024-12-05 | FURIA        | W   | 0.616      | 1.000        | -                | 0.379 (0.233)    | 1 (0.616) |     1.44 | apEX, flameZ, mezii, Spinx, ZywOo |
|           19 |     2200 | 2024-12-04 | GamerLegion  | W   | 0.615      | 1.000        | 0.129 (0.079)    | 0.490 (0.301)    | 1 (0.615) |     2.52 | apEX, flameZ, mezii, Spinx, ZywOo |
|           18 |     3223 | 2024-11-18 | FaZe Clan    | W   | 0.503      | -            | -                | -                | 1 (0.503) |     7.76 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     3277 | 2024-11-17 | BetBoom Team | W   | 0.496      | -            | -                | -                | 1 (0.496) |     0.12 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     3309 | 2024-11-16 | GamerLegion  | W   | 0.495      | -            | -                | -                | -         |     2.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     4170 | 2024-11-02 | G2 Esports   | L   | 0.396      | -            | -                | -                | -         |    -8.03 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           14 |     4227 | 2024-11-01 | MOUZ         | W   | 0.389      | 1.000        | 1.000 (0.389)    | 0.470 (0.183)    | -         |     7.43 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           13 |     4271 | 2024-10-31 | Team Liquid  | W   | 0.383      | -            | -                | -                | -         |     1.25 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           12 |     4334 | 2024-10-30 | Team Spirit  | L   | 0.377      | -            | -                | -                | -         |    -4.62 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           11 |     5260 | 2024-10-11 | MOUZ         | L   | 0.252      | -            | -                | -                | -         |    -3.08 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     5355 | 2024-10-09 | Team Falcons | L   | 0.238      | -            | -                | -                | -         |    -3.69 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     5437 | 2024-10-08 | The MongolZ  | W   | 0.230      | 0.624        | 1.000 (0.144)    | -                | -         |     3.91 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     5490 | 2024-10-07 | 9z Team      | W   | 0.224      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     6059 | 2024-09-28 | G2 Esports   | L   | 0.164      | -            | -                | -                | -         |    -3.43 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     6193 | 2024-09-26 | Team Liquid  | W   | 0.152      | -            | -                | -                | -         |     0.48 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     6306 | 2024-09-25 | Astralis     | W   | 0.144      | -            | -                | -                | -         |     1.88 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     6705 | 2024-09-19 | Eternal Fire | L   | 0.105      | -            | -                | -                | -         |    -1.75 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     6936 | 2024-09-15 | Team Liquid  | W   | 0.078      | -            | -                | -                | -         |     0.24 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     7149 | 2024-09-12 | FURIA        | W   | 0.057      | -            | -                | -                | -         |     0.12 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     7215 | 2024-09-11 | ATOX Esports | W   | 0.050      | -            | -                | -                | -         |     0.02 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($481,995.80)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-01-26 |      0.964 | $3,750.00      | $3,616.15       |
| 2024-12-15 |      0.683 | $45,000.00     | $30,723.96      |
| 2024-11-03 |      0.403 | $85,000.00     | $34,224.31      |
| 2024-10-13 |      0.265 | $10,000.00     | $2,645.83       |
| 2024-09-29 |      0.170 | $40,000.00     | $6,816.67       |
| 2024-09-22 |      0.124 | $32,000.00     | $3,968.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
