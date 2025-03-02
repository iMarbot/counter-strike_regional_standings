### Roster Details<br />
Team Name: DEPO<br />
Roster: botirshoT, fr0k, KxtsnE, shoxs, wetfy<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [14]( ../standings_asia.md)<br />
<br />
Final Rank Value:  791.4<br />
<br />
Final Rank Value (791.4) = Starting Rank Value (778.5) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.202[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.5
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 778.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     1729 | 2024-12-13 | Team Novaq            | L   | 0.684      | -            | -                | -                | -         |    -3.32 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           30 |     1806 | 2024-12-13 | Blaze (Uzbek team)    | W   | 0.678      | 0.333        | 0.005 (0.001)    | 0.070 (0.016)    | 1 (0.678) |     8.62 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           29 |     1815 | 2024-12-12 | AimAssassins          | L   | 0.677      | -            | -                | -                | -         |    -6.30 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           28 |     2441 | 2024-12-01 | 500 Rush              | W   | 0.598      | 0.284        | 0.002 (0.000)    | 0.146 (0.025)    | 0 (0.000) |     6.71 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           27 |     2539 | 2024-11-30 | Ex-ESC Gaming         | W   | 0.592      | 0.284        | 0.001 (0.000)    | 0.243 (0.041)    | 0 (0.000) |     6.33 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           26 |     2635 | 2024-11-28 | EC BANGA              | W   | 0.580      | 0.284        | 0.001 (0.000)    | 0.097 (0.016)    | -         |     3.33 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           25 |     3099 | 2024-11-20 | SkyFury               | W   | 0.527      | 0.284        | 0.004 (0.001)    | 0.342 (0.051)    | -         |     6.41 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           24 |     3114 | 2024-11-20 | Hypewrld              | W   | 0.526      | 0.284        | 0.002 (0.000)    | 0.187 (0.028)    | -         |     7.53 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           23 |     3243 | 2024-11-17 | MYSKILL               | L   | 0.506      | -            | -                | -                | -         |    -9.74 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           22 |     3262 | 2024-11-17 | ALLINNERS             | W   | 0.505      | 0.143        | 0.002 (0.000)    | 0.151 (0.011)    | -         |     7.16 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           21 |     3324 | 2024-11-16 | Yamato Esports        | W   | 0.499      | 0.143        | 0.000 (0.000)    | 0.020 (0.001)    | -         |     3.08 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           20 |     3337 | 2024-11-16 | MYSKILL               | L   | 0.498      | -            | -                | -                | -         |    -9.99 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           19 |     3739 | 2024-11-09 | AK BARS               | L   | 0.452      | -            | -                | -                | -         |    -5.91 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           18 |     3800 | 2024-11-08 | RAGE (Kazakh team)    | W   | 0.446      | 0.143        | 0.005 (0.000)    | 0.182 (0.012)    | -         |     8.17 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           17 |     3840 | 2024-11-07 | Yamato Esports        | W   | 0.440      | -            | -                | -                | -         |     2.73 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           16 |     3886 | 2024-11-06 | ALLINNERS             | L   | 0.433      | -            | -                | -                | -         |    -7.94 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           15 |     4071 | 2024-11-03 | Brodyagi              | W   | 0.412      | -            | -                | -                | -         |     1.42 | botirshoT, fr0k, KxtsnE, shoxs, wetfy        |
|           14 |     5618 | 2024-10-05 | AK BARS               | L   | 0.218      | -            | -                | -                | -         |    -2.83 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|           13 |     5631 | 2024-10-04 | MYSKILL               | L   | 0.217      | -            | -                | -                | -         |    -4.41 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|           12 |     5862 | 2024-10-01 | Blaze (Uzbek team)    | W   | 0.192      | -            | -                | -                | 1 (0.192) |     1.51 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|           11 |     5877 | 2024-10-01 | 5x5                   | W   | 0.190      | -            | -                | -                | 1 (0.190) |     0.64 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|           10 |     5976 | 2024-09-29 | BEZONE                | W   | 0.178      | -            | -                | -                | 1 (0.178) |     0.68 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            9 |     6068 | 2024-09-28 | BERMOOD               | W   | 0.171      | -            | -                | -                | 1 (0.171) |     0.62 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            8 |     6081 | 2024-09-28 | BEZONE                | W   | 0.170      | -            | -                | -                | 1 (0.170) |     0.64 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            7 |     6685 | 2024-09-19 | 500 Rush              | L   | 0.113      | -            | -                | -                | -         |    -2.42 | botirshoT, fr0k, tokyoyo, wetfy, yngtrxpstxr |
|            6 |     6747 | 2024-09-18 | Eternal prem          | W   | 0.107      | -            | -                | -                | -         |     0.92 | botirshoT, fr0k, tokyoyo, wetfy, yngtrxpstxr |
|            5 |     6934 | 2024-09-15 | Team Novaq            | L   | 0.085      | -            | -                | -                | -         |    -0.34 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            4 |     7033 | 2024-09-14 | Kvartira36            | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.45 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            3 |     7044 | 2024-09-14 | AITU                  | W   | 0.077      | -            | -                | -                | 1 (0.077) |     0.26 | botirshoT, fr0k, KxtsnE, wetfy, yngtrxpstxr  |
|            2 |     7065 | 2024-09-13 | FORTIS (Russian team) | L   | 0.073      | -            | -                | -                | -         |    -1.68 | botirshoT, fr0k, tokyoyo, wetfy, yngtrxpstxr |
|            1 |     7176 | 2024-09-11 | 500 Rush              | W   | 0.060      | 0.310        | 0.002 (0.000)    | 0.146 (0.003)    | -         |     0.61 | botirshoT, fr0k, tokyoyo, wetfy, yngtrxpstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,099.83)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-01 |      0.598 | $2,000.00      | $1,195.88       |
| 2024-11-17 |      0.506 | $200.62        | $101.43         |
| 2024-11-09 |      0.453 | $522.02        | $236.38         |
| 2024-10-06 |      0.224 | $1,000.00      | $224.44         |
| 2024-10-01 |      0.192 | $392.54        | $75.18          |
| 2024-09-21 |      0.127 | $700.00        | $88.57          |
| 2024-09-15 |      0.085 | $2,083.29      | $177.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
