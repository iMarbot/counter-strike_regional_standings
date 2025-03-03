### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, felps, HEN1, nyezin, venomzera<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [21]( ../standings_americas.md)<br />
<br />
Final Rank Value:  838.3<br />
<br />
Final Rank Value (838.3) = Starting Rank Value (849.6) + Head To Head Adjustments (-11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.174[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.6
- 400 + ( ( 0.225 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 849.6


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
|           36 |      270 | 2025-02-19 | Team Solid       | L   | 1.000      | -            | -                | -                | -         |   -13.86 | coldzera, felps, HEN1, nyezin, venomzera    |
|           35 |      680 | 2025-02-08 | PaiN Gaming      | L   | 1.000      | -            | -                | -                | -         |    -0.52 | coldzera, felps, HEN1, nyezin, venomzera    |
|           34 |      752 | 2025-02-07 | Nitro.GG         | L   | 1.000      | -            | -                | -                | -         |   -24.07 | coldzera, felps, HEN1, nyezin, venomzera    |
|           33 |      800 | 2025-02-07 | Elevate          | W   | 1.000      | 0.143        | -                | 0.227 (0.032)    | 0 (0.000) |     5.65 | coldzera, felps, HEN1, nyezin, venomzera    |
|           32 |      883 | 2025-02-05 | 9z Team          | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.119 (0.017)    | 0 (0.000) |    12.62 | coldzera, felps, HEN1, nyezin, venomzera    |
|           31 |      911 | 2025-02-05 | Elevate          | W   | 1.000      | 0.143        | -                | 0.227 (0.032)    | 0 (0.000) |     5.36 | coldzera, felps, HEN1, nyezin, venomzera    |
|           30 |     3426 | 2024-11-14 | Imperial Esports | L   | 0.482      | -            | -                | -                | -         |    -4.84 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           29 |     3483 | 2024-11-14 | Legacy           | W   | 0.476      | 0.143        | 0.036 (0.002)    | 0.549 (0.037)    | 1 (0.476) |     8.35 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           28 |     3531 | 2024-11-13 | Case Esports     | W   | 0.469      | -            | -                | -                | 1 (0.469) |     4.38 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           27 |     3566 | 2024-11-12 | M80              | L   | 0.463      | -            | -                | -                | -         |    -5.37 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           26 |     3586 | 2024-11-11 | 9z Team          | L   | 0.462      | -            | -                | -                | -         |    -8.85 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           25 |     4883 | 2024-10-18 | BESTIA           | L   | 0.299      | -            | -                | -                | -         |    -3.76 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           24 |     4929 | 2024-10-17 | Imperial Esports | W   | 0.293      | 0.450        | 0.092 (0.012)    | 0.562 (0.074)    | 0 (0.000) |     6.27 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           23 |     4980 | 2024-10-16 | MIBR             | L   | 0.286      | -            | -                | -                | -         |    -0.38 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           22 |     5047 | 2024-10-15 | BESTIA           | W   | 0.279      | 0.450        | 0.069 (0.009)    | 0.472 (0.059)    | -         |     5.39 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           21 |     5328 | 2024-10-09 | MIBR             | L   | 0.240      | -            | -                | -                | -         |    -0.31 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           20 |     5336 | 2024-10-09 | MIBR             | L   | 0.239      | -            | -                | -                | -         |    -0.31 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           19 |     5399 | 2024-10-08 | Dusty Roots      | W   | 0.233      | 0.450        | 0.009 (0.001)    | 0.366 (0.038)    | -         |     2.94 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           18 |     5410 | 2024-10-08 | Dusty Roots      | W   | 0.233      | 0.450        | 0.009 (0.001)    | 0.366 (0.038)    | -         |     2.99 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           17 |     5417 | 2024-10-08 | Team Solid       | L   | 0.232      | -            | -                | -                | -         |    -3.74 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           16 |     5425 | 2024-10-08 | Team Solid       | L   | 0.232      | -            | -                | -                | -         |    -3.81 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           15 |     5461 | 2024-10-07 | BESTIA           | L   | 0.226      | -            | -                | -                | -         |    -2.85 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           14 |     5464 | 2024-10-07 | BESTIA           | L   | 0.226      | -            | -                | -                | -         |    -2.91 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           13 |     5596 | 2024-10-05 | BESTIA           | W   | 0.211      | 0.143        | 0.069 (0.002)    | -                | 1 (0.211) |     3.99 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           12 |     5665 | 2024-10-04 | Imperial Esports | W   | 0.205      | 0.143        | 0.092 (0.003)    | -                | 1 (0.205) |     4.38 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           11 |     5772 | 2024-10-02 | PaiN Gaming      | L   | 0.192      | -            | -                | -                | -         |    -0.07 | coldzera, dav1deuS, HEN1, nython, venomzera |
|           10 |     5777 | 2024-10-02 | PaiN Gaming      | W   | 0.192      | 0.450        | 0.323 (0.028)    | 0.549 (0.047)    | -         |     5.97 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            9 |     6008 | 2024-09-28 | PaiN Gaming      | L   | 0.166      | -            | -                | -                | -         |    -0.06 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            8 |     6015 | 2024-09-28 | Fluxo            | L   | 0.165      | -            | -                | -                | -         |    -2.04 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            7 |     6264 | 2024-09-25 | Fluxo            | L   | 0.146      | -            | -                | -                | -         |    -1.85 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            6 |     6270 | 2024-09-25 | Fluxo            | L   | 0.146      | -            | -                | -                | -         |    -1.87 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            5 |     6947 | 2024-09-15 | FURIA            | L   | 0.077      | -            | -                | -                | -         |    -0.09 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            4 |     7041 | 2024-09-14 | Team Falcons     | W   | 0.070      | -            | -                | -                | 1 (0.070) |     0.75 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            3 |     7111 | 2024-09-13 | FURIA            | L   | 0.063      | -            | -                | -                | -         |    -0.07 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            2 |     7150 | 2024-09-12 | ENCE             | W   | 0.057      | 0.889        | 0.136 (0.007)    | 0.412 (0.021)    | 1 (0.057) |     1.27 | coldzera, dav1deuS, HEN1, nython, venomzera |
|            1 |     7251 | 2024-09-10 | Virtus.pro       | L   | 0.045      | -            | -                | -                | -         |    -0.01 | coldzera, dav1deuS, HEN1, nython, venomzera |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,529.63)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.312 | $5,000.00      | $1,559.72       |
| 2024-10-05 |      0.211 | $16,491.66     | $3,481.57       |
| 2024-09-22 |      0.124 | $12,000.00     | $1,488.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
