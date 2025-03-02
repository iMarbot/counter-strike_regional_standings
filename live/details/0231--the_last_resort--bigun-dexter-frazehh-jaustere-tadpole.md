### Roster Details<br />
Team Name: The Last Resort<br />
Roster: Bigun, DeXter, frazehh, JAUSTERE, Tadpole<br />
Global Rank: [231](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [162]( ../standings_europe.md)<br />
<br />
Final Rank Value:  687.5<br />
<br />
Final Rank Value (687.5) = Starting Rank Value (725.2) + Head To Head Adjustments (-37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.200[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.2
- 400 + ( ( 0.163 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 725.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      161 | 2025-02-22 | Ctrl Alt Defeat   | L   | 1.000      | -            | -                | -                | -         |    -8.94 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           17 |      165 | 2025-02-22 | Ross Kemp Bald    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 1 (1.000) |     6.94 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           16 |      185 | 2025-02-21 | Belfast Storm     | L   | 1.000      | -            | -                | -                | -         |   -14.69 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           15 |     2503 | 2024-11-30 | MYSKILL           | L   | 0.593      | -            | -                | -                | -         |   -10.03 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           14 |     2621 | 2024-11-28 | 777 Esports       | L   | 0.580      | -            | -                | -                | -         |   -10.93 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           13 |     2711 | 2024-11-26 | Regnum4Games      | W   | 0.567      | 0.333        | 0.002 (0.000)    | 0.115 (0.022)    | 0 (0.000) |     7.02 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           12 |     3421 | 2024-11-14 | Belfast Storm     | L   | 0.487      | -            | -                | -                | -         |    -7.57 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           11 |     3821 | 2024-11-07 | 8Sins             | W   | 0.441      | 0.143        | 0.005 (0.000)    | 0.234 (0.015)    | 0 (0.000) |    10.44 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           10 |     3923 | 2024-11-05 | ALASKA            | L   | 0.427      | -            | -                | -                | -         |    -1.69 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|            9 |     3980 | 2024-11-04 | Annex Esports     | W   | 0.420      | 0.143        | 0.000 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     4.92 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|            8 |     4353 | 2024-10-29 | TRAXXXMANIA       | L   | 0.381      | -            | -                | -                | -         |    -6.77 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            7 |     4499 | 2024-10-26 | 8Sins             | L   | 0.360      | -            | -                | -                | -         |    -2.85 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            6 |     4511 | 2024-10-26 | TRAXXXMANIA       | W   | 0.359      | 0.143        | 0.000 (0.000)    | 0.128 (0.007)    | 1 (0.359) |     4.97 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            5 |     4537 | 2024-10-26 | Verdant fe        | L   | 0.358      | -            | -                | -                | -         |    -6.10 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            4 |     4579 | 2024-10-25 | Viperio Academy   | W   | 0.353      | 0.143        | 0.001 (0.000)    | 0.114 (0.006)    | 1 (0.353) |     3.75 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            3 |     4739 | 2024-10-21 | ROYALS            | L   | 0.326      | -            | -                | -                | -         |    -5.46 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            2 |     4920 | 2024-10-17 | Dreams To Legends | W   | 0.300      | 0.143        | 0.000 (0.000)    | 0.083 (0.004)    | 0 (0.000) |     3.44 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            1 |     5279 | 2024-10-10 | Belfast Storm     | L   | 0.253      | -            | -                | -                | -         |    -4.19 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($319.91)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-10-27 |      0.366 | $615.65        | $225.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
