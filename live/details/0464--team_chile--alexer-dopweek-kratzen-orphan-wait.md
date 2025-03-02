### Roster Details<br />
Team Name: Team Chile<br />
Roster: alexer, DOPWEEK, KratZen, OrphaN, wait<br />
Global Rank: [464](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [101]( ../standings_americas.md)<br />
<br />
Final Rank Value:  549.1<br />
<br />
Final Rank Value (549.1) = Starting Rank Value (538.8) + Head To Head Adjustments (10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.069<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.8
- 400 + ( ( 0.069 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 538.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3386 | 2024-11-15 | Team Kosovo     | W   | 0.493      | 0.617        | 0.000 (0.000)    | 0.006 (0.002)    | 1 (0.493) |     8.16 | alexer, DOPWEEK, KratZen, OrphaN, wait |
|            4 |     3393 | 2024-11-15 | MAFE MA3LOM     | W   | 0.492      | 0.617        | 0.000 (0.000)    | 0.023 (0.007)    | 1 (0.492) |     7.25 | alexer, DOPWEEK, KratZen, OrphaN, wait |
|            3 |     3458 | 2024-11-14 | Team Hungary    | L   | 0.486      | -            | -                | -                | -         |    -2.92 | alexer, DOPWEEK, KratZen, OrphaN, wait |
|            2 |     3463 | 2024-11-14 | GTZ.ESPORTS     | L   | 0.485      | -            | -                | -                | -         |    -0.45 | alexer, DOPWEEK, KratZen, OrphaN, wait |
|            1 |     3468 | 2024-11-14 | ALTERNATE aTTaX | L   | 0.485      | -            | -                | -                | -         |    -1.73 | alexer, DOPWEEK, KratZen, OrphaN, wait |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
