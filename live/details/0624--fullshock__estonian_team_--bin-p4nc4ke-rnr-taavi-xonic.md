### Roster Details<br />
Team Name: FullShock (Estonian team)<br />
Roster: Bin, P4nc4ke, rnr, Taavi, Xonic<br />
Global Rank: [624](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [381]( ../standings_europe.md)<br />
<br />
Final Rank Value:  382.0<br />
<br />
Final Rank Value (382.0) = Starting Rank Value (400.0) + Head To Head Adjustments (-18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3234 | 2024-11-17 | Truck Drivers           | L   | 0.506      | -            | -                | -                | -         |    -2.63 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            6 |     3665 | 2024-11-10 | Godne                   | L   | 0.459      | -            | -                | -                | -         |    -7.32 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            5 |     4036 | 2024-11-03 | M1Z                     | L   | 0.413      | -            | -                | -                | -         |    -6.35 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            4 |     4449 | 2024-10-27 | W2TE                    | W   | 0.367      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     5.88 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            3 |     5070 | 2024-10-15 | SHOO7ERS                | L   | 0.286      | -            | -                | -                | -         |    -1.66 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            2 |     5135 | 2024-10-13 | GENESIS (Estonian team) | L   | 0.272      | -            | -                | -                | -         |    -3.25 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            1 |     5519 | 2024-10-06 | ANimaleGG               | L   | 0.226      | -            | -                | -                | -         |    -2.72 | Bin, P4nc4ke, rnr, Taavi, Xonic |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
