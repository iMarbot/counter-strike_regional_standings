### Roster Details<br />
Team Name: Cloud9<br />
Roster: Ax1Le, Boombl4, HeavyGod, ICY, interz<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.1<br />
<br />
Final Rank Value (928.1) = Starting Rank Value (891.4) + Head To Head Adjustments (36.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.247[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.4
- 400 + ( ( 0.246 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 891.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2371 | 2024-12-01 | Complexity      | L   | 0.603      | -            | -                | -                | -         |    -4.29 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           15 |     2452 | 2024-11-30 | PaiN Gaming     | L   | 0.596      | -            | -                | -                | -         |    -0.49 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           14 |     2550 | 2024-11-30 | Fnatic          | W   | 0.591      | 1.000        | 0.072 (0.042)    | 0.461 (0.272)    | 1 (0.591) |    13.01 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           13 |     2561 | 2024-11-29 | Team Liquid     | L   | 0.590      | -            | -                | -                | -         |    -0.64 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           12 |     3164 | 2024-11-19 | FaZe Clan       | L   | 0.518      | -            | -                | -                | -         |    -0.07 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           11 |     3177 | 2024-11-18 | SINNERS Esports | W   | 0.516      | 0.143        | 0.027 (0.002)    | 0.451 (0.033)    | 1 (0.516) |     8.56 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           10 |     3218 | 2024-11-17 | HEROIC          | W   | 0.509      | 0.143        | 0.131 (0.010)    | 0.404 (0.029)    | 1 (0.509) |    11.96 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            9 |     3255 | 2024-11-17 | Nemiga Gaming   | W   | 0.505      | 0.143        | 0.177 (0.013)    | 0.351 (0.025)    | 1 (0.505) |    11.09 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            8 |     3295 | 2024-11-16 | FaZe Clan       | L   | 0.503      | -            | -                | -                | -         |    -0.06 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            7 |     4609 | 2024-10-25 | Fnatic          | L   | 0.351      | -            | -                | -                | -         |    -3.06 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            6 |     4705 | 2024-10-22 | 9z Team         | W   | 0.333      | 0.934        | 0.015 (0.005)    | 0.121 (0.038)    | 0 (0.000) |     3.75 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            5 |     4714 | 2024-10-22 | The MongolZ     | L   | 0.331      | -            | -                | -                | -         |    -0.03 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            4 |     5273 | 2024-10-11 | Passion UA      | L   | 0.257      | -            | -                | -                | -         |    -2.42 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            3 |     7102 | 2024-09-13 | Tricked Esport  | L   | 0.071      | -            | -                | -                | -         |    -1.31 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            2 |     7451 | 2024-09-07 | Zero Tenacity   | W   | 0.032      | 0.384        | 0.028 (0.000)    | 0.692 (0.008)    | 0 (0.000) |     0.47 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            1 |     7625 | 2024-09-05 | ALTERNATE aTTaX | W   | 0.018      | 0.384        | 0.021 (0.000)    | 0.564 (0.004)    | 0 (0.000) |     0.31 | Ax1Le, Boombl4, HeavyGod, ICY, interz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,540.05)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.691 | $10,000.00     | $6,909.49       |
| 2024-09-07 |      0.032 | $20,000.00     | $630.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
