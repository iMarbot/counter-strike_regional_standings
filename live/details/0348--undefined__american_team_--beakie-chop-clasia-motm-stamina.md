### Roster Details<br />
Team Name: Undefined (American team)<br />
Roster: BeaKie, chop, CLASIA, motm, stamina<br />
Global Rank: [348](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [70]( ../standings_americas.md)<br />
<br />
Final Rank Value:  625.3<br />
<br />
Final Rank Value (625.3) = Starting Rank Value (620.3) + Head To Head Adjustments (5.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 620.3
- 400 + ( ( 0.110 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 620.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     6542 | 2024-09-21 | Akimbo Esports  | L   | 0.128      | -            | -                | -                | -         |    -1.86 | BeaKie, chop, CLASIA, motm, stamina |
|            7 |     6656 | 2024-09-19 | InControl       | W   | 0.115      | 0.372        | 0.001 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     1.85 | BeaKie, chop, CLASIA, motm, stamina |
|            6 |     6787 | 2024-09-17 | MIGHT           | W   | 0.102      | 0.372        | 0.002 (0.000)    | 0.444 (0.017)    | 0 (0.000) |     2.13 | BeaKie, chop, CLASIA, motm, stamina |
|            5 |     6908 | 2024-09-15 | Final Form      | W   | 0.088      | 0.372        | 0.001 (0.000)    | 0.076 (0.002)    | 0 (0.000) |     1.35 | BeaKie, chop, CLASIA, motm, stamina |
|            4 |     7054 | 2024-09-13 | Exceritus       | W   | 0.075      | 0.372        | 0.000 (0.000)    | 0.238 (0.007)    | 0 (0.000) |     1.19 | BeaKie, chop, CLASIA, motm, stamina |
|            3 |     7157 | 2024-09-11 | Jahsdnmasjdm v2 | W   | 0.062      | 0.372        | 0.000 (0.000)    | 0.013 (0.000)    | 0 (0.000) |     0.63 | BeaKie, chop, CLASIA, motm, stamina |
|            2 |     7324 | 2024-09-08 | Akimbo Esports  | L   | 0.042      | -            | -                | -                | -         |    -0.61 | BeaKie, chop, CLASIA, motm, stamina |
|            1 |     7547 | 2024-09-05 | MCS Gaming      | W   | 0.022      | 0.372        | 0.003 (0.000)    | 0.344 (0.003)    | 0 (0.000) |     0.37 | BeaKie, chop, CLASIA, motm, stamina |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($552.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.128 | $4,300.00      | $552.43         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
