### Roster Details<br />
Team Name: Team Sampi<br />
Roster: fino, sAvana1, semtex, The eLiVe, ZEDKO<br />
Global Rank: [155](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
<br />
Final Rank Value:  758.8<br />
<br />
Final Rank Value (758.8) = Starting Rank Value (803.3) + Head To Head Adjustments (-44.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 803.3
- 400 + ( ( 0.202 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 803.3


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
|           28 |     2103 | 2024-12-07 | CYBERSHOKE Esports     | L   | 0.630      | -            | -                | -                | -         |    -7.82 | fino, sAvana1, semtex, The eLiVe, ZEDKO  |
|           27 |     2168 | 2024-12-05 | Insilio                | L   | 0.619      | -            | -                | -                | -         |   -12.54 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           26 |     2188 | 2024-12-05 | Tricked Esport         | L   | 0.616      | -            | -                | -                | -         |    -6.76 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           25 |     2222 | 2024-12-04 | FLuffy Gangsters       | L   | 0.612      | -            | -                | -                | -         |    -7.77 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           24 |     2457 | 2024-12-01 | Betclic Apogee Esports | L   | 0.589      | -            | -                | -                | -         |    -6.90 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           23 |     2822 | 2024-11-24 | BRUTE                  | W   | 0.543      | 0.143        | 0.004 (0.000)    | 0.341 (0.026)    | 1 (0.543) |     6.43 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           22 |     2920 | 2024-11-23 | UNiTY esports          | L   | 0.536      | -            | -                | -                | -         |    -7.33 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           21 |     2975 | 2024-11-22 | ENTERPRISE Genesis     | W   | 0.531      | 0.143        | 0.001 (0.000)    | 0.175 (0.013)    | 1 (0.531) |     5.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           20 |     4098 | 2024-11-03 | Los kogutos            | L   | 0.403      | -            | -                | -                | -         |    -4.49 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           19 |     4395 | 2024-10-29 | 9INE                   | L   | 0.370      | -            | -                | -                | -         |    -6.08 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           18 |     4618 | 2024-10-25 | Los kogutos            | W   | 0.343      | 0.371        | 0.032 (0.004)    | 0.515 (0.065)    | 0 (0.000) |     7.51 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           17 |     5249 | 2024-10-12 | Los kogutos            | L   | 0.256      | -            | -                | -                | -         |    -2.17 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           16 |     5611 | 2024-10-05 | Dynamo Eclot           | L   | 0.210      | -            | -                | -                | -         |    -1.24 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           15 |     5638 | 2024-10-05 | Tricked Esport         | L   | 0.209      | -            | -                | -                | -         |    -3.12 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           14 |     5684 | 2024-10-04 | Dynamo Eclot           | W   | 0.204      | 0.143        | 0.128 (0.004)    | 0.692 (0.020)    | 1 (0.204) |     5.25 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           13 |     5744 | 2024-10-03 | AVEZ                   | W   | 0.196      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.196) |     0.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           12 |     6070 | 2024-09-28 | Wild Lotus             | L   | 0.163      | -            | -                | -                | -         |    -2.92 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           11 |     6534 | 2024-09-22 | SINNERS Esports        | L   | 0.123      | -            | -                | -                | -         |    -1.36 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|           10 |     6599 | 2024-09-21 | Dynamo Eclot           | W   | 0.117      | 0.143        | 0.128 (0.002)    | 0.692 (0.012)    | 1 (0.117) |     3.03 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            9 |     6653 | 2024-09-20 | UNiTY esports          | L   | 0.110      | -            | -                | -                | -         |    -1.59 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            8 |     6706 | 2024-09-19 | Wild Lotus             | L   | 0.105      | -            | -                | -                | -         |    -1.93 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            7 |     6918 | 2024-09-16 | B8                     | W   | 0.082      | 0.384        | 0.126 (0.004)    | 0.586 (0.018)    | 0 (0.000) |     2.20 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            6 |     7162 | 2024-09-12 | OG                     | L   | 0.056      | -            | -                | -                | -         |    -0.63 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            5 |     7274 | 2024-09-10 | MOUZ NXT               | W   | 0.043      | 0.384        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.21 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            4 |     7316 | 2024-09-09 | SINNERS Esports        | L   | 0.037      | -            | -                | -                | -         |    -0.41 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            3 |     7609 | 2024-09-05 | ENTERPRISE Genesis     | W   | 0.011      | 0.143        | 0.001 (0.000)    | 0.175 (0.000)    | 0 (0.000) |     0.10 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            2 |     7638 | 2024-09-05 | Tricked Esport         | W   | 0.009      | 0.384        | 0.034 (0.000)    | 0.687 (0.002)    | 0 (0.000) |     0.16 | fino, manguss, sAvana1, The eLiVe, ZEDKO |
|            1 |     7686 | 2024-09-04 | Metizport              | L   | 0.004      | -            | -                | -                | -         |    -0.02 | fino, manguss, sAvana1, The eLiVe, ZEDKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,074.45)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $4,932.95      | $2,681.61       |
| 2024-10-05 |      0.210 | $5,490.86      | $1,155.37       |
| 2024-09-22 |      0.124 | $1,336.22      | $166.22         |
| 2024-09-14 |      0.071 | $1,000.00      | $71.25          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
