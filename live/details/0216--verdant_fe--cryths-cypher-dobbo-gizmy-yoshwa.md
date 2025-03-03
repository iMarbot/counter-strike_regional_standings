### Roster Details<br />
Team Name: Verdant fe<br />
Roster: cryths, CYPHER, dobbo, Gizmy, Yoshwa<br />
Global Rank: [216](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [154]( ../standings_europe.md)<br />
<br />
Final Rank Value:  702.9<br />
<br />
Final Rank Value (702.9) = Starting Rank Value (686.0) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.0
- 400 + ( ( 0.143 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 686.0


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
|            5 |     4480 | 2024-10-27 | ALASKA          | L   | 0.358      | -            | -                | -                | -         |    -1.12 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            4 |     4494 | 2024-10-27 | 8Sins           | W   | 0.356      | 0.143        | 0.005 (0.000)    | 0.233 (0.012)    | 1 (0.356) |     8.69 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            3 |     4522 | 2024-10-26 | ALASKA          | L   | 0.351      | -            | -                | -                | -         |    -1.06 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            2 |     4549 | 2024-10-26 | The Last Resort | W   | 0.350      | 0.143        | 0.001 (0.000)    | 0.159 (0.008)    | 1 (0.350) |     5.97 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |
|            1 |     4592 | 2024-10-25 | The Last Resort | W   | 0.345      | 0.143        | 0.000 (0.000)    | 0.042 (0.002)    | 1 (0.345) |     4.42 | cryths, CYPHER, dobbo, Gizmy, Yoshwa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($556.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.358 | $1,555.32      | $556.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
