### Roster Details<br />
Team Name: Blazing Beavers<br />
Roster: Bay, Jayyyy, JohnSm1th, Rebornsoul, zune<br />
Global Rank: [583](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [95]( ../standings_asia.md)<br />
<br />
Final Rank Value:  422.6<br />
<br />
Final Rank Value (422.6) = Starting Rank Value (400.7) + Head To Head Adjustments (21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.7
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1044 | 2025-02-01 | SemperFi Esports         | L   | 1.000      | -            | -                | -                | -         |    -8.55 | Bay, Jayyyy, JohnSm1th, Rebornsoul, zune |
|            4 |     1046 | 2025-02-01 | Brojay and Co            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    14.39 | Bay, Jayyyy, JohnSm1th, Rebornsoul, zune |
|            3 |     1068 | 2025-02-01 | CAMO                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    15.42 | Bay, Jayyyy, JohnSm1th, Rebornsoul, zune |
|            2 |     1073 | 2025-01-31 | Unempluzzed              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.69 | Bay, Jayyyy, JohnSm1th, Rebornsoul, zune |
|            1 |     1077 | 2025-01-31 | Underground Esports Club | L   | 1.000      | -            | -                | -                | -         |   -15.07 | Bay, Jayyyy, JohnSm1th, Rebornsoul, zune |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
