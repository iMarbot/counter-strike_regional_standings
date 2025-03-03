### Roster Details<br />
Team Name: NRG<br />
Roster: br0, HexT, Jeorge, nitr0, oSee<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1047.8<br />
<br />
Final Rank Value (1047.8) = Starting Rank Value (1012.1) + Head To Head Adjustments (35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.433[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.372[<sup>2</sup>](#table1)

The average of these factors is 0.306<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1012.1
- 400 + ( ( 0.306 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 1012.1


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
|           43 |      488 | 2025-02-14 | M80                   | L   | 1.000      | -            | -                | -                | -         |   -17.66 | br0, HexT, Jeorge, nitr0, oSee       |
|           42 |      523 | 2025-02-13 | Exceritus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.02 | br0, HexT, Jeorge, nitr0, oSee       |
|           41 |      534 | 2025-02-12 | Nouns Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | br0, HexT, Jeorge, nitr0, oSee       |
|           40 |      554 | 2025-02-11 | BLUEJAYS              | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.511 (0.073)    | 0 (0.000) |    17.60 | br0, HexT, Jeorge, nitr0, oSee       |
|           39 |      560 | 2025-02-11 | Marsborne             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.50 | br0, HexT, Jeorge, nitr0, oSee       |
|           38 |     1614 | 2024-12-15 | Getting Info          | L   | 0.687      | -            | -                | -                | -         |   -15.10 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           37 |     1621 | 2024-12-15 | Party Astronauts      | W   | 0.686      | 0.303        | -                | 0.382 (0.079)    | 0 (0.000) |     4.34 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           36 |     1979 | 2024-12-08 | Sharks Esports        | W   | 0.641      | 0.384        | 0.055 (0.013)    | 0.622 (0.153)    | 1 (0.641) |     9.52 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           35 |     1983 | 2024-12-08 | Sharks Esports        | W   | 0.639      | 0.384        | 0.055 (0.013)    | 0.622 (0.153)    | 1 (0.639) |     9.67 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           34 |     2055 | 2024-12-07 | BLUEJAYS              | W   | 0.634      | 0.384        | 0.031 (0.008)    | 0.511 (0.125)    | 1 (0.634) |    13.02 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           33 |     2068 | 2024-12-07 | Undone                | W   | 0.633      | 0.384        | -                | 0.282 (0.069)    | 1 (0.633) |     4.17 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           32 |     2123 | 2024-12-06 | Stand On Business     | W   | 0.627      | -            | -                | -                | 1 (0.627) |     0.67 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           31 |     2777 | 2024-11-24 | Nouns Esports         | L   | 0.547      | -            | -                | -                | -         |   -12.00 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           30 |     2783 | 2024-11-24 | Getting Info          | W   | 0.546      | 0.303        | 0.011 (0.002)    | 0.309 (0.051)    | -         |     5.17 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           29 |     2833 | 2024-11-23 | Chill Guys            | W   | 0.540      | -            | -                | -                | -         |     2.55 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           28 |     4771 | 2024-10-20 | M80                   | L   | 0.313      | -            | -                | -                | -         |    -5.70 | autimatic, Brehze, HexT, nitr0, oSee |
|           27 |     4840 | 2024-10-19 | Legacy                | W   | 0.307      | 0.477        | 0.036 (0.005)    | 0.549 (0.080)    | -         |     3.44 | autimatic, Brehze, HexT, nitr0, oSee |
|           26 |     4878 | 2024-10-18 | Party Astronauts      | W   | 0.300      | 0.477        | -                | 0.382 (0.055)    | -         |     2.33 | autimatic, Brehze, HexT, nitr0, oSee |
|           25 |     4924 | 2024-10-17 | Wildcard              | W   | 0.293      | 0.477        | 0.178 (0.025)    | 0.422 (0.059)    | -         |     7.93 | autimatic, Brehze, HexT, nitr0, oSee |
|           24 |     4973 | 2024-10-16 | M80                   | L   | 0.287      | -            | -                | -                | -         |    -5.24 | autimatic, Brehze, HexT, nitr0, oSee |
|           23 |     5042 | 2024-10-15 | Party Astronauts      | W   | 0.280      | -            | -                | -                | -         |     2.17 | autimatic, Brehze, HexT, nitr0, oSee |
|           22 |     5389 | 2024-10-08 | Nouns Esports         | L   | 0.234      | -            | -                | -                | -         |    -5.98 | autimatic, Brehze, HexT, nitr0, oSee |
|           21 |     5395 | 2024-10-08 | Nouns Esports         | L   | 0.233      | -            | -                | -                | -         |    -6.05 | autimatic, Brehze, HexT, nitr0, oSee |
|           20 |     5709 | 2024-10-03 | BLUEJAYS              | L   | 0.200      | -            | -                | -                | -         |    -1.92 | autimatic, Brehze, HexT, nitr0, oSee |
|           19 |     5821 | 2024-10-01 | Legacy                | L   | 0.187      | -            | -                | -                | -         |    -3.92 | autimatic, Brehze, HexT, nitr0, oSee |
|           18 |     5827 | 2024-10-01 | Legacy                | L   | 0.187      | -            | -                | -                | -         |    -3.98 | autimatic, Brehze, HexT, nitr0, oSee |
|           17 |     5841 | 2024-10-01 | Final Form            | W   | 0.186      | -            | -                | -                | -         |     0.54 | autimatic, Brehze, HexT, nitr0, oSee |
|           16 |     6100 | 2024-09-27 | Legacy                | L   | 0.160      | -            | -                | -                | -         |    -3.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           15 |     6107 | 2024-09-27 | Familia Maquininha    | W   | 0.159      | -            | -                | -                | -         |     0.66 | autimatic, Brehze, HexT, nitr0, oSee |
|           14 |     6186 | 2024-09-26 | Seoul (American team) | W   | 0.153      | -            | -                | -                | -         |     0.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           13 |     6254 | 2024-09-25 | M80                   | L   | 0.147      | -            | -                | -                | -         |    -3.00 | autimatic, Brehze, HexT, nitr0, oSee |
|           12 |     6259 | 2024-09-25 | M80                   | W   | 0.147      | 0.477        | 0.038 (0.003)    | -                | -         |     1.64 | autimatic, Brehze, HexT, nitr0, oSee |
|           11 |     6347 | 2024-09-24 | Timbermen             | W   | 0.140      | -            | -                | -                | -         |     0.49 | autimatic, Brehze, HexT, nitr0, oSee |
|           10 |     6351 | 2024-09-24 | Timbermen             | W   | 0.140      | -            | -                | -                | -         |     0.49 | autimatic, Brehze, HexT, nitr0, oSee |
|            9 |     6507 | 2024-09-22 | Nouns Esports         | W   | 0.127      | -            | -                | -                | -         |     0.65 | autimatic, Brehze, HexT, nitr0, oSee |
|            8 |     6513 | 2024-09-22 | FLUFFY AIMERS         | W   | 0.125      | -            | -                | -                | -         |     0.92 | autimatic, Brehze, HexT, nitr0, oSee |
|            7 |     6561 | 2024-09-21 | Party Astronauts      | W   | 0.119      | -            | -                | -                | -         |     0.74 | autimatic, Brehze, HexT, nitr0, oSee |
|            6 |     6677 | 2024-09-19 | Wildcard              | W   | 0.107      | 0.477        | 0.178 (0.009)    | -                | -         |     2.94 | autimatic, Brehze, HexT, nitr0, oSee |
|            5 |     6681 | 2024-09-19 | Wildcard              | W   | 0.106      | 0.477        | 0.178 (0.009)    | -                | -         |     2.94 | autimatic, Brehze, HexT, nitr0, oSee |
|            4 |     6730 | 2024-09-18 | Bad News Capybaras    | W   | 0.100      | -            | -                | -                | -         |     0.40 | autimatic, Brehze, HexT, nitr0, oSee |
|            3 |     6737 | 2024-09-18 | Bad News Capybaras    | W   | 0.100      | -            | -                | -                | -         |     0.40 | autimatic, Brehze, HexT, nitr0, oSee |
|            2 |     6795 | 2024-09-17 | LAG Gaming            | W   | 0.094      | -            | -                | -                | -         |     0.65 | autimatic, Brehze, HexT, nitr0, oSee |
|            1 |     6806 | 2024-09-17 | LAG Gaming            | W   | 0.093      | -            | -                | -                | -         |     0.65 | autimatic, Brehze, HexT, nitr0, oSee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,206.83)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.687 | $1,000.00      | $687.22         |
| 2024-12-08 |      0.641 | $15,000.00     | $9,611.46       |
| 2024-11-24 |      0.547 | $1,000.00      | $546.97         |
| 2024-10-20 |      0.313 | $15,000.00     | $4,693.75       |
| 2024-10-05 |      0.214 | $750.00        | $160.21         |
| 2024-09-22 |      0.127 | $4,000.00      | $507.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
