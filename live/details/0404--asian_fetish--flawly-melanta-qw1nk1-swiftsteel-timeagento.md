### Roster Details<br />
Team Name: Asian fetish<br />
Roster: flawly, melanta, qw1nk1, swiftsteel, timeagento<br />
Global Rank: [404](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [251]( ../standings_europe.md)<br />
<br />
Final Rank Value:  595.2<br />
<br />
Final Rank Value (595.2) = Starting Rank Value (590.7) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.214[<sup>1</sup>](#table2)
- Bounty Collected: 0.167[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 590.7
- 400 + ( ( 0.095 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 590.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     6023 | 2024-09-28 | K27                   | L   | 0.173      | -            | -                | -                | -         |    -0.76 | flawly, melanta, qw1nk1, swiftsteel, timeagento |
|            5 |     6098 | 2024-09-27 | Preasy Esport         | L   | 0.167      | -            | -                | -                | -         |    -1.22 | flawly, melanta, qw1nk1, swiftsteel, timeagento |
|            4 |     6108 | 2024-09-27 | ENTERPRISE Genesis    | W   | 0.167      | 0.143        | 0.001 (0.000)    | 0.178 (0.004)    | 0 (0.000) |     3.03 | flawly, melanta, qw1nk1, swiftsteel, timeagento |
|            3 |     6447 | 2024-09-23 | RUSH B (Russian team) | L   | 0.140      | -            | -                | -                | -         |    -0.70 | flawly, nota, qw1nk1, swiftsteel, timeagento    |
|            2 |     6561 | 2024-09-21 | Underrated            | W   | 0.127      | 0.278        | 0.002 (0.000)    | 0.271 (0.010)    | 0 (0.000) |     2.56 | flawly, nota, qw1nk1, swiftsteel, timeagento    |
|            1 |     6566 | 2024-09-21 | Nemiga Academy        | W   | 0.127      | 0.278        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.54 | flawly, nota, qw1nk1, swiftsteel, timeagento    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-23 |      0.140 | $500.00        | $70.00          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
