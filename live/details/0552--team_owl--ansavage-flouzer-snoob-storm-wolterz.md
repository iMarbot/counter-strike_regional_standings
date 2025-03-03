### Roster Details<br />
Team Name: Team OWL<br />
Roster: aNsavage, flouzer, Snoob, sToRm, wolterz<br />
Global Rank: [552](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [340]( ../standings_europe.md)<br />
<br />
Final Rank Value:  477.5<br />
<br />
Final Rank Value (477.5) = Starting Rank Value (476.0) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.151[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 476.0
- 400 + ( ( 0.038 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 476.0


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
|            6 |     6928 | 2024-09-15 | THE GENTLEMEN ESPORTS | L   | 0.078      | -            | -                | -                | -         |    -0.58 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            5 |     7074 | 2024-09-13 | BAKS Esports          | W   | 0.065      | 0.333        | 0.000 (0.000)    | 0.151 (0.003)    | 0 (0.000) |     1.14 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            4 |     7183 | 2024-09-11 | GardenGarage          | W   | 0.052      | 0.333        | 0.001 (0.000)    | 0.408 (0.007)    | 0 (0.000) |     1.34 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            3 |     7312 | 2024-09-09 | Team Kosovo           | L   | 0.038      | -            | -                | -                | -         |    -0.43 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            2 |     7517 | 2024-09-06 | Flame Sharks          | L   | 0.018      | -            | -                | -                | -         |    -0.16 | aNsavage, flouzer, Snoob, sToRm, wolterz |
|            1 |     7575 | 2024-09-05 | Divergent             | W   | 0.012      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.18 | aNsavage, flouzer, Snoob, sToRm, wolterz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
