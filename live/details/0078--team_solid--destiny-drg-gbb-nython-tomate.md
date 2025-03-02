### Roster Details<br />
Team Name: Team Solid<br />
Roster: destiny, drg, gbb, nython, tomate<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  885.7<br />
<br />
Final Rank Value (885.7) = Starting Rank Value (824.0) + Head To Head Adjustments (61.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.212<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 824.0
- 400 + ( ( 0.212 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 824.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |      179 | 2025-02-21 | Fluxo              | L   | 1.000      | -            | -                | -                | -         |   -11.36 | destiny, drg, gbb, nython, tomate |
|           56 |      258 | 2025-02-19 | RED Canids         | W   | 1.000      | 0.371        | 0.020 (0.007)    | 0.193 (0.072)    | 0 (0.000) |    13.93 | destiny, drg, gbb, nython, tomate |
|           55 |      453 | 2025-02-14 | Dusty Roots        | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.371 (0.138)    | 0 (0.000) |    11.03 | destiny, drg, gbb, nython, tomate |
|           54 |      524 | 2025-02-12 | Game Hunters       | W   | 1.000      | 0.371        | -                | 0.396 (0.147)    | 0 (0.000) |     8.33 | destiny, drg, gbb, nython, tomate |
|           53 |      787 | 2025-02-07 | Legacy             | L   | 1.000      | -            | -                | -                | -         |   -13.58 | destiny, drg, gbb, nython, tomate |
|           52 |      829 | 2025-02-06 | Dusty Roots        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.71 | destiny, drg, gbb, nython, tomate |
|           51 |      874 | 2025-02-05 | Legacy             | L   | 1.000      | -            | -                | -                | -         |   -14.33 | destiny, drg, gbb, nython, tomate |
|           50 |      896 | 2025-02-05 | Dusty Roots        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.44 | destiny, drg, gbb, nython, tomate |
|           49 |     1192 | 2025-01-11 | BESTIA             | L   | 0.874      | -            | -                | -                | -         |   -10.69 | destiny, drg, gbb, nython, tomate |
|           48 |     1200 | 2025-01-10 | Familia Maquininha | W   | 0.866      | 0.384        | -                | 0.205 (0.068)    | 0 (0.000) |     7.05 | destiny, drg, gbb, nython, tomate |
|           47 |     1206 | 2025-01-09 | UNO MILLE          | W   | 0.860      | 0.384        | 0.010 (0.003)    | 0.526 (0.174)    | 0 (0.000) |     9.92 | destiny, drg, gbb, nython, tomate |
|           46 |     1525 | 2024-12-19 | LaChampionsLiga    | W   | 0.721      | 0.384        | -                | 0.444 (0.123)    | 0 (0.000) |     5.59 | destiny, drg, gbb, nython, tomate |
|           45 |     1548 | 2024-12-18 | 9z Academy         | W   | 0.715      | 0.384        | -                | 0.388 (0.107)    | 0 (0.000) |     5.98 | destiny, drg, gbb, nython, tomate |
|           44 |     1587 | 2024-12-16 | Fake do Biru       | L   | 0.699      | -            | -                | -                | -         |   -18.40 | destiny, drg, gbb, nython, tomate |
|           43 |     1755 | 2024-12-13 | Patins da Ferrari  | W   | 0.681      | -            | -                | -                | -         |     2.75 | destiny, drg, gbb, nython, tomate |
|           42 |     2514 | 2024-11-30 | Fluxo              | L   | 0.593      | -            | -                | -                | -         |    -6.41 | ALLE, destiny, drg, gbb, Misfit   |
|           41 |     2583 | 2024-11-29 | Dusty Roots        | W   | 0.587      | 0.371        | -                | 0.371 (0.081)    | -         |     6.50 | ALLE, destiny, drg, gbb, Misfit   |
|           40 |     2654 | 2024-11-27 | MIBR Academy       | W   | 0.574      | 0.371        | -                | 0.470 (0.100)    | -         |     5.27 | ALLE, destiny, drg, gbb, Misfit   |
|           39 |     2773 | 2024-11-24 | Fluxo              | L   | 0.554      | -            | -                | -                | -         |    -6.17 | ALLE, destiny, drg, gbb, Misfit   |
|           38 |     2940 | 2024-11-22 | ODDIK              | W   | 0.541      | 0.143        | 0.028 (0.002)    | -                | 1 (0.541) |     8.11 | ALLE, destiny, drg, gbb, Misfit   |
|           37 |     3716 | 2024-11-09 | Sharks Esports     | L   | 0.453      | -            | -                | -                | -         |    -4.28 | ALLE, destiny, drg, gbb, Misfit   |
|           36 |     3799 | 2024-11-08 | Hype Esports       | W   | 0.446      | -            | -                | -                | -         |     3.77 | ALLE, destiny, drg, gbb, Misfit   |
|           35 |     3864 | 2024-11-06 | Patins da Ferrari  | W   | 0.434      | -            | -                | -                | -         |     1.90 | ALLE, destiny, drg, gbb, Misfit   |
|           34 |     3911 | 2024-11-05 | América eSports    | W   | 0.428      | -            | -                | -                | -         |     2.51 | ALLE, destiny, drg, gbb, Misfit   |
|           33 |     3963 | 2024-11-04 | AdalYamigos        | W   | 0.422      | -            | -                | -                | -         |     4.52 | ALLE, destiny, drg, gbb, Misfit   |
|           32 |     4025 | 2024-11-03 | Sharks Esports     | W   | 0.415      | 0.143        | 0.054 (0.003)    | -                | -         |     9.56 | ALLE, destiny, drg, gbb, Misfit   |
|           31 |     4099 | 2024-11-02 | UNO MILLE          | W   | 0.408      | -            | -                | -                | -         |     4.74 | ALLE, destiny, drg, gbb, Misfit   |
|           30 |     4168 | 2024-11-01 | Intense Game       | W   | 0.401      | -            | -                | -                | -         |     3.94 | ALLE, destiny, drg, gbb, Misfit   |
|           29 |     4230 | 2024-10-31 | ODDIK              | L   | 0.394      | -            | -                | -                | -         |    -6.48 | ALLE, destiny, drg, gbb, Misfit   |
|           28 |     4309 | 2024-10-30 | Galorys Academy    | W   | 0.386      | -            | -                | -                | -         |     2.98 | ALLE, destiny, drg, gbb, Misfit   |
|           27 |     4388 | 2024-10-28 | Fluxo              | W   | 0.375      | 0.143        | 0.056 (0.003)    | -                | -         |     7.58 | ALLE, destiny, drg, gbb, Misfit   |
|           26 |     4940 | 2024-10-17 | BC.Game Esports    | L   | 0.299      | -            | -                | -                | -         |    -2.33 | ALLE, destiny, drg, gbb, Misfit   |
|           25 |     5003 | 2024-10-16 | PARIVISION         | L   | 0.292      | -            | -                | -                | -         |    -5.98 | ALLE, destiny, drg, gbb, Misfit   |
|           24 |     5317 | 2024-10-09 | Imperial Esports   | L   | 0.248      | -            | -                | -                | -         |    -2.29 | ALLE, destiny, drg, gbb, Misfit   |
|           23 |     5325 | 2024-10-09 | Imperial Esports   | L   | 0.247      | -            | -                | -                | -         |    -2.33 | ALLE, destiny, drg, gbb, Misfit   |
|           22 |     5390 | 2024-10-08 | Hype Esports       | L   | 0.241      | -            | -                | -                | -         |    -5.54 | ALLE, destiny, drg, gbb, Misfit   |
|           21 |     5401 | 2024-10-08 | Hype Esports       | W   | 0.241      | -            | -                | -                | -         |     2.07 | ALLE, destiny, drg, gbb, Misfit   |
|           20 |     5405 | 2024-10-08 | RED Canids         | W   | 0.240      | 0.450        | 0.020 (0.002)    | -                | -         |     3.90 | ALLE, destiny, drg, gbb, Misfit   |
|           19 |     5413 | 2024-10-08 | RED Canids         | W   | 0.240      | -            | -                | -                | -         |     3.97 | ALLE, destiny, drg, gbb, Misfit   |
|           18 |     5749 | 2024-10-02 | Sharks Esports     | L   | 0.201      | -            | -                | -                | -         |    -1.71 | ALLE, destiny, drg, gbb, Misfit   |
|           17 |     5755 | 2024-10-02 | Sharks Esports     | W   | 0.201      | 0.450        | 0.054 (0.005)    | 0.629 (0.057)    | -         |     4.68 | ALLE, destiny, drg, gbb, Misfit   |
|           16 |     5833 | 2024-10-01 | BESTIA             | L   | 0.194      | -            | -                | -                | -         |    -2.36 | ALLE, destiny, drg, gbb, Misfit   |
|           15 |     5834 | 2024-10-01 | BESTIA             | L   | 0.194      | -            | -                | -                | -         |    -2.40 | ALLE, destiny, drg, gbb, Misfit   |
|           14 |     5946 | 2024-09-29 | PaiN Gaming        | L   | 0.180      | -            | -                | -                | -         |    -0.06 | ALLE, destiny, drg, gbb, Misfit   |
|           13 |     5995 | 2024-09-28 | Fluxo              | L   | 0.175      | -            | -                | -                | -         |    -2.09 | ALLE, destiny, drg, gbb, Misfit   |
|           12 |     6004 | 2024-09-28 | PaiN Gaming        | W   | 0.173      | 0.143        | 0.318 (0.008)    | -                | -         |     5.41 | ALLE, destiny, drg, gbb, Misfit   |
|           11 |     6086 | 2024-09-27 | Case Esports       | W   | 0.168      | -            | -                | -                | -         |     1.62 | ALLE, destiny, drg, gbb, Misfit   |
|           10 |     6097 | 2024-09-27 | ODDIK              | W   | 0.168      | -            | -                | -                | -         |     2.53 | ALLE, destiny, drg, gbb, Misfit   |
|            9 |     6176 | 2024-09-26 | ShindeN            | W   | 0.161      | -            | -                | -                | -         |     1.80 | ALLE, destiny, drg, gbb, Misfit   |
|            8 |     6253 | 2024-09-25 | MIBR               | L   | 0.154      | -            | -                | -                | -         |    -0.15 | ALLE, destiny, drg, gbb, Misfit   |
|            7 |     6259 | 2024-09-25 | MIBR               | W   | 0.154      | 0.450        | 0.141 (0.010)    | -                | -         |     4.71 | ALLE, destiny, drg, gbb, Misfit   |
|            6 |     6344 | 2024-09-24 | Dusty Roots        | L   | 0.148      | -            | -                | -                | -         |    -2.59 | ALLE, destiny, drg, gbb, Misfit   |
|            5 |     6350 | 2024-09-24 | Dusty Roots        | W   | 0.147      | -            | -                | -                | -         |     2.08 | ALLE, destiny, drg, gbb, Misfit   |
|            4 |     6966 | 2024-09-14 | Bad News Chickens  | W   | 0.081      | -            | -                | -                | -         |     0.78 | ALLE, destiny, drg, gbb, Misfit   |
|            3 |     6983 | 2024-09-14 | Sharks Esports     | W   | 0.080      | -            | -                | -                | -         |     1.89 | ALLE, destiny, drg, gbb, Misfit   |
|            2 |     6989 | 2024-09-14 | MIBR Academy       | W   | 0.079      | -            | -                | -                | -         |     0.76 | ALLE, destiny, drg, gbb, Misfit   |
|            1 |     7721 | 2024-09-03 | ODDIK              | L   | 0.006      | -            | -                | -                | -         |    -0.10 | ALLE, destiny, drg, gbb, Lcm      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,710.90)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $750.00        | $750.00         |
| 2025-01-12 |      0.881 | $2,500.00      | $2,202.08       |
| 2024-11-30 |      0.595 | $1,500.00      | $891.98         |
| 2024-11-24 |      0.554 | $5,171.49      | $2,863.59       |
| 2024-11-09 |      0.455 | $1,500.00      | $682.26         |
| 2024-10-20 |      0.320 | $900.00        | $288.13         |
| 2024-09-14 |      0.081 | $269.53        | $21.77          |
| 2024-09-04 |      0.015 | $750.00        | $11.09          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
