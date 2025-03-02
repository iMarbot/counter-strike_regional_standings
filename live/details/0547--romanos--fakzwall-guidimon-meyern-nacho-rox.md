### Roster Details<br />
Team Name: Romanos<br />
Roster: fakzwall, guidimon, meyern, nacho, rox<br />
Global Rank: [547](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [124]( ../standings_americas.md)<br />
<br />
Final Rank Value:  481.4<br />
<br />
Final Rank Value (481.4) = Starting Rank Value (477.9) + Head To Head Adjustments (3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.155[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.039<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 477.9
- 400 + ( ( 0.039 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 477.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     5714 | 2024-10-03 | Bad News Chickens | L   | 0.207      | -            | -                | -                | -         |    -1.59 | fakzwall, guidimon, meyern, nacho, rox |
|            6 |     5831 | 2024-10-01 | 20/70             | W   | 0.194      | 0.143        | 0.001 (0.000)    | 0.290 (0.008)    | 0 (0.000) |     4.40 | fakzwall, guidimon, meyern, nacho, rox |
|            5 |     6000 | 2024-09-28 | Dusty Roots       | L   | 0.174      | -            | -                | -                | -         |    -0.81 | fakzwall, guidimon, meyern, nacho, rox |
|            4 |     6015 | 2024-09-28 | POR LA VENTANA    | W   | 0.173      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.13 | fakzwall, guidimon, meyern, nacho, rox |
|            3 |     6356 | 2024-09-24 | Yawara E-Sports   | L   | 0.147      | -            | -                | -                | -         |    -1.10 | fakzwall, guidimon, meyern, nacho, rox |
|            2 |     6499 | 2024-09-22 | LaChampionsLiga   | L   | 0.134      | -            | -                | -                | -         |    -1.06 | bichop, fakzwall, guidimon, nacho, rox |
|            1 |     6553 | 2024-09-21 | POR LA VENTANA    | W   | 0.127      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.57 | bichop, fakzwall, guidimon, nacho, rox |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
