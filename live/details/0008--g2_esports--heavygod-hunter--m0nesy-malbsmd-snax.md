### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HeavyGod, huNter-, m0NESY, malbsMd, Snax<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1804.3<br />
<br />
Final Rank Value (1804.3) = Starting Rank Value (1789.2) + Head To Head Adjustments (15.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.704[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.757[<sup>2</sup>](#table1)

The average of these factors is 0.694<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1789.2
- 400 + ( ( 0.694 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1789.2


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
|           32 |     1025 | 2025-02-03 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |   -13.15 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           31 |     1048 | 2025-02-02 | Team Falcons      | W   | 1.000      | 1.000        | 0.939 (0.939)    | 0.609 (0.609)    | 1 (1.000) |    16.94 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           30 |     1073 | 2025-02-01 | Virtus.pro        | L   | 1.000      | -            | -                | -                | -         |   -24.29 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           29 |     1144 | 2025-01-25 | Eternal Fire      | L   | 0.958      | -            | -                | -                | -         |   -13.71 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           28 |     1156 | 2025-01-23 | BetBoom Team      | W   | 0.945      | 0.769        | -                | 0.379 (0.275)    | 1 (0.945) |     0.48 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           27 |     1159 | 2025-01-19 | BIG               | W   | 0.919      | 0.363        | -                | 0.572 (0.191)    | -         |     3.05 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           26 |     1179 | 2025-01-17 | B8                | W   | 0.906      | 0.363        | -                | 0.586 (0.192)    | -         |     0.51 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           25 |     1726 | 2024-12-14 | FaZe Clan         | L   | 0.676      | -            | -                | -                | -         |    -8.82 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           24 |     1828 | 2024-12-12 | Team Falcons      | W   | 0.668      | 1.000        | 0.939 (0.628)    | 0.609 (0.407)    | 1 (0.668) |    11.92 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           23 |     2120 | 2024-12-06 | FaZe Clan         | W   | 0.628      | 1.000        | 0.753 (0.473)    | 0.478 (0.300)    | 1 (0.628) |    11.84 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           22 |     2159 | 2024-12-05 | 3DMAX             | W   | 0.621      | 1.000        | 0.298 (0.185)    | 0.528 (0.328)    | 1 (0.621) |     4.19 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           21 |     2181 | 2024-12-05 | BIG               | W   | 0.616      | 1.000        | 0.248 (0.153)    | 0.572 (0.353)    | 1 (0.616) |     2.56 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           20 |     2203 | 2024-12-04 | The MongolZ       | L   | 0.614      | -            | -                | -                | -         |    -6.58 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           19 |     2917 | 2024-11-23 | Team Spirit       | W   | 0.536      | -            | -                | -                | 1 (0.536) |    11.83 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           18 |     3005 | 2024-11-22 | 3DMAX             | L   | 0.529      | -            | -                | -                | -         |   -13.18 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           17 |     3064 | 2024-11-21 | 9Pandas           | W   | 0.523      | -            | -                | -                | 1 (0.523) |     0.22 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           16 |     3081 | 2024-11-20 | Ninjas in Pyjamas | W   | 0.521      | -            | -                | -                | 1 (0.521) |     0.08 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           15 |     4101 | 2024-11-03 | Team Spirit       | W   | 0.403      | 1.000        | 1.000 (0.403)    | 0.658 (0.265)    | 1 (0.403) |     9.24 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           14 |     4170 | 2024-11-02 | Team Vitality     | W   | 0.396      | 1.000        | 1.000 (0.396)    | -                | -         |     8.03 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           13 |     4264 | 2024-10-31 | Team Spirit       | W   | 0.384      | 1.000        | 1.000 (0.384)    | 0.658 (0.253)    | -         |     9.04 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           12 |     4341 | 2024-10-30 | Team Liquid       | W   | 0.376      | -            | -                | -                | -         |     2.13 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           11 |     5430 | 2024-10-08 | Eternal Fire      | L   | 0.231      | -            | -                | -                | -         |    -2.73 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           10 |     5489 | 2024-10-07 | Team Falcons      | L   | 0.224      | -            | -                | -                | -         |    -2.41 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            9 |     5976 | 2024-09-29 | Natus Vincere     | W   | 0.170      | -            | -                | -                | -         |     2.05 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            8 |     6059 | 2024-09-28 | Team Vitality     | W   | 0.164      | 0.729        | 1.000 (0.119)    | -                | -         |     3.43 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            7 |     6148 | 2024-09-27 | Team Spirit       | W   | 0.157      | 0.729        | 1.000 (0.115)    | -                | -         |     3.74 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            6 |     6226 | 2024-09-26 | Natus Vincere     | L   | 0.150      | -            | -                | -                | -         |    -2.94 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            5 |     6321 | 2024-09-25 | FaZe Clan         | W   | 0.143      | -            | -                | -                | -         |     3.07 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            4 |     6583 | 2024-09-21 | Natus Vincere     | L   | 0.118      | -            | -                | -                | -         |    -2.33 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            3 |     6638 | 2024-09-20 | Team Liquid       | W   | 0.111      | -            | -                | -                | -         |     0.64 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            2 |     7353 | 2024-09-08 | MIBR              | W   | 0.031      | -            | -                | -                | -         |     0.13 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            1 |     7615 | 2024-09-05 | 3DMAX             | W   | 0.011      | -            | -                | -                | -         |     0.09 | huNter-, m0NESY, malbsMd, NiKo, Snax     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($329,538.08)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2025-01-26 |      0.964 | $17,500.00     | $16,875.35      |
| 2024-12-15 |      0.683 | $80,000.00     | $54,620.37      |
| 2024-11-03 |      0.403 | $500,000.00    | $201,319.44     |
| 2024-10-13 |      0.265 | $4,000.00      | $1,058.33       |
| 2024-09-29 |      0.170 | $200,000.00    | $34,083.33      |
| 2024-09-22 |      0.124 | $45,000.00     | $5,581.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
