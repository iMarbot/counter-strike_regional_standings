### Roster Details<br />
Team Name: BRUTE<br />
Roster: m0nsterr, realzen, sAvana1, vANO, w4rden<br />
Global Rank: [213](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [155]( ../standings_europe.md)<br />
<br />
Final Rank Value:  702.5<br />
<br />
Final Rank Value (702.5) = Starting Rank Value (722.1) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.1
- 400 + ( ( 0.161 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 722.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1217 | 2025-01-06 | EYEBALLERS                  | L   | 0.839      | -            | -                | -                | -         |   -10.64 | m0nsterr, realzen, sAvana1, vANO, w4rden |
|           31 |     1224 | 2025-01-04 | Heimo Esports               | W   | 0.825      | 0.417        | 0.004 (0.001)    | 0.658 (0.226)    | 0 (0.000) |    13.35 | m0nsterr, M1key, realzen, vANO, w4rden   |
|           30 |     1264 | 2024-12-29 | Dark Cloud Esports          | L   | 0.784      | -            | -                | -                | -         |    -7.10 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           29 |     1308 | 2024-12-28 | Rhyno Esports               | L   | 0.777      | -            | -                | -                | -         |    -7.01 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           28 |     1322 | 2024-12-27 | M1Z                         | W   | 0.774      | 0.284        | 0.000 (0.000)    | 0.113 (0.025)    | 0 (0.000) |     4.14 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           27 |     1324 | 2024-12-27 | Sissi State Punks           | W   | 0.773      | 0.284        | 0.000 (0.000)    | -                | 0 (0.000) |     3.48 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           26 |     1344 | 2024-12-26 | Dark Cloud Esports          | L   | 0.767      | -            | -                | -                | -         |    -7.39 | m0nsterr, patrenzo, realzen, SiKO, vANO  |
|           25 |     1882 | 2024-12-11 | WOPA Esport                 | L   | 0.666      | -            | -                | -                | -         |    -7.53 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           24 |     1922 | 2024-12-10 | NEVERMORE (Ukrainian team)  | L   | 0.660      | -            | -                | -                | -         |    -7.90 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           23 |     1977 | 2024-12-08 | XI Esport                   | W   | 0.647      | 0.333        | 0.001 (0.000)    | 0.287 (0.062)    | 0 (0.000) |     9.07 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           22 |     2128 | 2024-12-06 | Donstu Esports              | W   | 0.633      | 0.333        | -                | 0.205 (0.043)    | 0 (0.000) |     4.91 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           21 |     2217 | 2024-12-04 | Ex-ESC Gaming               | W   | 0.620      | 0.333        | 0.001 (0.000)    | 0.243 (0.050)    | 0 (0.000) |     8.90 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           20 |     2508 | 2024-11-30 | XPERION NXT                 | L   | 0.593      | -            | -                | -                | -         |   -10.96 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           19 |     2609 | 2024-11-28 | Rhyno Esports               | W   | 0.580      | 0.333        | 0.013 (0.003)    | 0.447 (0.086)    | 0 (0.000) |    13.45 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           18 |     2704 | 2024-11-26 | 52squad                     | W   | 0.567      | -            | -                | -                | 0 (0.000) |     2.77 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           17 |     2810 | 2024-11-24 | Team Sampi                  | L   | 0.551      | -            | -                | -                | -         |    -6.47 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           16 |     2883 | 2024-11-23 | Dynamo Eclot                | L   | 0.546      | -            | -                | -                | -         |    -2.21 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           15 |     2987 | 2024-11-22 | SINNERS Academy             | W   | 0.538      | 0.143        | 0.001 (0.000)    | 0.102 (0.008)    | 1 (0.538) |     8.99 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           14 |     3229 | 2024-11-17 | Mission Possible            | L   | 0.507      | -            | -                | -                | -         |   -11.03 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           13 |     3322 | 2024-11-16 | Ins (Polish team)           | L   | 0.499      | -            | -                | -                | -         |    -8.38 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           12 |     3497 | 2024-11-13 | ENTERPRISE Genesis          | W   | 0.480      | 0.278        | 0.001 (0.000)    | 0.178 (0.024)    | 0 (0.000) |     6.05 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           11 |     3546 | 2024-11-12 | G2 Ares                     | W   | 0.472      | 0.278        | 0.001 (0.000)    | 0.261 (0.034)    | -         |     6.96 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           10 |     3713 | 2024-11-09 | ENCE Prospects              | W   | 0.453      | -            | -                | -                | -         |     2.12 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            9 |     3948 | 2024-11-05 | G2 Ares                     | L   | 0.426      | -            | -                | -                | -         |    -7.06 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            8 |     5517 | 2024-10-06 | XI Esport                   | L   | 0.226      | -            | -                | -                | -         |    -5.44 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            7 |     6826 | 2024-09-17 | Team Secret (Croatian team) | L   | 0.100      | -            | -                | -                | -         |    -2.49 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            6 |     7169 | 2024-09-11 | Ex-UHKA eSports             | L   | 0.060      | -            | -                | -                | -         |    -1.45 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            5 |     7294 | 2024-09-09 | Infinite Gaming             | L   | 0.046      | -            | -                | -                | -         |    -0.98 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            4 |     7347 | 2024-09-08 | Dynamo Eclot                | L   | 0.039      | -            | -                | -                | -         |    -0.14 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            3 |     7416 | 2024-09-07 | ENTERPRISE Genesis          | W   | 0.033      | 0.143        | 0.001 (0.000)    | 0.178 (0.001)    | -         |     0.41 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            2 |     7566 | 2024-09-05 | BIT eSports                 | W   | 0.020      | -            | -                | -                | -         |     0.12 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            1 |     7602 | 2024-09-05 | Dynamo Eclot                | L   | 0.019      | -            | -                | -                | -         |    -0.07 | m0nsterr, realzen, SiKO, vANO, w4rden    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,341.85)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.692 | $300.00        | $207.67         |
| 2024-11-24 |      0.552 | $2,055.40      | $1,134.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
