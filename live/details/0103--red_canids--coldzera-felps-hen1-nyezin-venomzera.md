### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, felps, HEN1, nyezin, venomzera<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  841.7<br />
<br />
Final Rank Value (841.7) = Starting Rank Value (853.7) + Head To Head Adjustments (-11.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.179[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.7
- 400 + ( ( 0.227 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 853.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      258 | 2025-02-19 | Team Solid       | L   | 1.000      | -            | -                | -                | -         |   -13.93 | coldzera, felps, HEN1, nyezin, venomzera    |
|           35 |      668 | 2025-02-08 | PaiN Gaming      | L   | 1.000      | -            | -                | -                | -         |    -0.53 | coldzera, felps, HEN1, nyezin, venomzera    |
|           34 |      740 | 2025-02-07 | Nitro.GG         | L   | 1.000      | -            | -                | -                | -         |   -24.17 | coldzera, felps, HEN1, nyezin, venomzera    |
|           33 |      788 | 2025-02-07 | Elevate          | W   | 1.000      | 0.143        | -                | 0.227 (0.032)    | 0 (0.000) |     5.57 | coldzera, felps, HEN1, nyezin, venomzera    |
|           32 |      871 | 2025-02-05 | 9z Team          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.121 (0.017)    | 0 (0.000) |    12.64 | coldzera, felps, HEN1, nyezin, venomzera    |
|           31 |      899 | 2025-02-05 | Elevate          | W   | 1.000      | 0.143        | -                | 0.227 (0.032)    | 0 (0.000) |     5.28 | coldzera, felps, HEN1, nyezin, venomzera    |
|           30 |     3414 | 2024-11-14 | Imperial Esports | L   | 0.490      | -            | -                | -                | -         |    -4.93 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           29 |     3471 | 2024-11-14 | Legacy           | W   | 0.484      | 0.143        | 0.036 (0.003)    | 0.554 (0.038)    | 1 (0.484) |     8.40 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           28 |     3519 | 2024-11-13 | Case Esports     | W   | 0.477      | -            | -                | -                | 1 (0.477) |     4.41 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           27 |     3554 | 2024-11-12 | M80              | L   | 0.472      | -            | -                | -                | -         |    -5.64 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           26 |     3574 | 2024-11-11 | 9z Team          | L   | 0.470      | -            | -                | -                | -         |    -9.00 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           25 |     4871 | 2024-10-18 | BESTIA           | L   | 0.307      | -            | -                | -                | -         |    -3.88 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           24 |     4917 | 2024-10-17 | Imperial Esports | W   | 0.301      | 0.450        | 0.091 (0.012)    | 0.564 (0.076)    | 0 (0.000) |     6.44 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           23 |     4968 | 2024-10-16 | MIBR             | L   | 0.294      | -            | -                | -                | -         |    -0.39 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           22 |     5035 | 2024-10-15 | BESTIA           | W   | 0.287      | 0.450        | 0.069 (0.009)    | 0.478 (0.062)    | -         |     5.53 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           21 |     5316 | 2024-10-09 | MIBR             | L   | 0.248      | -            | -                | -                | -         |    -0.32 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           20 |     5324 | 2024-10-09 | MIBR             | L   | 0.247      | -            | -                | -                | -         |    -0.32 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           19 |     5387 | 2024-10-08 | Dusty Roots      | W   | 0.241      | 0.450        | 0.008 (0.001)    | 0.371 (0.040)    | -         |     3.00 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           18 |     5398 | 2024-10-08 | Dusty Roots      | W   | 0.241      | 0.450        | 0.008 (0.001)    | 0.371 (0.040)    | -         |     3.06 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           17 |     5405 | 2024-10-08 | Team Solid       | L   | 0.240      | -            | -                | -                | -         |    -3.90 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           16 |     5413 | 2024-10-08 | Team Solid       | L   | 0.240      | -            | -                | -                | -         |    -3.97 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           15 |     5449 | 2024-10-07 | BESTIA           | L   | 0.234      | -            | -                | -                | -         |    -2.98 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           14 |     5452 | 2024-10-07 | BESTIA           | L   | 0.234      | -            | -                | -                | -         |    -3.03 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           13 |     5584 | 2024-10-05 | BESTIA           | W   | 0.219      | 0.143        | 0.069 (0.002)    | -                | 1 (0.219) |     4.13 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           12 |     5653 | 2024-10-04 | Imperial Esports | W   | 0.214      | 0.143        | 0.091 (0.003)    | -                | 1 (0.214) |     4.55 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           11 |     5760 | 2024-10-02 | PaiN Gaming      | L   | 0.200      | -            | -                | -                | -         |    -0.07 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           10 |     5765 | 2024-10-02 | PaiN Gaming      | W   | 0.200      | 0.450        | 0.318 (0.029)    | 0.555 (0.050)    | -         |     6.22 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            9 |     5996 | 2024-09-28 | PaiN Gaming      | L   | 0.175      | -            | -                | -                | -         |    -0.06 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            8 |     6003 | 2024-09-28 | Fluxo            | L   | 0.173      | -            | -                | -                | -         |    -2.16 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            7 |     6252 | 2024-09-25 | Fluxo            | L   | 0.154      | -            | -                | -                | -         |    -1.97 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            6 |     6258 | 2024-09-25 | Fluxo            | L   | 0.154      | -            | -                | -                | -         |    -2.00 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            5 |     6935 | 2024-09-15 | FURIA            | L   | 0.085      | -            | -                | -                | -         |    -0.10 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            4 |     7029 | 2024-09-14 | Team Falcons     | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.83 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            3 |     7099 | 2024-09-13 | FURIA            | L   | 0.071      | -            | -                | -                | -         |    -0.08 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            2 |     7138 | 2024-09-12 | ENCE             | W   | 0.065      | 0.889        | 0.136 (0.008)    | 0.414 (0.024)    | 1 (0.065) |     1.45 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            1 |     7239 | 2024-09-10 | Virtus.pro       | L   | 0.053      | -            | -                | -                | -         |    -0.02 | coldzera, dav1deuS, HEN1, nython, venomzera |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,804.07)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.320 | $5,000.00      | $1,600.69       |
| 2024-10-05 |      0.219 | $16,491.66     | $3,616.71       |
| 2024-09-22 |      0.132 | $12,000.00     | $1,586.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
