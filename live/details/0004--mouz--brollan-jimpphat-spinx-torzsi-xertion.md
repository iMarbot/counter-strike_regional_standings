### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, Spinx, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1885.4<br />
<br />
Final Rank Value (1885.4) = Starting Rank Value (2000.0) + Head To Head Adjustments (-114.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.716[<sup>2</sup>](#table1)
- Opponent Network: 0.488[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.801<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.801 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 2000.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       88 | 2025-02-23 | Team Falcons     | W   | 1.000      | 1.000        | 0.927 (0.927)    | 0.613 (0.613)    | 1 (1.000) |    14.76 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           35 |      157 | 2025-02-22 | Astralis         | W   | 1.000      | 1.000        | 0.609 (0.609)    | 0.787 (0.787)    | 1 (1.000) |     8.51 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           34 |      220 | 2025-02-21 | PaiN Gaming      | W   | 1.000      | 1.000        | 0.318 (0.318)    | 0.555 (0.555)    | 1 (1.000) |     6.18 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           33 |      267 | 2025-02-18 | Virtus.pro       | W   | 1.000      | 1.000        | 0.268 (0.268)    | 0.439 (0.439)    | 1 (1.000) |     6.01 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           32 |      306 | 2025-02-17 | Team Falcons     | L   | 1.000      | -            | -                | -                | -         |   -17.40 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           31 |      356 | 2025-02-16 | FaZe Clan        | L   | 1.000      | -            | -                | -                | -         |   -15.41 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           30 |      431 | 2025-02-15 | 3DMAX            | W   | 1.000      | 1.000        | 0.295 (0.295)    | 0.535 (0.535)    | 1 (1.000) |     5.06 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           29 |      499 | 2025-02-14 | BIG              | W   | 1.000      | 1.000        | 0.246 (0.246)    | 0.579 (0.579)    | 1 (1.000) |     1.59 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           28 |     1027 | 2025-02-03 | Team Liquid      | L   | 1.000      | -            | -                | -                | -         |   -28.08 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           27 |     1054 | 2025-02-01 | GamerLegion      | L   | 1.000      | -            | -                | -                | -         |   -27.30 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           26 |     1170 | 2025-01-17 | BetBoom Team     | L   | 0.913      | -            | -                | -                | -         |   -28.57 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1732 | 2024-12-13 | Team Spirit      | L   | 0.683      | -            | -                | -                | -         |   -11.17 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1851 | 2024-12-11 | The MongolZ      | W   | 0.670      | 1.000        | 1.000 (0.670)    | 0.579 (0.388)    | 1 (0.670) |    10.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     2039 | 2024-12-07 | MIBR             | W   | 0.643      | 1.000        | -                | 0.471 (0.303)    | 1 (0.643) |     0.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2107 | 2024-12-06 | 3DMAX            | W   | 0.636      | 1.000        | 0.295 (0.188)    | 0.535 (0.340)    | 1 (0.636) |     2.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2146 | 2024-12-05 | FaZe Clan        | L   | 0.629      | -            | -                | -                | -         |   -12.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2173 | 2024-12-05 | The MongolZ      | L   | 0.624      | -            | -                | -                | -         |   -10.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2187 | 2024-12-04 | PaiN Gaming      | W   | 0.623      | 1.000        | 0.318 (0.198)    | 0.555 (0.346)    | 1 (0.623) |     1.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     3215 | 2024-11-17 | Natus Vincere    | W   | 0.510      | -            | -                | -                | -         |     3.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     3256 | 2024-11-17 | HEROIC           | W   | 0.505      | -            | -                | -                | -         |     0.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     3296 | 2024-11-16 | Nemiga Gaming    | W   | 0.503      | -            | -                | -                | -         |     0.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     4215 | 2024-11-01 | Team Vitality    | L   | 0.397      | -            | -                | -                | -         |    -7.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     4262 | 2024-10-31 | Astralis         | L   | 0.391      | -            | -                | -                | -         |    -8.53 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     4333 | 2024-10-30 | FaZe Clan        | W   | 0.384      | 1.000        | 0.744 (0.286)    | -                | -         |     4.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     5130 | 2024-10-13 | Natus Vincere    | L   | 0.273      | -            | -                | -                | -         |    -7.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     5186 | 2024-10-12 | FURIA            | W   | 0.267      | -            | -                | -                | -         |     0.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     5248 | 2024-10-11 | Team Vitality    | W   | 0.260      | -            | -                | -                | -         |     3.20 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     5331 | 2024-10-09 | FaZe Clan        | W   | 0.247      | -            | -                | -                | -         |     3.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     5404 | 2024-10-08 | Complexity       | W   | 0.240      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     5463 | 2024-10-07 | FURIA            | L   | 0.233      | -            | -                | -                | -         |    -7.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     5488 | 2024-10-07 | PaiN Gaming      | W   | 0.232      | -            | -                | -                | -         |     0.83 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     6946 | 2024-09-15 | Complexity       | L   | 0.085      | -            | -                | -                | -         |    -2.64 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     7030 | 2024-09-14 | Fnatic           | W   | 0.078      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     7129 | 2024-09-12 | Complexity       | L   | 0.066      | -            | -                | -                | -         |    -2.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     7178 | 2024-09-11 | Imperial Esports | L   | 0.060      | -            | -                | -                | -         |    -1.87 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     7257 | 2024-09-10 | Rooster          | W   | 0.051      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($488,590.09)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.691 | $80,000.00     | $55,275.93      |
| 2024-11-03 |      0.411 | $25,000.00     | $10,270.83      |
| 2024-10-13 |      0.273 | $42,000.00     | $11,456.67      |
| 2024-09-22 |      0.132 | $12,000.00     | $1,586.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
