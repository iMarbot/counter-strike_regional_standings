### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: jottAAA, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1835.7<br />
<br />
Final Rank Value (1835.7) = Starting Rank Value (1887.3) + Head To Head Adjustments (-51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.814[<sup>1</sup>](#table2)
- Bounty Collected: 0.747[<sup>2</sup>](#table1)
- Opponent Network: 0.417[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.745<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1887.3
- 400 + ( ( 0.745 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1887.3


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
|           34 |      214 | 2025-02-21 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -16.01 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      302 | 2025-02-17 | 3DMAX           | W   | 1.000      | 1.000        | 0.295 (0.295)    | 0.535 (0.535)    | 1 (1.000) |     5.90 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |      378 | 2025-02-16 | BIG             | W   | 1.000      | 1.000        | 0.246 (0.246)    | 0.579 (0.579)    | 1 (1.000) |     1.94 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |      421 | 2025-02-15 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |   -15.04 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |      477 | 2025-02-14 | Imperial Female | W   | 1.000      | 1.000        | 0.134 (0.134)    | -                | 1 (1.000) |     0.24 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |      791 | 2025-02-07 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |   -12.55 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |      954 | 2025-02-04 | FaZe Clan       | W   | 1.000      | 1.000        | 0.744 (0.744)    | 0.482 (0.482)    | 1 (1.000) |    15.92 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1014 | 2025-02-03 | 3DMAX           | W   | 1.000      | 1.000        | 0.295 (0.295)    | 0.535 (0.535)    | 1 (1.000) |     5.36 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1035 | 2025-02-02 | Virtus.pro      | L   | 1.000      | -            | -                | -                | -         |   -25.08 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1065 | 2025-02-01 | Team Falcons    | W   | 1.000      | 1.000        | 0.927 (0.927)    | 0.613 (0.613)    | 1 (1.000) |    14.93 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1095 | 2025-01-30 | HEROIC          | W   | 1.000      | 1.000        | -                | 0.404 (0.404)    | 1 (1.000) |     0.60 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     1105 | 2025-01-29 | Complexity      | W   | 0.993      | 1.000        | -                | 0.229 (0.227)    | 1 (0.993) |     0.57 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     1126 | 2025-01-26 | Team Spirit     | L   | 0.973      | -            | -                | -                | -         |   -10.43 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     1132 | 2025-01-25 | G2 Esports      | W   | 0.966      | 0.769        | 1.000 (0.742)    | 0.359 (0.266)    | 1 (0.966) |    14.10 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     1140 | 2025-01-24 | Team Vitality   | W   | 0.959      | 0.769        | 1.000 (0.737)    | 0.445 (0.328)    | 1 (0.959) |    17.55 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     1156 | 2025-01-19 | Team Falcons    | W   | 0.925      | 0.363        | 0.927 (0.311)    | 0.613 (0.206)    | -         |    16.03 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     1179 | 2025-01-16 | Fluxo           | W   | 0.905      | -            | -                | -                | -         |     0.28 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2906 | 2024-11-23 | Astralis        | L   | 0.544      | -            | -                | -                | -         |    -8.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           16 |     3001 | 2024-11-21 | Sashi Esport    | L   | 0.536      | -            | -                | -                | -         |   -16.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           15 |     3048 | 2024-11-21 | 3DMAX           | L   | 0.532      | -            | -                | -                | -         |   -13.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           14 |     3067 | 2024-11-20 | Aurora Gaming   | W   | 0.530      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           13 |     4513 | 2024-10-26 | B8              | L   | 0.359      | -            | -                | -                | -         |   -11.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           12 |     4547 | 2024-10-26 | Team Falcons    | W   | 0.358      | -            | -                | -                | -         |     0.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           11 |     4608 | 2024-10-25 | B8              | L   | 0.351      | -            | -                | -                | -         |   -10.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           10 |     5346 | 2024-10-09 | The MongolZ     | L   | 0.245      | -            | -                | -                | -         |    -3.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            9 |     5418 | 2024-10-08 | G2 Esports      | W   | 0.239      | 0.624        | 1.000 (0.149)    | -                | -         |     2.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            8 |     5469 | 2024-10-07 | Astralis        | L   | 0.233      | -            | -                | -                | -         |    -4.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            7 |     6515 | 2024-09-22 | Natus Vincere   | L   | 0.132      | -            | -                | -                | -         |    -3.08 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            6 |     6582 | 2024-09-21 | MIBR            | W   | 0.125      | -            | -                | -                | -         |     0.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            5 |     6693 | 2024-09-19 | Team Vitality   | W   | 0.113      | -            | -                | -                | -         |     1.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            4 |     6774 | 2024-09-18 | The MongolZ     | W   | 0.104      | -            | -                | -                | -         |     1.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            3 |     7409 | 2024-09-07 | Natus Vincere   | L   | 0.033      | -            | -                | -                | -         |    -0.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            2 |     7671 | 2024-09-04 | HEROIC          | W   | 0.012      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            1 |     7749 | 2024-09-03 | FlyQuest        | W   | 0.005      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($198,811.70)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.59) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-26 |      0.973 | $85,625.00     | $83,270.31      |
| 2024-10-27 |      0.367 | $3,000.00      | $1,099.72       |
| 2024-10-13 |      0.273 | $5,000.00      | $1,363.89       |
| 2024-09-22 |      0.132 | $80,000.00     | $10,577.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
