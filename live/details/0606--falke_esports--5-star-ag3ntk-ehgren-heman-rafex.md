### Roster Details<br />
Team Name: FALKE ESPORTS<br />
Roster: 5-Star, Ag3NTK, Ehgren, HeMan, Rafex<br />
Global Rank: [606](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [370]( ../standings_europe.md)<br />
<br />
Final Rank Value:  399.4<br />
<br />
Final Rank Value (399.4) = Starting Rank Value (400.2) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.2
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.2


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
|            7 |     2434 | 2024-12-01 | Team M33        | L   | 0.599      | -            | -                | -                | -         |    -9.82 | 5-Star, Ag3NTK, Ehgren, HeMan, Rafex |
|            6 |     2610 | 2024-11-28 | XPERION NXT     | L   | 0.580      | -            | -                | -                | -         |    -3.90 | 5-Star, Ag3NTK, Ehgren, HeMan, Rafex |
|            5 |     2705 | 2024-11-26 | Ex-DOSKI        | W   | 0.567      | 0.333        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     8.70 | 5-Star, Ag3NTK, Ehgren, HeMan, Rafex |
|            4 |     4621 | 2024-10-24 | GOOFYBOYZ       | L   | 0.346      | -            | -                | -                | -         |    -1.39 | 5-Star, Ag3NTK, HeMan, Rafex, shin   |
|            3 |     4686 | 2024-10-22 | The Agency Clan | L   | 0.334      | -            | -                | -                | -         |    -0.85 | 5-Star, Ag3NTK, HeMan, Rafex, shin   |
|            2 |     4698 | 2024-10-22 | Talaintanse     | W   | 0.333      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     6.55 | 5-Star, Ag3NTK, HeMan, Rafex, shin   |
|            1 |     7343 | 2024-09-08 | GOOFYBOYZ       | L   | 0.039      | -            | -                | -                | -         |    -0.14 | 5-Star, Ag3NTK, ar3a, GOYO007, Rafex |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
