### Roster Details<br />
Team Name: Panter Esports<br />
Roster: ANGEK, Brajean, Cuboss, Rdq, sop<br />
Global Rank: [319](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [64]( ../standings_americas.md)<br />
<br />
Final Rank Value:  639.6<br />
<br />
Final Rank Value (639.6) = Starting Rank Value (617.5) + Head To Head Adjustments (22.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.248[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.5
- 400 + ( ( 0.109 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 617.5


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
|            5 |     1612 | 2024-12-15 | TriChetiri      | L   | 0.688      | -            | -                | -                | -         |   -10.91 | ANGEK, Brajean, Cuboss, Rdq, sop |
|            4 |     1753 | 2024-12-13 | Quebon          | W   | 0.674      | 0.274        | 0.001 (0.000)    | 0.028 (0.005)    | 0 (0.000) |     9.19 | ANGEK, Brajean, Cuboss, Rdq, sop |
|            3 |     1864 | 2024-12-11 | Abduls          | W   | 0.661      | 0.274        | 0.001 (0.000)    | 0.060 (0.011)    | 0 (0.000) |     9.89 | ANGEK, Brajean, Cuboss, Rdq, sop |
|            2 |     1950 | 2024-12-09 | Lobster Legion  | W   | 0.647      | 0.274        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.84 | ANGEK, Brajean, Cuboss, Rdq, sop |
|            1 |     2052 | 2024-12-07 | NeverBrokeAgain | W   | 0.634      | 0.274        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.06 | ANGEK, Brajean, Cuboss, Rdq, sop |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($309.38)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.688 | $450.00        | $309.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
