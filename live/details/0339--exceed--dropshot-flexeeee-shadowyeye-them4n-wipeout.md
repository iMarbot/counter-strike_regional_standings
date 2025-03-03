### Roster Details<br />
Team Name: Exceed<br />
Roster: DropShot, flexeeee, Shadowyeye, TheM4N, wipeout<br />
Global Rank: [339](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [53]( ../standings_asia.md)<br />
<br />
Final Rank Value:  629.0<br />
<br />
Final Rank Value (629.0) = Starting Rank Value (629.3) + Head To Head Adjustments (-0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.148[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.3
- 400 + ( ( 0.115 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 629.3


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
|            6 |     5993 | 2024-09-29 | The Punishers                  | L   | 0.169      | -            | -                | -                | -         |    -2.26 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            5 |     6073 | 2024-09-28 | Nixuh                          | W   | 0.163      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 1 (0.163) |     2.32 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            4 |     6142 | 2024-09-27 | Kipi                           | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.027 (0.001)    | 1 (0.158) |     1.69 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            3 |     6768 | 2024-09-18 | Kitsune Esports                | L   | 0.098      | -            | -                | -                | -         |    -1.62 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            2 |     7300 | 2024-09-09 | The Punishers                  | L   | 0.038      | -            | -                | -                | -         |    -0.52 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |
|            1 |     7594 | 2024-09-05 | Synthesis (South African team) | W   | 0.012      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.12 | DropShot, flexeeee, Shadowyeye, TheM4N, wipeout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($711.40)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.169 | $4,089.70      | $692.69         |
| 2024-09-22 |      0.125 | $150.00        | $18.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
