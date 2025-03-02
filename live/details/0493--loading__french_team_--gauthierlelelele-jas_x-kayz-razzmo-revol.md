### Roster Details<br />
Team Name: LOADING (French team)<br />
Roster: Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol<br />
Global Rank: [493](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [307]( ../standings_europe.md)<br />
<br />
Final Rank Value:  522.5<br />
<br />
Final Rank Value (522.5) = Starting Rank Value (514.6) + Head To Head Adjustments (7.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 514.6
- 400 + ( ( 0.057 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 514.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     5610 | 2024-10-05 | KONO.ECF            | L   | 0.218      | -            | -                | -                | -         |    -0.69 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            7 |     5847 | 2024-10-01 | Leo Team            | W   | 0.193      | 0.354        | 0.026 (0.002)    | 0.758 (0.052)    | 0 (0.000) |     5.21 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            6 |     5917 | 2024-09-30 | Preasy Esport       | W   | 0.186      | 0.354        | 0.012 (0.001)    | 0.710 (0.047)    | 0 (0.000) |     4.90 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            5 |     6112 | 2024-09-27 | Leo Team            | L   | 0.167      | -            | -                | -                | -         |    -0.75 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            4 |     6564 | 2024-09-21 | Preasy Esport       | L   | 0.127      | -            | -                | -                | -         |    -0.64 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            3 |     6620 | 2024-09-20 | Natus Vincere Youth | L   | 0.120      | -            | -                | -                | -         |    -2.04 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            2 |     6743 | 2024-09-18 | ROYALS              | W   | 0.107      | 0.333        | 0.004 (0.000)    | 0.205 (0.007)    | 0 (0.000) |     2.42 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            1 |     6780 | 2024-09-18 | GenOne              | L   | 0.104      | -            | -                | -                | -         |    -0.47 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
