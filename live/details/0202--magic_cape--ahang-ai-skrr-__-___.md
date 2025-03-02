### Roster Details<br />
Team Name: Magic Cape<br />
Roster: AHang, AI, skrr, 夜岚, 金闪火<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
<br />
Final Rank Value:  711.2<br />
<br />
Final Rank Value (711.2) = Starting Rank Value (681.5) + Head To Head Adjustments (29.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.5
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 681.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      308 | 2025-02-17 | Boring Players        | L   | 1.000      | -            | -                | -                | -         |   -22.93 | AHang, AI, skrr, 夜岚, 金闪火       |
|           12 |      310 | 2025-02-16 | TakeMeAway Gaming     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |     4.75 | AHang, AI, skrr, 夜岚, 金闪火       |
|           11 |      319 | 2025-02-16 | FengDa Gaming         | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.553 (0.079)    | 0 (0.000) |    15.45 | AHang, AI, skrr, 夜岚, 金闪火       |
|           10 |     1313 | 2024-12-28 | FengDa Gaming         | W   | 0.777      | 0.143        | 0.008 (0.001)    | 0.553 (0.061)    | 0 (0.000) |    13.30 | AHang, AI, skrr, 夜岚, 金闪火       |
|            9 |     1422 | 2024-12-22 | Change The Game       | W   | 0.737      | 0.143        | 0.061 (0.006)    | 0.221 (0.023)    | 0 (0.000) |    14.44 | AHang, AI, skrr, 夜岚, 金闪火       |
|            8 |     3686 | 2024-11-10 | Win New Star          | L   | 0.457      | -            | -                | -                | -         |    -8.16 | AHang, skrr, 深渊之王, 野玫瑰の幻想, 金闪火 |
|            7 |     3690 | 2024-11-09 | WITS                  | W   | 0.456      | 0.143        | 0.000 (0.000)    | 0.042 (0.003)    | 0 (0.000) |     5.37 | AHang, skrr, 深渊之王, 野玫瑰の幻想, 金闪火 |
|            6 |     3763 | 2024-11-08 | Secret (Chinese team) | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     5.05 | AHang, skrr, 深渊之王, 野玫瑰の幻想, 金闪火 |
|            5 |     3770 | 2024-11-08 | Znynn                 | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.75 | AHang, skrr, 深渊之王, 野玫瑰の幻想, 金闪火 |
|            4 |     5620 | 2024-10-05 | StudFarm              | L   | 0.217      | -            | -                | -                | -         |    -4.14 | skrr, 夜岚, 深渊之王, 金闪火, 阿杭        |
|            3 |     5623 | 2024-10-05 | Change The Game       | W   | 0.217      | 0.143        | 0.061 (0.002)    | 0.221 (0.007)    | 0 (0.000) |     4.39 | skrr, 夜岚, 深渊之王, 金闪火, 阿杭        |
|            2 |     5680 | 2024-10-04 | FengDa Gaming         | L   | 0.211      | -            | -                | -                | -         |    -3.15 | skrr, 夜岚, 深渊之王, 金闪火, 阿杭        |
|            1 |     5686 | 2024-10-04 | ShanghaiBaiDuRen      | W   | 0.211      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.67 | skrr, 夜岚, 深渊之王, 金闪火, 阿杭        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,325.99)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.777 | $1,370.09      | $1,064.86       |
| 2024-11-10 |      0.457 | $557.16        | $254.75         |
| 2024-10-06 |      0.224 | $28.50         | $6.38           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
