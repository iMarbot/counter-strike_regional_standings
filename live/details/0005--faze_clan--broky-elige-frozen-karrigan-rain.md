### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, EliGE, frozen, karrigan, rain<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1851.9<br />
<br />
Final Rank Value (1851.9) = Starting Rank Value (1924.6) + Head To Head Adjustments (-72.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.886[<sup>1</sup>](#table2)
- Bounty Collected: 0.797[<sup>2</sup>](#table1)
- Opponent Network: 0.369[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.763<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1924.6
- 400 + ( ( 0.763 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1924.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      105 | 2025-02-23 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -22.65 | broky, EliGE, frozen, karrigan, rain |
|           40 |      136 | 2025-02-22 | Team Falcons      | L   | 1.000      | -            | -                | -                | -         |   -17.01 | broky, EliGE, frozen, karrigan, rain |
|           39 |      197 | 2025-02-21 | SAW               | W   | 1.000      | 1.000        | 0.262 (0.262)    | 0.329 (0.329)    | 1 (1.000) |     1.02 | broky, EliGE, frozen, karrigan, rain |
|           38 |      356 | 2025-02-16 | MOUZ              | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.473 (0.473)    | 1 (1.000) |    15.41 | broky, EliGE, frozen, karrigan, rain |
|           37 |      421 | 2025-02-15 | Eternal Fire      | W   | 1.000      | 1.000        | 0.591 (0.591)    | 0.512 (0.512)    | 1 (1.000) |    15.04 | broky, EliGE, frozen, karrigan, rain |
|           36 |      493 | 2025-02-14 | SAW               | W   | 1.000      | 1.000        | 0.262 (0.262)    | 0.329 (0.329)    | 1 (1.000) |     0.95 | broky, EliGE, frozen, karrigan, rain |
|           35 |      954 | 2025-02-04 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |   -15.92 | broky, EliGE, frozen, karrigan, rain |
|           34 |     1013 | 2025-02-03 | G2 Esports        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.359 (0.359)    | 1 (1.000) |    13.38 | broky, EliGE, frozen, karrigan, rain |
|           33 |     1031 | 2025-02-02 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -14.09 | broky, EliGE, frozen, karrigan, rain |
|           32 |     1060 | 2025-02-01 | BIG               | W   | 1.000      | 1.000        | 0.246 (0.246)    | 0.579 (0.579)    | 1 (1.000) |     2.55 | broky, EliGE, frozen, karrigan, rain |
|           31 |     1165 | 2025-01-18 | PaiN Gaming       | L   | 0.919      | -            | -                | -                | -         |   -24.36 | broky, EliGE, frozen, karrigan, rain |
|           30 |     1178 | 2025-01-16 | M80               | W   | 0.906      | -            | -                | -                | -         |     0.14 | broky, EliGE, frozen, karrigan, rain |
|           29 |     1645 | 2024-12-15 | Team Spirit       | L   | 0.691      | -            | -                | -                | -         |    -9.04 | broky, frozen, karrigan, rain, ropz  |
|           28 |     1714 | 2024-12-14 | G2 Esports        | W   | 0.685      | 1.000        | 1.000 (0.685)    | -                | 1 (0.685) |     9.11 | broky, frozen, karrigan, rain, ropz  |
|           27 |     1805 | 2024-12-13 | Team Vitality     | W   | 0.678      | 1.000        | 1.000 (0.678)    | 0.445 (0.301)    | 1 (0.678) |    11.46 | broky, frozen, karrigan, rain, ropz  |
|           26 |     2021 | 2024-12-08 | FURIA             | W   | 0.644      | 1.000        | -                | 0.384 (0.248)    | 1 (0.644) |     1.85 | broky, frozen, karrigan, rain, ropz  |
|           25 |     2108 | 2024-12-06 | G2 Esports        | L   | 0.636      | -            | -                | -                | -         |   -11.79 | broky, frozen, karrigan, rain, ropz  |
|           24 |     2146 | 2024-12-05 | MOUZ              | W   | 0.629      | 1.000        | 1.000 (0.629)    | 0.473 (0.298)    | 1 (0.629) |    12.06 | broky, frozen, karrigan, rain, ropz  |
|           23 |     2165 | 2024-12-05 | Team Falcons      | L   | 0.625      | -            | -                | -                | -         |    -9.90 | broky, frozen, karrigan, rain, ropz  |
|           22 |     2186 | 2024-12-04 | Wildcard          | W   | 0.623      | 1.000        | -                | 0.428 (0.267)    | -         |     0.85 | broky, frozen, karrigan, rain, ropz  |
|           21 |     3164 | 2024-11-19 | Cloud9            | W   | 0.518      | -            | -                | -                | -         |     0.07 | broky, frozen, karrigan, rain, ropz  |
|           20 |     3169 | 2024-11-19 | Fnatic            | W   | 0.517      | -            | -                | -                | -         |     0.17 | broky, frozen, karrigan, rain, ropz  |
|           19 |     3211 | 2024-11-18 | Team Vitality     | L   | 0.511      | -            | -                | -                | -         |    -7.81 | broky, frozen, karrigan, rain, ropz  |
|           18 |     3251 | 2024-11-17 | Team Falcons      | W   | 0.505      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz  |
|           17 |     3295 | 2024-11-16 | Cloud9            | W   | 0.503      | -            | -                | -                | -         |     0.06 | broky, frozen, karrigan, rain, ropz  |
|           16 |     4209 | 2024-11-01 | Team Spirit       | L   | 0.398      | -            | -                | -                | -         |    -4.91 | broky, frozen, karrigan, rain, ropz  |
|           15 |     4266 | 2024-10-30 | Natus Vincere     | W   | 0.390      | 1.000        | 0.555 (0.217)    | -                | -         |     3.24 | broky, frozen, karrigan, rain, ropz  |
|           14 |     4333 | 2024-10-30 | MOUZ              | L   | 0.384      | -            | -                | -                | -         |    -4.68 | broky, frozen, karrigan, rain, ropz  |
|           13 |     5331 | 2024-10-09 | MOUZ              | L   | 0.247      | -            | -                | -                | -         |    -3.05 | broky, frozen, karrigan, rain, ropz  |
|           12 |     5410 | 2024-10-08 | Team Liquid       | W   | 0.240      | -            | -                | -                | -         |     0.79 | broky, frozen, karrigan, rain, ropz  |
|           11 |     5460 | 2024-10-07 | PaiN Gaming       | W   | 0.233      | -            | -                | -                | -         |     1.25 | broky, frozen, karrigan, rain, ropz  |
|           10 |     5489 | 2024-10-07 | FURIA             | L   | 0.232      | -            | -                | -                | -         |    -6.83 | broky, frozen, karrigan, rain, ropz  |
|            9 |     6007 | 2024-09-28 | Natus Vincere     | L   | 0.173      | -            | -                | -                | -         |    -4.16 | broky, frozen, karrigan, rain, ropz  |
|            8 |     6122 | 2024-09-27 | Team Liquid       | W   | 0.166      | -            | -                | -                | -         |     0.53 | broky, frozen, karrigan, rain, ropz  |
|            7 |     6227 | 2024-09-26 | Team Falcons      | W   | 0.158      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            6 |     6309 | 2024-09-25 | G2 Esports        | L   | 0.151      | -            | -                | -                | -         |    -3.21 | broky, frozen, karrigan, rain, ropz  |
|            5 |     6832 | 2024-09-17 | Complexity        | L   | 0.100      | -            | -                | -                | -         |    -3.10 | broky, frozen, karrigan, rain, ropz  |
|            4 |     7520 | 2024-09-06 | HEROIC            | W   | 0.025      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            3 |     7577 | 2024-09-05 | Ninjas in Pyjamas | W   | 0.020      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |
|            2 |     7672 | 2024-09-04 | FlyQuest          | W   | 0.012      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |
|            1 |     7739 | 2024-09-03 | HEROIC            | L   | 0.005      | -            | -                | -                | -         |    -0.17 | broky, frozen, karrigan, rain, ropz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($250,327.18)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $87,500.00     | $87,500.00      |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-12-15 |      0.691 | $170,000.00    | $117,461.34     |
| 2024-11-03 |      0.411 | $25,000.00     | $10,270.83      |
| 2024-10-13 |      0.273 | $6,000.00      | $1,636.67       |
| 2024-09-29 |      0.179 | $40,000.00     | $7,144.44       |
| 2024-09-22 |      0.132 | $17,500.00     | $2,313.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
