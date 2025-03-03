### Roster Details<br />
Team Name: StandOnBusiness<br />
Roster: cuze, milesd, Outback, Revampzz, tripp<br />
Global Rank: [588](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [137]( ../standings_americas.md)<br />
<br />
Final Rank Value:  411.4<br />
<br />
Final Rank Value (411.4) = Starting Rank Value (400.6) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.6
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2255 | 2024-12-03 | SUPER EVIL GANG     | L   | 0.608      | -            | -                | -                | -         |    -3.18 | cuze, milesd, Outback, Revampzz, tripp |
|            4 |     2390 | 2024-12-01 | MCS Gaming          | L   | 0.594      | -            | -                | -                | -         |    -3.86 | cuze, milesd, Outback, Revampzz, tripp |
|            3 |     2577 | 2024-11-29 | Ascend              | W   | 0.581      | 0.372        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |    10.84 | cuze, milesd, Outback, Revampzz, tripp |
|            2 |     2699 | 2024-11-26 | Orbital vsat online | W   | 0.561      | 0.372        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |     8.75 | cuze, milesd, Outback, Revampzz, tripp |
|            1 |     6627 | 2024-09-20 | InControl           | L   | 0.113      | -            | -                | -                | -         |    -1.78 | corim, cuze, milesd, Revampzz, tripp   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
