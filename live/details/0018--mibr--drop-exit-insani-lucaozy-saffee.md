### Roster Details<br />
Team Name: MIBR<br />
Roster: drop, exit, insani, Lucaozy, saffee<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1360.4<br />
<br />
Final Rank Value (1360.4) = Starting Rank Value (1454.3) + Head To Head Adjustments (-93.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.540[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.257[<sup>2</sup>](#table1)
- LAN Wins: 0.754[<sup>2</sup>](#table1)

The average of these factors is 0.528<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1454.3
- 400 + ( ( 0.528 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1454.3


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
|           56 |      303 | 2025-02-17 | Astralis                 | L   | 1.000      | -            | -                | -                | -         |    -4.32 | drop, exit, insani, Lucaozy, saffee |
|           55 |      377 | 2025-02-16 | 3DMAX                    | L   | 1.000      | -            | -                | -                | -         |    -7.18 | drop, exit, insani, Lucaozy, saffee |
|           54 |      420 | 2025-02-15 | Imperial Female          | W   | 1.000      | 1.000        | 0.134 (0.134)    | 0.165 (0.165)    | 1 (1.000) |     3.32 | drop, exit, insani, Lucaozy, saffee |
|           53 |      482 | 2025-02-14 | Wildcard                 | L   | 1.000      | -            | -                | -                | -         |   -17.00 | drop, exit, insani, Lucaozy, saffee |
|           52 |      611 | 2025-02-09 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -27.08 | drop, exit, insani, Lucaozy, saffee |
|           51 |      628 | 2025-02-09 | Sharks Esports           | W   | 1.000      | 0.143        | -                | 0.629 (0.090)    | -         |     2.96 | drop, exit, insani, Lucaozy, saffee |
|           50 |      679 | 2025-02-08 | Legacy                   | W   | 1.000      | 0.143        | -                | 0.554 (0.079)    | -         |     2.06 | drop, exit, insani, Lucaozy, saffee |
|           49 |     1091 | 2025-01-31 | Virtus.pro               | L   | 1.000      | -            | -                | -                | -         |    -8.89 | drop, exit, insani, Lucaozy, saffee |
|           48 |     1099 | 2025-01-30 | 3DMAX                    | L   | 0.999      | -            | -                | -                | -         |    -9.86 | drop, exit, insani, Lucaozy, saffee |
|           47 |     1111 | 2025-01-29 | Astralis                 | W   | 0.992      | 1.000        | 0.609 (0.604)    | 0.787 (0.780)    | 1 (0.992) |    27.67 | drop, exit, insani, Lucaozy, saffee |
|           46 |     1188 | 2025-01-14 | FlyQuest                 | L   | 0.891      | -            | -                | -                | -         |   -23.14 | drop, exit, insani, Lucaozy, saffee |
|           45 |     2039 | 2024-12-07 | MOUZ                     | L   | 0.643      | -            | -                | -                | -         |    -0.95 | drop, exit, insani, Lucaozy, saffee |
|           44 |     2103 | 2024-12-06 | Team Liquid              | L   | 0.637      | -            | -                | -                | -         |    -6.96 | drop, exit, insani, Lucaozy, saffee |
|           43 |     2144 | 2024-12-05 | Team Vitality            | L   | 0.630      | -            | -                | -                | -         |    -1.21 | drop, exit, insani, Lucaozy, saffee |
|           42 |     2170 | 2024-12-05 | Natus Vincere            | W   | 0.625      | 1.000        | 0.555 (0.347)    | 0.478 (0.299)    | 1 (0.625) |    16.53 | drop, exit, insani, Lucaozy, saffee |
|           41 |     2183 | 2024-12-04 | 3DMAX                    | W   | 0.623      | 1.000        | 0.295 (0.184)    | 0.535 (0.333)    | 1 (0.623) |    14.43 | drop, exit, insani, Lucaozy, saffee |
|           40 |     2304 | 2024-12-02 | FlyQuest                 | W   | 0.610      | 1.000        | 0.105 (0.064)    | 0.239 (0.146)    | 1 (0.610) |     3.49 | drop, exit, insani, Lucaozy, saffee |
|           39 |     2376 | 2024-12-01 | Rare Atom                | W   | 0.603      | 1.000        | 0.063 (0.038)    | 0.581 (0.350)    | 1 (0.603) |     1.71 | drop, exit, insani, Lucaozy, saffee |
|           38 |     2454 | 2024-11-30 | Passion UA               | L   | 0.596      | -            | -                | -                | -         |   -16.68 | drop, exit, insani, Lucaozy, saffee |
|           37 |     2543 | 2024-11-30 | The MongolZ              | L   | 0.591      | -            | -                | -                | -         |    -0.97 | drop, exit, insani, Lucaozy, saffee |
|           36 |     2563 | 2024-11-29 | Virtus.pro               | W   | 0.589      | 1.000        | 0.268 (0.158)    | 0.439 (0.258)    | 1 (0.589) |    14.38 | drop, exit, insani, Lucaozy, saffee |
|           35 |     3520 | 2024-11-13 | Complexity               | W   | 0.477      | -            | -                | -                | 1 (0.477) |     3.26 | drop, exit, insani, Lucaozy, saffee |
|           34 |     3549 | 2024-11-12 | Imperial Esports         | W   | 0.472      | -            | -                | -                | 1 (0.472) |     1.43 | drop, exit, insani, Lucaozy, saffee |
|           33 |     3572 | 2024-11-11 | KRÜ Esports              | W   | 0.471      | -            | -                | -                | 1 (0.471) |     0.29 | drop, exit, insani, Lucaozy, saffee |
|           32 |     4587 | 2024-10-25 | Monte                    | L   | 0.353      | -            | -                | -                | -         |   -10.60 | drop, exit, insani, Lucaozy, saffee |
|           31 |     4601 | 2024-10-25 | Legacy                   | L   | 0.352      | -            | -                | -                | -         |   -10.51 | drop, exit, insani, Lucaozy, saffee |
|           30 |     4761 | 2024-10-20 | PaiN Gaming              | L   | 0.320      | -            | -                | -                | -         |    -2.57 | drop, exit, insani, Lucaozy, saffee |
|           29 |     4829 | 2024-10-19 | BESTIA                   | W   | 0.314      | 0.450        | 0.069 (0.010)    | 0.478 (0.068)    | -         |     0.65 | drop, exit, insani, Lucaozy, saffee |
|           28 |     4915 | 2024-10-17 | PaiN Gaming              | L   | 0.301      | -            | -                | -                | -         |    -2.46 | drop, exit, insani, Lucaozy, saffee |
|           27 |     4968 | 2024-10-16 | RED Canids               | W   | 0.294      | -            | -                | -                | -         |     0.39 | drop, exit, insani, Lucaozy, saffee |
|           26 |     5316 | 2024-10-09 | RED Canids               | W   | 0.248      | -            | -                | -                | -         |     0.32 | drop, exit, insani, Lucaozy, saffee |
|           25 |     5324 | 2024-10-09 | RED Canids               | W   | 0.247      | -            | -                | -                | -         |     0.32 | drop, exit, insani, Lucaozy, saffee |
|           24 |     5386 | 2024-10-08 | KRÜ Esports              | W   | 0.241      | -            | -                | -                | -         |     0.13 | drop, exit, insani, Lucaozy, saffee |
|           23 |     5397 | 2024-10-08 | KRÜ Esports              | W   | 0.241      | -            | -                | -                | -         |     0.13 | drop, exit, insani, Lucaozy, saffee |
|           22 |     5411 | 2024-10-08 | PaiN Gaming              | L   | 0.240      | -            | -                | -                | -         |    -1.80 | drop, exit, insani, Lucaozy, saffee |
|           21 |     5414 | 2024-10-08 | PaiN Gaming              | L   | 0.240      | -            | -                | -                | -         |    -1.83 | drop, exit, insani, Lucaozy, saffee |
|           20 |     5502 | 2024-10-06 | Imperial Esports         | W   | 0.228      | -            | -                | -                | -         |     0.59 | drop, exit, insani, Lucaozy, saffee |
|           19 |     5503 | 2024-10-06 | Imperial Esports         | L   | 0.228      | -            | -                | -                | -         |    -6.61 | drop, exit, insani, Lucaozy, saffee |
|           18 |     5645 | 2024-10-04 | Fluxo                    | L   | 0.214      | -            | -                | -                | -         |    -6.33 | drop, exit, insani, Lucaozy, saffee |
|           17 |     5647 | 2024-10-04 | Fluxo                    | W   | 0.214      | -            | -                | -                | -         |     0.42 | drop, exit, insani, Lucaozy, saffee |
|           16 |     5746 | 2024-10-02 | Players (Brazilian team) | W   | 0.201      | -            | -                | -                | -         |     0.02 | drop, exit, insani, Lucaozy, saffee |
|           15 |     5752 | 2024-10-02 | Players (Brazilian team) | W   | 0.201      | -            | -                | -                | -         |     0.02 | drop, exit, insani, Lucaozy, saffee |
|           14 |     5818 | 2024-10-01 | Case Esports             | W   | 0.195      | -            | -                | -                | -         |     0.10 | drop, exit, insani, Lucaozy, saffee |
|           13 |     5822 | 2024-10-01 | Case Esports             | L   | 0.194      | -            | -                | -                | -         |    -6.03 | drop, exit, insani, Lucaozy, saffee |
|           12 |     5840 | 2024-10-01 | Sharks Esports           | L   | 0.193      | -            | -                | -                | -         |    -5.57 | drop, exit, insani, Lucaozy, saffee |
|           11 |     5843 | 2024-10-01 | Sharks Esports           | W   | 0.193      | -            | -                | -                | -         |     0.52 | drop, exit, insani, Lucaozy, saffee |
|           10 |     6184 | 2024-09-26 | BESTIA                   | L   | 0.160      | -            | -                | -                | -         |    -4.80 | drop, exit, insani, Lucaozy, saffee |
|            9 |     6253 | 2024-09-25 | Team Solid               | W   | 0.154      | -            | -                | -                | -         |     0.15 | drop, exit, insani, Lucaozy, saffee |
|            8 |     6259 | 2024-09-25 | Team Solid               | L   | 0.154      | -            | -                | -                | -         |    -4.71 | drop, exit, insani, Lucaozy, saffee |
|            7 |     6295 | 2024-09-25 | Sharks Esports           | L   | 0.152      | -            | -                | -                | -         |    -4.41 | drop, exit, insani, Lucaozy, saffee |
|            6 |     6582 | 2024-09-21 | Eternal Fire             | L   | 0.125      | -            | -                | -                | -         |    -0.32 | brnz4n, drop, exit, insani, saffee  |
|            5 |     6703 | 2024-09-19 | M80                      | W   | 0.112      | -            | -                | -                | -         |     0.17 | brnz4n, drop, exit, insani, saffee  |
|            4 |     6773 | 2024-09-18 | Team Falcons             | W   | 0.104      | 0.889        | 0.927 (0.086)    | -                | -         |     3.06 | brnz4n, drop, exit, insani, saffee  |
|            3 |     7341 | 2024-09-08 | G2 Esports               | L   | 0.040      | -            | -                | -                | -         |    -0.16 | brnz4n, drop, exit, insani, saffee  |
|            2 |     7619 | 2024-09-05 | Team Spirit              | W   | 0.018      | 0.889        | 1.000 (0.016)    | -                | -         |     0.54 | brnz4n, drop, exit, insani, saffee  |
|            1 |     7725 | 2024-09-03 | 9z Team                  | W   | 0.006      | -            | -                | -                | -         |     0.00 | brnz4n, drop, exit, insani, saffee  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47,433.73)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-12-15 |      0.691 | $20,000.00     | $13,818.98      |
| 2024-10-27 |      0.367 | $2,000.00      | $733.15         |
| 2024-10-20 |      0.320 | $11,500.00     | $3,681.60       |
| 2024-09-22 |      0.132 | $45,000.00     | $5,950.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
