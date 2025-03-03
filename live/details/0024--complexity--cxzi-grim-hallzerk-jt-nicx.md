### Roster Details<br />
Team Name: Complexity<br />
Roster: Cxzi, Grim, hallzerk, JT, nicx<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1110.7<br />
<br />
Final Rank Value (1110.7) = Starting Rank Value (1143.8) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.498[<sup>1</sup>](#table2)
- Bounty Collected: 0.429[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.474[<sup>2</sup>](#table1)

The average of these factors is 0.372<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1143.8
- 400 + ( ( 0.372 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1143.8


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
|           29 |      296 | 2025-02-17 | SAW              | L   | 1.000      | -            | -                | -                | -         |    -9.99 | Cxzi, Grim, hallzerk, JT, nicx    |
|           28 |      369 | 2025-02-16 | Imperial Female  | W   | 1.000      | 1.000        | 0.136 (0.136)    | 0.162 (0.162)    | 1 (1.000) |    10.05 | Cxzi, Grim, hallzerk, JT, nicx    |
|           27 |      437 | 2025-02-15 | Virtus.pro       | L   | 1.000      | -            | -                | -                | -         |    -1.84 | Cxzi, Grim, hallzerk, JT, nicx    |
|           26 |      500 | 2025-02-14 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -0.32 | Cxzi, Grim, hallzerk, JT, nicx    |
|           25 |      717 | 2025-02-08 | Betera Esports   | L   | 1.000      | -            | -                | -                | -         |   -30.14 | Cxzi, Grim, hallzerk, JT, nicx    |
|           24 |      768 | 2025-02-07 | SIUUUUUU         | W   | 1.000      | -            | -                | -                | -         |     0.42 | Cxzi, Grim, hallzerk, JT, nicx    |
|           23 |     1106 | 2025-01-31 | Team Liquid      | L   | 0.997      | -            | -                | -                | -         |    -3.96 | Cxzi, Grim, hallzerk, JT, nicx    |
|           22 |     1117 | 2025-01-29 | Eternal Fire     | L   | 0.985      | -            | -                | -                | -         |    -0.56 | Cxzi, Grim, hallzerk, JT, nicx    |
|           21 |     1192 | 2025-01-16 | Virtus.pro       | L   | 0.897      | -            | -                | -                | -         |    -2.22 | Cxzi, Grim, hallzerk, JT, nicx    |
|           20 |     2319 | 2024-12-02 | BIG              | L   | 0.601      | -            | -                | -                | -         |    -2.62 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     2383 | 2024-12-01 | Cloud9           | W   | 0.595      | 1.000        | 0.022 (0.013)    | 0.115 (0.068)    | 1 (0.595) |     4.22 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2460 | 2024-12-01 | Imperial Esports | W   | 0.589      | 1.000        | 0.092 (0.054)    | 0.562 (0.331)    | 1 (0.589) |     5.56 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2556 | 2024-11-30 | Passion UA       | L   | 0.583      | -            | -                | -                | -         |   -12.40 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2572 | 2024-11-29 | FlyQuest         | L   | 0.581      | -            | -                | -                | -         |   -10.61 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     3491 | 2024-11-13 | M80              | W   | 0.475      | 0.143        | -                | 0.462 (0.031)    | 1 (0.475) |     3.58 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     3532 | 2024-11-13 | MIBR             | L   | 0.469      | -            | -                | -                | -         |    -3.20 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3567 | 2024-11-12 | BLUEJAYS         | W   | 0.463      | 0.143        | -                | 0.511 (0.034)    | 1 (0.463) |     7.19 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     3588 | 2024-11-11 | BESTIA           | W   | 0.462      | 0.143        | 0.069 (0.005)    | -                | 1 (0.462) |     3.48 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     5416 | 2024-10-08 | MOUZ             | L   | 0.232      | -            | -                | -                | -         |    -0.07 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     5465 | 2024-10-07 | Imperial Esports | W   | 0.226      | 0.624        | 0.092 (0.013)    | 0.562 (0.079)    | 1 (0.226) |     2.01 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     5498 | 2024-10-07 | Team Liquid      | L   | 0.224      | -            | -                | -                | -         |    -0.79 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     6766 | 2024-09-18 | Team Liquid      | L   | 0.098      | -            | -                | -                | -         |    -0.35 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     6844 | 2024-09-17 | FaZe Clan        | W   | 0.091      | 0.889        | 0.753 (0.061)    | 0.478 (0.039)    | 1 (0.091) |     2.84 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     6958 | 2024-09-15 | MOUZ             | W   | 0.076      | 0.889        | 1.000 (0.068)    | 0.470 (0.032)    | 1 (0.076) |     2.39 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     7015 | 2024-09-14 | Astralis         | W   | 0.071      | 0.889        | 0.619 (0.039)    | 0.786 (0.049)    | 1 (0.071) |     2.18 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     7098 | 2024-09-13 | BIG              | L   | 0.064      | -            | -                | -                | -         |    -0.23 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     7141 | 2024-09-12 | MOUZ             | W   | 0.058      | 0.889        | 1.000 (0.052)    | -                | -         |     1.81 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     7201 | 2024-09-11 | Astralis         | W   | 0.051      | 0.889        | 0.619 (0.028)    | 0.786 (0.035)    | -         |     1.57 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     7253 | 2024-09-10 | M80              | L   | 0.045      | -            | -                | -                | -         |    -1.10 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32,315.12)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-12-15 |      0.683 | $10,000.00     | $6,827.55       |
| 2024-10-13 |      0.265 | $5,000.00      | $1,322.92       |
| 2024-09-22 |      0.124 | $23,500.00     | $2,914.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
