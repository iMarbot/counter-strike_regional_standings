### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, Rossi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  864.4<br />
<br />
Final Rank Value (864.4) = Starting Rank Value (909.7) + Head To Head Adjustments (-45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.388[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 909.7
- 400 + ( ( 0.255 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 909.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |       18 | 2025-03-01 | Victores Sumus          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.173 (0.025)    | 1 (1.000) |     8.61 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           43 |       26 | 2025-02-27 | Flashback Gaming        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.140 (0.020)    | 1 (1.000) |    12.34 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           42 |       30 | 2025-02-27 | Victores Sumus          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.173 (0.025)    | 1 (1.000) |     8.40 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           41 |       68 | 2025-02-24 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |    -6.29 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           40 |       87 | 2025-02-23 | Nomads (Mongolian team) | L   | 1.000      | -            | -                | -                | -         |   -25.39 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           39 |      614 | 2025-02-09 | Unsettled Resentment    | L   | 1.000      | -            | -                | -                | -         |   -21.13 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           38 |      656 | 2025-02-08 | Unsettled Resentment    | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.258 (0.037)    | 0 (0.000) |     9.57 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           37 |      740 | 2025-02-07 | Only One Word           | W   | 1.000      | 0.143        | -                | 0.190 (0.027)    | 0 (0.000) |     6.50 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           36 |     1261 | 2024-12-29 | Flashback Gaming        | W   | 0.778      | 0.143        | 0.006 (0.001)    | 0.140 (0.016)    | 0 (0.000) |    10.06 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           35 |     1265 | 2024-12-29 | Red Viperz              | W   | 0.778      | -            | -                | -                | 0 (0.000) |     1.72 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           34 |     1736 | 2024-12-14 | Big W                   | W   | 0.676      | 0.262        | 0.005 (0.001)    | 0.071 (0.013)    | 0 (0.000) |     6.25 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           33 |     1746 | 2024-12-13 | Victores Sumus          | W   | 0.675      | 0.262        | 0.006 (0.001)    | 0.173 (0.031)    | 0 (0.000) |     6.74 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           32 |     2547 | 2024-11-30 | Real Original Gaming    | L   | 0.583      | -            | -                | -                | -         |   -12.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           31 |     2813 | 2024-11-24 | Half Of Devil           | W   | 0.543      | 0.333        | 0.002 (0.000)    | -                | -         |     3.67 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           30 |     2909 | 2024-11-23 | SUBUTAI                 | W   | 0.537      | 0.333        | -                | 0.051 (0.009)    | -         |     2.25 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           29 |     3182 | 2024-11-18 | St4rboys                | L   | 0.509      | -            | -                | -                | -         |   -12.27 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           28 |     3183 | 2024-11-18 | Indian Gamers           | W   | 0.508      | -            | -                | -                | -         |     1.10 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           27 |     3361 | 2024-11-16 | Big W                   | L   | 0.489      | -            | -                | -                | -         |   -11.37 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           26 |     3917 | 2024-11-06 | Clutch Gaming           | L   | 0.422      | -            | -                | -                | -         |   -11.56 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           25 |     3920 | 2024-11-05 | The Huns Esports        | L   | 0.422      | -            | -                | -                | -         |    -5.89 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           24 |     4501 | 2024-10-27 | Big W                   | W   | 0.356      | 0.262        | 0.005 (0.000)    | -                | -         |     2.72 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           23 |     4502 | 2024-10-26 | St4rboys                | W   | 0.355      | 0.262        | 0.002 (0.000)    | -                | -         |     2.29 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           22 |     4831 | 2024-10-20 | True Rippers Esports    | W   | 0.309      | -            | -                | -                | 1 (0.309) |     0.62 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           21 |     5090 | 2024-10-15 | Harizma                 | L   | 0.277      | -            | -                | -                | -         |    -6.37 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |     5364 | 2024-10-09 | DEWA United             | L   | 0.237      | -            | -                | -                | -         |    -6.62 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           19 |     5370 | 2024-10-09 | DEWA United             | W   | 0.237      | 0.417        | -                | 0.158 (0.016)    | -         |     0.84 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |     5443 | 2024-10-08 | KENLA Gaming            | W   | 0.230      | -            | -                | -                | -         |     0.41 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |     5449 | 2024-10-08 | KENLA Gaming            | W   | 0.230      | -            | -                | -                | -         |     0.42 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |     5502 | 2024-10-07 | Harizma                 | L   | 0.223      | -            | -                | -                | -         |    -5.24 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |     5504 | 2024-10-07 | Harizma                 | L   | 0.223      | -            | -                | -                | -         |    -5.31 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     5793 | 2024-10-02 | Clutch Gaming           | W   | 0.190      | -            | -                | -                | -         |     0.70 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           13 |     5798 | 2024-10-02 | Clutch Gaming           | W   | 0.190      | -            | -                | -                | -         |     0.71 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     5871 | 2024-10-01 | The Huns Esports        | L   | 0.183      | -            | -                | -                | -         |    -2.56 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           11 |     5877 | 2024-10-01 | The Huns Esports        | L   | 0.183      | -            | -                | -                | -         |    -2.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           10 |     5987 | 2024-09-29 | True Rippers Esports    | W   | 0.170      | -            | -                | -                | -         |     0.29 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     6147 | 2024-09-27 | Victores Sumus          | W   | 0.157      | -            | -                | -                | -         |     1.59 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     6230 | 2024-09-26 | Fight 4 Fame            | W   | 0.150      | -            | -                | -                | -         |     0.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     6314 | 2024-09-25 | Noobs But Diligent      | W   | 0.143      | -            | -                | -                | -         |     0.38 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     6320 | 2024-09-25 | Noobs But Diligent      | W   | 0.143      | -            | -                | -                | -         |     0.38 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     6550 | 2024-09-21 | St4rboys                | W   | 0.122      | -            | -                | -                | -         |     0.72 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|            4 |     6551 | 2024-09-21 | True Rippers Esports    | W   | 0.121      | -            | -                | -                | -         |     0.21 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|            3 |     7465 | 2024-09-07 | Come Mid                | W   | 0.023      | -            | -                | -                | -         |     0.04 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     7541 | 2024-09-06 | The Huns Esports        | L   | 0.017      | -            | -                | -                | -         |    -0.23 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     7630 | 2024-09-05 | HXG Esports             | W   | 0.010      | -            | -                | -                | -         |     0.02 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,024.84)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-01 |      1.000 | $2,863.20      | $2,863.20       |
| 2024-12-29 |      0.778 | $340.32        | $264.85         |
| 2024-12-14 |      0.676 | $1,000.00      | $675.79         |
| 2024-11-30 |      0.583 | $2,000.00      | $1,166.94       |
| 2024-11-18 |      0.509 | $500.00        | $254.44         |
| 2024-11-03 |      0.403 | $800.00        | $322.07         |
| 2024-10-27 |      0.356 | $1,000.00      | $355.63         |
| 2024-09-21 |      0.122 | $1,000.00      | $121.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
