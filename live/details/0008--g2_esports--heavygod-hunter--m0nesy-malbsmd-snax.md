### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HeavyGod, huNter-, m0NESY, malbsMd, Snax<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1807.5<br />
<br />
Final Rank Value (1807.5) = Starting Rank Value (1794.0) + Head To Head Adjustments (13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.705[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.763[<sup>2</sup>](#table1)

The average of these factors is 0.698<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1794.0
- 400 + ( ( 0.698 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1794.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     1013 | 2025-02-03 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |   -13.38 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           32 |     1036 | 2025-02-02 | Team Falcons      | W   | 1.000      | 1.000        | 0.927 (0.927)    | 0.613 (0.613)    | 1 (1.000) |    16.67 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           31 |     1061 | 2025-02-01 | Virtus.pro        | L   | 1.000      | -            | -                | -                | -         |   -24.45 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           30 |     1132 | 2025-01-25 | Eternal Fire      | L   | 0.966      | -            | -                | -                | -         |   -14.10 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           29 |     1144 | 2025-01-23 | BetBoom Team      | W   | 0.953      | 0.769        | -                | 0.382 (0.280)    | 1 (0.953) |     0.48 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           28 |     1147 | 2025-01-19 | BIG               | W   | 0.927      | 0.363        | -                | 0.579 (0.195)    | -         |     3.02 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           27 |     1167 | 2025-01-17 | B8                | W   | 0.914      | 0.363        | -                | 0.590 (0.196)    | -         |     0.51 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           26 |     1714 | 2024-12-14 | FaZe Clan         | L   | 0.685      | -            | -                | -                | -         |    -9.11 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           25 |     1816 | 2024-12-12 | Team Falcons      | W   | 0.677      | 1.000        | 0.927 (0.627)    | 0.613 (0.415)    | 1 (0.677) |    11.85 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           24 |     2108 | 2024-12-06 | FaZe Clan         | W   | 0.636      | 1.000        | 0.744 (0.473)    | 0.482 (0.307)    | 1 (0.636) |    11.79 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           23 |     2147 | 2024-12-05 | 3DMAX             | W   | 0.629      | 1.000        | 0.295 (0.186)    | 0.535 (0.336)    | 1 (0.629) |     4.17 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           22 |     2169 | 2024-12-05 | BIG               | W   | 0.625      | 1.000        | 0.246 (0.153)    | 0.579 (0.361)    | 1 (0.625) |     2.54 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           21 |     2191 | 2024-12-04 | The MongolZ       | L   | 0.623      | -            | -                | -                | -         |    -6.79 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           20 |     2905 | 2024-11-23 | Team Spirit       | W   | 0.544      | -            | -                | -                | 1 (0.544) |    11.90 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           19 |     2993 | 2024-11-22 | 3DMAX             | L   | 0.538      | -            | -                | -                | -         |   -13.45 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           18 |     3052 | 2024-11-21 | 9Pandas           | W   | 0.531      | -            | -                | -                | 1 (0.531) |     0.22 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           17 |     3069 | 2024-11-20 | Ninjas in Pyjamas | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.08 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           16 |     4089 | 2024-11-03 | Team Spirit       | W   | 0.411      | 1.000        | 1.000 (0.411)    | 0.663 (0.272)    | 1 (0.411) |     9.35 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           15 |     4158 | 2024-11-02 | Team Vitality     | W   | 0.404      | 1.000        | 1.000 (0.404)    | -                | -         |     8.12 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           14 |     4252 | 2024-10-31 | Team Spirit       | W   | 0.392      | 1.000        | 1.000 (0.392)    | 0.663 (0.260)    | -         |     9.17 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           13 |     4329 | 2024-10-30 | Team Liquid       | W   | 0.385      | -            | -                | -                | -         |     2.15 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           12 |     5418 | 2024-10-08 | Eternal Fire      | L   | 0.239      | -            | -                | -                | -         |    -2.89 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           11 |     5477 | 2024-10-07 | Team Falcons      | L   | 0.233      | -            | -                | -                | -         |    -2.57 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           10 |     5964 | 2024-09-29 | Natus Vincere     | W   | 0.179      | -            | -                | -                | -         |     2.14 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            9 |     6047 | 2024-09-28 | Team Vitality     | W   | 0.172      | 0.729        | 1.000 (0.125)    | -                | -         |     3.57 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            8 |     6136 | 2024-09-27 | Team Spirit       | W   | 0.165      | 0.729        | 1.000 (0.120)    | -                | -         |     3.91 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            7 |     6214 | 2024-09-26 | Natus Vincere     | L   | 0.159      | -            | -                | -                | -         |    -3.11 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            6 |     6309 | 2024-09-25 | FaZe Clan         | W   | 0.151      | -            | -                | -                | -         |     3.21 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            5 |     6571 | 2024-09-21 | Natus Vincere     | L   | 0.126      | -            | -                | -                | -         |    -2.50 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            4 |     6626 | 2024-09-20 | Team Liquid       | W   | 0.120      | -            | -                | -                | -         |     0.68 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            3 |     7341 | 2024-09-08 | MIBR              | W   | 0.040      | -            | -                | -                | -         |     0.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            2 |     7603 | 2024-09-05 | 3DMAX             | W   | 0.019      | -            | -                | -                | -         |     0.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            1 |     7722 | 2024-09-03 | Iberian Soul      | W   | 0.006      | -            | -                | -                | -         |     0.00 | huNter-, m0NESY, malbsMd, NiKo, Snax     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($336,474.68)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2025-01-26 |      0.973 | $17,500.00     | $17,018.75      |
| 2024-12-15 |      0.691 | $80,000.00     | $55,275.93      |
| 2024-11-03 |      0.411 | $500,000.00    | $205,416.67     |
| 2024-10-13 |      0.273 | $4,000.00      | $1,091.11       |
| 2024-09-29 |      0.179 | $200,000.00    | $35,722.22      |
| 2024-09-22 |      0.132 | $45,000.00     | $5,950.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
