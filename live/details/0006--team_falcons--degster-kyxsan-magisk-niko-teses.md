### Roster Details<br />
Team Name: Team Falcons<br />
Roster: degster, kyxsan, Magisk, NiKo, TeSeS<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1848.2<br />
<br />
Final Rank Value (1848.2) = Starting Rank Value (1914.5) + Head To Head Adjustments (-66.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.968[<sup>1</sup>](#table2)
- Bounty Collected: 0.733[<sup>2</sup>](#table1)
- Opponent Network: 0.402[<sup>2</sup>](#table1)
- LAN Wins: 0.930[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1914.5
- 400 + ( ( 0.758 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1914.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |       88 | 2025-02-23 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |   -14.76 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           42 |      136 | 2025-02-22 | FaZe Clan          | W   | 1.000      | 1.000        | 0.744 (0.744)    | 0.482 (0.482)    | 1 (1.000) |    17.01 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           41 |      214 | 2025-02-21 | Eternal Fire       | W   | 1.000      | 1.000        | 0.591 (0.591)    | 0.512 (0.512)    | 1 (1.000) |    16.01 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           40 |      306 | 2025-02-17 | MOUZ               | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.473 (0.473)    | 1 (1.000) |    17.40 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           39 |      366 | 2025-02-16 | Astralis           | W   | 1.000      | 1.000        | 0.609 (0.609)    | 0.787 (0.787)    | 1 (1.000) |    10.94 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           38 |      409 | 2025-02-15 | PaiN Gaming        | L   | 1.000      | -            | -                | -                | -         |   -24.65 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           37 |      489 | 2025-02-14 | FlyQuest           | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.239 (0.239)    | 1 (1.000) |     0.68 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           36 |      588 | 2025-02-10 | BetBoom Team       | W   | 1.000      | -            | -                | -                | -         |     0.50 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           35 |      599 | 2025-02-10 | TEAM NEXT LEVEL    | W   | 1.000      | -            | -                | -                | -         |     0.09 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           34 |     1036 | 2025-02-02 | G2 Esports         | L   | 1.000      | -            | -                | -                | -         |   -16.67 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           33 |     1065 | 2025-02-01 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |   -14.93 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           32 |     1156 | 2025-01-19 | Eternal Fire       | L   | 0.925      | -            | -                | -                | -         |   -16.03 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           31 |     1182 | 2025-01-15 | ENCE               | W   | 0.899      | -            | -                | -                | -         |     0.25 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           30 |     1816 | 2024-12-12 | G2 Esports         | L   | 0.677      | -            | -                | -                | -         |   -11.85 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           29 |     2037 | 2024-12-07 | Natus Vincere      | W   | 0.643      | 1.000        | 0.555 (0.357)    | 0.478 (0.308)    | 1 (0.643) |     5.51 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           28 |     2098 | 2024-12-07 | Team Spirit        | L   | 0.637      | -            | -                | -                | -         |    -8.42 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           27 |     2142 | 2024-12-06 | The MongolZ        | L   | 0.631      | -            | -                | -                | -         |    -8.25 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           26 |     2165 | 2024-12-05 | FaZe Clan          | W   | 0.625      | 1.000        | 0.744 (0.465)    | 0.482 (0.301)    | 1 (0.625) |     9.90 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           25 |     2184 | 2024-12-04 | BIG                | W   | 0.623      | 1.000        | 0.246 (0.153)    | 0.579 (0.361)    | 1 (0.623) |     1.85 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           24 |     2911 | 2024-11-22 | Passion UA         | W   | 0.544      | -            | -                | -                | 1 (0.544) |     0.12 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           23 |     3000 | 2024-11-21 | Ninjas in Pyjamas  | W   | 0.536      | -            | -                | -                | 1 (0.536) |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           22 |     3041 | 2024-11-21 | BIG                | L   | 0.532      | -            | -                | -                | -         |   -15.28 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           21 |     3065 | 2024-11-20 | PARIVISION         | W   | 0.530      | -            | -                | -                | -         |     0.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           20 |     4050 | 2024-11-03 | The MongolZ        | L   | 0.413      | -            | -                | -                | -         |    -6.11 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           19 |     4131 | 2024-11-02 | OG                 | W   | 0.406      | 0.934        | -                | 1.000 (0.379)    | -         |     0.05 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           18 |     4527 | 2024-10-26 | Fnatic             | W   | 0.358      | -            | -                | -                | -         |     0.10 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           17 |     4644 | 2024-10-23 | Ninjas in Pyjamas  | W   | 0.340      | -            | -                | -                | -         |     0.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           16 |     4682 | 2024-10-23 | Legacy             | W   | 0.337      | 0.934        | -                | 0.554 (0.175)    | -         |     0.04 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           15 |     4797 | 2024-10-20 | ENCE               | L   | 0.319      | -            | -                | -                | -         |    -9.98 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           14 |     4834 | 2024-10-19 | B8                 | W   | 0.313      | -            | -                | -                | -         |     0.12 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           13 |     4939 | 2024-10-17 | ENCE               | W   | 0.299      | -            | -                | -                | -         |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           12 |     4952 | 2024-10-17 | Rebels Gaming      | W   | 0.297      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           11 |     5201 | 2024-10-12 | Natus Vincere      | L   | 0.266      | -            | -                | -                | -         |    -6.38 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           10 |     5343 | 2024-10-09 | Team Vitality      | W   | 0.246      | 0.624        | 1.000 (0.154)    | -                | -         |     3.85 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            9 |     5415 | 2024-10-08 | Astralis           | W   | 0.240      | -            | -                | -                | -         |     3.07 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            8 |     5477 | 2024-10-07 | G2 Esports         | W   | 0.233      | 0.624        | 1.000 (0.145)    | -                | -         |     2.57 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            7 |     6773 | 2024-09-18 | MIBR               | L   | 0.104      | -            | -                | -                | -         |    -3.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            6 |     6848 | 2024-09-17 | Virtus.pro         | W   | 0.098      | -            | -                | -                | -         |     0.59 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            5 |     7350 | 2024-09-08 | HEROIC             | W   | 0.039      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            4 |     7424 | 2024-09-07 | Ninjas in Pyjamas  | W   | 0.032      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            3 |     7586 | 2024-09-05 | HEROIC             | L   | 0.020      | -            | -                | -                | -         |    -0.61 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            2 |     7659 | 2024-09-04 | Lynn Vision Gaming | W   | 0.013      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            1 |     7738 | 2024-09-03 | Ninjas in Pyjamas  | L   | 0.005      | -            | -                | -                | -         |    -0.17 | degster, kyxsan, NertZ, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($311,845.76)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.93) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $187,500.00    | $187,500.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.691 | $45,000.00     | $31,092.71      |
| 2024-11-03 |      0.413 | $150,000.00    | $61,937.50      |
| 2024-10-20 |      0.319 | $40,000.00     | $12,752.78      |
| 2024-10-13 |      0.273 | $20,000.00     | $5,455.56       |
| 2024-09-22 |      0.132 | $23,500.00     | $3,107.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
