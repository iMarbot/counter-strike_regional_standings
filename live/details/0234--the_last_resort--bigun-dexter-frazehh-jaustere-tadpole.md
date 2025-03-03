### Roster Details<br />
Team Name: The Last Resort<br />
Roster: Bigun, DeXter, frazehh, JAUSTERE, Tadpole<br />
Global Rank: [234](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [162]( ../standings_europe.md)<br />
<br />
Final Rank Value:  687.6<br />
<br />
Final Rank Value (687.6) = Starting Rank Value (725.0) + Head To Head Adjustments (-37.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.196[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.0
- 400 + ( ( 0.162 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 725.0


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
|           18 |      173 | 2025-02-22 | Ctrl Alt Defeat   | L   | 1.000      | -            | -                | -                | -         |    -8.87 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           17 |      177 | 2025-02-22 | Ross Kemp Bald    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 1 (1.000) |     6.95 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           16 |      197 | 2025-02-21 | Belfast Storm     | L   | 1.000      | -            | -                | -                | -         |   -14.69 | Bigun, DeXter, frazehh, JAUSTERE, Tadpole |
|           15 |     2515 | 2024-11-30 | MYSKILL           | L   | 0.585      | -            | -                | -                | -         |    -9.94 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           14 |     2633 | 2024-11-28 | 777 Esports       | L   | 0.572      | -            | -                | -                | -         |   -10.83 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           13 |     2723 | 2024-11-26 | Regnum4Games      | W   | 0.559      | 0.333        | 0.002 (0.000)    | 0.112 (0.021)    | 0 (0.000) |     6.93 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           12 |     3433 | 2024-11-14 | Belfast Storm     | L   | 0.479      | -            | -                | -                | -         |    -7.44 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           11 |     3833 | 2024-11-07 | 8Sins             | W   | 0.432      | 0.143        | 0.005 (0.000)    | 0.233 (0.014)    | 0 (0.000) |    10.26 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|           10 |     3935 | 2024-11-05 | ALASKA            | L   | 0.419      | -            | -                | -                | -         |    -1.64 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|            9 |     3992 | 2024-11-04 | Annex Esports     | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     4.82 | Bigun, DeXter, frazehh, JAUSTERE, Zulu    |
|            8 |     4365 | 2024-10-29 | TRAXXXMANIA       | L   | 0.372      | -            | -                | -                | -         |    -6.64 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            7 |     4511 | 2024-10-26 | 8Sins             | L   | 0.352      | -            | -                | -                | -         |    -2.78 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            6 |     4523 | 2024-10-26 | TRAXXXMANIA       | W   | 0.351      | 0.143        | 0.000 (0.000)    | 0.126 (0.006)    | 1 (0.351) |     4.84 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            5 |     4549 | 2024-10-26 | Verdant fe        | L   | 0.350      | -            | -                | -                | -         |    -5.97 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            4 |     4591 | 2024-10-25 | Viperio Academy   | W   | 0.345      | 0.143        | 0.001 (0.000)    | 0.113 (0.006)    | 1 (0.345) |     3.67 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            3 |     4751 | 2024-10-21 | ROYALS            | L   | 0.318      | -            | -                | -                | -         |    -5.35 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            2 |     4932 | 2024-10-17 | Dreams To Legends | W   | 0.292      | 0.143        | 0.000 (0.000)    | 0.081 (0.003)    | 0 (0.000) |     3.33 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |
|            1 |     5291 | 2024-10-10 | Belfast Storm     | L   | 0.245      | -            | -                | -                | -         |    -4.05 | DeXter, frazehh, ifan, JAUSTERE, Zulu     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($314.87)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-10-27 |      0.358 | $615.65        | $220.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
