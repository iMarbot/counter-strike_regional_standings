### Roster Details<br />
Team Name: Bad News Chickens<br />
Roster: Alisson, desh, Leomonster, short, Skr<br />
Global Rank: [209](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [39]( ../standings_americas.md)<br />
<br />
Final Rank Value:  707.1<br />
<br />
Final Rank Value (707.1) = Starting Rank Value (678.8) + Head To Head Adjustments (28.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.8
- 400 + ( ( 0.139 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 678.8


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
|           31 |     1562 | 2024-12-18 | LaChampionsLiga           | W   | 0.705      | 0.384        | 0.003 (0.001)    | 0.440 (0.119)    | 0 (0.000) |    10.09 | Alisson, desh, Leomonster, short, Skr  |
|           30 |     1591 | 2024-12-16 | UNO MILLE                 | W   | 0.692      | 0.384        | 0.010 (0.003)    | 0.522 (0.139)    | 0 (0.000) |    13.32 | Alisson, desh, Leomonster, short, Skr  |
|           29 |     1806 | 2024-12-13 | Game Hunters              | W   | 0.671      | 0.384        | 0.003 (0.001)    | 0.392 (0.101)    | 0 (0.000) |    12.19 | Alisson, desh, Leomonster, short, Skr  |
|           28 |     2685 | 2024-11-27 | TROPA DO TACO             | L   | 0.564      | -            | -                | -                | -         |    -6.58 | Alisson, desh, Leomonster, short, Skr  |
|           27 |     3234 | 2024-11-17 | TROPA DO TACO             | L   | 0.500      | -            | -                | -                | -         |    -6.48 | Alisson, desh, Leomonster, short, Skr  |
|           26 |     3546 | 2024-11-12 | Nitro.GG                  | W   | 0.465      | 0.143        | 0.002 (0.000)    | 0.512 (0.034)    | 0 (0.000) |     7.24 | Alisson, desh, Leomonster, short, Skr  |
|           25 |     3605 | 2024-11-11 | Patins da Ferrari         | W   | 0.459      | 0.143        | -                | 0.124 (0.008)    | 0 (0.000) |     4.44 | Alisson, desh, Leomonster, short, Skr  |
|           24 |     3652 | 2024-11-10 | Game Hunters              | L   | 0.452      | -            | -                | -                | -         |    -6.38 | Alisson, desh, Leomonster, short, Skr  |
|           23 |     3712 | 2024-11-09 | MIBR Academy              | W   | 0.445      | 0.242        | 0.001 (0.000)    | 0.464 (0.050)    | 0 (0.000) |     7.40 | Alisson, desh, Leomonster, short, Skr  |
|           22 |     3790 | 2024-11-08 | SamuraiS (Brazilian team) | W   | 0.439      | 0.242        | -                | 0.154 (0.016)    | 0 (0.000) |     4.06 | Alisson, desh, Leomonster, short, Skr  |
|           21 |     3894 | 2024-11-06 | Game Hunters              | L   | 0.425      | -            | -                | -                | -         |    -6.17 | Alisson, desh, Leomonster, short, Skr  |
|           20 |     4252 | 2024-10-31 | Nitro.GG                  | L   | 0.385      | -            | -                | -                | -         |    -5.98 | Alisson, desh, Leomonster, short, Skr  |
|           19 |     4370 | 2024-10-29 | BeBold.gg                 | W   | 0.372      | -            | -                | -                | 0 (0.000) |     4.10 | Alisson, desh, Leomonster, short, Skr  |
|           18 |     4432 | 2024-10-28 | AMIGOS (Brazilian team)   | L   | 0.365      | -            | -                | -                | -         |    -8.67 | Alisson, desh, Leomonster, rainny, Skr |
|           17 |     4697 | 2024-10-22 | Pugdesonesto              | L   | 0.326      | -            | -                | -                | -         |    -5.83 | Alisson, desh, Leomonster, rainny, Skr |
|           16 |     5517 | 2024-10-06 | MIBR Academy              | W   | 0.219      | 0.143        | 0.001 (0.000)    | 0.464 (0.015)    | 0 (0.000) |     3.40 | Alisson, desh, Leomonster, short, Skr  |
|           15 |     5580 | 2024-10-05 | Galorys Academy           | W   | 0.212      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     2.99 | Alisson, desh, Leomonster, short, Skr  |
|           14 |     5726 | 2024-10-03 | Romanos                   | W   | 0.198      | -            | -                | -                | -         |     1.54 | Alisson, desh, Leomonster, short, Skr  |
|           13 |     6049 | 2024-09-28 | Myth e-Sports             | L   | 0.164      | -            | -                | -                | -         |    -3.27 | Alisson, desh, Leomonster, short, Skr  |
|           12 |     6108 | 2024-09-27 | Case Esports              | L   | 0.159      | -            | -                | -                | -         |    -2.52 | Alisson, desh, Leomonster, short, Skr  |
|           11 |     6111 | 2024-09-27 | Game Hunters              | W   | 0.159      | 0.143        | 0.003 (0.000)    | 0.392 (0.009)    | -         |     2.56 | Alisson, desh, Leomonster, short, Skr  |
|           10 |     6370 | 2024-09-24 | Floripa Stars             | W   | 0.139      | -            | -                | -                | -         |     2.01 | Alisson, desh, Leomonster, short, Skr  |
|            9 |     6516 | 2024-09-22 | Floripa Stars             | W   | 0.125      | 0.262        | 0.001 (0.000)    | 0.296 (0.010)    | -         |     1.83 | Alisson, desh, Leomonster, short, Skr  |
|            8 |     6809 | 2024-09-17 | Patins da Ferrari         | W   | 0.093      | -            | -                | -                | -         |     0.82 | Alisson, desh, Leomonster, short, Skr  |
|            7 |     6811 | 2024-09-17 | AMIGOS (Brazilian team)   | W   | 0.093      | -            | -                | -                | -         |     0.74 | Alisson, desh, Leomonster, short, Skr  |
|            6 |     6978 | 2024-09-14 | Team Solid                | L   | 0.073      | -            | -                | -                | -         |    -0.70 | Alisson, desh, Leomonster, short, Skr  |
|            5 |     7004 | 2024-09-14 | Myth e-Sports             | W   | 0.071      | -            | -                | -                | -         |     0.84 | Alisson, desh, Leomonster, short, Skr  |
|            4 |     7343 | 2024-09-08 | Yawara E-Sports           | W   | 0.032      | 0.262        | 0.002 (0.000)    | -                | -         |     0.51 | Alisson, desh, Leomonster, short, Skr  |
|            3 |     7430 | 2024-09-07 | MIBR Academy              | W   | 0.024      | -            | -                | -                | -         |     0.38 | Alisson, desh, Leomonster, short, Skr  |
|            2 |     7505 | 2024-09-06 | Yawara E-Sports           | W   | 0.018      | -            | -                | -                | -         |     0.30 | Alisson, desh, Leomonster, short, Skr  |
|            1 |     7649 | 2024-09-04 | Floripa Stars             | W   | 0.006      | -            | -                | -                | -         |     0.09 | Alisson, desh, Leomonster, short, Skr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($818.12)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.500 | $517.51        | $258.54         |
| 2024-11-10 |      0.452 | $175.00        | $79.16          |
| 2024-10-06 |      0.219 | $1,465.96      | $320.68         |
| 2024-09-22 |      0.125 | $1,000.00      | $125.00         |
| 2024-09-07 |      0.024 | $1,429.06      | $34.73          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
