### Roster Details<br />
Team Name: GENESIS (Estonian team)<br />
Roster: Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz<br />
Global Rank: [530](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [329]( ../standings_europe.md)<br />
<br />
Final Rank Value:  488.5<br />
<br />
Final Rank Value (488.5) = Starting Rank Value (486.1) + Head To Head Adjustments (2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.170[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 486.1
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 486.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1262 | 2024-12-29 | KUUSAMO.gg                | L   | 0.778      | -            | -                | -                | -         |   -11.23 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            9 |     1300 | 2024-12-28 | EC BANGA                  | L   | 0.772      | -            | -                | -                | -         |   -12.16 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            8 |     2028 | 2024-12-08 | Truck Drivers             | L   | 0.636      | -            | -                | -                | -         |    -5.78 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            7 |     3236 | 2024-11-17 | ANimaleGG                 | W   | 0.499      | 0.143        | 0.000 (0.000)    | 0.055 (0.004)    | 0 (0.000) |     7.26 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            6 |     3662 | 2024-11-10 | Truck Drivers             | W   | 0.452      | 0.143        | 0.002 (0.000)    | 0.120 (0.008)    | 0 (0.000) |    10.40 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            5 |     4047 | 2024-11-03 | Godne                     | W   | 0.405      | 0.143        | 0.000 (0.000)    | 0.045 (0.003)    | 0 (0.000) |     4.51 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            4 |     4473 | 2024-10-27 | M1Z                       | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.111 (0.006)    | 0 (0.000) |     4.33 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            3 |     4801 | 2024-10-20 | W2TE                      | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     3.76 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            2 |     5147 | 2024-10-13 | FullShock (Estonian team) | W   | 0.264      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.16 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |
|            1 |     5523 | 2024-10-06 | SHOO7ERS                  | L   | 0.218      | -            | -                | -                | -         |    -1.92 | Cuba, Kirikuõpetaja, M4rdik, Nunnn, rikzz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
