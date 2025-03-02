### Roster Details<br />
Team Name: Unorganized Five<br />
Roster: devus, FaskDee, Mathew, striNg, ykyli<br />
Global Rank: [432](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [269]( ../standings_europe.md)<br />
<br />
Final Rank Value:  572.4<br />
<br />
Final Rank Value (572.4) = Starting Rank Value (574.4) + Head To Head Adjustments (-2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.202[<sup>1</sup>](#table2)
- Bounty Collected: 0.147[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.087<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.4
- 400 + ( ( 0.087 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 574.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3729 | 2024-11-09 | Team Fragster        | L   | 0.452      | -            | -                | -                | -         |    -6.53 | devus, FaskDee, Mathew, striNg, ykyli |
|            9 |     3835 | 2024-11-07 | UNEVEN               | W   | 0.440      | 0.143        | 0.000 (0.000)    | 0.009 (0.001)    | 0 (0.000) |     4.58 | devus, FaskDee, Mathew, striNg, ykyli |
|            8 |     3998 | 2024-11-04 | Entropy Gaming       | L   | 0.420      | -            | -                | -                | -         |    -6.89 | devus, FaskDee, Mathew, striNg, ykyli |
|            7 |     4054 | 2024-11-03 | AKA HERO             | W   | 0.413      | 0.143        | 0.000 (0.000)    | 0.062 (0.004)    | 0 (0.000) |     6.83 | devus, FaskDee, Mathew, striNg, ykyli |
|            6 |     4886 | 2024-10-18 | RIZON                | W   | 0.306      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.58 | devus, FaskDee, Mathew, striNg, ykyli |
|            5 |     5140 | 2024-10-13 | BIG SELECTA          | W   | 0.272      | 0.143        | 0.000 (0.000)    | 0.049 (0.002)    | 0 (0.000) |     4.23 | devus, FaskDee, Mathew, striNg, ykyli |
|            4 |     5660 | 2024-10-04 | Team Fragster        | L   | 0.213      | -            | -                | -                | -         |    -3.14 | devus, FaskDee, Mathew, striNg, ykyli |
|            3 |     6125 | 2024-09-27 | Reveal (German team) | L   | 0.166      | -            | -                | -                | -         |    -2.20 | devus, FaskDee, Mathew, striNg, ykyli |
|            2 |     7080 | 2024-09-13 | ALTERNATE aTTaX Evo  | L   | 0.073      | -            | -                | -                | -         |    -1.03 | devus, FaskDee, Mathew, striNg, ykyli |
|            1 |     7509 | 2024-09-06 | Team NinjaParentz    | L   | 0.026      | -            | -                | -                | -         |    -0.42 | devus, FaskDee, Mathew, striNg, ykyli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($36.99)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.460 | $80.42         | $36.99          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
