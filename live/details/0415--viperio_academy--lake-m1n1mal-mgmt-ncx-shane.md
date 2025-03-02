### Roster Details<br />
Team Name: Viperio Academy<br />
Roster: Lake, M1n1maL, mgmt, ncx, Shane<br />
Global Rank: [415](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [256]( ../standings_europe.md)<br />
<br />
Final Rank Value:  584.5<br />
<br />
Final Rank Value (584.5) = Starting Rank Value (599.8) + Head To Head Adjustments (-15.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.158[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 599.8
- 400 + ( ( 0.100 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 599.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      162 | 2025-02-22 | DUSTY                     | L   | 1.000      | -            | -                | -                | -         |    -7.87 | Lake, M1n1maL, mgmt, ncx, Shane     |
|            9 |      168 | 2025-02-22 | Glitchtech Esports        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.087 (0.012)    | 1 (1.000) |    13.98 | Lake, M1n1maL, mgmt, ncx, Shane     |
|            8 |      184 | 2025-02-21 | ANTARCTICA (British team) | L   | 1.000      | -            | -                | -                | -         |   -10.88 | Lake, M1n1maL, mgmt, ncx, Shane     |
|            7 |     2698 | 2024-11-26 | Half Natty                | W   | 0.567      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.58 | M1n1maL, mgmt, ncx, Shane, Zuuphler |
|            6 |     3078 | 2024-11-20 | No Pauses                 | L   | 0.527      | -            | -                | -                | -         |    -7.99 | M1n1maL, mgmt, ncx, Shane, Zuuphler |
|            5 |     3140 | 2024-11-19 | Robins Esports            | W   | 0.521      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.19 | M1n1maL, mgmt, ncx, Shane, Zuuphler |
|            4 |     3661 | 2024-11-10 | TRAXXXMANIA               | L   | 0.460      | -            | -                | -                | -         |    -5.35 | jkn, M1n1maL, Menace, mgmt, Shane   |
|            3 |     4540 | 2024-10-26 | The Last Resort           | L   | 0.358      | -            | -                | -                | -         |    -5.25 | fett1s, M1n1maL, mgmt, ncx, Shane   |
|            2 |     4560 | 2024-10-26 | Flowstate (British team)  | W   | 0.357      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.357) |     3.06 | fett1s, M1n1maL, mgmt, ncx, Shane   |
|            1 |     4579 | 2024-10-25 | The Last Resort           | L   | 0.353      | -            | -                | -                | -         |    -3.75 | fett1s, M1n1maL, mgmt, ncx, Shane   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($232.32)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-11-27 |      0.574 | $157.15        | $90.19          |
| 2024-10-27 |      0.366 | $129.61        | $47.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
