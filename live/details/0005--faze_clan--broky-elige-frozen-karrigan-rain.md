### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, EliGE, frozen, karrigan, rain<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1853.7<br />
<br />
Final Rank Value (1853.7) = Starting Rank Value (1926.2) + Head To Head Adjustments (-72.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.890[<sup>1</sup>](#table2)
- Bounty Collected: 0.797[<sup>2</sup>](#table1)
- Opponent Network: 0.365[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.763<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1926.2
- 400 + ( ( 0.763 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1926.2


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
|           40 |      120 | 2025-02-23 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -22.63 | broky, EliGE, frozen, karrigan, rain |
|           39 |      151 | 2025-02-22 | Team Falcons      | L   | 1.000      | -            | -                | -                | -         |   -16.99 | broky, EliGE, frozen, karrigan, rain |
|           38 |      209 | 2025-02-21 | SAW               | W   | 1.000      | 1.000        | 0.266 (0.266)    | 0.326 (0.326)    | 1 (1.000) |     1.01 | broky, EliGE, frozen, karrigan, rain |
|           37 |      368 | 2025-02-16 | MOUZ              | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.470 (0.470)    | 1 (1.000) |    15.39 | broky, EliGE, frozen, karrigan, rain |
|           36 |      433 | 2025-02-15 | Eternal Fire      | W   | 1.000      | 1.000        | 0.599 (0.599)    | 0.509 (0.509)    | 1 (1.000) |    15.05 | broky, EliGE, frozen, karrigan, rain |
|           35 |      505 | 2025-02-14 | SAW               | W   | 1.000      | 1.000        | 0.266 (0.266)    | 0.326 (0.326)    | 1 (1.000) |     0.94 | broky, EliGE, frozen, karrigan, rain |
|           34 |      966 | 2025-02-04 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |   -15.90 | broky, EliGE, frozen, karrigan, rain |
|           33 |     1025 | 2025-02-03 | G2 Esports        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.355 (0.355)    | 1 (1.000) |    13.15 | broky, EliGE, frozen, karrigan, rain |
|           32 |     1043 | 2025-02-02 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -14.19 | broky, EliGE, frozen, karrigan, rain |
|           31 |     1072 | 2025-02-01 | BIG               | W   | 1.000      | 1.000        | 0.248 (0.248)    | 0.572 (0.572)    | 1 (1.000) |     2.52 | broky, EliGE, frozen, karrigan, rain |
|           30 |     1177 | 2025-01-18 | PaiN Gaming       | L   | 0.911      | -            | -                | -                | -         |   -24.15 | broky, EliGE, frozen, karrigan, rain |
|           29 |     1190 | 2025-01-16 | M80               | W   | 0.898      | -            | -                | -                | -         |     0.15 | broky, EliGE, frozen, karrigan, rain |
|           28 |     1657 | 2024-12-15 | Team Spirit       | L   | 0.683      | -            | -                | -                | -         |    -8.97 | broky, frozen, karrigan, rain, ropz  |
|           27 |     1726 | 2024-12-14 | G2 Esports        | W   | 0.676      | 1.000        | 1.000 (0.676)    | -                | 1 (0.676) |     8.82 | broky, frozen, karrigan, rain, ropz  |
|           26 |     1817 | 2024-12-13 | Team Vitality     | W   | 0.670      | 1.000        | 1.000 (0.670)    | 0.442 (0.296)    | 1 (0.670) |    11.23 | broky, frozen, karrigan, rain, ropz  |
|           25 |     2033 | 2024-12-08 | FURIA             | W   | 0.636      | 1.000        | -                | 0.379 (0.241)    | 1 (0.636) |     1.77 | broky, frozen, karrigan, rain, ropz  |
|           24 |     2120 | 2024-12-06 | G2 Esports        | L   | 0.628      | -            | -                | -                | -         |   -11.84 | broky, frozen, karrigan, rain, ropz  |
|           23 |     2158 | 2024-12-05 | MOUZ              | W   | 0.621      | 1.000        | 1.000 (0.621)    | 0.470 (0.292)    | 1 (0.621) |    11.87 | broky, frozen, karrigan, rain, ropz  |
|           22 |     2177 | 2024-12-05 | Team Falcons      | L   | 0.617      | -            | -                | -                | -         |    -9.76 | broky, frozen, karrigan, rain, ropz  |
|           21 |     2198 | 2024-12-04 | Wildcard          | W   | 0.615      | 1.000        | -                | 0.422 (0.260)    | -         |     0.84 | broky, frozen, karrigan, rain, ropz  |
|           20 |     3176 | 2024-11-19 | Cloud9            | W   | 0.510      | -            | -                | -                | -         |     0.07 | broky, frozen, karrigan, rain, ropz  |
|           19 |     3181 | 2024-11-19 | Fnatic            | W   | 0.509      | -            | -                | -                | -         |     0.16 | broky, frozen, karrigan, rain, ropz  |
|           18 |     3223 | 2024-11-18 | Team Vitality     | L   | 0.503      | -            | -                | -                | -         |    -7.76 | broky, frozen, karrigan, rain, ropz  |
|           17 |     3263 | 2024-11-17 | Team Falcons      | W   | 0.497      | -            | -                | -                | -         |     0.02 | broky, frozen, karrigan, rain, ropz  |
|           16 |     3307 | 2024-11-16 | Cloud9            | W   | 0.495      | -            | -                | -                | -         |     0.05 | broky, frozen, karrigan, rain, ropz  |
|           15 |     4221 | 2024-11-01 | Team Spirit       | L   | 0.390      | -            | -                | -                | -         |    -4.85 | broky, frozen, karrigan, rain, ropz  |
|           14 |     4278 | 2024-10-30 | Natus Vincere     | W   | 0.382      | 1.000        | 0.557 (0.213)    | -                | -         |     3.09 | broky, frozen, karrigan, rain, ropz  |
|           13 |     4345 | 2024-10-30 | MOUZ              | L   | 0.376      | -            | -                | -                | -         |    -4.61 | broky, frozen, karrigan, rain, ropz  |
|           12 |     5343 | 2024-10-09 | MOUZ              | L   | 0.238      | -            | -                | -                | -         |    -2.96 | broky, frozen, karrigan, rain, ropz  |
|           11 |     5422 | 2024-10-08 | Team Liquid       | W   | 0.232      | -            | -                | -                | -         |     0.74 | broky, frozen, karrigan, rain, ropz  |
|           10 |     5472 | 2024-10-07 | PaiN Gaming       | W   | 0.225      | -            | -                | -                | -         |     1.21 | broky, frozen, karrigan, rain, ropz  |
|            9 |     5501 | 2024-10-07 | FURIA             | L   | 0.224      | -            | -                | -                | -         |    -6.60 | broky, frozen, karrigan, rain, ropz  |
|            8 |     6019 | 2024-09-28 | Natus Vincere     | L   | 0.165      | -            | -                | -                | -         |    -4.00 | broky, frozen, karrigan, rain, ropz  |
|            7 |     6134 | 2024-09-27 | Team Liquid       | W   | 0.158      | -            | -                | -                | -         |     0.49 | broky, frozen, karrigan, rain, ropz  |
|            6 |     6239 | 2024-09-26 | Team Falcons      | W   | 0.149      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            5 |     6321 | 2024-09-25 | G2 Esports        | L   | 0.143      | -            | -                | -                | -         |    -3.07 | broky, frozen, karrigan, rain, ropz  |
|            4 |     6844 | 2024-09-17 | Complexity        | L   | 0.091      | -            | -                | -                | -         |    -2.84 | broky, frozen, karrigan, rain, ropz  |
|            3 |     7532 | 2024-09-06 | HEROIC            | W   | 0.017      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            2 |     7589 | 2024-09-05 | Ninjas in Pyjamas | W   | 0.012      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |
|            1 |     7684 | 2024-09-04 | FlyQuest          | W   | 0.004      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($248,208.91)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.75) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $87,500.00     | $87,500.00      |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-12-15 |      0.683 | $170,000.00    | $116,068.29     |
| 2024-11-03 |      0.403 | $25,000.00     | $10,065.97      |
| 2024-10-13 |      0.265 | $6,000.00      | $1,587.50       |
| 2024-09-29 |      0.170 | $40,000.00     | $6,816.67       |
| 2024-09-22 |      0.124 | $17,500.00     | $2,170.49       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
