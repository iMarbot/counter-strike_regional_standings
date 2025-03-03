### Roster Details<br />
Team Name: TRAXXXMANIA<br />
Roster: BENJYMIN, Ehgren, msN, nellozz, sonder<br />
Global Rank: [242](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [167]( ../standings_europe.md)<br />
<br />
Final Rank Value:  682.0<br />
<br />
Final Rank Value (682.0) = Starting Rank Value (660.2) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.122[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.2
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 660.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2757 | 2024-11-25 | ALASKA                | L   | 0.552      | -            | -                | -                | -         |    -3.10 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|           12 |     3650 | 2024-11-10 | Endpoint              | L   | 0.452      | -            | -                | -                | -         |    -5.26 | BENJYMIN, Ehgren, msN, Rack, sonder      |
|           11 |     3673 | 2024-11-10 | Viperio Academy       | W   | 0.452      | 0.143        | 0.001 (0.000)    | 0.113 (0.007)    | 0 (0.000) |     5.29 | BENJYMIN, Ehgren, msN, Rack, sonder      |
|           10 |     3934 | 2024-11-05 | Annex Esports         | W   | 0.419      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     5.26 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            9 |     4247 | 2024-10-31 | Belfast Storm         | L   | 0.386      | -            | -                | -                | -         |    -5.51 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            8 |     4299 | 2024-10-30 | ALASKA                | L   | 0.379      | -            | -                | -                | -         |    -1.11 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            7 |     4310 | 2024-10-30 | ROYALS                | W   | 0.378      | 0.143        | 0.004 (0.000)    | 0.200 (0.011)    | 0 (0.000) |     6.38 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            6 |     4360 | 2024-10-29 | Dreams To Legends     | W   | 0.373      | 0.143        | 0.000 (0.000)    | 0.081 (0.004)    | 0 (0.000) |     4.85 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            5 |     4365 | 2024-10-29 | The Last Resort       | W   | 0.372      | 0.143        | 0.001 (0.000)    | 0.159 (0.008)    | 0 (0.000) |     6.64 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            4 |     4523 | 2024-10-26 | The Last Resort       | L   | 0.351      | -            | -                | -                | -         |    -4.84 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            3 |     4551 | 2024-10-26 | Annex Esports         | W   | 0.350      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 1 (0.350) |     4.89 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            2 |     4569 | 2024-10-26 | Belfast Storm         | W   | 0.349      | 0.143        | 0.002 (0.000)    | 0.160 (0.008)    | 1 (0.349) |     6.23 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            1 |     4595 | 2024-10-25 | Chucklestorm Strikers | W   | 0.345      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.345) |     2.04 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46.34)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.358 | $129.61        | $46.34          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
