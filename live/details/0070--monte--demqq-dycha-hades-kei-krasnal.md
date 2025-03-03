### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, KEi, kRaSnaL<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  895.4<br />
<br />
Final Rank Value (895.4) = Starting Rank Value (840.5) + Head To Head Adjustments (55.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.5
- 400 + ( ( 0.220 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 840.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     1596 | 2024-12-16 | Dynamo Eclot        | L   | 0.691      | -            | -                | -                | -         |    -6.33 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           30 |     1811 | 2024-12-13 | Metizport           | L   | 0.670      | -            | -                | -                | -         |    -6.36 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           29 |     1937 | 2024-12-10 | Aurora Gaming       | W   | 0.651      | 0.435        | 0.019 (0.005)    | 0.514 (0.145)    | 0 (0.000) |     8.52 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           28 |     1965 | 2024-12-09 | GUN5 Esports        | W   | 0.645      | 0.435        | 0.103 (0.029)    | 0.505 (0.141)    | 0 (0.000) |    11.85 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           27 |     2805 | 2024-11-24 | ENCE                | L   | 0.544      | -            | -                | -                | -         |    -5.47 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           26 |     2899 | 2024-11-23 | Johnny Speeds       | W   | 0.537      | 0.143        | 0.039 (0.003)    | 0.345 (0.026)    | 0 (0.000) |     9.50 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           25 |     3679 | 2024-11-10 | FAVBET Team         | W   | 0.451      | 0.143        | 0.031 (0.002)    | 0.801 (0.052)    | 0 (0.000) |     6.82 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           24 |     3863 | 2024-11-07 | 500                 | L   | 0.430      | -            | -                | -                | -         |    -4.42 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           23 |     3908 | 2024-11-06 | Team Spirit Academy | W   | 0.424      | 0.143        | 0.068 (0.004)    | 0.702 (0.043)    | 0 (0.000) |     7.99 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           22 |     4490 | 2024-10-27 | SAW                 | L   | 0.357      | -            | -                | -                | -         |    -0.81 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           21 |     4543 | 2024-10-26 | Legacy              | W   | 0.350      | 0.500        | 0.036 (0.006)    | 0.549 (0.096)    | 1 (0.350) |     6.01 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           20 |     4599 | 2024-10-25 | MIBR                | W   | 0.345      | 0.500        | 0.142 (0.024)    | 0.465 (0.080)    | 1 (0.345) |    10.36 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           19 |     4615 | 2024-10-25 | PaiN Gaming         | L   | 0.343      | -            | -                | -                | -         |    -0.16 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           18 |     5263 | 2024-10-11 | SINNERS Esports     | L   | 0.251      | -            | -                | -                | -         |    -3.46 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           17 |     5509 | 2024-10-07 | Metizport           | W   | 0.223      | 0.435        | 0.074 (0.007)    | 0.507 (0.049)    | 0 (0.000) |     5.50 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           16 |     5623 | 2024-10-05 | Adventurers         | W   | 0.210      | -            | -                | -                | 0 (0.000) |     2.68 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           15 |     5735 | 2024-10-03 | Team Spirit Academy | L   | 0.197      | -            | -                | -                | -         |    -2.51 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           14 |     5932 | 2024-09-30 | ECSTATIC            | W   | 0.177      | 0.435        | 0.033 (0.003)    | 0.820 (0.063)    | 0 (0.000) |     3.03 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           13 |     6245 | 2024-09-26 | 3DMAX               | L   | 0.149      | -            | -                | -                | -         |    -0.07 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           12 |     6385 | 2024-09-24 | Rebels Gaming       | W   | 0.138      | -            | -                | -                | -         |     1.52 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           11 |     6388 | 2024-09-24 | GameAgents          | W   | 0.138      | -            | -                | -                | -         |     1.26 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           10 |     6421 | 2024-09-24 | BIG                 | W   | 0.136      | 0.384        | 0.248 (0.013)    | 0.572 (0.030)    | -         |     4.19 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            9 |     6448 | 2024-09-23 | 4wb                 | W   | 0.132      | -            | -                | -                | -         |     0.32 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            8 |     6475 | 2024-09-23 | Ins (Polish team)   | W   | 0.132      | -            | -                | -                | -         |     1.13 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            7 |     6497 | 2024-09-23 | PARIVISION          | W   | 0.130      | -            | -                | -                | -         |     1.35 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            6 |     6722 | 2024-09-19 | Sashi Esport        | W   | 0.103      | -            | -                | -                | -         |     2.12 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            5 |     6859 | 2024-09-17 | EYEBALLERS          | W   | 0.090      | -            | -                | -                | -         |     1.27 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            4 |     7155 | 2024-09-12 | Nemiga Gaming       | L   | 0.056      | -            | -                | -                | -         |    -0.49 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            3 |     7490 | 2024-09-07 | GamerLegion         | L   | 0.022      | -            | -                | -                | -         |    -0.48 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            2 |     7639 | 2024-09-05 | SINNERS Esports     | W   | 0.009      | -            | -                | -                | -         |     0.17 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            1 |     7694 | 2024-09-04 | PARIVISION          | L   | 0.003      | -            | -                | -                | -         |    -0.06 | DemQQ, dycha, hades, KEi, kRaSnaL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,690.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.698 | $5,000.00      | $3,492.36       |
| 2024-11-24 |      0.544 | $4,262.60      | $2,318.97       |
| 2024-11-09 |      0.444 | $15.18         | $6.74           |
| 2024-10-27 |      0.358 | $10,000.00     | $3,583.80       |
| 2024-09-26 |      0.151 | $1,500.00      | $226.18         |
| 2024-09-08 |      0.031 | $2,000.00      | $61.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
