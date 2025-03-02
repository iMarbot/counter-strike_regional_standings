### Roster Details<br />
Team Name: Complexity<br />
Roster: Cxzi, Grim, hallzerk, JT, nicx<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1112.6<br />
<br />
Final Rank Value (1112.6) = Starting Rank Value (1149.5) + Head To Head Adjustments (-36.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.497[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.481[<sup>2</sup>](#table1)

The average of these factors is 0.375<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1149.5
- 400 + ( ( 0.375 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1149.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      284 | 2025-02-17 | SAW              | L   | 1.000      | -            | -                | -                | -         |   -10.06 | Cxzi, Grim, hallzerk, JT, nicx    |
|           28 |      357 | 2025-02-16 | Imperial Female  | W   | 1.000      | 1.000        | 0.134 (0.134)    | 0.165 (0.165)    | 1 (1.000) |    10.03 | Cxzi, Grim, hallzerk, JT, nicx    |
|           27 |      425 | 2025-02-15 | Virtus.pro       | L   | 1.000      | -            | -                | -                | -         |    -1.87 | Cxzi, Grim, hallzerk, JT, nicx    |
|           26 |      488 | 2025-02-14 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -0.33 | Cxzi, Grim, hallzerk, JT, nicx    |
|           25 |      705 | 2025-02-08 | Betera Esports   | L   | 1.000      | -            | -                | -                | -         |   -30.15 | Cxzi, Grim, hallzerk, JT, nicx    |
|           24 |      756 | 2025-02-07 | SIUUUUUU         | W   | 1.000      | -            | -                | -                | -         |     0.41 | Cxzi, Grim, hallzerk, JT, nicx    |
|           23 |     1094 | 2025-01-31 | Team Liquid      | L   | 1.000      | -            | -                | -                | -         |    -3.96 | Cxzi, Grim, hallzerk, JT, nicx    |
|           22 |     1105 | 2025-01-29 | Eternal Fire     | L   | 0.993      | -            | -                | -                | -         |    -0.57 | Cxzi, Grim, hallzerk, JT, nicx    |
|           21 |     1180 | 2025-01-16 | Virtus.pro       | L   | 0.905      | -            | -                | -                | -         |    -2.28 | Cxzi, Grim, hallzerk, JT, nicx    |
|           20 |     2307 | 2024-12-02 | BIG              | L   | 0.609      | -            | -                | -                | -         |    -2.67 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     2371 | 2024-12-01 | Cloud9           | W   | 0.603      | 1.000        | 0.022 (0.014)    | 0.117 (0.071)    | 1 (0.603) |     4.29 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2448 | 2024-12-01 | Imperial Esports | W   | 0.597      | 1.000        | 0.091 (0.055)    | 0.564 (0.337)    | 1 (0.597) |     5.67 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2544 | 2024-11-30 | Passion UA       | L   | 0.591      | -            | -                | -                | -         |   -12.59 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2560 | 2024-11-29 | FlyQuest         | L   | 0.590      | -            | -                | -                | -         |   -10.71 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     3479 | 2024-11-13 | M80              | W   | 0.484      | 0.143        | -                | 0.465 (0.032)    | 1 (0.484) |     3.54 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     3520 | 2024-11-13 | MIBR             | L   | 0.477      | -            | -                | -                | -         |    -3.26 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3555 | 2024-11-12 | BOSS             | W   | 0.472      | -            | -                | -                | 1 (0.472) |     2.97 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     3576 | 2024-11-11 | BESTIA           | W   | 0.470      | 0.143        | 0.069 (0.005)    | 0.478 (0.032)    | 1 (0.470) |     3.49 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     5404 | 2024-10-08 | MOUZ             | L   | 0.240      | -            | -                | -                | -         |    -0.07 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     5453 | 2024-10-07 | Imperial Esports | W   | 0.234      | 0.624        | 0.091 (0.013)    | 0.564 (0.082)    | 1 (0.234) |     2.06 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     5486 | 2024-10-07 | Team Liquid      | L   | 0.232      | -            | -                | -                | -         |    -0.83 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     6754 | 2024-09-18 | Team Liquid      | L   | 0.106      | -            | -                | -                | -         |    -0.39 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     6832 | 2024-09-17 | FaZe Clan        | W   | 0.100      | 0.889        | 0.744 (0.066)    | 0.482 (0.043)    | 1 (0.100) |     3.10 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     6946 | 2024-09-15 | MOUZ             | W   | 0.085      | 0.889        | 1.000 (0.075)    | 0.473 (0.036)    | 1 (0.085) |     2.64 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     7003 | 2024-09-14 | Astralis         | W   | 0.079      | 0.889        | 0.609 (0.043)    | 0.787 (0.055)    | 1 (0.079) |     2.43 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     7086 | 2024-09-13 | BIG              | L   | 0.072      | -            | -                | -                | -         |    -0.27 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     7129 | 2024-09-12 | MOUZ             | W   | 0.066      | 0.889        | 1.000 (0.059)    | -                | -         |     2.07 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     7189 | 2024-09-11 | Astralis         | W   | 0.059      | 0.889        | 0.609 (0.032)    | 0.787 (0.041)    | -         |     1.82 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     7241 | 2024-09-10 | M80              | L   | 0.053      | -            | -                | -                | -         |    -1.31 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32,630.60)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-12-15 |      0.691 | $10,000.00     | $6,909.49       |
| 2024-10-13 |      0.273 | $5,000.00      | $1,363.89       |
| 2024-09-22 |      0.132 | $23,500.00     | $3,107.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
