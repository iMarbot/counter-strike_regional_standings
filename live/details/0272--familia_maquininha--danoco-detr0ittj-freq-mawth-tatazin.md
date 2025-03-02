### Roster Details<br />
Team Name: Familia Maquininha<br />
Roster: danoco, detr0ittJ, fREQ, mawth, tatazin<br />
Global Rank: [272](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  666.6<br />
<br />
Final Rank Value (666.6) = Starting Rank Value (682.5) + Head To Head Adjustments (-15.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.5
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 682.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      331 | 2025-02-16 | Players (Brazilian team) | L   | 1.000      | -            | -                | -                | -         |   -11.28 | danoco, detr0ittJ, fREQ, mawth, tatazin   |
|           33 |      503 | 2025-02-13 | Yawara E-Sports          | L   | 1.000      | -            | -                | -                | -         |   -16.54 | danoco, detr0ittJ, fREQ, mawth, tatazin   |
|           32 |      546 | 2025-02-11 | Nitro.GG                 | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.518 (0.192)    | 0 (0.000) |    14.14 | danoco, detr0ittJ, fREQ, mawth, tatazin   |
|           31 |      580 | 2025-02-10 | MIBR Academy             | L   | 1.000      | -            | -                | -                | -         |   -14.83 | danoco, detr0ittJ, fREQ, mawth, tatazin   |
|           30 |      839 | 2025-02-06 | Dusty Roots              | L   | 1.000      | -            | -                | -                | -         |   -13.55 | danoco, detr0ittJ, mawth, tatazin, urban0 |
|           29 |      897 | 2025-02-05 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |    -8.36 | danoco, detr0ittJ, mawth, tatazin, urban0 |
|           28 |      927 | 2025-02-04 | UNO MILLE                | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.526 (0.075)    | 0 (0.000) |    18.23 | danoco, detr0ittJ, mawth, tatazin, urban0 |
|           27 |      932 | 2025-02-04 | LaChampionsLiga          | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.444 (0.063)    | 0 (0.000) |    13.51 | danoco, detr0ittJ, mawth, tatazin, urban0 |
|           26 |     1200 | 2025-01-10 | Team Solid               | L   | 0.866      | -            | -                | -                | -         |    -7.05 | danoco, ksloks, mawth, RCF, tatazin       |
|           25 |     4963 | 2024-10-16 | Party Astronauts         | L   | 0.295      | -            | -                | -                | -         |    -3.37 | danoco, land1n, mawth, tatazin, w1        |
|           24 |     5032 | 2024-10-15 | Timbermen                | W   | 0.288      | 0.477        | 0.011 (0.002)    | 0.160 (0.022)    | 0 (0.000) |     4.88 | danoco, land1n, mawth, tatazin, w1        |
|           23 |     5307 | 2024-10-09 | Legacy                   | L   | 0.249      | -            | -                | -                | -         |    -1.88 | danoco, land1n, mawth, tatazin, w1        |
|           22 |     5314 | 2024-10-09 | Legacy                   | L   | 0.248      | -            | -                | -                | -         |    -1.91 | danoco, land1n, mawth, tatazin, w1        |
|           21 |     5373 | 2024-10-08 | Bad News Capybaras       | W   | 0.242      | 0.477        | 0.001 (0.000)    | 0.115 (0.013)    | 0 (0.000) |     3.44 | danoco, land1n, mawth, tatazin, w1        |
|           20 |     5379 | 2024-10-08 | Bad News Capybaras       | W   | 0.242      | 0.477        | -                | 0.115 (0.013)    | 0 (0.000) |     3.51 | danoco, land1n, mawth, tatazin, w1        |
|           19 |     5445 | 2024-10-07 | Chill Guys               | W   | 0.235      | 0.477        | 0.003 (0.000)    | 0.313 (0.035)    | 0 (0.000) |     3.49 | danoco, land1n, mawth, tatazin, w1        |
|           18 |     5447 | 2024-10-07 | Chill Guys               | L   | 0.235      | -            | -                | -                | -         |    -3.98 | danoco, land1n, mawth, tatazin, w1        |
|           17 |     5889 | 2024-09-30 | Timbermen                | L   | 0.188      | -            | -                | -                | -         |    -2.75 | danoco, land1n, mawth, tatazin, w1        |
|           16 |     6095 | 2024-09-27 | NRG                      | L   | 0.168      | -            | -                | -                | -         |    -0.72 | danoco, land1n, mawth, tatazin, w1        |
|           15 |     6170 | 2024-09-26 | MIGHT                    | W   | 0.161      | -            | -                | -                | 0 (0.000) |     2.91 | danoco, land1n, mawth, tatazin, w1        |
|           14 |     6239 | 2024-09-25 | Party Astronauts         | L   | 0.155      | -            | -                | -                | -         |    -1.89 | danoco, land1n, mawth, tatazin, w1        |
|           13 |     6243 | 2024-09-25 | Party Astronauts         | L   | 0.155      | -            | -                | -                | -         |    -1.91 | danoco, land1n, mawth, tatazin, w1        |
|           12 |     6336 | 2024-09-24 | Vagrants                 | W   | 0.148      | 0.477        | 0.001 (0.000)    | 0.278 (0.020)    | 0 (0.000) |     2.10 | danoco, land1n, mawth, tatazin, w1        |
|           11 |     6338 | 2024-09-24 | Vagrants                 | W   | 0.148      | 0.477        | 0.001 (0.000)    | 0.278 (0.020)    | 0 (0.000) |     2.12 | danoco, land1n, mawth, tatazin, w1        |
|           10 |     6422 | 2024-09-23 | Timbermen                | W   | 0.142      | 0.477        | 0.011 (0.001)    | 0.160 (0.011)    | -         |     2.48 | danoco, land1n, mawth, tatazin, w1        |
|            9 |     6426 | 2024-09-23 | Timbermen                | W   | 0.142      | 0.477        | 0.011 (0.001)    | -                | -         |     2.50 | danoco, land1n, mawth, tatazin, w1        |
|            8 |     6493 | 2024-09-22 | Final Form               | W   | 0.135      | -            | -                | -                | -         |     1.71 | danoco, land1n, mawth, tatazin, w1        |
|            7 |     6548 | 2024-09-21 | Akimbo Esports           | L   | 0.128      | -            | -                | -                | -         |    -2.17 | danoco, land1n, mawth, tatazin, w1        |
|            6 |     6719 | 2024-09-18 | Wildcard                 | L   | 0.108      | -            | -                | -                | -         |    -0.07 | danoco, land1n, mawth, tatazin, w1        |
|            5 |     6724 | 2024-09-18 | Wildcard                 | L   | 0.108      | -            | -                | -                | -         |    -0.07 | danoco, land1n, mawth, tatazin, w1        |
|            4 |     6796 | 2024-09-17 | Jahsdnmasjdm v2          | W   | 0.102      | -            | -                | -                | -         |     0.81 | danoco, land1n, mawth, tatazin, w1        |
|            3 |     7222 | 2024-09-10 | Regain                   | W   | 0.054      | -            | -                | -                | -         |     0.43 | danoco, land1n, mawth, tatazin, w1        |
|            2 |     7689 | 2024-09-03 | Mythic                   | W   | 0.009      | -            | -                | -                | -         |     0.07 | danoco, land1n, mawth, tatazin, w1        |
|            1 |     7699 | 2024-09-03 | Mythic                   | W   | 0.008      | -            | -                | -                | -         |     0.07 | danoco, land1n, mawth, tatazin, w1        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($963.33)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $3,000.00      | $963.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
