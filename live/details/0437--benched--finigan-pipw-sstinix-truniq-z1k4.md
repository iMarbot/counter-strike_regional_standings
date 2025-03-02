### Roster Details<br />
Team Name: Benched<br />
Roster: FinigaN, Pipw, sstiNiX, TruNiQ, z1k4<br />
Global Rank: [437](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [273]( ../standings_europe.md)<br />
<br />
Final Rank Value:  567.5<br />
<br />
Final Rank Value (567.5) = Starting Rank Value (538.0) + Head To Head Adjustments (29.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.069<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.0
- 400 + ( ( 0.069 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 538.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      145 | 2025-02-22 | Insilio               | L   | 1.000      | -            | -                | -                | -         |    -8.26 | FinigaN, Pipw, sstiNiX, TruNiQ, z1k4 |
|            6 |      237 | 2025-02-20 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |    -3.97 | FinigaN, Pipw, sstiNiX, supra, z1k4  |
|            5 |      412 | 2025-02-15 | Ninjas in Pyjamas     | L   | 1.000      | -            | -                | -                | -         |   -10.77 | FinigaN, Pipw, sstiNiX, supra, z1k4  |
|            4 |      457 | 2025-02-14 | Eternal Fire Academy  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    11.77 | FinigaN, Pipw, sstiNiX, supra, z1k4  |
|            3 |      678 | 2025-02-08 | OG                    | L   | 1.000      | -            | -                | -                | -         |    -3.30 | FinigaN, Pipw, sstiNiX, supra, z1k4  |
|            2 |      699 | 2025-02-08 | ATRIVM                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    13.80 | FinigaN, Pipw, sstiNiX, supra, z1k4  |
|            1 |      763 | 2025-02-07 | B8                    | W   | 1.000      | 0.143        | 0.124 (0.018)    | 0.590 (0.084)    | 0 (0.000) |    30.19 | FinigaN, Pipw, sstiNiX, supra, z1k4  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
