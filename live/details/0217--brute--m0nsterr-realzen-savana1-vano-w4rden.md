### Roster Details<br />
Team Name: BRUTE<br />
Roster: m0nsterr, realzen, sAvana1, vANO, w4rden<br />
Global Rank: [217](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [155]( ../standings_europe.md)<br />
<br />
Final Rank Value:  702.2<br />
<br />
Final Rank Value (702.2) = Starting Rank Value (721.5) + Head To Head Adjustments (-19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.5
- 400 + ( ( 0.161 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 721.5


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
|           32 |     1229 | 2025-01-06 | EYEBALLERS                  | L   | 0.831      | -            | -                | -                | -         |   -10.53 | m0nsterr, realzen, sAvana1, vANO, w4rden |
|           31 |     1236 | 2025-01-04 | Heimo Esports               | W   | 0.817      | 0.417        | 0.004 (0.001)    | 0.651 (0.222)    | 0 (0.000) |    13.10 | m0nsterr, M1key, realzen, vANO, w4rden   |
|           30 |     1276 | 2024-12-29 | Dark Cloud Esports          | L   | 0.776      | -            | -                | -                | -         |    -7.07 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           29 |     1320 | 2024-12-28 | Rhyno Esports               | L   | 0.769      | -            | -                | -                | -         |    -6.99 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           28 |     1334 | 2024-12-27 | M1Z                         | W   | 0.766      | 0.284        | 0.000 (0.000)    | 0.111 (0.024)    | 0 (0.000) |     4.10 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           27 |     1336 | 2024-12-27 | Sissi State Punks           | W   | 0.765      | 0.284        | 0.000 (0.000)    | -                | 0 (0.000) |     3.44 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           26 |     1356 | 2024-12-26 | Dark Cloud Esports          | L   | 0.758      | -            | -                | -                | -         |    -7.36 | m0nsterr, patrenzo, realzen, SiKO, vANO  |
|           25 |     1894 | 2024-12-11 | WOPA Esport                 | L   | 0.658      | -            | -                | -                | -         |    -7.45 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           24 |     1934 | 2024-12-10 | NEVERMORE (Ukrainian team)  | L   | 0.652      | -            | -                | -                | -         |    -7.82 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           23 |     1989 | 2024-12-08 | XI Esport                   | W   | 0.639      | 0.333        | 0.001 (0.000)    | 0.282 (0.060)    | 0 (0.000) |     8.95 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           22 |     2140 | 2024-12-06 | Donstu Esports              | W   | 0.625      | 0.333        | -                | 0.203 (0.042)    | 0 (0.000) |     4.84 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           21 |     2229 | 2024-12-04 | Ex-ESC Gaming               | W   | 0.612      | 0.333        | 0.001 (0.000)    | 0.239 (0.049)    | 0 (0.000) |     8.78 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           20 |     2520 | 2024-11-30 | XPERION NXT                 | L   | 0.585      | -            | -                | -                | -         |   -10.82 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           19 |     2621 | 2024-11-28 | Rhyno Esports               | W   | 0.572      | 0.333        | 0.013 (0.003)    | 0.441 (0.084)    | 0 (0.000) |    13.20 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           18 |     2716 | 2024-11-26 | 52squad                     | W   | 0.559      | -            | -                | -                | 0 (0.000) |     2.73 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           17 |     2822 | 2024-11-24 | Team Sampi                  | L   | 0.543      | -            | -                | -                | -         |    -6.43 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           16 |     2895 | 2024-11-23 | Dynamo Eclot                | L   | 0.538      | -            | -                | -                | -         |    -2.19 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           15 |     2999 | 2024-11-22 | SINNERS Academy             | W   | 0.530      | 0.143        | 0.001 (0.000)    | 0.101 (0.008)    | 1 (0.530) |     8.85 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           14 |     3241 | 2024-11-17 | Mission Possible            | L   | 0.498      | -            | -                | -                | -         |   -10.88 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           13 |     3334 | 2024-11-16 | Ins (Polish team)           | L   | 0.491      | -            | -                | -                | -         |    -8.26 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           12 |     3509 | 2024-11-13 | ENTERPRISE Genesis          | W   | 0.471      | 0.278        | 0.001 (0.000)    | 0.175 (0.023)    | 0 (0.000) |     5.95 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           11 |     3558 | 2024-11-12 | G2 Ares                     | W   | 0.464      | 0.278        | 0.001 (0.000)    | 0.257 (0.033)    | -         |     6.82 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|           10 |     3725 | 2024-11-09 | ENCE Prospects              | W   | 0.445      | -            | -                | -                | -         |     2.08 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            9 |     3960 | 2024-11-05 | G2 Ares                     | L   | 0.418      | -            | -                | -                | -         |    -6.94 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            8 |     5529 | 2024-10-06 | XI Esport                   | L   | 0.218      | -            | -                | -                | -         |    -5.25 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            7 |     6838 | 2024-09-17 | Team Secret (Croatian team) | L   | 0.092      | -            | -                | -                | -         |    -2.29 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            6 |     7181 | 2024-09-11 | Ex-UHKA eSports             | L   | 0.052      | -            | -                | -                | -         |    -1.25 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            5 |     7306 | 2024-09-09 | Infinite Gaming             | L   | 0.038      | -            | -                | -                | -         |    -0.81 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            4 |     7359 | 2024-09-08 | Dynamo Eclot                | L   | 0.031      | -            | -                | -                | -         |    -0.11 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            3 |     7428 | 2024-09-07 | ENTERPRISE Genesis          | W   | 0.024      | 0.143        | 0.001 (0.000)    | 0.175 (0.001)    | -         |     0.31 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            2 |     7578 | 2024-09-05 | BIT eSports                 | W   | 0.012      | -            | -                | -                | -         |     0.05 | m0nsterr, realzen, SiKO, vANO, w4rden    |
|            1 |     7614 | 2024-09-05 | Dynamo Eclot                | L   | 0.011      | -            | -                | -                | -         |    -0.04 | m0nsterr, realzen, SiKO, vANO, w4rden    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,322.54)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $300.00        | $205.21         |
| 2024-11-24 |      0.544 | $2,055.40      | $1,117.34       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
