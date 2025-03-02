### Roster Details<br />
Team Name: Yarp<br />
Roster: Amelie, ar1a, barf, maddy, morganne<br />
Global Rank: [304](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [45]( ../standings_asia.md)<br />
<br />
Final Rank Value:  645.8<br />
<br />
Final Rank Value (645.8) = Starting Rank Value (631.7) + Head To Head Adjustments (14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.283[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 631.7
- 400 + ( ( 0.116 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 631.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1318 | 2024-12-27 | Virtualgangstas | L   | 0.776      | -            | -                | -                | -         |   -13.46 | Amelie, ar1a, barf, maddy, morganne |
|            5 |     2104 | 2024-12-06 | Sootcase        | W   | 0.636      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.11 | Amelie, ar1a, maddy, Mew, morganne  |
|            4 |     2556 | 2024-11-29 | Virtualgangstas | W   | 0.590      | 0.233        | 0.001 (0.000)    | 0.036 (0.005)    | 0 (0.000) |     8.56 | Amelie, ar1a, barf, maddy, morganne |
|            3 |     3366 | 2024-11-15 | Team Berny050   | W   | 0.496      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.04 | Amelie, ar1a, barf, maddy, morganne |
|            2 |     4162 | 2024-11-01 | Team Berny050   | W   | 0.403      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.24 | Amelie, ar1a, barf, maddy, morganne |
|            1 |     4564 | 2024-10-25 | Team Berny050   | W   | 0.356      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.67 | Amelie, ar1a, barf, maddy, morganne |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($985.24)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-27 |      0.776 | $150.00        | $116.46         |
| 2024-12-06 |      0.636 | $350.00        | $222.74         |
| 2024-11-29 |      0.590 | $350.00        | $206.50         |
| 2024-11-15 |      0.496 | $350.00        | $173.74         |
| 2024-11-01 |      0.403 | $350.00        | $141.07         |
| 2024-10-25 |      0.356 | $350.00        | $124.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
