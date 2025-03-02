### Roster Details<br />
Team Name: Team OWL<br />
Roster: aNsavage, flouzer, Snoob, sToRm, wolterz<br />
Global Rank: [551](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [341]( ../standings_europe.md)<br />
<br />
Final Rank Value:  478.4<br />
<br />
Final Rank Value (478.4) = Starting Rank Value (476.7) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.152[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 476.7
- 400 + ( ( 0.038 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 476.7


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
|            6 |     6916 | 2024-09-15 | THE GENTLEMEN ESPORTS | L   | 0.087      | -            | -                | -                | -         |    -0.65 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            5 |     7062 | 2024-09-13 | BAKS Esports          | W   | 0.073      | 0.333        | 0.000 (0.000)    | 0.153 (0.004)    | 0 (0.000) |     1.29 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            4 |     7171 | 2024-09-11 | GardenGarage          | W   | 0.060      | 0.333        | 0.001 (0.000)    | 0.413 (0.008)    | 0 (0.000) |     1.56 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            3 |     7300 | 2024-09-09 | Team Kosovo           | L   | 0.046      | -            | -                | -                | -         |    -0.52 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            2 |     7505 | 2024-09-06 | Flame Sharks          | L   | 0.026      | -            | -                | -                | -         |    -0.23 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            1 |     7563 | 2024-09-05 | Divergent             | W   | 0.020      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.32 | aNsavage, flouzer, Snoob, sToRm, wolterz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
