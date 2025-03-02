### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: eraa, Fessor, sausol, szejn, Tapewaare<br />
Global Rank: [448](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [281]( ../standings_europe.md)<br />
<br />
Final Rank Value:  560.4<br />
<br />
Final Rank Value (560.4) = Starting Rank Value (531.5) + Head To Head Adjustments (29.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 531.5
- 400 + ( ( 0.066 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 531.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     5848 | 2024-10-01 | ALTERNATE aTTaX  | L   | 0.193      | -            | -                | -                | -         |    -0.72 | eraa, Fessor, sausol, szejn, Tapewaare |
|           22 |     5956 | 2024-09-29 | G2 Ares          | L   | 0.179      | -            | -                | -                | -         |    -1.87 | eraa, Fessor, sausol, szejn, Tapewaare |
|           21 |     5966 | 2024-09-29 | Wild Lotus       | W   | 0.178      | 0.435        | 0.001 (0.000)    | 0.444 (0.034)    | 0 (0.000) |     4.24 | eraa, Fessor, sausol, szejn, Tapewaare |
|           20 |     6083 | 2024-09-28 | K27              | W   | 0.170      | 0.143        | 0.008 (0.000)    | 0.776 (0.019)    | 0 (0.000) |     4.76 | eraa, Fessor, sausol, szejn, Tapewaare |
|           19 |     6131 | 2024-09-27 | Passion UA       | L   | 0.166      | -            | -                | -                | -         |    -0.34 | eraa, Fessor, sausol, szejn, Tapewaare |
|           18 |     6188 | 2024-09-26 | GamerLegion      | L   | 0.160      | -            | -                | -                | -         |    -1.52 | eraa, Fessor, sausol, szejn, Tapewaare |
|           17 |     6304 | 2024-09-25 | Endpoint         | W   | 0.151      | 0.435        | 0.009 (0.001)    | 0.385 (0.025)    | 0 (0.000) |     3.71 | eraa, Fessor, sausol, szejn, Tapewaare |
|           16 |     6329 | 2024-09-25 | RUSTEC           | W   | 0.150      | -            | -                | -                | 0 (0.000) |     2.43 | eraa, Fessor, sausol, szejn, Tapewaare |
|           15 |     6411 | 2024-09-24 | K27              | L   | 0.144      | -            | -                | -                | -         |    -0.49 | eraa, Fessor, sausol, szejn, Tapewaare |
|           14 |     6459 | 2024-09-23 | ECSTATIC         | L   | 0.140      | -            | -                | -                | -         |    -0.59 | eraa, Fessor, sausol, szejn, Tapewaare |
|           13 |     6517 | 2024-09-22 | Team Space       | W   | 0.132      | -            | -                | -                | 0 (0.000) |     1.81 | eraa, Fessor, sausol, szejn, Tapewaare |
|           12 |     6529 | 2024-09-22 | Zero Tenacity    | W   | 0.131      | 0.435        | 0.028 (0.002)    | 0.692 (0.039)    | 0 (0.000) |     3.55 | eraa, Fessor, sausol, szejn, Tapewaare |
|           11 |     6569 | 2024-09-21 | FLuffy Gangsters | W   | 0.126      | 0.143        | 0.014 (0.000)    | 0.925 (0.017)    | 0 (0.000) |     3.21 | eraa, Fessor, sausol, szejn, Tapewaare |
|           10 |     6623 | 2024-09-20 | RUBY             | L   | 0.120      | -            | -                | -                | -         |    -1.15 | eraa, Fessor, sausol, szejn, Tapewaare |
|            9 |     6690 | 2024-09-19 | 9Pandas          | W   | 0.113      | 0.435        | 0.085 (0.004)    | 0.485 (0.024)    | 0 (0.000) |     3.28 | eraa, Fessor, sausol, szejn, Tapewaare |
|            8 |     6699 | 2024-09-19 | ALASKA           | W   | 0.112      | 0.143        | 0.030 (0.000)    | 0.875 (0.014)    | 0 (0.000) |     3.43 | eraa, Fessor, sausol, szejn, Tapewaare |
|            7 |     7046 | 2024-09-14 | FLuffy Gangsters | W   | 0.077      | 0.143        | 0.014 (0.000)    | 0.925 (0.010)    | 0 (0.000) |     1.97 | eraa, Fessor, sausol, szejn, Tapewaare |
|            6 |     7136 | 2024-09-12 | AMKAL ESPORTS    | W   | 0.065      | 0.143        | -                | 0.681 (0.006)    | -         |     1.61 | eraa, Fessor, sausol, szejn, Tapewaare |
|            5 |     7149 | 2024-09-12 | Astralis Talent  | L   | 0.064      | -            | -                | -                | -         |    -0.41 | eraa, Fessor, sausol, szejn, Tapewaare |
|            4 |     7213 | 2024-09-11 | ENCE Academy     | W   | 0.057      | 0.143        | 0.009 (0.000)    | -                | -         |     1.50 | eraa, Fessor, sausol, szejn, Tapewaare |
|            3 |     7265 | 2024-09-10 | GameAgents       | L   | 0.050      | -            | -                | -                | -         |    -0.48 | eraa, Fessor, sausol, szejn, Tapewaare |
|            2 |     7473 | 2024-09-07 | Los kogutos      | W   | 0.031      | 0.333        | 0.032 (0.000)    | 0.527 (0.005)    | -         |     0.91 | eraa, Fessor, sausol, szejn, Tapewaare |
|            1 |     7752 | 2024-09-03 | Heimo Esports    | W   | 0.004      | -            | -                | -                | -         |     0.10 | eraa, Fessor, sausol, szejn, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
