### Roster Details<br />
Team Name: MIBR<br />
Roster: drop, exit, insani, Lucaozy, saffee<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1359.1<br />
<br />
Final Rank Value (1359.1) = Starting Rank Value (1450.5) + Head To Head Adjustments (-91.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.541[<sup>1</sup>](#table2)
- Bounty Collected: 0.559[<sup>2</sup>](#table1)
- Opponent Network: 0.252[<sup>2</sup>](#table1)
- LAN Wins: 0.748[<sup>2</sup>](#table1)

The average of these factors is 0.525<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1450.5
- 400 + ( ( 0.525 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1450.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |      315 | 2025-02-17 | Astralis                 | L   | 1.000      | -            | -                | -                | -         |    -4.23 | drop, exit, insani, Lucaozy, saffee |
|           54 |      389 | 2025-02-16 | 3DMAX                    | L   | 1.000      | -            | -                | -                | -         |    -7.15 | drop, exit, insani, Lucaozy, saffee |
|           53 |      432 | 2025-02-15 | Imperial Female          | W   | 1.000      | 1.000        | 0.136 (0.136)    | 0.162 (0.162)    | 1 (1.000) |     3.33 | drop, exit, insani, Lucaozy, saffee |
|           52 |      494 | 2025-02-14 | Wildcard                 | L   | 1.000      | -            | -                | -                | -         |   -16.85 | drop, exit, insani, Lucaozy, saffee |
|           51 |      623 | 2025-02-09 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -27.11 | drop, exit, insani, Lucaozy, saffee |
|           50 |      640 | 2025-02-09 | Sharks Esports           | W   | 1.000      | 0.143        | -                | 0.622 (0.089)    | -         |     3.12 | drop, exit, insani, Lucaozy, saffee |
|           49 |      691 | 2025-02-08 | Legacy                   | W   | 1.000      | 0.143        | -                | 0.549 (0.078)    | -         |     2.08 | drop, exit, insani, Lucaozy, saffee |
|           48 |     1103 | 2025-01-31 | Virtus.pro               | L   | 0.998      | -            | -                | -                | -         |    -8.75 | drop, exit, insani, Lucaozy, saffee |
|           47 |     1111 | 2025-01-30 | 3DMAX                    | L   | 0.991      | -            | -                | -                | -         |    -9.73 | drop, exit, insani, Lucaozy, saffee |
|           46 |     1123 | 2025-01-29 | Astralis                 | W   | 0.983      | 1.000        | 0.619 (0.609)    | 0.786 (0.773)    | 1 (0.983) |    27.53 | drop, exit, insani, Lucaozy, saffee |
|           45 |     1200 | 2025-01-14 | FlyQuest                 | L   | 0.883      | -            | -                | -                | -         |   -22.98 | drop, exit, insani, Lucaozy, saffee |
|           44 |     2051 | 2024-12-07 | MOUZ                     | L   | 0.634      | -            | -                | -                | -         |    -0.92 | drop, exit, insani, Lucaozy, saffee |
|           43 |     2115 | 2024-12-06 | Team Liquid              | L   | 0.628      | -            | -                | -                | -         |    -6.90 | drop, exit, insani, Lucaozy, saffee |
|           42 |     2156 | 2024-12-05 | Team Vitality            | L   | 0.622      | -            | -                | -                | -         |    -1.19 | drop, exit, insani, Lucaozy, saffee |
|           41 |     2182 | 2024-12-05 | Natus Vincere            | W   | 0.616      | 1.000        | 0.557 (0.343)    | 0.473 (0.291)    | 1 (0.616) |    16.29 | drop, exit, insani, Lucaozy, saffee |
|           40 |     2195 | 2024-12-04 | 3DMAX                    | W   | 0.615      | 1.000        | 0.298 (0.183)    | 0.528 (0.325)    | 1 (0.615) |    14.27 | drop, exit, insani, Lucaozy, saffee |
|           39 |     2316 | 2024-12-02 | FlyQuest                 | W   | 0.602      | 1.000        | 0.105 (0.063)    | 0.235 (0.141)    | 1 (0.602) |     3.40 | drop, exit, insani, Lucaozy, saffee |
|           38 |     2388 | 2024-12-01 | Rare Atom                | W   | 0.594      | 1.000        | 0.063 (0.038)    | 0.578 (0.343)    | 1 (0.594) |     1.69 | drop, exit, insani, Lucaozy, saffee |
|           37 |     2466 | 2024-11-30 | Passion UA               | L   | 0.588      | -            | -                | -                | -         |   -16.45 | drop, exit, insani, Lucaozy, saffee |
|           36 |     2555 | 2024-11-30 | The MongolZ              | L   | 0.583      | -            | -                | -                | -         |    -0.94 | drop, exit, insani, Lucaozy, saffee |
|           35 |     2575 | 2024-11-29 | Virtus.pro               | W   | 0.581      | 1.000        | 0.272 (0.158)    | 0.436 (0.253)    | 1 (0.581) |    14.24 | drop, exit, insani, Lucaozy, saffee |
|           34 |     3532 | 2024-11-13 | Complexity               | W   | 0.469      | -            | -                | -                | 1 (0.469) |     3.20 | drop, exit, insani, Lucaozy, saffee |
|           33 |     3561 | 2024-11-12 | Imperial Esports         | W   | 0.464      | -            | -                | -                | 1 (0.464) |     1.39 | drop, exit, insani, Lucaozy, saffee |
|           32 |     3584 | 2024-11-11 | KRÜ Esports              | W   | 0.462      | -            | -                | -                | 1 (0.462) |     0.28 | drop, exit, insani, Lucaozy, saffee |
|           31 |     4599 | 2024-10-25 | Monte                    | L   | 0.345      | -            | -                | -                | -         |   -10.36 | drop, exit, insani, Lucaozy, saffee |
|           30 |     4613 | 2024-10-25 | Legacy                   | L   | 0.344      | -            | -                | -                | -         |   -10.26 | drop, exit, insani, Lucaozy, saffee |
|           29 |     4773 | 2024-10-20 | PaiN Gaming              | L   | 0.312      | -            | -                | -                | -         |    -2.46 | drop, exit, insani, Lucaozy, saffee |
|           28 |     4841 | 2024-10-19 | BESTIA                   | W   | 0.306      | 0.450        | 0.069 (0.010)    | 0.472 (0.065)    | -         |     0.63 | drop, exit, insani, Lucaozy, saffee |
|           27 |     4927 | 2024-10-17 | PaiN Gaming              | L   | 0.293      | -            | -                | -                | -         |    -2.34 | drop, exit, insani, Lucaozy, saffee |
|           26 |     4980 | 2024-10-16 | RED Canids               | W   | 0.286      | -            | -                | -                | -         |     0.38 | drop, exit, insani, Lucaozy, saffee |
|           25 |     5328 | 2024-10-09 | RED Canids               | W   | 0.240      | -            | -                | -                | -         |     0.31 | drop, exit, insani, Lucaozy, saffee |
|           24 |     5336 | 2024-10-09 | RED Canids               | W   | 0.239      | -            | -                | -                | -         |     0.31 | drop, exit, insani, Lucaozy, saffee |
|           23 |     5398 | 2024-10-08 | KRÜ Esports              | W   | 0.233      | -            | -                | -                | -         |     0.13 | drop, exit, insani, Lucaozy, saffee |
|           22 |     5409 | 2024-10-08 | KRÜ Esports              | W   | 0.233      | -            | -                | -                | -         |     0.13 | drop, exit, insani, Lucaozy, saffee |
|           21 |     5423 | 2024-10-08 | PaiN Gaming              | L   | 0.232      | -            | -                | -                | -         |    -1.71 | drop, exit, insani, Lucaozy, saffee |
|           20 |     5426 | 2024-10-08 | PaiN Gaming              | L   | 0.232      | -            | -                | -                | -         |    -1.73 | drop, exit, insani, Lucaozy, saffee |
|           19 |     5514 | 2024-10-06 | Imperial Esports         | W   | 0.220      | 0.450        | 0.092 (0.009)    | -                | -         |     0.57 | drop, exit, insani, Lucaozy, saffee |
|           18 |     5515 | 2024-10-06 | Imperial Esports         | L   | 0.219      | -            | -                | -                | -         |    -6.37 | drop, exit, insani, Lucaozy, saffee |
|           17 |     5657 | 2024-10-04 | Fluxo                    | L   | 0.206      | -            | -                | -                | -         |    -6.09 | drop, exit, insani, Lucaozy, saffee |
|           16 |     5659 | 2024-10-04 | Fluxo                    | W   | 0.206      | -            | -                | -                | -         |     0.41 | drop, exit, insani, Lucaozy, saffee |
|           15 |     5758 | 2024-10-02 | Players (Brazilian team) | W   | 0.193      | -            | -                | -                | -         |     0.02 | drop, exit, insani, Lucaozy, saffee |
|           14 |     5764 | 2024-10-02 | Players (Brazilian team) | W   | 0.193      | -            | -                | -                | -         |     0.02 | drop, exit, insani, Lucaozy, saffee |
|           13 |     5830 | 2024-10-01 | Case Esports             | W   | 0.187      | -            | -                | -                | -         |     0.09 | drop, exit, insani, Lucaozy, saffee |
|           12 |     5834 | 2024-10-01 | Case Esports             | L   | 0.186      | -            | -                | -                | -         |    -5.78 | drop, exit, insani, Lucaozy, saffee |
|           11 |     5852 | 2024-10-01 | Sharks Esports           | L   | 0.185      | -            | -                | -                | -         |    -5.32 | drop, exit, insani, Lucaozy, saffee |
|           10 |     5855 | 2024-10-01 | Sharks Esports           | W   | 0.185      | -            | -                | -                | -         |     0.51 | drop, exit, insani, Lucaozy, saffee |
|            9 |     6196 | 2024-09-26 | BESTIA                   | L   | 0.152      | -            | -                | -                | -         |    -4.55 | drop, exit, insani, Lucaozy, saffee |
|            8 |     6265 | 2024-09-25 | Team Solid               | W   | 0.146      | -            | -                | -                | -         |     0.14 | drop, exit, insani, Lucaozy, saffee |
|            7 |     6271 | 2024-09-25 | Team Solid               | L   | 0.146      | -            | -                | -                | -         |    -4.46 | drop, exit, insani, Lucaozy, saffee |
|            6 |     6307 | 2024-09-25 | Sharks Esports           | L   | 0.144      | -            | -                | -                | -         |    -4.16 | drop, exit, insani, Lucaozy, saffee |
|            5 |     6594 | 2024-09-21 | Eternal Fire             | L   | 0.117      | -            | -                | -                | -         |    -0.29 | brnz4n, drop, exit, insani, saffee  |
|            4 |     6715 | 2024-09-19 | M80                      | W   | 0.104      | -            | -                | -                | -         |     0.15 | brnz4n, drop, exit, insani, saffee  |
|            3 |     6785 | 2024-09-18 | Team Falcons             | W   | 0.096      | 0.889        | 0.939 (0.080)    | -                | -         |     2.82 | brnz4n, drop, exit, insani, saffee  |
|            2 |     7353 | 2024-09-08 | G2 Esports               | L   | 0.031      | -            | -                | -                | -         |    -0.13 | brnz4n, drop, exit, insani, saffee  |
|            1 |     7631 | 2024-09-05 | Team Spirit              | W   | 0.010      | -            | -                | -                | -         |     0.29 | brnz4n, drop, exit, insani, saffee  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,790.46)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-12-15 |      0.683 | $20,000.00     | $13,655.09      |
| 2024-10-27 |      0.358 | $2,000.00      | $716.76         |
| 2024-10-20 |      0.312 | $11,500.00     | $3,587.36       |
| 2024-09-22 |      0.124 | $45,000.00     | $5,581.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
