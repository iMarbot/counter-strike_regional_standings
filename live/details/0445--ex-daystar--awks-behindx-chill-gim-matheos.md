### Roster Details<br />
Team Name: Ex-Daystar<br />
Roster: awks, BehinDx, Chill, giM, Matheos<br />
Global Rank: [445](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [275]( ../standings_europe.md)<br />
<br />
Final Rank Value:  563.5<br />
<br />
Final Rank Value (563.5) = Starting Rank Value (531.2) + Head To Head Adjustments (32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 531.2
- 400 + ( ( 0.066 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 531.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      150 | 2025-02-22 | Roler Coaster     | L   | 1.000      | -            | -                | -                | -         |   -16.94 | awks, BehinDx, Chill, giM, Matheos |
|            6 |      676 | 2025-02-08 | TEAM NEXT LEVEL   | L   | 1.000      | -            | -                | -                | -         |    -8.08 | awks, BehinDx, Chill, giM, Matheos |
|            5 |      688 | 2025-02-08 | Hesta             | L   | 1.000      | -            | -                | -                | -         |    -7.99 | awks, BehinDx, Chill, giM, Matheos |
|            4 |      694 | 2025-02-08 | Betera Esports    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    15.57 | awks, BehinDx, Chill, giM, Matheos |
|            3 |      716 | 2025-02-08 | FAVBET Team       | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.801 (0.114)    | 0 (0.000) |    25.66 | awks, BehinDx, Chill, giM, Matheos |
|            2 |      765 | 2025-02-07 | Fire Flux Esports | W   | 1.000      | 0.143        | 0.008 (0.001)    | 1.000 (0.143)    | 0 (0.000) |    28.23 | awks, BehinDx, Chill, giM, Matheos |
|            1 |      995 | 2025-02-04 | Permitta Esports  | L   | 1.000      | -            | -                | -                | -         |    -4.25 | awks, BehinDx, Chill, giM, Matheos |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
