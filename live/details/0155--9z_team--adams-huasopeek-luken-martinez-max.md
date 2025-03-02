### Roster Details<br />
Team Name: 9z Team<br />
Roster: adamS, HUASOPEEK, Luken, Martinez, max<br />
Global Rank: [155](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  757.2<br />
<br />
Final Rank Value (757.2) = Starting Rank Value (781.4) + Head To Head Adjustments (-24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.147[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.4
- 400 + ( ( 0.191 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 781.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      259 | 2025-02-19 | ODDIK         | L   | 1.000      | -            | -                | -                | -         |   -10.42 | adamS, HUASOPEEK, Luken, Martinez, max |
|           23 |      823 | 2025-02-06 | Elevate       | L   | 1.000      | -            | -                | -                | -         |   -23.28 | HUASOPEEK, Luken, Martinez, max, yel   |
|           22 |      871 | 2025-02-05 | RED Canids    | L   | 1.000      | -            | -                | -                | -         |   -12.64 | dgt, HUASOPEEK, Luken, Martinez, max   |
|           21 |      898 | 2025-02-05 | Tropa do VSM  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.140 (0.020)    | 0 (0.000) |     4.85 | dgt, HUASOPEEK, Luken, Martinez, max   |
|           20 |     3413 | 2024-11-15 | FURIA         | L   | 0.491      | -            | -                | -                | -         |    -0.42 | buda, dgt, HUASOPEEK, Martinez, max    |
|           19 |     3481 | 2024-11-13 | PaiN Gaming   | L   | 0.483      | -            | -                | -                | -         |    -0.18 | buda, dgt, HUASOPEEK, Martinez, max    |
|           18 |     3525 | 2024-11-12 | Wildcard      | L   | 0.477      | -            | -                | -                | -         |    -0.73 | buda, dgt, HUASOPEEK, Martinez, max    |
|           17 |     3562 | 2024-11-12 | Legacy        | W   | 0.471      | 0.143        | 0.036 (0.002)    | 0.554 (0.037)    | 1 (0.471) |     9.73 | buda, dgt, HUASOPEEK, Martinez, max    |
|           16 |     3574 | 2024-11-11 | RED Canids    | W   | 0.470      | 0.143        | 0.020 (0.001)    | 0.193 (0.013)    | 1 (0.470) |     9.00 | buda, dgt, HUASOPEEK, Martinez, max    |
|           15 |     4705 | 2024-10-22 | Cloud9        | L   | 0.333      | -            | -                | -                | -         |    -3.75 | buda, dgt, HUASOPEEK, Martinez, max    |
|           14 |     4711 | 2024-10-22 | Fnatic        | L   | 0.332      | -            | -                | -                | -         |    -1.85 | buda, dgt, HUASOPEEK, Martinez, max    |
|           13 |     4891 | 2024-10-18 | ENCE          | L   | 0.306      | -            | -                | -                | -         |    -2.20 | buda, dgt, HUASOPEEK, Martinez, max    |
|           12 |     4929 | 2024-10-17 | Rebels Gaming | W   | 0.299      | 0.589        | 0.009 (0.002)    | 0.301 (0.053)    | 1 (0.299) |     4.07 | buda, dgt, HUASOPEEK, Martinez, max    |
|           11 |     4948 | 2024-10-17 | ENCE          | L   | 0.298      | -            | -                | -                | -         |    -2.14 | buda, dgt, HUASOPEEK, Martinez, max    |
|           10 |     5426 | 2024-10-08 | Virtus.pro    | L   | 0.239      | -            | -                | -                | -         |    -0.06 | buda, dgt, HUASOPEEK, Martinez, max    |
|            9 |     5478 | 2024-10-07 | Team Vitality | L   | 0.233      | -            | -                | -                | -         |    -0.01 | buda, dgt, HUASOPEEK, Martinez, max    |
|            8 |     6021 | 2024-09-28 | SAW           | L   | 0.173      | -            | -                | -                | -         |    -0.24 | buda, dgt, HUASOPEEK, Martinez, max    |
|            7 |     6053 | 2024-09-28 | GameAgents    | W   | 0.172      | 0.143        | 0.003 (0.000)    | 0.119 (0.003)    | 0 (0.000) |     2.11 | buda, dgt, HUASOPEEK, Martinez, max    |
|            6 |     6120 | 2024-09-27 | 3DMAX         | L   | 0.166      | -            | -                | -                | -         |    -0.05 | buda, dgt, HUASOPEEK, Martinez, max    |
|            5 |     6139 | 2024-09-27 | Alliance      | W   | 0.165      | 0.143        | 0.015 (0.000)    | 0.573 (0.014)    | 0 (0.000) |     3.43 | buda, dgt, HUASOPEEK, Martinez, max    |
|            4 |     7455 | 2024-09-07 | The MongolZ   | L   | 0.031      | -            | -                | -                | -         |    -0.00 | buda, dgt, HUASOPEEK, Martinez, max    |
|            3 |     7532 | 2024-09-06 | 3DMAX         | L   | 0.025      | -            | -                | -                | -         |    -0.01 | buda, dgt, HUASOPEEK, Martinez, max    |
|            2 |     7605 | 2024-09-05 | Wildcard      | W   | 0.019      | 0.889        | 0.176 (0.003)    | 0.428 (0.007)    | 1 (0.019) |     0.57 | buda, dgt, HUASOPEEK, Martinez, max    |
|            1 |     7725 | 2024-09-03 | MIBR          | L   | 0.006      | -            | -                | -                | -         |    -0.00 | buda, dgt, HUASOPEEK, Martinez, max    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,204.86)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.319 | $10,000.00     | $3,188.19       |
| 2024-10-13 |      0.273 | $4,000.00      | $1,091.11       |
| 2024-09-22 |      0.132 | $7,000.00      | $925.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
