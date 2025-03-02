### Roster Details<br />
Team Name: Change The Game<br />
Roster: 957, Hack1ng, LaiKeXu, yancher, zero<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [23]( ../standings_asia.md)<br />
<br />
Final Rank Value:  708.6<br />
<br />
Final Rank Value (708.6) = Starting Rank Value (789.3) + Head To Head Adjustments (-80.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.084[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.3
- 400 + ( ( 0.195 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 789.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |       19 | 2025-02-26 | DogEvil               | L   | 1.000      | -            | -                | -                | -         |    -8.97 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           13 |       33 | 2025-02-25 | FengDa Gaming         | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.553 (0.079)    | 0 (0.000) |    15.15 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           12 |       39 | 2025-02-25 | Shika                 | L   | 1.000      | -            | -                | -                | -         |   -19.41 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           11 |       59 | 2025-02-24 | Unsettled Resentment  | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.259 (0.037)    | 0 (0.000) |    17.00 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|           10 |      422 | 2025-02-15 | Loveset               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.140 (0.020)    | 0 (0.000) |     5.67 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            9 |      428 | 2025-02-15 | Team XDM              | L   | 1.000      | -            | -                | -                | -         |   -22.11 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            8 |      432 | 2025-02-14 | Secret (Chinese team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.40 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            7 |      440 | 2025-02-14 | Steel Helmet          | L   | 1.000      | -            | -                | -                | -         |   -22.88 | 957, Hack1ng, LaiKeXu, Yancher, zero    |
|            6 |      868 | 2025-02-05 | Five Handsome Guys    | L   | 1.000      | -            | -                | -                | -         |   -17.96 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            5 |     1317 | 2024-12-27 | FengDa Gaming         | L   | 0.776      | -            | -                | -                | -         |   -13.32 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            4 |     1422 | 2024-12-22 | Magic Cape            | L   | 0.737      | -            | -                | -                | -         |   -14.44 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            3 |     1522 | 2024-12-19 | Dolphins Esports      | W   | 0.723      | 0.143        | 0.015 (0.002)    | 0.000 (0.000)    | 1 (0.723) |     5.43 | 957, Hack1ng, LaiKeXu, yancher, zero    |
|            2 |     5623 | 2024-10-05 | Magic Cape            | L   | 0.217      | -            | -                | -                | -         |    -4.39 | 957, Hack1ng, LaiKeXu, LIngGod, yancher |
|            1 |     5685 | 2024-10-04 | StudFarm              | L   | 0.211      | -            | -                | -                | -         |    -4.89 | 957, Hack1ng, LaiKeXu, LIngGod, yancher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,369.74)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.777 | $685.04        | $532.43         |
| 2024-12-19 |      0.723 | $27,410.77     | $19,830.93      |
| 2024-10-06 |      0.224 | $28.50         | $6.38           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
