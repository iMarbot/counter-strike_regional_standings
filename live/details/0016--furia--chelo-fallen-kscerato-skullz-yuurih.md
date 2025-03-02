### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1452.3<br />
<br />
Final Rank Value (1452.3) = Starting Rank Value (1438.4) + Head To Head Adjustments (14.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.493[<sup>1</sup>](#table2)
- Bounty Collected: 0.572[<sup>2</sup>](#table1)
- Opponent Network: 0.256[<sup>2</sup>](#table1)
- LAN Wins: 0.759[<sup>2</sup>](#table1)

The average of these factors is 0.520<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1438.4
- 400 + ( ( 0.520 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1438.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1024 | 2025-02-03 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -4.66 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           31 |     1053 | 2025-02-01 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -5.78 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           30 |     1093 | 2025-01-31 | Wildcard         | W   | 1.000      | 1.000        | 0.176 (0.176)    | 0.428 (0.428)    | 1 (1.000) |    11.37 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           29 |     1107 | 2025-01-29 | Imperial Female  | W   | 0.993      | 1.000        | 0.134 (0.133)    | 0.165 (0.164)    | 1 (0.993) |     2.81 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           28 |     1155 | 2025-01-19 | BetBoom Team     | L   | 0.925      | -            | -                | -                | -         |   -25.92 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           27 |     1175 | 2025-01-17 | Nemiga Gaming    | W   | 0.912      | 0.363        | 0.177 (0.058)    | 0.351 (0.116)    | -         |     2.17 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           26 |     2021 | 2024-12-08 | FaZe Clan        | L   | 0.644      | -            | -                | -                | -         |    -1.85 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           25 |     2097 | 2024-12-07 | PaiN Gaming      | W   | 0.637      | 1.000        | 0.318 (0.203)    | 0.555 (0.354)    | 1 (0.637) |    12.98 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           24 |     2148 | 2024-12-05 | Team Liquid      | L   | 0.629      | -            | -                | -                | -         |    -8.10 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           23 |     2181 | 2024-12-05 | Team Vitality    | L   | 0.624      | -            | -                | -                | -         |    -1.48 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           22 |     2189 | 2024-12-04 | Team Spirit      | W   | 0.623      | 1.000        | 1.000 (0.623)    | 0.663 (0.413)    | 1 (0.623) |    18.43 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           21 |     2377 | 2024-12-01 | BIG              | W   | 0.603      | 1.000        | 0.246 (0.148)    | 0.579 (0.349)    | 1 (0.603) |    10.55 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           20 |     2453 | 2024-11-30 | Wildcard         | W   | 0.596      | 1.000        | 0.176 (0.105)    | 0.428 (0.255)    | 1 (0.596) |     6.58 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           19 |     2536 | 2024-11-30 | Imperial Esports | W   | 0.592      | 1.000        | -                | 0.564 (0.333)    | 1 (0.592) |     1.49 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           18 |     2564 | 2024-11-29 | GamerLegion      | L   | 0.589      | -            | -                | -                | -         |    -6.11 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           17 |     3402 | 2024-11-15 | M80              | W   | 0.492      | -            | -                | -                | 1 (0.492) |     0.97 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           16 |     3413 | 2024-11-15 | 9z Team          | W   | 0.491      | -            | -                | -                | 1 (0.491) |     0.42 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           15 |     3472 | 2024-11-14 | Team Liquid      | L   | 0.484      | -            | -                | -                | -         |    -6.18 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           14 |     3529 | 2024-11-12 | BOSS             | W   | 0.476      | -            | -                | -                | 1 (0.476) |     0.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           13 |     3559 | 2024-11-12 | Case Esports     | W   | 0.471      | -            | -                | -                | -         |     0.22 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           12 |     3579 | 2024-11-11 | Legacy           | L   | 0.469      | -            | -                | -                | -         |   -14.16 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           11 |     5186 | 2024-10-12 | MOUZ             | L   | 0.267      | -            | -                | -                | -         |    -0.40 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           10 |     5342 | 2024-10-09 | Natus Vincere    | W   | 0.246      | 0.624        | 0.555 (0.085)    | 0.478 (0.073)    | -         |     6.28 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            9 |     5463 | 2024-10-07 | MOUZ             | W   | 0.233      | 0.624        | 1.000 (0.146)    | -                | -         |     7.02 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            8 |     5489 | 2024-10-07 | FaZe Clan        | W   | 0.232      | 0.624        | 0.744 (0.108)    | 0.482 (0.070)    | -         |     6.83 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            7 |     6840 | 2024-09-17 | Team Spirit      | L   | 0.099      | -            | -                | -                | -         |    -0.13 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            6 |     6935 | 2024-09-15 | RED Canids       | W   | 0.085      | -            | -                | -                | -         |     0.10 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            5 |     7002 | 2024-09-14 | ATOX Esports     | W   | 0.079      | -            | -                | -                | -         |     0.33 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            4 |     7061 | 2024-09-13 | Virtus.pro       | L   | 0.073      | -            | -                | -                | -         |    -0.53 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            3 |     7099 | 2024-09-13 | RED Canids       | W   | 0.071      | -            | -                | -                | -         |     0.08 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            2 |     7137 | 2024-09-12 | Team Vitality    | L   | 0.065      | -            | -                | -                | -         |    -0.13 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            1 |     7202 | 2024-09-11 | Team Falcons     | W   | 0.058      | -            | -                | -                | -         |     0.03 | chelo, FalleN, KSCERATO, skullz, yuurih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,588.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-10-13 |      0.273 | $20,000.00     | $5,455.56       |
| 2024-09-22 |      0.132 | $17,500.00     | $2,313.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
