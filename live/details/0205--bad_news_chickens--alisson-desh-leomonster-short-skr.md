### Roster Details<br />
Team Name: Bad News Chickens<br />
Roster: Alisson, desh, Leomonster, short, Skr<br />
Global Rank: [205](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  708.8<br />
<br />
Final Rank Value (708.8) = Starting Rank Value (679.6) + Head To Head Adjustments (29.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.6
- 400 + ( ( 0.140 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 679.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     1550 | 2024-12-18 | LaChampionsLiga           | W   | 0.713      | 0.384        | 0.003 (0.001)    | 0.444 (0.122)    | 0 (0.000) |    10.21 | Alisson, desh, Leomonster, short, Skr  |
|           30 |     1579 | 2024-12-16 | UNO MILLE                 | W   | 0.701      | 0.384        | 0.010 (0.003)    | 0.526 (0.142)    | 0 (0.000) |    13.47 | Alisson, desh, Leomonster, short, Skr  |
|           29 |     1794 | 2024-12-13 | Game Hunters              | W   | 0.679      | 0.384        | 0.002 (0.001)    | 0.396 (0.103)    | 0 (0.000) |    12.33 | Alisson, desh, Leomonster, short, Skr  |
|           28 |     2673 | 2024-11-27 | TROPA DO TACO             | L   | 0.572      | -            | -                | -                | -         |    -6.66 | Alisson, desh, Leomonster, short, Skr  |
|           27 |     3222 | 2024-11-17 | TROPA DO TACO             | L   | 0.508      | -            | -                | -                | -         |    -6.59 | Alisson, desh, Leomonster, short, Skr  |
|           26 |     3534 | 2024-11-12 | Nitro.GG                  | W   | 0.474      | 0.143        | 0.002 (0.000)    | 0.518 (0.035)    | 0 (0.000) |     7.35 | Alisson, desh, Leomonster, short, Skr  |
|           25 |     3593 | 2024-11-11 | Patins da Ferrari         | W   | 0.467      | 0.143        | -                | 0.127 (0.008)    | 0 (0.000) |     4.54 | Alisson, desh, Leomonster, short, Skr  |
|           24 |     3640 | 2024-11-10 | Game Hunters              | L   | 0.461      | -            | -                | -                | -         |    -6.51 | Alisson, desh, Leomonster, short, Skr  |
|           23 |     3700 | 2024-11-09 | MIBR Academy              | W   | 0.454      | 0.242        | 0.001 (0.000)    | 0.470 (0.052)    | 0 (0.000) |     7.54 | Alisson, desh, Leomonster, short, Skr  |
|           22 |     3778 | 2024-11-08 | SamuraiS (Brazilian team) | W   | 0.447      | 0.242        | -                | 0.157 (0.017)    | 0 (0.000) |     4.12 | Alisson, desh, Leomonster, short, Skr  |
|           21 |     3882 | 2024-11-06 | Game Hunters              | L   | 0.433      | -            | -                | -                | -         |    -6.30 | Alisson, desh, Leomonster, short, Skr  |
|           20 |     4240 | 2024-10-31 | Nitro.GG                  | L   | 0.394      | -            | -                | -                | -         |    -6.11 | Alisson, desh, Leomonster, short, Skr  |
|           19 |     4358 | 2024-10-29 | BeBold.gg                 | W   | 0.380      | -            | -                | -                | 0 (0.000) |     4.16 | Alisson, desh, Leomonster, short, Skr  |
|           18 |     4420 | 2024-10-28 | AMIGOS (Brazilian team)   | L   | 0.374      | -            | -                | -                | -         |    -8.87 | Alisson, desh, Leomonster, rainny, Skr |
|           17 |     4685 | 2024-10-22 | Pugdesonesto              | L   | 0.334      | -            | -                | -                | -         |    -6.00 | Alisson, desh, Leomonster, rainny, Skr |
|           16 |     5505 | 2024-10-06 | MIBR Academy              | W   | 0.227      | 0.143        | 0.001 (0.000)    | 0.470 (0.015)    | 0 (0.000) |     3.53 | Alisson, desh, Leomonster, short, Skr  |
|           15 |     5568 | 2024-10-05 | Galorys Academy           | W   | 0.220      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     3.10 | Alisson, desh, Leomonster, short, Skr  |
|           14 |     5714 | 2024-10-03 | Romanos                   | W   | 0.207      | -            | -                | -                | -         |     1.59 | Alisson, desh, Leomonster, short, Skr  |
|           13 |     6037 | 2024-09-28 | Myth e-Sports             | L   | 0.173      | -            | -                | -                | -         |    -3.44 | Alisson, desh, Leomonster, short, Skr  |
|           12 |     6096 | 2024-09-27 | Case Esports              | L   | 0.168      | -            | -                | -                | -         |    -2.65 | Alisson, desh, Leomonster, short, Skr  |
|           11 |     6099 | 2024-09-27 | Game Hunters              | W   | 0.167      | 0.143        | 0.002 (0.000)    | 0.396 (0.009)    | -         |     2.69 | Alisson, desh, Leomonster, short, Skr  |
|           10 |     6358 | 2024-09-24 | Floripa Stars             | W   | 0.147      | -            | -                | -                | -         |     2.13 | Alisson, desh, Leomonster, short, Skr  |
|            9 |     6504 | 2024-09-22 | Floripa Stars             | W   | 0.133      | 0.262        | 0.001 (0.000)    | 0.302 (0.011)    | -         |     1.95 | Alisson, desh, Leomonster, short, Skr  |
|            8 |     6797 | 2024-09-17 | Patins da Ferrari         | W   | 0.101      | -            | -                | -                | -         |     0.89 | Alisson, desh, Leomonster, short, Skr  |
|            7 |     6799 | 2024-09-17 | AMIGOS (Brazilian team)   | W   | 0.101      | -            | -                | -                | -         |     0.80 | Alisson, desh, Leomonster, short, Skr  |
|            6 |     6966 | 2024-09-14 | Team Solid                | L   | 0.081      | -            | -                | -                | -         |    -0.78 | Alisson, desh, Leomonster, short, Skr  |
|            5 |     6992 | 2024-09-14 | Myth e-Sports             | W   | 0.079      | -            | -                | -                | -         |     0.94 | Alisson, desh, Leomonster, short, Skr  |
|            4 |     7331 | 2024-09-08 | Yawara E-Sports           | W   | 0.040      | 0.262        | 0.002 (0.000)    | -                | -         |     0.64 | Alisson, desh, Leomonster, short, Skr  |
|            3 |     7418 | 2024-09-07 | MIBR Academy              | W   | 0.033      | -            | -                | -                | -         |     0.51 | Alisson, desh, Leomonster, short, Skr  |
|            2 |     7493 | 2024-09-06 | Yawara E-Sports           | W   | 0.027      | -            | -                | -                | -         |     0.43 | Alisson, desh, Leomonster, short, Skr  |
|            1 |     7637 | 2024-09-04 | Floripa Stars             | W   | 0.014      | -            | -                | -                | -         |     0.21 | Alisson, desh, Leomonster, short, Skr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($855.71)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.508 | $517.51        | $262.78         |
| 2024-11-10 |      0.461 | $175.00        | $80.60          |
| 2024-10-06 |      0.227 | $1,465.96      | $332.69         |
| 2024-09-22 |      0.133 | $1,000.00      | $133.19         |
| 2024-09-07 |      0.033 | $1,429.06      | $46.44          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
