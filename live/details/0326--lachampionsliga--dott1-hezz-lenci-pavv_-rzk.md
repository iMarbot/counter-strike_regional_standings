### Roster Details<br />
Team Name: LaChampionsLiga<br />
Roster: dott1, Hezz, lenci, pavv+, rzk<br />
Global Rank: [326](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [64]( ../standings_americas.md)<br />
<br />
Final Rank Value:  636.4<br />
<br />
Final Rank Value (636.4) = Starting Rank Value (673.8) + Head To Head Adjustments (-37.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.8
- 400 + ( ( 0.137 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 673.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      392 | 2025-02-15 | Tropa do VSM             | L   | 1.000      | -            | -                | -                | -         |   -20.74 | dott1, Hezz, lenci, pavv+, rzk   |
|           35 |      395 | 2025-02-15 | América eSports          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.429 (0.061)    | 0 (0.000) |    13.29 | dott1, Hezz, lenci, pavv+, rzk   |
|           34 |      399 | 2025-02-15 | 7REX                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.40 | dott1, Hezz, lenci, pavv+, rzk   |
|           33 |      660 | 2025-02-08 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |    -5.05 | dott1, Hezz, lenci, pavv+, rzk   |
|           32 |      738 | 2025-02-07 | Tropa do KinGui          | W   | 1.000      | 0.143        | -                | 0.093 (0.013)    | 0 (0.000) |     8.32 | dott1, Hezz, lenci, pavv+, rzk   |
|           31 |      932 | 2025-02-04 | Familia Maquininha       | L   | 1.000      | -            | -                | -                | -         |   -13.51 | dott1, Hezz, lenci, pavv+, rzk   |
|           30 |     1431 | 2024-12-21 | Game Hunters             | L   | 0.734      | -            | -                | -                | -         |    -9.72 | dott1, Hezz, lenci, nacho, pavv+ |
|           29 |     1525 | 2024-12-19 | Team Solid               | L   | 0.721      | -            | -                | -                | -         |    -5.59 | dott1, Hezz, lenci, nacho, pavv+ |
|           28 |     1550 | 2024-12-18 | Bad News Chickens        | L   | 0.713      | -            | -                | -                | -         |   -10.21 | dott1, Hezz, lenci, nacho, pavv+ |
|           27 |     1578 | 2024-12-16 | 20/70                    | W   | 0.701      | 0.384        | 0.001 (0.000)    | 0.290 (0.078)    | 0 (0.000) |    10.95 | dott1, Hezz, lenci, nacho, pavv+ |
|           26 |     1661 | 2024-12-14 | Players (Brazilian team) | W   | 0.688      | 0.384        | 0.008 (0.002)    | 0.637 (0.169)    | 0 (0.000) |    14.87 | dott1, Hezz, lenci, nacho, pavv+ |
|           25 |     1909 | 2024-12-10 | 9z Academy               | L   | 0.661      | -            | -                | -                | -         |    -9.61 | dott1, Hezz, lenci, nacho, pavv+ |
|           24 |     1942 | 2024-12-09 | Floripa Stars            | W   | 0.654      | 0.143        | 0.001 (0.000)    | 0.302 (0.028)    | 0 (0.000) |     9.71 | dott1, Hezz, lenci, nacho, pavv+ |
|           23 |     2121 | 2024-12-06 | MIBR Academy             | L   | 0.634      | -            | -                | -                | -         |    -8.54 | dott1, Hezz, lenci, nacho, pavv+ |
|           22 |     2251 | 2024-12-03 | Nitro.GG                 | W   | 0.614      | 0.143        | 0.002 (0.000)    | 0.518 (0.045)    | 0 (0.000) |    10.97 | dott1, Hezz, lenci, nacho, pavv+ |
|           21 |     2468 | 2024-11-30 | Team Leveling            | W   | 0.594      | 0.143        | -                | 0.157 (0.013)    | 0 (0.000) |     6.20 | dott1, Hezz, lenci, nacho, pavv+ |
|           20 |     2492 | 2024-11-30 | 9z Academy               | W   | 0.594      | 0.143        | 0.001 (0.000)    | 0.388 (0.033)    | 0 (0.000) |     9.73 | dott1, Hezz, lenci, nacho, pavv+ |
|           19 |     2778 | 2024-11-24 | América eSports          | L   | 0.553      | -            | -                | -                | -         |    -9.69 | dott1, Hezz, lenci, pavv+, rzk   |
|           18 |     2782 | 2024-11-24 | Patins da Ferrari        | L   | 0.553      | -            | -                | -                | -         |   -11.50 | dott1, Hezz, lenci, pavv+, rzk   |
|           17 |     2829 | 2024-11-23 | PURPLE RAIN              | W   | 0.547      | -            | -                | -                | 0 (0.000) |     5.36 | dott1, Hezz, lenci, pavv+, rzk   |
|           16 |     2848 | 2024-11-23 | WiSe.Black               | W   | 0.547      | -            | -                | -                | -         |     3.51 | dott1, Hezz, lenci, pavv+, rzk   |
|           15 |     2979 | 2024-11-22 | BESTIA Academy           | W   | 0.539      | -            | -                | -                | -         |     3.32 | dott1, Hezz, lenci, pavv+, rzk   |
|           14 |     3106 | 2024-11-20 | Floripa Stars            | L   | 0.527      | -            | -                | -                | -         |    -7.95 | dott1, Hezz, lenci, pavv+, rzk   |
|           13 |     3179 | 2024-11-18 | ShindeN                  | L   | 0.514      | -            | -                | -                | -         |    -6.34 | dott1, Hezz, lenci, pavv+, rzk   |
|           12 |     3816 | 2024-11-07 | PaiN Gaming Academy      | L   | 0.441      | -            | -                | -                | -         |    -9.89 | dott1, Hezz, lenci, pavv+, rzk   |
|           11 |     4034 | 2024-11-03 | 9z Academy               | L   | 0.414      | -            | -                | -                | -         |    -6.40 | dott1, Hezz, lenci, pavv+, rzk   |
|           10 |     4202 | 2024-11-01 | BeBold.gg                | W   | 0.399      | 0.371        | 0.000 (0.000)    | -                | -         |     4.18 | dott1, Hezz, lenci, pavv+, rzk   |
|            9 |     4320 | 2024-10-30 | Yawara E-Sports          | L   | 0.386      | -            | -                | -                | -         |    -5.55 | dott1, Hezz, lenci, pavv+, rzk   |
|            8 |     4381 | 2024-10-29 | VELOX Argentina          | L   | 0.379      | -            | -                | -                | -         |    -7.11 | dott1, Hezz, lenci, pavv+, rzk   |
|            7 |     5247 | 2024-10-11 | ShindeN                  | L   | 0.262      | -            | -                | -                | -         |    -3.62 | dott1, Hezz, lenci, pavv+, rzk   |
|            6 |     5942 | 2024-09-29 | Dusty Roots              | W   | 0.181      | 0.143        | 0.008 (0.000)    | 0.371 (0.010)    | -         |     3.76 | dott1, Hezz, lenci, pavv+, rzk   |
|            5 |     5999 | 2024-09-28 | VELOX Argentina          | W   | 0.174      | 0.143        | 0.000 (0.000)    | 0.266 (0.007)    | -         |     2.16 | dott1, Hezz, lenci, pavv+, rzk   |
|            4 |     6014 | 2024-09-28 | BESTIA Academy           | W   | 0.173      | -            | -                | -                | -         |     0.97 | dott1, Hezz, lenci, pavv+, rzk   |
|            3 |     6496 | 2024-09-22 | ShindeN                  | L   | 0.135      | -            | -                | -                | -         |    -1.84 | dott1, Hezz, lenci, pavv+, rzk   |
|            2 |     6499 | 2024-09-22 | Romanos                  | W   | 0.134      | -            | -                | -                | -         |     1.06 | dott1, Hezz, lenci, pavv+, rzk   |
|            1 |     6554 | 2024-09-21 | BOSKIANS                 | W   | 0.127      | -            | -                | -                | -         |     0.71 | dott1, Hezz, lenci, pavv+, rzk   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($940.30)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-11 |      0.262 | $3,590.65      | $940.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
