### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, Spinx, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1886.8<br />
<br />
Final Rank Value (1886.8) = Starting Rank Value (2000.0) + Head To Head Adjustments (-113.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.717[<sup>2</sup>](#table1)
- Opponent Network: 0.482[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.800<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.800 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 2000.0


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
|           36 |      103 | 2025-02-23 | Team Falcons     | W   | 1.000      | 1.000        | 0.939 (0.939)    | 0.609 (0.609)    | 1 (1.000) |    14.80 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           35 |      169 | 2025-02-22 | Astralis         | W   | 1.000      | 1.000        | 0.619 (0.619)    | 0.786 (0.786)    | 1 (1.000) |     8.54 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           34 |      232 | 2025-02-21 | PaiN Gaming      | W   | 1.000      | 1.000        | 0.323 (0.323)    | 0.549 (0.549)    | 1 (1.000) |     6.18 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           33 |      279 | 2025-02-18 | Virtus.pro       | W   | 1.000      | 1.000        | 0.272 (0.272)    | 0.436 (0.436)    | 1 (1.000) |     6.01 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           32 |      318 | 2025-02-17 | Team Falcons     | L   | 1.000      | -            | -                | -                | -         |   -17.35 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           31 |      368 | 2025-02-16 | FaZe Clan        | L   | 1.000      | -            | -                | -                | -         |   -15.39 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           30 |      443 | 2025-02-15 | 3DMAX            | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.528 (0.528)    | 1 (1.000) |     5.02 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           29 |      511 | 2025-02-14 | BIG              | W   | 1.000      | 1.000        | 0.248 (0.248)    | 0.572 (0.572)    | 1 (1.000) |     1.58 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           28 |     1039 | 2025-02-03 | Team Liquid      | L   | 1.000      | -            | -                | -                | -         |   -28.15 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           27 |     1066 | 2025-02-01 | GamerLegion      | L   | 1.000      | -            | -                | -                | -         |   -27.35 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           26 |     1182 | 2025-01-17 | BetBoom Team     | L   | 0.905      | -            | -                | -                | -         |   -28.32 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1744 | 2024-12-13 | Team Spirit      | L   | 0.675      | -            | -                | -                | -         |   -11.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1863 | 2024-12-11 | The MongolZ      | W   | 0.662      | 1.000        | 1.000 (0.662)    | 0.574 (0.380)    | 1 (0.662) |    10.14 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     2051 | 2024-12-07 | MIBR             | W   | 0.634      | 1.000        | -                | 0.465 (0.295)    | 1 (0.634) |     0.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2119 | 2024-12-06 | 3DMAX            | W   | 0.628      | 1.000        | 0.298 (0.187)    | 0.528 (0.332)    | 1 (0.628) |     2.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2158 | 2024-12-05 | FaZe Clan        | L   | 0.621      | -            | -                | -                | -         |   -11.87 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2185 | 2024-12-05 | The MongolZ      | L   | 0.616      | -            | -                | -                | -         |   -10.65 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2199 | 2024-12-04 | PaiN Gaming      | W   | 0.615      | 1.000        | 0.323 (0.199)    | 0.549 (0.338)    | 1 (0.615) |     1.89 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     3227 | 2024-11-17 | Natus Vincere    | W   | 0.502      | -            | -                | -                | -         |     2.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     3268 | 2024-11-17 | HEROIC           | W   | 0.497      | -            | -                | -                | -         |     0.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     3308 | 2024-11-16 | Nemiga Gaming    | W   | 0.495      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     4227 | 2024-11-01 | Team Vitality    | L   | 0.389      | -            | -                | -                | -         |    -7.43 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     4274 | 2024-10-31 | Astralis         | L   | 0.383      | -            | -                | -                | -         |    -8.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     4345 | 2024-10-30 | FaZe Clan        | W   | 0.376      | 1.000        | 0.753 (0.283)    | -                | -         |     4.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     5142 | 2024-10-13 | Natus Vincere    | L   | 0.265      | -            | -                | -                | -         |    -6.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     5198 | 2024-10-12 | FURIA            | W   | 0.258      | -            | -                | -                | -         |     0.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     5260 | 2024-10-11 | Team Vitality    | W   | 0.252      | -            | -                | -                | -         |     3.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     5343 | 2024-10-09 | FaZe Clan        | W   | 0.238      | -            | -                | -                | -         |     2.96 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     5416 | 2024-10-08 | Complexity       | W   | 0.232      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     5475 | 2024-10-07 | FURIA            | L   | 0.225      | -            | -                | -                | -         |    -6.78 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     5500 | 2024-10-07 | PaiN Gaming      | W   | 0.224      | -            | -                | -                | -         |     0.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     6958 | 2024-09-15 | Complexity       | L   | 0.076      | -            | -                | -                | -         |    -2.39 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     7042 | 2024-09-14 | Fnatic           | W   | 0.070      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     7141 | 2024-09-12 | Complexity       | L   | 0.058      | -            | -                | -                | -         |    -1.81 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     7190 | 2024-09-11 | Imperial Esports | L   | 0.052      | -            | -                | -                | -         |    -1.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     7269 | 2024-09-10 | Rooster          | W   | 0.043      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($487,287.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.683 | $80,000.00     | $54,620.37      |
| 2024-11-03 |      0.403 | $25,000.00     | $10,065.97      |
| 2024-10-13 |      0.265 | $42,000.00     | $11,112.50      |
| 2024-09-22 |      0.124 | $12,000.00     | $1,488.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
