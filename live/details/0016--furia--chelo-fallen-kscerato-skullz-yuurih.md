### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1449.5<br />
<br />
Final Rank Value (1449.5) = Starting Rank Value (1433.4) + Head To Head Adjustments (16.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.571[<sup>2</sup>](#table1)
- Opponent Network: 0.250[<sup>2</sup>](#table1)
- LAN Wins: 0.752[<sup>2</sup>](#table1)

The average of these factors is 0.517<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1433.4
- 400 + ( ( 0.517 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1433.4


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
|           32 |     1036 | 2025-02-03 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -4.53 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           31 |     1065 | 2025-02-01 | Natus Vincere    | L   | 1.000      | -            | -                | -                | -         |    -5.78 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           30 |     1105 | 2025-01-31 | Wildcard         | W   | 0.997      | 1.000        | 0.178 (0.178)    | 0.422 (0.421)    | 1 (0.997) |    11.55 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           29 |     1119 | 2025-01-29 | Imperial Female  | W   | 0.984      | 1.000        | 0.136 (0.134)    | 0.162 (0.159)    | 1 (0.984) |     2.81 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           28 |     1167 | 2025-01-19 | BetBoom Team     | L   | 0.917      | -            | -                | -                | -         |   -25.68 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           27 |     1187 | 2025-01-17 | Nemiga Gaming    | W   | 0.904      | 0.363        | 0.176 (0.058)    | 0.345 (0.113)    | -         |     2.15 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           26 |     2033 | 2024-12-08 | FaZe Clan        | L   | 0.636      | -            | -                | -                | -         |    -1.77 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           25 |     2109 | 2024-12-07 | PaiN Gaming      | W   | 0.629      | 1.000        | 0.323 (0.203)    | 0.549 (0.345)    | 1 (0.629) |    12.96 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           24 |     2160 | 2024-12-05 | Team Liquid      | L   | 0.621      | -            | -                | -                | -         |    -7.99 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           23 |     2193 | 2024-12-05 | Team Vitality    | L   | 0.616      | -            | -                | -                | -         |    -1.44 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           22 |     2201 | 2024-12-04 | Team Spirit      | W   | 0.615      | 1.000        | 1.000 (0.615)    | 0.658 (0.405)    | 1 (0.615) |    18.21 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           21 |     2389 | 2024-12-01 | BIG              | W   | 0.594      | 1.000        | 0.248 (0.148)    | 0.572 (0.340)    | 1 (0.594) |    10.48 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           20 |     2465 | 2024-11-30 | Wildcard         | W   | 0.588      | 1.000        | 0.178 (0.105)    | 0.422 (0.248)    | 1 (0.588) |     6.65 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           19 |     2548 | 2024-11-30 | Imperial Esports | W   | 0.583      | 1.000        | -                | 0.562 (0.328)    | 1 (0.583) |     1.47 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           18 |     2576 | 2024-11-29 | GamerLegion      | L   | 0.581      | -            | -                | -                | -         |    -5.98 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           17 |     3414 | 2024-11-15 | M80              | W   | 0.483      | -            | -                | -                | 1 (0.483) |     0.99 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           16 |     3425 | 2024-11-15 | 9z Team          | W   | 0.483      | -            | -                | -                | 1 (0.483) |     0.41 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           15 |     3484 | 2024-11-14 | Team Liquid      | L   | 0.476      | -            | -                | -                | -         |    -6.07 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           14 |     3541 | 2024-11-12 | BLUEJAYS         | W   | 0.468      | -            | -                | -                | 1 (0.468) |     2.41 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           13 |     3571 | 2024-11-12 | Case Esports     | W   | 0.463      | -            | -                | -                | -         |     0.22 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           12 |     3591 | 2024-11-11 | Legacy           | L   | 0.461      | -            | -                | -                | -         |   -13.89 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           11 |     5198 | 2024-10-12 | MOUZ             | L   | 0.258      | -            | -                | -                | -         |    -0.37 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           10 |     5354 | 2024-10-09 | Natus Vincere    | W   | 0.238      | 0.624        | 0.557 (0.083)    | 0.473 (0.070)    | -         |     6.08 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            9 |     5475 | 2024-10-07 | MOUZ             | W   | 0.225      | 0.624        | 1.000 (0.140)    | -                | -         |     6.78 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            8 |     5501 | 2024-10-07 | FaZe Clan        | W   | 0.224      | 0.624        | 0.753 (0.105)    | 0.478 (0.067)    | -         |     6.60 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            7 |     6852 | 2024-09-17 | Team Spirit      | L   | 0.090      | -            | -                | -                | -         |    -0.12 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            6 |     6947 | 2024-09-15 | RED Canids       | W   | 0.077      | -            | -                | -                | -         |     0.09 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            5 |     7014 | 2024-09-14 | ATOX Esports     | W   | 0.071      | -            | -                | -                | -         |     0.30 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            4 |     7073 | 2024-09-13 | Virtus.pro       | L   | 0.065      | -            | -                | -                | -         |    -0.46 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            3 |     7111 | 2024-09-13 | RED Canids       | W   | 0.063      | -            | -                | -                | -         |     0.07 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            2 |     7149 | 2024-09-12 | Team Vitality    | L   | 0.057      | -            | -                | -                | -         |    -0.12 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            1 |     7214 | 2024-09-11 | Team Falcons     | W   | 0.050      | -            | -                | -                | -         |     0.03 | chelo, FalleN, KSCERATO, skullz, yuurih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,117.25)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-10-13 |      0.265 | $20,000.00     | $5,291.67       |
| 2024-09-22 |      0.124 | $17,500.00     | $2,170.49       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
