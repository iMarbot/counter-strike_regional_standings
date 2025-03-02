### Roster Details<br />
Team Name: Belfast Storm<br />
Roster: devi, dexie, Finui, Nem, Stop_it<br />
Global Rank: [210](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [153]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.5<br />
<br />
Final Rank Value (706.5) = Starting Rank Value (709.0) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.0
- 400 + ( ( 0.155 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 709.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      152 | 2025-02-22 | DUSTY                      | L   | 1.000      | -            | -                | -                | -         |   -12.19 | devi, dexie, Finui, Nem, Stop_it    |
|           17 |      160 | 2025-02-22 | ALASKA                     | L   | 1.000      | -            | -                | -                | -         |    -9.43 | devi, dexie, Finui, Nem, Stop_it    |
|           16 |      185 | 2025-02-21 | The Last Resort            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.161 (0.023)    | 1 (1.000) |    14.69 | devi, dexie, Finui, Nem, Stop_it    |
|           15 |     1409 | 2024-12-22 | NEVERMORE (Ukrainian team) | L   | 0.738      | -            | -                | -                | -         |    -9.59 | devi, dexie, Finui, PALM1, tsutskam |
|           14 |     1416 | 2024-12-22 | Doge Soldiers              | L   | 0.738      | -            | -                | -                | -         |   -18.26 | devi, dexie, Finui, PALM1, tsutskam |
|           13 |     2086 | 2024-12-07 | ALASKA                     | L   | 0.639      | -            | -                | -                | -         |    -4.91 | devi, dexie, Finui, Nem, tsutskam   |
|           12 |     3075 | 2024-11-20 | 8Sins                      | W   | 0.527      | 0.143        | 0.005 (0.000)    | 0.234 (0.018)    | 0 (0.000) |    11.94 | devi, dexie, Finui, Nem, tsutskam   |
|           11 |     3421 | 2024-11-14 | The Last Resort            | W   | 0.487      | 0.143        | 0.001 (0.000)    | 0.161 (0.011)    | 0 (0.000) |     7.57 | devi, dexie, Finui, Nem, tsutskam   |
|           10 |     3824 | 2024-11-07 | Dreams To Legends          | W   | 0.441      | 0.143        | 0.000 (0.000)    | 0.083 (0.005)    | 0 (0.000) |     4.92 | devi, dexie, Finui, Nem, tsutskam   |
|            9 |     3865 | 2024-11-06 | 8Sins                      | L   | 0.434      | -            | -                | -                | -         |    -3.49 | devi, dexie, Finui, Nem, tsutskam   |
|            8 |     3971 | 2024-11-04 | Glitchtech Esports         | W   | 0.421      | 0.143        | 0.000 (0.000)    | 0.087 (0.005)    | 0 (0.000) |     3.42 | devi, dexie, Finui, Nem, tsutskam   |
|            7 |     4235 | 2024-10-31 | TRAXXXMANIA                | W   | 0.394      | 0.143        | 0.000 (0.000)    | 0.128 (0.007)    | 0 (0.000) |     5.66 | devi, dexie, Finui, Nem, tsutskam   |
|            6 |     4281 | 2024-10-30 | ALASKA                     | W   | 0.387      | 0.143        | 0.030 (0.002)    | 0.875 (0.048)    | 0 (0.000) |    10.91 | devi, dexie, Finui, Nem, tsutskam   |
|            5 |     4557 | 2024-10-26 | TRAXXXMANIA                | L   | 0.357      | -            | -                | -                | -         |    -6.34 | devi, dexie, Finui, Nem, tsutskam   |
|            4 |     4582 | 2024-10-25 | ALASKA                     | L   | 0.353      | -            | -                | -                | -         |    -1.20 | devi, dexie, Finui, Nem, tsutskam   |
|            3 |     5045 | 2024-10-15 | Annex Esports              | W   | 0.287      | 0.143        | 0.000 (0.000)    | 0.059 (0.002)    | 0 (0.000) |     3.54 | devi, dexie, Finui, Nem, tsutskam   |
|            2 |     5279 | 2024-10-10 | The Last Resort            | W   | 0.253      | 0.143        | 0.001 (0.000)    | 0.161 (0.006)    | 0 (0.000) |     4.19 | devi, dexie, Finui, Nem, tsutskam   |
|            1 |     5407 | 2024-10-08 | ROYALS                     | L   | 0.240      | -            | -                | -                | -         |    -3.92 | devi, dexie, Finui, Nem, tsutskam   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($746.31)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-12-07 |      0.639 | $1,019.42      | $651.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
