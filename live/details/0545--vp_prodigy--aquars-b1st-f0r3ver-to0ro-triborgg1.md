### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: AquaRS, b1st, F0R3VER, tO0RO, TriBorgg1<br />
Global Rank: [545](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [337]( ../standings_europe.md)<br />
<br />
Final Rank Value:  482.1<br />
<br />
Final Rank Value (482.1) = Starting Rank Value (464.8) + Head To Head Adjustments (17.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.127[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.032<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 464.8
- 400 + ( ( 0.032 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 464.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      622 | 2025-02-09 | Eternal premium                 | L   | 1.000      | -            | -                | -                | -         |    -7.66 | AquaRS, b1st, F0R3VER, tO0RO, TriBorgg1 |
|           14 |      627 | 2025-02-09 | Broken dreams                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.87 | AquaRS, b1st, F0R3VER, tO0RO, TriBorgg1 |
|           13 |      878 | 2025-02-05 | NewBALLS                        | L   | 1.000      | -            | -                | -                | -         |    -7.51 | AquaRS, b1st, F0R3VER, tO0RO, TriBorgg1 |
|           12 |      880 | 2025-02-05 | TEAM GELO                       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    12.05 | AquaRS, b1st, F0R3VER, tO0RO, TriBorgg1 |
|           11 |     2419 | 2024-12-01 | BAKS Esports                    | L   | 0.600      | -            | -                | -                | -         |    -8.38 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|           10 |     2639 | 2024-11-28 | LEON Esports                    | L   | 0.579      | -            | -                | -                | -         |    -3.18 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            9 |     2723 | 2024-11-26 | VOID GAMING (Russian team)      | W   | 0.567      | 0.333        | 0.000 (0.000)    | 0.028 (0.005)    | 0 (0.000) |     8.25 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            8 |     2855 | 2024-11-23 | HOTU                            | L   | 0.547      | -            | -                | -                | -         |    -3.41 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            7 |     3245 | 2024-11-17 | HOTU                            | L   | 0.505      | -            | -                | -                | -         |    -3.79 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            6 |     3258 | 2024-11-17 | Donstu Esports                  | W   | 0.505      | 0.143        | 0.000 (0.000)    | 0.205 (0.015)    | 0 (0.000) |     8.41 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            5 |     3274 | 2024-11-17 | Hyuga                           | L   | 0.504      | -            | -                | -                | -         |    -6.98 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            4 |     3677 | 2024-11-10 | Cerberus eSports (Russian team) | W   | 0.458      | 0.143        | 0.000 (0.000)    | 0.081 (0.005)    | 0 (0.000) |     9.49 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            3 |     3681 | 2024-11-10 | Mangustini                      | W   | 0.458      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.71 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            2 |     4070 | 2024-11-03 | HOTU                            | L   | 0.412      | -            | -                | -                | -         |    -2.85 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |
|            1 |     4079 | 2024-11-03 | Pisyatdva                       | W   | 0.411      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.28 | AquaRS, b1st, tO0RO, TriBorgg1, turbo   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
