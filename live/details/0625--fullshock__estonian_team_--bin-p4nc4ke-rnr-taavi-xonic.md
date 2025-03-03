### Roster Details<br />
Team Name: FullShock (Estonian team)<br />
Roster: Bin, P4nc4ke, rnr, Taavi, Xonic<br />
Global Rank: [625](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [380]( ../standings_europe.md)<br />
<br />
Final Rank Value:  382.4<br />
<br />
Final Rank Value (382.4) = Starting Rank Value (400.0) + Head To Head Adjustments (-17.7)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


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
|            7 |     3246 | 2024-11-17 | Truck Drivers           | L   | 0.498      | -            | -                | -                | -         |    -2.59 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            6 |     3677 | 2024-11-10 | Godne                   | L   | 0.451      | -            | -                | -                | -         |    -7.19 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            5 |     4048 | 2024-11-03 | M1Z                     | L   | 0.405      | -            | -                | -                | -         |    -6.23 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            4 |     4461 | 2024-10-27 | W2TE                    | W   | 0.359      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     5.74 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            3 |     5082 | 2024-10-15 | SHOO7ERS                | L   | 0.277      | -            | -                | -                | -         |    -1.62 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            2 |     5147 | 2024-10-13 | GENESIS (Estonian team) | L   | 0.264      | -            | -                | -                | -         |    -3.16 | Bin, P4nc4ke, rnr, Taavi, Xonic |
|            1 |     5531 | 2024-10-06 | ANimaleGG               | L   | 0.218      | -            | -                | -                | -         |    -2.62 | Bin, P4nc4ke, rnr, Taavi, Xonic |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
