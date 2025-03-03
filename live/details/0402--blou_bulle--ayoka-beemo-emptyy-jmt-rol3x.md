### Roster Details<br />
Team Name: Blou Bulle<br />
Roster: ayoka, Beemo, EmpTyy, jmt, Rol3x<br />
Global Rank: [402](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [67]( ../standings_asia.md)<br />
<br />
Final Rank Value:  597.1<br />
<br />
Final Rank Value (597.1) = Starting Rank Value (593.2) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.222[<sup>1</sup>](#table2)
- Bounty Collected: 0.163[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 593.2
- 400 + ( ( 0.097 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 593.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1842 | 2024-12-12 | Kitsune Esports | L   | 0.665      | -            | -                | -                | -         |   -10.53 | ayoka, Beemo, EmpTyy, jmt, Rol3x |
|            4 |     1931 | 2024-12-10 | Southern5       | W   | 0.652      | 0.250        | 0.000 (0.000)    | 0.055 (0.009)    | 0 (0.000) |     9.81 | ayoka, Beemo, EmpTyy, jmt, Rol3x |
|            3 |     2273 | 2024-12-03 | Monarch Realm   | W   | 0.605      | 0.250        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     4.86 | ayoka, Beemo, EmpTyy, jmt, Rol3x |
|            2 |     2344 | 2024-12-02 | The Punishers   | L   | 0.599      | -            | -                | -                | -         |    -6.98 | ayoka, Beemo, EmpTyy, jmt, Rol3x |
|            1 |     2673 | 2024-11-27 | Kipi            | W   | 0.565      | 0.250        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     6.72 | ayoka, Beemo, EmpTyy, jmt, Rol3x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102.77)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $150.00        | $102.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
