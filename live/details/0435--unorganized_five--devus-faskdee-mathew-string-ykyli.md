### Roster Details<br />
Team Name: Unorganized Five<br />
Roster: devus, FaskDee, Mathew, striNg, ykyli<br />
Global Rank: [435](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [269]( ../standings_europe.md)<br />
<br />
Final Rank Value:  572.9<br />
<br />
Final Rank Value (572.9) = Starting Rank Value (574.6) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.202[<sup>1</sup>](#table2)
- Bounty Collected: 0.147[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.087<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.6
- 400 + ( ( 0.087 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 574.6


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
|           10 |     3741 | 2024-11-09 | Team Fragster        | L   | 0.444      | -            | -                | -                | -         |    -6.42 | devus, FaskDee, Mathew, striNg, ykyli |
|            9 |     3847 | 2024-11-07 | UNEVEN               | W   | 0.432      | 0.143        | 0.000 (0.000)    | 0.008 (0.001)    | 0 (0.000) |     4.49 | devus, FaskDee, Mathew, striNg, ykyli |
|            8 |     4010 | 2024-11-04 | Entropy Gaming       | L   | 0.412      | -            | -                | -                | -         |    -6.76 | devus, FaskDee, Mathew, striNg, ykyli |
|            7 |     4066 | 2024-11-03 | AKA HERO             | W   | 0.405      | 0.143        | 0.000 (0.000)    | 0.060 (0.003)    | 0 (0.000) |     6.68 | devus, FaskDee, Mathew, striNg, ykyli |
|            6 |     4898 | 2024-10-18 | RIZON                | W   | 0.298      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.51 | devus, FaskDee, Mathew, striNg, ykyli |
|            5 |     5152 | 2024-10-13 | BIG SELECTA          | W   | 0.264      | 0.143        | 0.000 (0.000)    | 0.048 (0.002)    | 0 (0.000) |     4.09 | devus, FaskDee, Mathew, striNg, ykyli |
|            4 |     5672 | 2024-10-04 | Team Fragster        | L   | 0.205      | -            | -                | -                | -         |    -3.02 | devus, FaskDee, Mathew, striNg, ykyli |
|            3 |     6137 | 2024-09-27 | Reveal (German team) | L   | 0.158      | -            | -                | -                | -         |    -2.09 | devus, FaskDee, Mathew, striNg, ykyli |
|            2 |     7092 | 2024-09-13 | ALTERNATE aTTaX Evo  | L   | 0.065      | -            | -                | -                | -         |    -0.92 | devus, FaskDee, Mathew, striNg, ykyli |
|            1 |     7521 | 2024-09-06 | Team NinjaParentz    | L   | 0.018      | -            | -                | -                | -         |    -0.29 | devus, FaskDee, Mathew, striNg, ykyli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($36.33)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.452 | $80.42         | $36.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
