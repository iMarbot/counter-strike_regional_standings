### Roster Details<br />
Team Name: Verdant fe<br />
Roster: cryths, CYPHER, dobbo, Gizmy, Yoshwa<br />
Global Rank: [211](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [154]( ../standings_europe.md)<br />
<br />
Final Rank Value:  704.2<br />
<br />
Final Rank Value (704.2) = Starting Rank Value (686.9) + Head To Head Adjustments (17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.9
- 400 + ( ( 0.144 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 686.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4468 | 2024-10-27 | ALASKA          | L   | 0.366      | -            | -                | -                | -         |    -1.16 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            4 |     4482 | 2024-10-27 | 8Sins           | W   | 0.364      | 0.143        | 0.005 (0.000)    | 0.234 (0.012)    | 1 (0.364) |     8.87 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            3 |     4510 | 2024-10-26 | ALASKA          | L   | 0.359      | -            | -                | -                | -         |    -1.10 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            2 |     4537 | 2024-10-26 | The Last Resort | W   | 0.358      | 0.143        | 0.001 (0.000)    | 0.161 (0.008)    | 1 (0.358) |     6.10 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            1 |     4580 | 2024-10-25 | The Last Resort | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.043 (0.002)    | 1 (0.353) |     4.52 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($568.88)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.366 | $1,555.32      | $568.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
