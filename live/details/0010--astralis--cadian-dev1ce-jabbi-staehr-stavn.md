### Roster Details<br />
Team Name: Astralis<br />
Roster: cadiaN, dev1ce, jabbi, Staehr, stavn<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1709.6<br />
<br />
Final Rank Value (1709.6) = Starting Rank Value (1854.9) + Head To Head Adjustments (-145.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.828[<sup>1</sup>](#table2)
- Bounty Collected: 0.688[<sup>2</sup>](#table1)
- Opponent Network: 0.393[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.727<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1854.9
- 400 + ( ( 0.727 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1854.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      120 | 2025-02-23 | FaZe Clan       | W   | 1.000      | 1.000        | 0.753 (0.753)    | 0.478 (0.478)    | 1 (1.000) |    22.63 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           40 |      169 | 2025-02-22 | MOUZ            | L   | 1.000      | -            | -                | -                | -         |    -8.54 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           39 |      229 | 2025-02-21 | The MongolZ     | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.574 (0.574)    | 1 (1.000) |    24.98 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           38 |      262 | 2025-02-20 | HEROIC          | L   | 1.000      | -            | -                | -                | -         |   -29.72 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           37 |      282 | 2025-02-18 | BIG             | W   | 1.000      | 1.000        | 0.248 (0.248)    | 0.572 (0.572)    | 1 (1.000) |     4.32 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           36 |      315 | 2025-02-17 | MIBR            | W   | 1.000      | 1.000        | 0.142 (0.142)    | 0.465 (0.465)    | 1 (1.000) |     4.23 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           35 |      378 | 2025-02-16 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -10.95 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           34 |      423 | 2025-02-15 | SAW             | W   | 1.000      | 1.000        | 0.266 (0.266)    | 0.326 (0.326)    | 1 (1.000) |     2.18 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           33 |      495 | 2025-02-14 | PaiN Gaming     | L   | 1.000      | -            | -                | -                | -         |   -21.91 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           32 |      564 | 2025-02-11 | BetBoom Team    | W   | 1.000      | -            | -                | -                | -         |     0.90 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           31 |      572 | 2025-02-11 | Zero Tenacity   | W   | 1.000      | -            | -                | -                | -         |     0.28 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           30 |      599 | 2025-02-10 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -30.57 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           29 |      608 | 2025-02-10 | OG              | W   | 1.000      | -            | -                | -                | -         |     0.33 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           28 |      642 | 2025-02-09 | PARIVISION      | W   | 1.000      | -            | -                | -                | -         |     0.17 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           27 |      647 | 2025-02-09 | 500             | W   | 1.000      | -            | -                | -                | -         |     0.79 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           26 |      722 | 2025-02-08 | 9INE            | W   | 1.000      | -            | -                | -                | -         |     0.32 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           25 |     1008 | 2025-02-04 | GamerLegion     | L   | 1.000      | -            | -                | -                | -         |   -22.26 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           24 |     1036 | 2025-02-03 | FURIA           | W   | 1.000      | 1.000        | 0.094 (0.094)    | 0.379 (0.379)    | 1 (1.000) |     4.53 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           23 |     1052 | 2025-02-02 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -7.12 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           22 |     1101 | 2025-01-31 | PaiN Gaming     | W   | 0.998      | 1.000        | 0.323 (0.322)    | 0.549 (0.548)    | 1 (0.998) |     8.28 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           21 |     1112 | 2025-01-30 | FlyQuest        | W   | 0.991      | 1.000        | 0.105 (0.104)    | 0.235 (0.232)    | 1 (0.991) |     0.92 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           20 |     1123 | 2025-01-29 | MIBR            | L   | 0.983      | -            | -                | -                | -         |   -27.53 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           19 |     1169 | 2025-01-18 | Natus Vincere   | L   | 0.912      | -            | -                | -                | -         |   -18.17 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           18 |     1196 | 2025-01-15 | Wildcard        | W   | 0.890      | -            | -                | -                | -         |     1.93 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           17 |     2828 | 2024-11-23 | Passion UA      | L   | 0.542      | -            | -                | -                | -         |   -16.89 | br0, cadiaN, jabbi, Staehr, stavn    |
|           16 |     2918 | 2024-11-23 | Eternal Fire    | W   | 0.536      | -            | -                | -                | 1 (0.536) |     8.70 | br0, cadiaN, jabbi, Staehr, stavn    |
|           15 |     3004 | 2024-11-22 | B8              | W   | 0.529      | -            | -                | -                | 1 (0.529) |     0.36 | br0, cadiaN, jabbi, Staehr, stavn    |
|           14 |     3061 | 2024-11-21 | Sashi Esport    | L   | 0.524      | -            | -                | -                | -         |   -16.38 | br0, cadiaN, jabbi, Staehr, stavn    |
|           13 |     3076 | 2024-11-20 | 9Pandas         | L   | 0.522      | -            | -                | -                | -         |   -16.26 | br0, cadiaN, jabbi, Staehr, stavn    |
|           12 |     4157 | 2024-11-02 | Team Spirit     | L   | 0.397      | -            | -                | -                | -         |    -4.00 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           11 |     4274 | 2024-10-31 | MOUZ            | W   | 0.383      | 1.000        | 1.000 (0.383)    | 0.470 (0.180)    | -         |     8.33 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           10 |     4346 | 2024-10-29 | Natus Vincere   | W   | 0.375      | 1.000        | 0.557 (0.209)    | 0.473 (0.177)    | -         |     3.94 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            9 |     5359 | 2024-10-09 | Virtus.pro      | L   | 0.237      | -            | -                | -                | -         |    -5.55 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            8 |     5427 | 2024-10-08 | Team Falcons    | L   | 0.231      | -            | -                | -                | -         |    -2.97 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            7 |     5481 | 2024-10-07 | Eternal Fire    | W   | 0.225      | -            | -                | -                | -         |     3.96 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            6 |     6215 | 2024-09-26 | Team Spirit     | L   | 0.151      | -            | -                | -                | -         |    -1.48 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            5 |     6306 | 2024-09-25 | Team Vitality   | L   | 0.144      | -            | -                | -                | -         |    -1.88 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            4 |     7015 | 2024-09-14 | Complexity      | L   | 0.071      | -            | -                | -                | -         |    -2.18 | br0, dev1ce, jabbi, Staehr, stavn    |
|            3 |     7103 | 2024-09-13 | Rooster         | W   | 0.064      | -            | -                | -                | -         |     0.00 | br0, dev1ce, jabbi, Staehr, stavn    |
|            2 |     7201 | 2024-09-11 | Complexity      | L   | 0.051      | -            | -                | -                | -         |    -1.57 | br0, dev1ce, jabbi, Staehr, stavn    |
|            1 |     7268 | 2024-09-10 | Fnatic          | L   | 0.043      | -            | -                | -                | -         |    -1.34 | br0, dev1ce, jabbi, Staehr, stavn    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($204,119.58)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.62) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $150,000.00    | $150,000.00     |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.403 | $85,000.00     | $34,224.31      |
| 2024-10-13 |      0.265 | $5,000.00      | $1,322.92       |
| 2024-09-29 |      0.170 | $10,000.00     | $1,704.17       |
| 2024-09-22 |      0.124 | $7,000.00      | $868.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
