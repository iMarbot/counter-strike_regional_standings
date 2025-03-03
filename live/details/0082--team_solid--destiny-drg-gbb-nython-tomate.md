### Roster Details<br />
Team Name: Team Solid<br />
Roster: destiny, drg, gbb, nython, tomate<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  883.9<br />
<br />
Final Rank Value (883.9) = Starting Rank Value (822.8) + Head To Head Adjustments (61.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 822.8
- 400 + ( ( 0.211 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 822.8


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
|           56 |      191 | 2025-02-21 | Fluxo              | L   | 1.000      | -            | -                | -                | -         |   -11.38 | destiny, drg, gbb, nython, tomate |
|           55 |      270 | 2025-02-19 | RED Canids         | W   | 1.000      | 0.371        | 0.020 (0.007)    | 0.191 (0.071)    | 0 (0.000) |    13.86 | destiny, drg, gbb, nython, tomate |
|           54 |      465 | 2025-02-14 | Dusty Roots        | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.366 (0.136)    | 0 (0.000) |    11.09 | destiny, drg, gbb, nython, tomate |
|           53 |      536 | 2025-02-12 | Game Hunters       | W   | 1.000      | 0.371        | -                | 0.392 (0.145)    | 0 (0.000) |     8.37 | destiny, drg, gbb, nython, tomate |
|           52 |      799 | 2025-02-07 | Legacy             | L   | 1.000      | -            | -                | -                | -         |   -13.49 | destiny, drg, gbb, nython, tomate |
|           51 |      841 | 2025-02-06 | Dusty Roots        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.77 | destiny, drg, gbb, nython, tomate |
|           50 |      886 | 2025-02-05 | Legacy             | L   | 1.000      | -            | -                | -                | -         |   -14.23 | destiny, drg, gbb, nython, tomate |
|           49 |      908 | 2025-02-05 | Dusty Roots        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.52 | destiny, drg, gbb, nython, tomate |
|           48 |     1204 | 2025-01-11 | BESTIA             | L   | 0.865      | -            | -                | -                | -         |   -10.45 | destiny, drg, gbb, nython, tomate |
|           47 |     1212 | 2025-01-10 | Familia Maquininha | W   | 0.857      | 0.384        | -                | 0.202 (0.066)    | 0 (0.000) |     6.83 | destiny, drg, gbb, nython, tomate |
|           46 |     1218 | 2025-01-09 | UNO MILLE          | W   | 0.852      | 0.384        | 0.010 (0.003)    | 0.522 (0.171)    | 0 (0.000) |     9.85 | destiny, drg, gbb, nython, tomate |
|           45 |     1537 | 2024-12-19 | LaChampionsLiga    | W   | 0.712      | 0.384        | -                | 0.440 (0.120)    | 0 (0.000) |     5.54 | destiny, drg, gbb, nython, tomate |
|           44 |     1560 | 2024-12-18 | 9z Academy         | W   | 0.707      | 0.384        | -                | 0.384 (0.104)    | 0 (0.000) |     5.91 | destiny, drg, gbb, nython, tomate |
|           43 |     1599 | 2024-12-16 | Fake do Biru       | L   | 0.691      | -            | -                | -                | -         |   -18.17 | destiny, drg, gbb, nython, tomate |
|           42 |     1767 | 2024-12-13 | Patins da Ferrari  | W   | 0.673      | -            | -                | -                | -         |     2.75 | destiny, drg, gbb, nython, tomate |
|           41 |     2526 | 2024-11-30 | Fluxo              | L   | 0.585      | -            | -                | -                | -         |    -6.33 | ALLE, destiny, drg, gbb, Misfit   |
|           40 |     2595 | 2024-11-29 | Dusty Roots        | W   | 0.578      | 0.371        | -                | 0.366 (0.078)    | -         |     6.46 | ALLE, destiny, drg, gbb, Misfit   |
|           39 |     2666 | 2024-11-27 | MIBR Academy       | W   | 0.566      | 0.371        | -                | 0.464 (0.097)    | -         |     5.18 | ALLE, destiny, drg, gbb, Misfit   |
|           38 |     2785 | 2024-11-24 | Fluxo              | L   | 0.546      | -            | -                | -                | -         |    -6.09 | ALLE, destiny, drg, gbb, Misfit   |
|           37 |     2952 | 2024-11-22 | ODDIK              | W   | 0.533      | 0.143        | 0.028 (0.002)    | -                | 1 (0.533) |     8.01 | ALLE, destiny, drg, gbb, Misfit   |
|           36 |     3728 | 2024-11-09 | Sharks Esports     | L   | 0.445      | -            | -                | -                | -         |    -4.14 | ALLE, destiny, drg, gbb, Misfit   |
|           35 |     3811 | 2024-11-08 | Hype Esports       | W   | 0.438      | -            | -                | -                | -         |     3.70 | ALLE, destiny, drg, gbb, Misfit   |
|           34 |     3876 | 2024-11-06 | Patins da Ferrari  | W   | 0.426      | -            | -                | -                | -         |     1.86 | ALLE, destiny, drg, gbb, Misfit   |
|           33 |     3923 | 2024-11-05 | América eSports    | W   | 0.420      | -            | -                | -                | -         |     2.49 | ALLE, destiny, drg, gbb, Misfit   |
|           32 |     3975 | 2024-11-04 | AdalYamigos        | W   | 0.414      | -            | -                | -                | -         |     4.45 | ALLE, destiny, drg, gbb, Misfit   |
|           31 |     4037 | 2024-11-03 | Sharks Esports     | W   | 0.407      | 0.143        | 0.055 (0.003)    | -                | -         |     9.43 | ALLE, destiny, drg, gbb, Misfit   |
|           30 |     4111 | 2024-11-02 | UNO MILLE          | W   | 0.400      | -            | -                | -                | -         |     4.65 | ALLE, destiny, drg, gbb, Misfit   |
|           29 |     4180 | 2024-11-01 | Intense Game       | W   | 0.393      | -            | -                | -                | -         |     3.87 | ALLE, destiny, drg, gbb, Misfit   |
|           28 |     4242 | 2024-10-31 | ODDIK              | L   | 0.386      | -            | -                | -                | -         |    -6.33 | ALLE, destiny, drg, gbb, Misfit   |
|           27 |     4321 | 2024-10-30 | Galorys Academy    | W   | 0.378      | -            | -                | -                | -         |     2.93 | ALLE, destiny, drg, gbb, Misfit   |
|           26 |     4400 | 2024-10-28 | Fluxo              | W   | 0.367      | 0.143        | 0.056 (0.003)    | -                | -         |     7.41 | ALLE, destiny, drg, gbb, Misfit   |
|           25 |     4952 | 2024-10-17 | BC.Game Esports    | L   | 0.290      | -            | -                | -                | -         |    -2.25 | ALLE, destiny, drg, gbb, Misfit   |
|           24 |     5015 | 2024-10-16 | PARIVISION         | L   | 0.284      | -            | -                | -                | -         |    -5.82 | ALLE, destiny, drg, gbb, Misfit   |
|           23 |     5329 | 2024-10-09 | Imperial Esports   | L   | 0.240      | -            | -                | -                | -         |    -2.23 | ALLE, destiny, drg, gbb, Misfit   |
|           22 |     5337 | 2024-10-09 | Imperial Esports   | L   | 0.239      | -            | -                | -                | -         |    -2.27 | ALLE, destiny, drg, gbb, Misfit   |
|           21 |     5402 | 2024-10-08 | Hype Esports       | L   | 0.233      | -            | -                | -                | -         |    -5.34 | ALLE, destiny, drg, gbb, Misfit   |
|           20 |     5413 | 2024-10-08 | Hype Esports       | W   | 0.233      | -            | -                | -                | -         |     2.01 | ALLE, destiny, drg, gbb, Misfit   |
|           19 |     5417 | 2024-10-08 | RED Canids         | W   | 0.232      | 0.450        | 0.020 (0.002)    | -                | -         |     3.74 | ALLE, destiny, drg, gbb, Misfit   |
|           18 |     5425 | 2024-10-08 | RED Canids         | W   | 0.232      | -            | -                | -                | -         |     3.81 | ALLE, destiny, drg, gbb, Misfit   |
|           17 |     5761 | 2024-10-02 | Sharks Esports     | L   | 0.193      | -            | -                | -                | -         |    -1.61 | ALLE, destiny, drg, gbb, Misfit   |
|           16 |     5767 | 2024-10-02 | Sharks Esports     | W   | 0.193      | 0.450        | 0.055 (0.005)    | 0.622 (0.054)    | -         |     4.51 | ALLE, destiny, drg, gbb, Misfit   |
|           15 |     5845 | 2024-10-01 | BESTIA             | L   | 0.186      | -            | -                | -                | -         |    -2.26 | ALLE, destiny, drg, gbb, Misfit   |
|           14 |     5846 | 2024-10-01 | BESTIA             | L   | 0.185      | -            | -                | -                | -         |    -2.29 | ALLE, destiny, drg, gbb, Misfit   |
|           13 |     5958 | 2024-09-29 | PaiN Gaming        | L   | 0.172      | -            | -                | -                | -         |    -0.06 | ALLE, destiny, drg, gbb, Misfit   |
|           12 |     6007 | 2024-09-28 | Fluxo              | L   | 0.166      | -            | -                | -                | -         |    -1.99 | ALLE, destiny, drg, gbb, Misfit   |
|           11 |     6016 | 2024-09-28 | PaiN Gaming        | W   | 0.165      | 0.143        | 0.323 (0.008)    | -                | -         |     5.15 | ALLE, destiny, drg, gbb, Misfit   |
|           10 |     6098 | 2024-09-27 | Case Esports       | W   | 0.160      | -            | -                | -                | -         |     1.54 | ALLE, destiny, drg, gbb, Misfit   |
|            9 |     6109 | 2024-09-27 | ODDIK              | W   | 0.159      | -            | -                | -                | -         |     2.42 | ALLE, destiny, drg, gbb, Misfit   |
|            8 |     6188 | 2024-09-26 | ShindeN            | W   | 0.153      | -            | -                | -                | -         |     1.71 | ALLE, destiny, drg, gbb, Misfit   |
|            7 |     6265 | 2024-09-25 | MIBR               | L   | 0.146      | -            | -                | -                | -         |    -0.14 | ALLE, destiny, drg, gbb, Misfit   |
|            6 |     6271 | 2024-09-25 | MIBR               | W   | 0.146      | 0.450        | 0.142 (0.009)    | -                | -         |     4.46 | ALLE, destiny, drg, gbb, Misfit   |
|            5 |     6356 | 2024-09-24 | Dusty Roots        | L   | 0.140      | -            | -                | -                | -         |    -2.44 | ALLE, destiny, drg, gbb, Misfit   |
|            4 |     6362 | 2024-09-24 | Dusty Roots        | W   | 0.139      | -            | -                | -                | -         |     1.97 | ALLE, destiny, drg, gbb, Misfit   |
|            3 |     6978 | 2024-09-14 | Bad News Chickens  | W   | 0.073      | -            | -                | -                | -         |     0.70 | ALLE, destiny, drg, gbb, Misfit   |
|            2 |     6995 | 2024-09-14 | Sharks Esports     | W   | 0.071      | -            | -                | -                | -         |     1.70 | ALLE, destiny, drg, gbb, Misfit   |
|            1 |     7001 | 2024-09-14 | MIBR Academy       | W   | 0.071      | -            | -                | -                | -         |     0.69 | ALLE, destiny, drg, gbb, Misfit   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,602.77)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $750.00        | $750.00         |
| 2025-01-12 |      0.873 | $2,500.00      | $2,181.60       |
| 2024-11-30 |      0.586 | $1,500.00      | $879.69         |
| 2024-11-24 |      0.546 | $5,171.49      | $2,821.21       |
| 2024-11-09 |      0.447 | $1,500.00      | $669.97         |
| 2024-10-20 |      0.312 | $900.00        | $280.75         |
| 2024-09-14 |      0.073 | $269.53        | $19.56          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
