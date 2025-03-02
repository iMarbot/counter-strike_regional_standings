### Roster Details<br />
Team Name: 8Sins<br />
Roster: Dutchy, moz, Prime, wfn, Wolfie<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  891.8<br />
<br />
Final Rank Value (891.8) = Starting Rank Value (915.2) + Head To Head Adjustments (-23.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.303[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.475[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 915.2
- 400 + ( ( 0.258 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 915.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      104 | 2025-02-23 | ALASKA                    | L   | 1.000      | -            | -                | -                | -         |   -16.22 | Dutchy, moz, Prime, wfn, Wolfie  |
|           14 |      149 | 2025-02-22 | ALASKA                    | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.875 (0.125)    | 1 (1.000) |    14.51 | Dutchy, moz, Prime, wfn, Wolfie  |
|           13 |      159 | 2025-02-22 | ANTARCTICA (British team) | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.123 (0.018)    | 1 (1.000) |     8.07 | Dutchy, moz, Prime, wfn, Wolfie  |
|           12 |      183 | 2025-02-21 | DUSTY                     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | 1 (1.000) |    11.53 | Dutchy, moz, Prime, wfn, Wolfie  |
|           11 |      772 | 2025-02-07 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |   -22.16 | Dutchy, moz, Prime, wfn, Wolfie  |
|           10 |     3075 | 2024-11-20 | Belfast Storm             | L   | 0.527      | -            | -                | -                | -         |   -11.94 | coldpera, f0cus, moz, Prime, wfn |
|            9 |     3821 | 2024-11-07 | The Last Resort           | L   | 0.441      | -            | -                | -                | -         |   -10.44 | coldpera, f0cus, moz, Prime, wfn |
|            8 |     3865 | 2024-11-06 | Belfast Storm             | W   | 0.434      | 0.143        | 0.002 (0.000)    | 0.162 (0.010)    | 0 (0.000) |     3.49 | coldpera, f0cus, moz, Prime, wfn |
|            7 |     3866 | 2024-11-06 | Annex Esports             | W   | 0.434      | 0.143        | 0.000 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     1.97 | coldpera, f0cus, moz, Prime, wfn |
|            6 |     3921 | 2024-11-05 | ROYALS                    | W   | 0.427      | 0.143        | 0.004 (0.000)    | 0.205 (0.013)    | 0 (0.000) |     3.18 | coldpera, f0cus, moz, Prime, wfn |
|            5 |     4482 | 2024-10-27 | Verdant fe                | L   | 0.364      | -            | -                | -                | -         |    -8.87 | f0cus, Menace, moz, Prime, wfn   |
|            4 |     4499 | 2024-10-26 | The Last Resort           | W   | 0.360      | 0.143        | 0.001 (0.000)    | 0.161 (0.008)    | 1 (0.360) |     2.85 | f0cus, Menace, moz, Prime, wfn   |
|            3 |     4512 | 2024-10-26 | The Last Resort           | W   | 0.359      | 0.143        | 0.000 (0.000)    | 0.043 (0.002)    | 1 (0.359) |     1.88 | f0cus, Menace, moz, Prime, wfn   |
|            2 |     4538 | 2024-10-26 | ALASKA                    | L   | 0.358      | -            | -                | -                | -         |    -3.07 | f0cus, Menace, moz, Prime, wfn   |
|            1 |     4581 | 2024-10-25 | Annex Esports             | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.059 (0.003)    | 1 (0.353) |     1.86 | f0cus, Menace, moz, Prime, wfn   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,669.90)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $1,326.20      | $1,326.20       |
| 2024-10-27 |      0.366 | $939.67        | $343.70         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
