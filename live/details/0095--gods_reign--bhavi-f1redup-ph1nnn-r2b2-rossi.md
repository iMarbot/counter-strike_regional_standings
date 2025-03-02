### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, Rossi<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  862.9<br />
<br />
Final Rank Value (862.9) = Starting Rank Value (908.4) + Head To Head Adjustments (-45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.387[<sup>2</sup>](#table1)

The average of these factors is 0.255<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 908.4
- 400 + ( ( 0.255 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 908.4


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
|           44 |        3 | 2025-03-01 | Victores Sumus          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.174 (0.025)    | 1 (1.000) |     8.59 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           43 |       11 | 2025-02-27 | Flashback Gaming        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.141 (0.020)    | 1 (1.000) |    12.39 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           42 |       15 | 2025-02-27 | Victores Sumus          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.174 (0.025)    | 1 (1.000) |     8.38 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           41 |       53 | 2025-02-24 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |    -6.17 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           40 |       72 | 2025-02-23 | Nomads (Mongolian team) | L   | 1.000      | -            | -                | -                | -         |   -25.35 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           39 |      602 | 2025-02-09 | Unsettled Resentment    | L   | 1.000      | -            | -                | -                | -         |   -21.05 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           38 |      644 | 2025-02-08 | Unsettled Resentment    | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.259 (0.037)    | 0 (0.000) |     9.65 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           37 |      728 | 2025-02-07 | Only One Word           | W   | 1.000      | 0.143        | -                | 0.191 (0.027)    | 0 (0.000) |     6.56 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           36 |     1249 | 2024-12-29 | Flashback Gaming        | W   | 0.786      | 0.143        | 0.006 (0.001)    | 0.141 (0.016)    | 0 (0.000) |    10.23 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           35 |     1253 | 2024-12-29 | Red Viperz              | W   | 0.786      | -            | -                | -                | 0 (0.000) |     1.76 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           34 |     1724 | 2024-12-14 | Big W                   | W   | 0.684      | 0.262        | 0.005 (0.001)    | 0.072 (0.013)    | 0 (0.000) |     6.37 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           33 |     1734 | 2024-12-13 | Victores Sumus          | W   | 0.683      | 0.262        | 0.006 (0.001)    | 0.174 (0.031)    | 0 (0.000) |     6.82 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           32 |     2535 | 2024-11-30 | Real Original Gaming    | L   | 0.592      | -            | -                | -                | -         |   -12.42 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           31 |     2801 | 2024-11-24 | Half Of Devil           | W   | 0.552      | 0.333        | 0.002 (0.000)    | -                | -         |     3.75 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           30 |     2897 | 2024-11-23 | SUBUTAI                 | W   | 0.545      | 0.333        | -                | 0.051 (0.009)    | -         |     2.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           29 |     3170 | 2024-11-18 | St4rboys                | L   | 0.517      | -            | -                | -                | -         |   -12.44 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           28 |     3171 | 2024-11-18 | Indian Gamers           | W   | 0.517      | -            | -                | -                | -         |     1.13 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           27 |     3349 | 2024-11-16 | Big W                   | L   | 0.498      | -            | -                | -                | -         |   -11.53 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           26 |     3905 | 2024-11-06 | Clutch Gaming           | L   | 0.431      | -            | -                | -                | -         |   -11.76 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           25 |     3908 | 2024-11-05 | The Huns Esports        | L   | 0.430      | -            | -                | -                | -         |    -5.95 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           24 |     4489 | 2024-10-27 | Big W                   | W   | 0.364      | 0.262        | 0.005 (0.000)    | -                | -         |     2.80 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           23 |     4490 | 2024-10-26 | St4rboys                | W   | 0.363      | 0.262        | 0.002 (0.000)    | -                | -         |     2.36 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           22 |     4819 | 2024-10-20 | True Rippers Esports    | W   | 0.317      | -            | -                | -                | 1 (0.317) |     0.65 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           21 |     5078 | 2024-10-15 | Harizma                 | L   | 0.285      | -            | -                | -                | -         |    -6.52 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           20 |     5352 | 2024-10-09 | DEWA United             | L   | 0.245      | -            | -                | -                | -         |    -6.83 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           19 |     5358 | 2024-10-09 | DEWA United             | W   | 0.245      | 0.417        | -                | 0.161 (0.016)    | -         |     0.88 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           18 |     5431 | 2024-10-08 | KENLA Gaming            | W   | 0.238      | -            | -                | -                | -         |     0.43 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           17 |     5437 | 2024-10-08 | KENLA Gaming            | W   | 0.238      | -            | -                | -                | -         |     0.43 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           16 |     5490 | 2024-10-07 | Harizma                 | L   | 0.232      | -            | -                | -                | -         |    -5.41 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           15 |     5492 | 2024-10-07 | Harizma                 | L   | 0.231      | -            | -                | -                | -         |    -5.49 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           14 |     5781 | 2024-10-02 | Clutch Gaming           | W   | 0.198      | -            | -                | -                | -         |     0.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           13 |     5786 | 2024-10-02 | Clutch Gaming           | W   | 0.198      | -            | -                | -                | -         |     0.75 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     5859 | 2024-10-01 | The Huns Esports        | L   | 0.192      | -            | -                | -                | -         |    -2.65 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           11 |     5865 | 2024-10-01 | The Huns Esports        | L   | 0.191      | -            | -                | -                | -         |    -2.69 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           10 |     5975 | 2024-09-29 | True Rippers Esports    | W   | 0.178      | -            | -                | -                | -         |     0.31 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            9 |     6135 | 2024-09-27 | Victores Sumus          | W   | 0.165      | -            | -                | -                | -         |     1.67 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            8 |     6218 | 2024-09-26 | Fight 4 Fame            | W   | 0.158      | -            | -                | -                | -         |     0.27 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            7 |     6302 | 2024-09-25 | Noobs But Diligent      | W   | 0.152      | -            | -                | -                | -         |     0.40 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            6 |     6308 | 2024-09-25 | Noobs But Diligent      | W   | 0.151      | -            | -                | -                | -         |     0.40 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     6538 | 2024-09-21 | St4rboys                | W   | 0.130      | -            | -                | -                | -         |     0.77 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|            4 |     6539 | 2024-09-21 | True Rippers Esports    | W   | 0.130      | -            | -                | -                | -         |     0.22 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn |
|            3 |     7453 | 2024-09-07 | Come Mid                | W   | 0.031      | -            | -                | -                | -         |     0.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     7529 | 2024-09-06 | The Huns Esports        | L   | 0.025      | -            | -                | -                | -         |    -0.34 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     7618 | 2024-09-05 | HXG Esports             | W   | 0.018      | -            | -                | -                | -         |     0.03 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,079.26)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-01 |      1.000 | $2,863.20      | $2,863.20       |
| 2024-12-29 |      0.786 | $340.32        | $267.64         |
| 2024-12-14 |      0.684 | $1,000.00      | $683.98         |
| 2024-11-30 |      0.592 | $2,000.00      | $1,183.33       |
| 2024-11-18 |      0.517 | $500.00        | $258.54         |
| 2024-11-03 |      0.411 | $800.00        | $328.63         |
| 2024-10-27 |      0.364 | $1,000.00      | $363.82         |
| 2024-09-21 |      0.130 | $1,000.00      | $130.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
