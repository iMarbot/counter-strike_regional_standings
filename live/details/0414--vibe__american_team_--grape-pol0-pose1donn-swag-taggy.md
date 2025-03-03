### Roster Details<br />
Team Name: Vibe (American team)<br />
Roster: grape, Pol0, Pose1doNN, swag, taggy<br />
Global Rank: [414](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [94]( ../standings_americas.md)<br />
<br />
Final Rank Value:  588.9<br />
<br />
Final Rank Value (588.9) = Starting Rank Value (586.9) + Head To Head Adjustments (2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.227[<sup>1</sup>](#table2)
- Bounty Collected: 0.146[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.093<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 586.9
- 400 + ( ( 0.093 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 586.9


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
|            7 |     2323 | 2024-12-02 | SUPER EVIL GANG | L   | 0.601      | -            | -                | -                | -         |    -6.83 | grape, Pol0, Pose1doNN, swag, taggy |
|            6 |     2396 | 2024-12-01 | Zomblers        | W   | 0.594      | 0.372        | 0.000 (0.000)    | 0.047 (0.010)    | 0 (0.000) |     4.67 | grape, Pol0, Pose1doNN, swag, taggy |
|            5 |     2582 | 2024-11-29 | Undone          | L   | 0.581      | -            | -                | -                | -         |    -4.89 | grape, Pol0, Pose1doNN, swag, taggy |
|            4 |     2704 | 2024-11-26 | Lycus Empire    | W   | 0.561      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.45 | grape, Pol0, Pose1doNN, swag, taggy |
|            3 |     6506 | 2024-09-22 | Gentlemans Club | W   | 0.127      | 0.284        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.94 | blend, grape, Pol0, Skadoodle, swag |
|            2 |     6671 | 2024-09-19 | Ozempic 5       | W   | 0.107      | 0.284        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.59 | blend, grape, Pol0, Skadoodle, swag |
|            1 |     6803 | 2024-09-17 | THEMONEYTEAM    | W   | 0.094      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.11 | blend, grape, Pol0, Skadoodle, swag |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($126.94)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-22 |      0.127 | $1,000.00      | $126.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
