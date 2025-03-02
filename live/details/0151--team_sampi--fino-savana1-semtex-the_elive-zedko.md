### Roster Details<br />
Team Name: Team Sampi<br />
Roster: fino, sAvana1, semtex, The eLiVe, ZEDKO<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  760.9<br />
<br />
Final Rank Value (760.9) = Starting Rank Value (806.2) + Head To Head Adjustments (-45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.190[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 806.2
- 400 + ( ( 0.203 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 806.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     2091 | 2024-12-07 | CYBERSHOKE Esports     | L   | 0.638      | -            | -                | -                | -         |    -7.97 | fino, sAvana1, semtex, The eLiVe, ZEDKO  |
|           28 |     2156 | 2024-12-05 | Insilio                | L   | 0.627      | -            | -                | -                | -         |   -12.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           27 |     2176 | 2024-12-05 | Tricked Esport         | L   | 0.624      | -            | -                | -                | -         |    -6.86 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           26 |     2210 | 2024-12-04 | FLuffy Gangsters       | L   | 0.620      | -            | -                | -                | -         |    -7.85 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           25 |     2445 | 2024-12-01 | Betclic Apogee Esports | L   | 0.598      | -            | -                | -                | -         |    -7.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           24 |     2810 | 2024-11-24 | BRUTE                  | W   | 0.551      | 0.143        | 0.004 (0.000)    | 0.345 (0.027)    | 1 (0.551) |     6.47 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           23 |     2908 | 2024-11-23 | UNiTY esports          | L   | 0.544      | -            | -                | -                | -         |    -7.44 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           22 |     2963 | 2024-11-22 | ENTERPRISE Genesis     | W   | 0.540      | 0.143        | 0.001 (0.000)    | 0.178 (0.014)    | 1 (0.540) |     5.14 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           21 |     4086 | 2024-11-03 | Los kogutos            | L   | 0.411      | -            | -                | -                | -         |    -4.62 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           20 |     4383 | 2024-10-29 | 9INE                   | L   | 0.379      | -            | -                | -                | -         |    -6.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           19 |     4606 | 2024-10-25 | Los kogutos            | W   | 0.351      | 0.371        | 0.032 (0.004)    | 0.527 (0.069)    | 0 (0.000) |     7.68 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           18 |     5237 | 2024-10-12 | Los kogutos            | L   | 0.264      | -            | -                | -                | -         |    -2.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           17 |     5603 | 2024-10-05 | Dynamo Eclot           | L   | 0.219      | -            | -                | -                | -         |    -1.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           16 |     5626 | 2024-10-05 | Tricked Esport         | L   | 0.217      | -            | -                | -                | -         |    -3.26 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           15 |     5672 | 2024-10-04 | Dynamo Eclot           | W   | 0.212      | 0.143        | 0.127 (0.004)    | 0.703 (0.021)    | 1 (0.212) |     5.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           14 |     5732 | 2024-10-03 | AVEZ                   | W   | 0.204      | 0.143        | -                | 0.003 (0.000)    | 1 (0.204) |     0.61 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           13 |     6058 | 2024-09-28 | Wild Lotus             | L   | 0.172      | -            | -                | -                | -         |    -3.07 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           12 |     6522 | 2024-09-22 | SINNERS Esports        | L   | 0.132      | -            | -                | -                | -         |    -1.46 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           11 |     6587 | 2024-09-21 | Dynamo Eclot           | W   | 0.125      | 0.143        | 0.127 (0.002)    | 0.703 (0.013)    | 1 (0.125) |     3.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           10 |     6641 | 2024-09-20 | UNiTY esports          | L   | 0.118      | -            | -                | -                | -         |    -1.71 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            9 |     6694 | 2024-09-19 | Wild Lotus             | L   | 0.113      | -            | -                | -                | -         |    -2.09 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            8 |     6906 | 2024-09-16 | B8                     | W   | 0.090      | 0.384        | 0.124 (0.004)    | 0.590 (0.020)    | 0 (0.000) |     2.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            7 |     7150 | 2024-09-12 | OG                     | L   | 0.064      | -            | -                | -                | -         |    -0.72 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            6 |     7262 | 2024-09-10 | MOUZ NXT               | W   | 0.051      | 0.384        | 0.000 (0.000)    | -                | 0 (0.000) |     0.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            5 |     7304 | 2024-09-09 | SINNERS Esports        | L   | 0.045      | -            | -                | -                | -         |    -0.50 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            4 |     7597 | 2024-09-05 | ENTERPRISE Genesis     | W   | 0.019      | 0.143        | 0.001 (0.000)    | 0.178 (0.000)    | 0 (0.000) |     0.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            3 |     7626 | 2024-09-05 | Tricked Esport         | W   | 0.018      | 0.384        | 0.033 (0.000)    | 0.696 (0.005)    | 0 (0.000) |     0.29 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            2 |     7674 | 2024-09-04 | Metizport              | L   | 0.012      | -            | -                | -                | -         |    -0.06 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            1 |     7755 | 2024-09-03 | Ex-ENTERPRISE esports  | W   | 0.004      | 0.384        | 0.003 (0.000)    | 0.085 (0.000)    | -         |     0.05 | fino, manguss, sAvana1, The eLiVe, ZEDKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,179.01)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $4,932.95      | $2,722.03       |
| 2024-10-05 |      0.219 | $5,490.86      | $1,200.36       |
| 2024-09-22 |      0.133 | $1,336.22      | $177.17         |
| 2024-09-14 |      0.079 | $1,000.00      | $79.44          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
