### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: jottAAA, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1837.7<br />
<br />
Final Rank Value (1837.7) = Starting Rank Value (1889.2) + Head To Head Adjustments (-51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.818[<sup>1</sup>](#table2)
- Bounty Collected: 0.748[<sup>2</sup>](#table1)
- Opponent Network: 0.412[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.744<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1889.2
- 400 + ( ( 0.744 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1889.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      226 | 2025-02-21 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -15.99 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |      314 | 2025-02-17 | 3DMAX           | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.528 (0.528)    | 1 (1.000) |     5.83 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |      390 | 2025-02-16 | BIG             | W   | 1.000      | 1.000        | 0.248 (0.248)    | 0.572 (0.572)    | 1 (1.000) |     1.92 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |      433 | 2025-02-15 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |   -15.05 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |      489 | 2025-02-14 | Imperial Female | W   | 1.000      | 1.000        | 0.136 (0.136)    | -                | 1 (1.000) |     0.24 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |      803 | 2025-02-07 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |   -12.65 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |      966 | 2025-02-04 | FaZe Clan       | W   | 1.000      | 1.000        | 0.753 (0.753)    | 0.478 (0.478)    | 1 (1.000) |    15.90 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1026 | 2025-02-03 | 3DMAX           | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.528 (0.528)    | 1 (1.000) |     5.29 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1047 | 2025-02-02 | Virtus.pro      | L   | 1.000      | -            | -                | -                | -         |   -25.11 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1077 | 2025-02-01 | Team Falcons    | W   | 1.000      | 1.000        | 0.939 (0.939)    | 0.609 (0.609)    | 1 (1.000) |    14.96 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     1107 | 2025-01-30 | HEROIC          | W   | 0.992      | 1.000        | -                | 0.401 (0.398)    | 1 (0.992) |     0.58 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     1117 | 2025-01-29 | Complexity      | W   | 0.985      | 1.000        | -                | 0.226 (0.223)    | 1 (0.985) |     0.56 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     1138 | 2025-01-26 | Team Spirit     | L   | 0.964      | -            | -                | -                | -         |   -10.43 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     1144 | 2025-01-25 | G2 Esports      | W   | 0.958      | 0.769        | 1.000 (0.736)    | 0.355 (0.261)    | 1 (0.958) |    13.71 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     1152 | 2025-01-24 | Team Vitality   | W   | 0.951      | 0.769        | 1.000 (0.731)    | 0.442 (0.323)    | 1 (0.951) |    17.27 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     1168 | 2025-01-19 | Team Falcons    | W   | 0.917      | 0.363        | 0.939 (0.312)    | 0.609 (0.202)    | -         |    15.88 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     1191 | 2025-01-16 | Fluxo           | W   | 0.897      | -            | -                | -                | -         |     0.27 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2918 | 2024-11-23 | Astralis        | L   | 0.536      | -            | -                | -                | -         |    -8.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           15 |     3013 | 2024-11-21 | Sashi Esport    | L   | 0.528      | -            | -                | -                | -         |   -16.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           14 |     3060 | 2024-11-21 | 3DMAX           | L   | 0.524      | -            | -                | -                | -         |   -13.82 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           13 |     3079 | 2024-11-20 | Aurora Gaming   | W   | 0.522      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           12 |     4525 | 2024-10-26 | B8              | L   | 0.351      | -            | -                | -                | -         |   -10.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           11 |     4559 | 2024-10-26 | Team Falcons    | W   | 0.349      | -            | -                | -                | -         |     0.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           10 |     4620 | 2024-10-25 | B8              | L   | 0.343      | -            | -                | -                | -         |   -10.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            9 |     5358 | 2024-10-09 | The MongolZ     | L   | 0.237      | -            | -                | -                | -         |    -3.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            8 |     5430 | 2024-10-08 | G2 Esports      | W   | 0.231      | 0.624        | 1.000 (0.144)    | -                | -         |     2.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            7 |     5481 | 2024-10-07 | Astralis        | L   | 0.225      | -            | -                | -                | -         |    -3.96 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            6 |     6527 | 2024-09-22 | Natus Vincere   | L   | 0.124      | -            | -                | -                | -         |    -2.92 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            5 |     6594 | 2024-09-21 | MIBR            | W   | 0.117      | -            | -                | -                | -         |     0.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            4 |     6705 | 2024-09-19 | Team Vitality   | W   | 0.105      | -            | -                | -                | -         |     1.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            3 |     6786 | 2024-09-18 | The MongolZ     | W   | 0.096      | -            | -                | -                | -         |     1.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            2 |     7421 | 2024-09-07 | Natus Vincere   | L   | 0.025      | -            | -                | -                | -         |    -0.59 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            1 |     7683 | 2024-09-04 | HEROIC          | W   | 0.004      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($197,388.94)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.60) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-26 |      0.964 | $85,625.00     | $82,568.66      |
| 2024-10-27 |      0.358 | $3,000.00      | $1,075.14       |
| 2024-10-13 |      0.265 | $5,000.00      | $1,322.92       |
| 2024-09-22 |      0.124 | $80,000.00     | $9,922.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
