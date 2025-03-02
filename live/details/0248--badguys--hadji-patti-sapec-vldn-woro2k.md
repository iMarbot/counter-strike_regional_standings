### Roster Details<br />
Team Name: BadGuys<br />
Roster: hAdji, Patti, Sapec, VLDN, Woro2k<br />
Global Rank: [248](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [174]( ../standings_europe.md)<br />
<br />
Final Rank Value:  679.4<br />
<br />
Final Rank Value (679.4) = Starting Rank Value (593.4) + Head To Head Adjustments (85.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 593.4
- 400 + ( ( 0.097 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 593.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1207 | 2025-01-09 | KONO.ECF                   | L   | 0.859      | -            | -                | -                | -         |   -15.06 | hAdji, Patti, Sapec, VLDN, Woro2k |
|           11 |     1211 | 2025-01-08 | FLuffy Gangsters           | W   | 0.853      | 0.417        | 0.014 (0.005)    | 0.925 (0.329)    | 0 (0.000) |    18.83 | hAdji, Patti, Sapec, VLDN, Woro2k |
|           10 |     1218 | 2025-01-06 | WOPA Esport                | W   | 0.838      | 0.417        | 0.031 (0.011)    | 0.785 (0.275)    | 0 (0.000) |    18.89 | hAdji, Patti, Sapec, VLDN, Woro2k |
|            9 |     1221 | 2025-01-05 | Los kogutos                | L   | 0.832      | -            | -                | -                | -         |    -6.26 | hAdji, Patti, Sapec, VLDN, Woro2k |
|            8 |     1229 | 2025-01-03 | ECSTATIC                   | L   | 0.818      | -            | -                | -                | -         |    -4.72 | hAdji, Patti, Sapec, VLDN, Woro2k |
|            7 |     1284 | 2024-12-28 | GenOne                     | W   | 0.780      | 0.417        | 0.012 (0.004)    | 0.848 (0.276)    | 0 (0.000) |    17.50 | hAdji, Patti, Sapec, VLDN, Woro2k |
|            6 |     1484 | 2024-12-20 | Nuclear TigeRES            | W   | 0.728      | 0.143        | 0.004 (0.000)    | 0.586 (0.061)    | 0 (0.000) |    15.82 | hAdji, Kvem, Patti, VLDN, Woro2k  |
|            5 |     1492 | 2024-12-20 | NEVERMORE (Ukrainian team) | W   | 0.727      | 0.143        | 0.010 (0.001)    | 0.911 (0.095)    | 0 (0.000) |    17.35 | hAdji, Kvem, Patti, VLDN, Woro2k  |
|            4 |     1502 | 2024-12-20 | Dragon Esports Club        | W   | 0.727      | 0.143        | 0.007 (0.001)    | 0.312 (0.032)    | 0 (0.000) |    13.80 | hAdji, Kvem, Patti, VLDN, Woro2k  |
|            3 |     1772 | 2024-12-13 | Ex-GODSENT                 | L   | 0.680      | -            | -                | -                | -         |   -12.50 | hAdji, Kvem, Sapec, Topa, Woro2k  |
|            2 |     1776 | 2024-12-13 | Hesta                      | W   | 0.680      | 0.143        | 0.002 (0.000)    | 0.656 (0.064)    | 0 (0.000) |    14.36 | hAdji, Kvem, Sapec, Topa, Woro2k  |
|            1 |     1782 | 2024-12-13 | WW Team                    | W   | 0.680      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     7.93 | hAdji, Kvem, Sapec, Topa, Woro2k  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
