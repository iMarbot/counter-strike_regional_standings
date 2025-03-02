### Roster Details<br />
Team Name: Inner Circle Esports<br />
Roster: Fessor, kRaSnaL, oskar, Q-Q, STYKO<br />
Global Rank: [447](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [280]( ../standings_europe.md)<br />
<br />
Final Rank Value:  560.7<br />
<br />
Final Rank Value (560.7) = Starting Rank Value (514.7) + Head To Head Adjustments (46.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 514.7
- 400 + ( ( 0.057 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 514.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |       87 | 2025-02-23 | Roler Coaster      | L   | 1.000      | -            | -                | -                | -         |   -13.66 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            6 |       92 | 2025-02-23 | K27                | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.776 (0.111)    | 0 (0.000) |    24.96 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            5 |      101 | 2025-02-23 | TEAM NEXT LEVEL    | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.465 (0.066)    | 0 (0.000) |    24.92 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            4 |      134 | 2025-02-22 | MOUZ NXT           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.186 (0.027)    | 0 (0.000) |    18.80 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            3 |      244 | 2025-02-20 | Informmix          | L   | 1.000      | -            | -                | -                | -         |   -15.23 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            2 |      701 | 2025-02-08 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |    -4.14 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |
|            1 |      767 | 2025-02-07 | Superior Esports   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.36 | Fessor, kRaSnaL, oskar, Q-Q, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
