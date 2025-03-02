### Roster Details<br />
Team Name: HEROIC<br />
Roster: LNZ, SunPayus, tN1R, xfl0ud, yxngstxr<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1202.7<br />
<br />
Final Rank Value (1202.7) = Starting Rank Value (1079.0) + Head To Head Adjustments (123.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.531[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.128[<sup>2</sup>](#table1)
- LAN Wins: 0.250[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1079.0
- 400 + ( ( 0.340 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1079.0


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
|           33 |      250 | 2025-02-20 | Astralis             | W   | 1.000      | 0.143        | 0.609 (0.087)    | 0.787 (0.112)    | 0 (0.000) |    29.67 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           32 |      554 | 2025-02-11 | Metizport            | W   | 1.000      | 0.143        | -                | 0.513 (0.073)    | 0 (0.000) |     9.58 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           31 |      562 | 2025-02-11 | BIG                  | W   | 1.000      | 0.143        | 0.246 (0.035)    | 0.579 (0.083)    | 0 (0.000) |    24.25 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           30 |      582 | 2025-02-10 | 3DMAX                | L   | 1.000      | -            | -                | -                | -         |    -2.62 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           29 |      593 | 2025-02-10 | Zero Tenacity        | W   | 1.000      | 0.143        | -                | 0.692 (0.099)    | -         |     5.69 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           28 |      639 | 2025-02-09 | PARIVISION           | L   | 1.000      | -            | -                | -                | -         |   -27.45 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           27 |      716 | 2025-02-08 | Passion UA           | W   | 1.000      | 0.143        | -                | 0.557 (0.080)    | -         |    12.59 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           26 |     1092 | 2025-01-31 | BIG                  | L   | 1.000      | -            | -                | -                | -         |    -5.29 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           25 |     1095 | 2025-01-30 | Eternal Fire         | L   | 1.000      | -            | -                | -                | -         |    -0.60 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           24 |     1104 | 2025-01-29 | Team Liquid          | W   | 0.993      | 1.000        | 0.186 (0.184)    | 0.383 (0.380)    | 1 (0.993) |    27.67 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           23 |     1146 | 2025-01-23 | Team Spirit          | L   | 0.953      | -            | -                | -                | -         |    -0.27 | LNZ, maden, SunPayus, xfl0ud, yxngstxr |
|           22 |     1166 | 2025-01-18 | Team Liquid          | W   | 0.918      | 0.363        | 0.186 (0.062)    | 0.383 (0.127)    | -         |    26.39 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           21 |     1187 | 2025-01-14 | 3DMAX                | W   | 0.892      | 0.363        | 0.295 (0.095)    | 0.535 (0.173)    | -         |    26.32 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           20 |     3176 | 2024-11-18 | Dynamo Eclot         | L   | 0.516      | -            | -                | -                | -         |    -8.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           19 |     3218 | 2024-11-17 | Cloud9               | L   | 0.509      | -            | -                | -                | -         |   -11.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           18 |     3256 | 2024-11-17 | MOUZ                 | L   | 0.505      | -            | -                | -                | -         |    -0.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           17 |     3288 | 2024-11-16 | Rebels Gaming        | W   | 0.504      | -            | -                | -                | 1 (0.504) |     1.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           16 |     4796 | 2024-10-20 | Nemiga Gaming        | W   | 0.319      | 0.500        | 0.177 (0.028)    | -                | -         |     4.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           15 |     4854 | 2024-10-19 | BC.Game Esports      | L   | 0.312      | -            | -                | -                | -         |    -5.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           14 |     4926 | 2024-10-17 | Nemiga Gaming        | W   | 0.299      | 0.500        | 0.177 (0.026)    | -                | -         |     3.81 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           13 |     4945 | 2024-10-17 | Fluxo                | W   | 0.298      | 0.624        | -                | 0.430 (0.080)    | 1 (0.298) |     2.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           12 |     4995 | 2024-10-16 | SAW                  | W   | 0.293      | 0.500        | 0.262 (0.038)    | -                | -         |     7.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           11 |     5017 | 2024-10-16 | Nemiga Gaming        | W   | 0.291      | 0.624        | 0.177 (0.032)    | -                | 1 (0.291) |     3.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           10 |     5058 | 2024-10-15 | Sashi Esport         | W   | 0.286      | 0.500        | -                | 0.503 (0.072)    | -         |     3.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            9 |     6114 | 2024-09-27 | BetBoom Team         | L   | 0.166      | -            | -                | -                | -         |    -3.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            8 |     6220 | 2024-09-26 | Passion UA           | W   | 0.158      | -            | -                | -                | -         |     2.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            7 |     6271 | 2024-09-25 | Natus Vincere Junior | L   | 0.154      | -            | -                | -                | -         |    -3.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            6 |     7350 | 2024-09-08 | Team Falcons         | L   | 0.039      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            5 |     7454 | 2024-09-07 | FlyQuest             | W   | 0.031      | -            | -                | -                | 1 (0.031) |     0.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            4 |     7520 | 2024-09-06 | FaZe Clan            | L   | 0.025      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            3 |     7586 | 2024-09-05 | Team Falcons         | W   | 0.020      | 0.889        | 0.927 (0.016)    | -                | 1 (0.020) |     0.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            2 |     7671 | 2024-09-04 | Eternal Fire         | L   | 0.012      | -            | -                | -                | -         |    -0.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            1 |     7739 | 2024-09-03 | FaZe Clan            | W   | 0.005      | -            | -                | -                | 1 (0.005) |     0.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,994.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.973 | $25,000.00     | $24,312.50      |
| 2024-10-20 |      0.319 | $17,000.00     | $5,421.11       |
| 2024-10-19 |      0.313 | $25,000.00     | $7,828.13       |
| 2024-09-28 |      0.173 | $2,000.00      | $345.88         |
| 2024-09-22 |      0.132 | $12,000.00     | $1,586.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
