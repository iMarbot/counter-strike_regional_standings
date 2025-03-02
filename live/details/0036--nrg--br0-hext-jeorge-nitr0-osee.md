### Roster Details<br />
Team Name: NRG<br />
Roster: br0, HexT, Jeorge, nitr0, oSee<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1018.8<br />
<br />
Final Rank Value (1018.8) = Starting Rank Value (1009.4) + Head To Head Adjustments (9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.433[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.375[<sup>2</sup>](#table1)

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1009.4
- 400 + ( ( 0.305 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1009.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |      476 | 2025-02-14 | M80                   | L   | 1.000      | -            | -                | -                | -         |   -17.46 | br0, HexT, Jeorge, nitr0, oSee       |
|           42 |      511 | 2025-02-13 | Exceritus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.50 | br0, HexT, Jeorge, nitr0, oSee       |
|           41 |      522 | 2025-02-12 | Nouns Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | br0, HexT, Jeorge, nitr0, oSee       |
|           40 |      542 | 2025-02-11 | BOSS                  | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    10.67 | br0, HexT, Jeorge, nitr0, oSee       |
|           39 |      548 | 2025-02-11 | Marsborne             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.01 | br0, HexT, Jeorge, nitr0, oSee       |
|           38 |     1602 | 2024-12-15 | Timbermen             | L   | 0.695      | -            | -                | -                | -         |   -17.84 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           37 |     1609 | 2024-12-15 | Party Astronauts      | W   | 0.694      | 0.303        | -                | 0.385 (0.081)    | 0 (0.000) |     4.51 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           36 |     1967 | 2024-12-08 | Sharks Esports        | W   | 0.649      | 0.384        | 0.054 (0.014)    | 0.629 (0.157)    | 1 (0.649) |     9.74 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           35 |     1971 | 2024-12-08 | Sharks Esports        | W   | 0.647      | 0.384        | 0.054 (0.014)    | 0.629 (0.157)    | 1 (0.647) |    10.06 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           34 |     2043 | 2024-12-07 | BOSS                  | W   | 0.642      | 0.384        | 0.014 (0.004)    | 0.327 (0.081)    | 1 (0.642) |     7.49 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           33 |     2056 | 2024-12-07 | Undone                | W   | 0.641      | 0.384        | -                | 0.286 (0.070)    | 1 (0.641) |     4.29 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           32 |     2111 | 2024-12-06 | Stand On Business     | W   | 0.636      | -            | -                | -                | 1 (0.636) |     0.70 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           31 |     2765 | 2024-11-24 | Nouns Esports         | L   | 0.555      | -            | -                | -                | -         |   -12.27 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           30 |     2771 | 2024-11-24 | Timbermen             | W   | 0.554      | 0.303        | 0.011 (0.002)    | -                | -         |     3.05 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           29 |     2821 | 2024-11-23 | Chill Guys            | W   | 0.548      | 0.303        | -                | 0.313 (0.052)    | -         |     2.60 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           28 |     4759 | 2024-10-20 | M80                   | L   | 0.321      | -            | -                | -                | -         |    -5.79 | autimatic, Brehze, HexT, nitr0, oSee |
|           27 |     4828 | 2024-10-19 | Legacy                | W   | 0.315      | 0.477        | 0.036 (0.005)    | 0.554 (0.083)    | -         |     3.58 | autimatic, Brehze, HexT, nitr0, oSee |
|           26 |     4866 | 2024-10-18 | Party Astronauts      | W   | 0.308      | 0.477        | -                | 0.385 (0.057)    | -         |     2.43 | autimatic, Brehze, HexT, nitr0, oSee |
|           25 |     4912 | 2024-10-17 | Wildcard              | W   | 0.302      | 0.477        | 0.176 (0.025)    | 0.428 (0.062)    | -         |     8.16 | autimatic, Brehze, HexT, nitr0, oSee |
|           24 |     4961 | 2024-10-16 | M80                   | L   | 0.295      | -            | -                | -                | -         |    -5.33 | autimatic, Brehze, HexT, nitr0, oSee |
|           23 |     5030 | 2024-10-15 | Party Astronauts      | W   | 0.288      | 0.477        | -                | 0.385 (0.053)    | -         |     2.27 | autimatic, Brehze, HexT, nitr0, oSee |
|           22 |     5377 | 2024-10-08 | Nouns Esports         | L   | 0.242      | -            | -                | -                | -         |    -6.16 | autimatic, Brehze, HexT, nitr0, oSee |
|           21 |     5383 | 2024-10-08 | Nouns Esports         | L   | 0.242      | -            | -                | -                | -         |    -6.23 | autimatic, Brehze, HexT, nitr0, oSee |
|           20 |     5697 | 2024-10-03 | BOSS                  | L   | 0.208      | -            | -                | -                | -         |    -4.25 | autimatic, Brehze, HexT, nitr0, oSee |
|           19 |     5809 | 2024-10-01 | Legacy                | L   | 0.195      | -            | -                | -                | -         |    -4.08 | autimatic, Brehze, HexT, nitr0, oSee |
|           18 |     5815 | 2024-10-01 | Legacy                | L   | 0.195      | -            | -                | -                | -         |    -4.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           17 |     5829 | 2024-10-01 | Final Form            | W   | 0.194      | -            | -                | -                | -         |     0.57 | autimatic, Brehze, HexT, nitr0, oSee |
|           16 |     6088 | 2024-09-27 | Legacy                | L   | 0.168      | -            | -                | -                | -         |    -3.66 | autimatic, Brehze, HexT, nitr0, oSee |
|           15 |     6095 | 2024-09-27 | Familia Maquininha    | W   | 0.168      | -            | -                | -                | -         |     0.72 | autimatic, Brehze, HexT, nitr0, oSee |
|           14 |     6174 | 2024-09-26 | Seoul (American team) | W   | 0.161      | -            | -                | -                | -         |     0.15 | autimatic, Brehze, HexT, nitr0, oSee |
|           13 |     6242 | 2024-09-25 | M80                   | L   | 0.155      | -            | -                | -                | -         |    -3.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           12 |     6247 | 2024-09-25 | M80                   | W   | 0.155      | 0.477        | 0.038 (0.003)    | -                | -         |     1.77 | autimatic, Brehze, HexT, nitr0, oSee |
|           11 |     6335 | 2024-09-24 | Timbermen             | W   | 0.149      | -            | -                | -                | -         |     0.74 | autimatic, Brehze, HexT, nitr0, oSee |
|           10 |     6339 | 2024-09-24 | Timbermen             | W   | 0.148      | -            | -                | -                | -         |     0.74 | autimatic, Brehze, HexT, nitr0, oSee |
|            9 |     6495 | 2024-09-22 | Nouns Esports         | W   | 0.135      | -            | -                | -                | -         |     0.70 | autimatic, Brehze, HexT, nitr0, oSee |
|            8 |     6501 | 2024-09-22 | FLUFFY AIMERS         | W   | 0.133      | -            | -                | -                | -         |     0.99 | autimatic, Brehze, HexT, nitr0, oSee |
|            7 |     6549 | 2024-09-21 | Party Astronauts      | W   | 0.128      | -            | -                | -                | -         |     0.81 | autimatic, Brehze, HexT, nitr0, oSee |
|            6 |     6665 | 2024-09-19 | Wildcard              | W   | 0.115      | 0.477        | 0.176 (0.010)    | -                | -         |     3.18 | autimatic, Brehze, HexT, nitr0, oSee |
|            5 |     6669 | 2024-09-19 | Wildcard              | W   | 0.114      | 0.477        | 0.176 (0.010)    | -                | -         |     3.18 | autimatic, Brehze, HexT, nitr0, oSee |
|            4 |     6718 | 2024-09-18 | Bad News Capybaras    | W   | 0.109      | -            | -                | -                | -         |     0.43 | autimatic, Brehze, HexT, nitr0, oSee |
|            3 |     6725 | 2024-09-18 | Bad News Capybaras    | W   | 0.108      | -            | -                | -                | -         |     0.43 | autimatic, Brehze, HexT, nitr0, oSee |
|            2 |     6783 | 2024-09-17 | LAG Gaming            | W   | 0.102      | -            | -                | -                | -         |     0.33 | autimatic, Brehze, HexT, nitr0, oSee |
|            1 |     6794 | 2024-09-17 | LAG Gaming            | W   | 0.102      | -            | -                | -                | -         |     0.33 | autimatic, Brehze, HexT, nitr0, oSee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,507.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.695 | $1,000.00      | $695.42         |
| 2024-12-08 |      0.649 | $15,000.00     | $9,734.38       |
| 2024-11-24 |      0.555 | $1,000.00      | $555.16         |
| 2024-10-20 |      0.321 | $15,000.00     | $4,816.67       |
| 2024-10-05 |      0.222 | $750.00        | $166.35         |
| 2024-09-22 |      0.135 | $4,000.00      | $540.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
