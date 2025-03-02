### Roster Details<br />
Team Name: NO BYSTANDERS<br />
Roster: actava, K4je, noph, YDI, z3r0X<br />
Global Rank: [523](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [326]( ../standings_europe.md)<br />
<br />
Final Rank Value:  493.3<br />
<br />
Final Rank Value (493.3) = Starting Rank Value (489.4) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.045<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 489.4
- 400 + ( ( 0.045 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 489.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5231 | 2024-10-12 | BAKS Esports                    | L   | 0.265      | -            | -                | -                | -         |    -3.88 | actava, K4je, noph, YDI, z3r0X |
|            5 |     5242 | 2024-10-12 | HOTU                            | W   | 0.264      | 0.143        | 0.003 (0.000)    | 0.777 (0.029)    | 0 (0.000) |     6.51 | actava, K4je, noph, YDI, z3r0X |
|            4 |     6518 | 2024-09-22 | CS2NEWS                         | L   | 0.132      | -            | -                | -                | -         |    -1.73 | actava, K4je, noph, YDI, z3r0X |
|            3 |     6573 | 2024-09-21 | Nuclear TigeRES                 | W   | 0.126      | 0.143        | 0.004 (0.000)    | 0.586 (0.011)    | 0 (0.000) |     3.47 | actava, K4je, noph, YDI, z3r0X |
|            2 |     7397 | 2024-09-07 | Cerberus eSports (Russian team) | L   | 0.033      | -            | -                | -                | -         |    -0.37 | actava, K4je, noph, YDI, z3r0X |
|            1 |     7714 | 2024-09-03 | Astra Gaming                    | L   | 0.007      | -            | -                | -                | -         |    -0.13 | actava, K4je, noph, YDI, z3r0X |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
