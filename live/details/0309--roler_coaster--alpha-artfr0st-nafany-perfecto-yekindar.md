### Roster Details<br />
Team Name: Roler Coaster<br />
Roster: alpha, ArtFr0st, nafany, Perfecto, YEKINDAR<br />
Global Rank: [309](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [204]( ../standings_europe.md)<br />
<br />
Final Rank Value:  644.8<br />
<br />
Final Rank Value (644.8) = Starting Rank Value (536.4) + Head To Head Adjustments (108.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.4
- 400 + ( ( 0.068 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 536.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |       96 | 2025-02-23 | ARCRED               | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.480 (0.069)    | 0 (0.000) |    22.72 | alpha, ArtFr0st, nafany, Perfecto, YEKINDAR |
|            4 |      102 | 2025-02-23 | Inner Circle Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |    13.65 | alpha, ArtFr0st, nafany, Perfecto, YEKINDAR |
|            3 |      106 | 2025-02-23 | Alliance             | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.570 (0.081)    | 0 (0.000) |    25.50 | alpha, ArtFr0st, nafany, Perfecto, YEKINDAR |
|            2 |      114 | 2025-02-23 | Team Novaq           | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.393 (0.056)    | 0 (0.000) |    29.58 | alpha, ArtFr0st, nafany, Perfecto, YEKINDAR |
|            1 |      150 | 2025-02-22 | Ex-Daystar           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |    16.94 | alpha, ArtFr0st, nafany, Perfecto, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
