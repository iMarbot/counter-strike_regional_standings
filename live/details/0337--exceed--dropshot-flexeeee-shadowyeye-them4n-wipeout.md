### Roster Details<br />
Team Name: Exceed<br />
Roster: DropShot, flexeeee, Shadowyeye, TheM4N, wipeout<br />
Global Rank: [337](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [53]( ../standings_asia.md)<br />
<br />
Final Rank Value:  630.5<br />
<br />
Final Rank Value (630.5) = Starting Rank Value (630.8) + Head To Head Adjustments (-0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.149[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.8
- 400 + ( ( 0.116 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 630.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     5981 | 2024-09-29 | The Punishers                  | L   | 0.178      | -            | -                | -                | -         |    -2.37 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            6 |     6061 | 2024-09-28 | Nixuh                          | W   | 0.171      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 1 (0.171) |     2.43 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            5 |     6130 | 2024-09-27 | Kipi                           | W   | 0.166      | 0.143        | 0.000 (0.000)    | 0.027 (0.001)    | 1 (0.166) |     1.77 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            4 |     6756 | 2024-09-18 | Kitsune Esports                | L   | 0.106      | -            | -                | -                | -         |    -1.76 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            3 |     7288 | 2024-09-09 | The Punishers                  | L   | 0.046      | -            | -                | -                | -         |    -0.63 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            2 |     7582 | 2024-09-05 | Synthesis (South African team) | W   | 0.020      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.26 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            1 |     7720 | 2024-09-03 | Dreamer Esports                | W   | 0.007      | 0.250        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.06 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($746.14)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.178 | $4,089.70      | $726.21         |
| 2024-09-22 |      0.133 | $150.00        | $19.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
