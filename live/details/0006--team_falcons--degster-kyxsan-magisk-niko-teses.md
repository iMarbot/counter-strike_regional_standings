### Roster Details<br />
Team Name: Team Falcons<br />
Roster: degster, kyxsan, Magisk, NiKo, TeSeS<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1850.5<br />
<br />
Final Rank Value (1850.5) = Starting Rank Value (1916.6) + Head To Head Adjustments (-66.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.974[<sup>1</sup>](#table2)
- Bounty Collected: 0.734[<sup>2</sup>](#table1)
- Opponent Network: 0.397[<sup>2</sup>](#table1)
- LAN Wins: 0.929[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1916.6
- 400 + ( ( 0.758 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1916.6


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
|           42 |      103 | 2025-02-23 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |   -14.80 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           41 |      151 | 2025-02-22 | FaZe Clan          | W   | 1.000      | 1.000        | 0.753 (0.753)    | 0.478 (0.478)    | 1 (1.000) |    16.99 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           40 |      226 | 2025-02-21 | Eternal Fire       | W   | 1.000      | 1.000        | 0.599 (0.599)    | 0.509 (0.509)    | 1 (1.000) |    15.99 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           39 |      318 | 2025-02-17 | MOUZ               | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.470 (0.470)    | 1 (1.000) |    17.35 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           38 |      378 | 2025-02-16 | Astralis           | W   | 1.000      | 1.000        | 0.619 (0.619)    | 0.786 (0.786)    | 1 (1.000) |    10.95 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           37 |      421 | 2025-02-15 | PaiN Gaming        | L   | 1.000      | -            | -                | -                | -         |   -24.67 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           36 |      501 | 2025-02-14 | FlyQuest           | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.235 (0.235)    | 1 (1.000) |     0.66 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           35 |      600 | 2025-02-10 | BetBoom Team       | W   | 1.000      | -            | -                | -                | -         |     0.49 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           34 |      611 | 2025-02-10 | TEAM NEXT LEVEL    | W   | 1.000      | -            | -                | -                | -         |     0.09 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           33 |     1048 | 2025-02-02 | G2 Esports         | L   | 1.000      | -            | -                | -                | -         |   -16.94 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           32 |     1077 | 2025-02-01 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |   -14.96 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           31 |     1168 | 2025-01-19 | Eternal Fire       | L   | 0.917      | -            | -                | -                | -         |   -15.88 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           30 |     1194 | 2025-01-15 | ENCE               | W   | 0.891      | -            | -                | -                | -         |     0.24 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           29 |     1828 | 2024-12-12 | G2 Esports         | L   | 0.668      | -            | -                | -                | -         |   -11.92 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           28 |     2049 | 2024-12-07 | Natus Vincere      | W   | 0.635      | 1.000        | 0.557 (0.354)    | 0.473 (0.300)    | 1 (0.635) |     5.31 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           27 |     2110 | 2024-12-07 | Team Spirit        | L   | 0.629      | -            | -                | -                | -         |    -8.38 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           26 |     2154 | 2024-12-06 | The MongolZ        | L   | 0.622      | -            | -                | -                | -         |    -8.23 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           25 |     2177 | 2024-12-05 | FaZe Clan          | W   | 0.617      | 1.000        | 0.753 (0.465)    | 0.478 (0.295)    | 1 (0.617) |     9.76 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           24 |     2196 | 2024-12-04 | BIG                | W   | 0.615      | 1.000        | 0.248 (0.153)    | 0.572 (0.352)    | 1 (0.615) |     1.79 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           23 |     2923 | 2024-11-22 | Passion UA         | W   | 0.535      | -            | -                | -                | 1 (0.535) |     0.12 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           22 |     3012 | 2024-11-21 | Ninjas in Pyjamas  | W   | 0.528      | -            | -                | -                | 1 (0.528) |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           21 |     3053 | 2024-11-21 | BIG                | L   | 0.524      | -            | -                | -                | -         |   -15.07 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           20 |     3077 | 2024-11-20 | PARIVISION         | W   | 0.522      | -            | -                | -                | -         |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           19 |     4062 | 2024-11-03 | The MongolZ        | L   | 0.405      | -            | -                | -                | -         |    -6.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           18 |     4143 | 2024-11-02 | OG                 | W   | 0.398      | 0.934        | -                | 1.000 (0.372)    | -         |     0.05 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           17 |     4539 | 2024-10-26 | Fnatic             | W   | 0.350      | -            | -                | -                | -         |     0.10 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           16 |     4656 | 2024-10-23 | Ninjas in Pyjamas  | W   | 0.332      | -            | -                | -                | -         |     0.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           15 |     4694 | 2024-10-23 | Legacy             | W   | 0.329      | 0.934        | -                | 0.549 (0.169)    | -         |     0.04 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           14 |     4809 | 2024-10-20 | ENCE               | L   | 0.311      | -            | -                | -                | -         |    -9.72 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           13 |     4846 | 2024-10-19 | B8                 | W   | 0.305      | -            | -                | -                | -         |     0.11 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           12 |     4951 | 2024-10-17 | ENCE               | W   | 0.290      | -            | -                | -                | -         |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           11 |     4964 | 2024-10-17 | Rebels Gaming      | W   | 0.289      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           10 |     5213 | 2024-10-12 | Natus Vincere      | L   | 0.257      | -            | -                | -                | -         |    -6.23 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            9 |     5355 | 2024-10-09 | Team Vitality      | W   | 0.238      | 0.624        | 1.000 (0.148)    | -                | -         |     3.69 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            8 |     5427 | 2024-10-08 | Astralis           | W   | 0.231      | -            | -                | -                | -         |     2.97 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            7 |     5489 | 2024-10-07 | G2 Esports         | W   | 0.224      | 0.624        | 1.000 (0.140)    | -                | -         |     2.41 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            6 |     6785 | 2024-09-18 | MIBR               | L   | 0.096      | -            | -                | -                | -         |    -2.82 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            5 |     6860 | 2024-09-17 | Virtus.pro         | W   | 0.090      | -            | -                | -                | -         |     0.54 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            4 |     7362 | 2024-09-08 | HEROIC             | W   | 0.031      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            3 |     7436 | 2024-09-07 | Ninjas in Pyjamas  | W   | 0.024      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            2 |     7598 | 2024-09-05 | HEROIC             | L   | 0.011      | -            | -                | -                | -         |    -0.36 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            1 |     7671 | 2024-09-04 | Lynn Vision Gaming | W   | 0.005      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($309,563.61)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.94) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $187,500.00    | $187,500.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.683 | $45,000.00     | $30,723.96      |
| 2024-11-03 |      0.405 | $150,000.00    | $60,708.33      |
| 2024-10-20 |      0.311 | $40,000.00     | $12,425.00      |
| 2024-10-13 |      0.265 | $20,000.00     | $5,291.67       |
| 2024-09-22 |      0.124 | $23,500.00     | $2,914.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
