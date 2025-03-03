### Roster Details<br />
Team Name: HEROIC<br />
Roster: LNZ, SunPayus, tN1R, xfl0ud, yxngstxr<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1199.2<br />
<br />
Final Rank Value (1199.2) = Starting Rank Value (1075.8) + Head To Head Adjustments (123.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.126[<sup>2</sup>](#table1)
- LAN Wins: 0.245[<sup>2</sup>](#table1)

The average of these factors is 0.338<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.8
- 400 + ( ( 0.338 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1075.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      262 | 2025-02-20 | Astralis             | W   | 1.000      | 0.143        | 0.619 (0.088)    | 0.786 (0.112)    | 0 (0.000) |    29.72 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           31 |      566 | 2025-02-11 | Metizport            | W   | 1.000      | 0.143        | 0.074 (0.011)    | 0.507 (0.072)    | 0 (0.000) |     9.63 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           30 |      574 | 2025-02-11 | BIG                  | W   | 1.000      | 0.143        | 0.248 (0.035)    | 0.572 (0.082)    | 0 (0.000) |    24.36 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           29 |      594 | 2025-02-10 | 3DMAX                | L   | 1.000      | -            | -                | -                | -         |    -2.58 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           28 |      605 | 2025-02-10 | Zero Tenacity        | W   | 1.000      | 0.143        | -                | 0.684 (0.098)    | 0 (0.000) |     5.74 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           27 |      651 | 2025-02-09 | PARIVISION           | L   | 1.000      | -            | -                | -                | -         |   -27.38 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           26 |      728 | 2025-02-08 | Passion UA           | W   | 1.000      | 0.143        | -                | 0.545 (0.078)    | -         |    12.68 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           25 |     1104 | 2025-01-31 | BIG                  | L   | 0.998      | -            | -                | -                | -         |    -5.18 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           24 |     1107 | 2025-01-30 | Eternal Fire         | L   | 0.992      | -            | -                | -                | -         |    -0.58 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           23 |     1116 | 2025-01-29 | Team Liquid          | W   | 0.985      | 1.000        | 0.187 (0.184)    | 0.379 (0.374)    | 1 (0.985) |    27.47 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           22 |     1158 | 2025-01-23 | Team Spirit          | L   | 0.944      | -            | -                | -                | -         |    -0.26 | LNZ, maden, SunPayus, xfl0ud, yxngstxr |
|           21 |     1178 | 2025-01-18 | Team Liquid          | W   | 0.910      | 0.363        | 0.187 (0.062)    | 0.379 (0.125)    | -         |    26.17 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           20 |     1199 | 2025-01-14 | 3DMAX                | W   | 0.884      | 0.363        | 0.298 (0.095)    | 0.528 (0.169)    | -         |    26.11 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           19 |     3188 | 2024-11-18 | Dynamo Eclot         | L   | 0.507      | -            | -                | -                | -         |    -8.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           18 |     3230 | 2024-11-17 | Cloud9               | L   | 0.501      | -            | -                | -                | -         |   -11.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           17 |     3268 | 2024-11-17 | MOUZ                 | L   | 0.497      | -            | -                | -                | -         |    -0.11 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           16 |     3300 | 2024-11-16 | Rebels Gaming        | W   | 0.495      | -            | -                | -                | 1 (0.495) |     1.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           15 |     4808 | 2024-10-20 | Nemiga Gaming        | W   | 0.311      | 0.500        | 0.176 (0.027)    | -                | -         |     4.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           14 |     4866 | 2024-10-19 | BC.Game Esports      | L   | 0.303      | -            | -                | -                | -         |    -5.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           13 |     4938 | 2024-10-17 | Nemiga Gaming        | W   | 0.291      | 0.500        | 0.176 (0.026)    | -                | -         |     3.71 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           12 |     4957 | 2024-10-17 | Fluxo                | W   | 0.290      | 0.624        | -                | 0.423 (0.077)    | 1 (0.290) |     2.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           11 |     5007 | 2024-10-16 | SAW                  | W   | 0.285      | 0.500        | 0.266 (0.038)    | -                | -         |     7.22 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           10 |     5029 | 2024-10-16 | Nemiga Gaming        | W   | 0.283      | 0.624        | 0.176 (0.031)    | -                | 1 (0.283) |     3.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            9 |     5070 | 2024-10-15 | Sashi Esport         | W   | 0.278      | 0.500        | -                | 0.499 (0.069)    | -         |     2.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            8 |     6126 | 2024-09-27 | BetBoom Team         | L   | 0.158      | -            | -                | -                | -         |    -2.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            7 |     6232 | 2024-09-26 | Passion UA           | W   | 0.150      | -            | -                | -                | -         |     2.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            6 |     6283 | 2024-09-25 | Natus Vincere Junior | L   | 0.145      | -            | -                | -                | -         |    -2.97 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            5 |     7362 | 2024-09-08 | Team Falcons         | L   | 0.031      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            4 |     7466 | 2024-09-07 | FlyQuest             | W   | 0.023      | -            | -                | -                | 1 (0.023) |     0.39 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            3 |     7532 | 2024-09-06 | FaZe Clan            | L   | 0.017      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            2 |     7598 | 2024-09-05 | Team Falcons         | W   | 0.011      | -            | -                | -                | 1 (0.011) |     0.36 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            1 |     7683 | 2024-09-04 | Eternal Fire         | L   | 0.004      | -            | -                | -                | -         |    -0.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,330.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.964 | $25,000.00     | $24,107.64      |
| 2024-10-20 |      0.311 | $17,000.00     | $5,281.81       |
| 2024-10-19 |      0.305 | $25,000.00     | $7,623.26       |
| 2024-09-28 |      0.165 | $2,000.00      | $329.49         |
| 2024-09-22 |      0.124 | $12,000.00     | $1,488.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
