### Roster Details<br />
Team Name: LOADING (French team)<br />
Roster: Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol<br />
Global Rank: [495](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [306]( ../standings_europe.md)<br />
<br />
Final Rank Value:  521.5<br />
<br />
Final Rank Value (521.5) = Starting Rank Value (514.0) + Head To Head Adjustments (7.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 514.0
- 400 + ( ( 0.057 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 514.0


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
|            8 |     5622 | 2024-10-05 | KONO.ECF            | L   | 0.210      | -            | -                | -                | -         |    -0.67 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            7 |     5859 | 2024-10-01 | Leo Team            | W   | 0.185      | 0.354        | 0.026 (0.002)    | 0.748 (0.049)    | 0 (0.000) |     4.99 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            6 |     5929 | 2024-09-30 | Preasy Esport       | W   | 0.177      | 0.354        | 0.012 (0.001)    | 0.701 (0.044)    | 0 (0.000) |     4.68 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            5 |     6124 | 2024-09-27 | Leo Team            | L   | 0.158      | -            | -                | -                | -         |    -0.72 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            4 |     6576 | 2024-09-21 | Preasy Esport       | L   | 0.118      | -            | -                | -                | -         |    -0.60 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            3 |     6632 | 2024-09-20 | Natus Vincere Youth | L   | 0.112      | -            | -                | -                | -         |    -1.90 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            2 |     6755 | 2024-09-18 | ROYALS              | W   | 0.098      | 0.333        | 0.004 (0.000)    | 0.200 (0.007)    | 0 (0.000) |     2.23 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |
|            1 |     6792 | 2024-09-18 | GenOne              | L   | 0.095      | -            | -                | -                | -         |    -0.44 | Gauthierlelelele, Jas_x, kayZ, Razzmo, Revol |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
