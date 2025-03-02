### Roster Details<br />
Team Name: Ctrl Alt Defeat<br />
Roster: BENJYMIN, f0cus, onder, Sorex, z_nan<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  866.7<br />
<br />
Final Rank Value (866.7) = Starting Rank Value (865.0) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.467[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.0
- 400 + ( ( 0.233 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 865.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      111 | 2025-02-23 | ALASKA                    | L   | 1.000      | -            | -                | -                | -         |   -15.81 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            5 |      124 | 2025-02-22 | DUSTY                     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | 1 (1.000) |    12.20 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            4 |      151 | 2025-02-22 | ANTARCTICA (British team) | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.123 (0.018)    | 1 (1.000) |     8.59 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            3 |      161 | 2025-02-22 | The Last Resort           | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.161 (0.023)    | 1 (1.000) |     8.94 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            2 |      166 | 2025-02-22 | Proqfanclub               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 1 (1.000) |     3.32 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            1 |      186 | 2025-02-21 | ALASKA                    | L   | 1.000      | -            | -                | -                | -         |   -15.51 | BENJYMIN, f0cus, onder, Sorex, z_nan |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($599.95)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $599.95        | $599.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
