### Roster Details<br />
Team Name: TRAXXXMANIA<br />
Roster: BENJYMIN, Ehgren, msN, nellozz, sonder<br />
Global Rank: [237](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [166]( ../standings_europe.md)<br />
<br />
Final Rank Value:  683.4<br />
<br />
Final Rank Value (683.4) = Starting Rank Value (661.4) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.4
- 400 + ( ( 0.131 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 661.4


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
|           13 |     2745 | 2024-11-25 | ALASKA                | L   | 0.561      | -            | -                | -                | -         |    -3.21 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|           12 |     3638 | 2024-11-10 | Endpoint              | L   | 0.461      | -            | -                | -                | -         |    -5.36 | BENJYMIN, Ehgren, msN, Rack, sonder      |
|           11 |     3661 | 2024-11-10 | Viperio Academy       | W   | 0.460      | 0.143        | 0.001 (0.000)    | 0.114 (0.008)    | 0 (0.000) |     5.35 | BENJYMIN, Ehgren, msN, Rack, sonder      |
|           10 |     3922 | 2024-11-05 | Annex Esports         | W   | 0.427      | 0.143        | 0.000 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     5.34 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            9 |     4235 | 2024-10-31 | Belfast Storm         | L   | 0.394      | -            | -                | -                | -         |    -5.66 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            8 |     4287 | 2024-10-30 | ALASKA                | L   | 0.387      | -            | -                | -                | -         |    -1.16 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            7 |     4298 | 2024-10-30 | ROYALS                | W   | 0.387      | 0.143        | 0.004 (0.000)    | 0.205 (0.011)    | 0 (0.000) |     6.53 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            6 |     4348 | 2024-10-29 | Dreams To Legends     | W   | 0.381      | 0.143        | 0.000 (0.000)    | 0.083 (0.004)    | 0 (0.000) |     4.94 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            5 |     4353 | 2024-10-29 | The Last Resort       | W   | 0.381      | 0.143        | 0.001 (0.000)    | 0.161 (0.009)    | 0 (0.000) |     6.77 | BENJYMIN, Ehgren, msN, nellozz, sonder   |
|            4 |     4511 | 2024-10-26 | The Last Resort       | L   | 0.359      | -            | -                | -                | -         |    -4.97 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            3 |     4539 | 2024-10-26 | Annex Esports         | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.059 (0.003)    | 1 (0.358) |     4.98 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            2 |     4557 | 2024-10-26 | Belfast Storm         | W   | 0.357      | 0.143        | 0.002 (0.000)    | 0.162 (0.008)    | 1 (0.357) |     6.34 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |
|            1 |     4583 | 2024-10-25 | Chucklestorm Strikers | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.353) |     2.08 | BENJYMIN, Ehgren, PRAISy, seiren, sonder |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($47.41)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.366 | $129.61        | $47.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
