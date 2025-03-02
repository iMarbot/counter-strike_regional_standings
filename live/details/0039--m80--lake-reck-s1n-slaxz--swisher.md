### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1008.0<br />
<br />
Final Rank Value (1008.0) = Starting Rank Value (916.1) + Head To Head Adjustments (91.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 916.1
- 400 + ( ( 0.258 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 916.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      454 | 2025-02-14 | BOSS               | W   | 1.000      | 0.143        | -                | 0.327 (0.047)    | 0 (0.000) |    10.65 | Lake, reck, s1n, slaxz-, Swisher |
|           45 |      476 | 2025-02-14 | NRG                | W   | 1.000      | 0.143        | 0.049 (0.007)    | 0.444 (0.063)    | 0 (0.000) |    17.46 | Lake, reck, s1n, slaxz-, Swisher |
|           44 |      507 | 2025-02-13 | Nouns Esports      | W   | 1.000      | 0.143        | -                | 0.328 (0.047)    | 0 (0.000) |    10.26 | Lake, reck, s1n, slaxz-, Swisher |
|           43 |      571 | 2025-02-10 | Marsborne          | W   | 1.000      | -            | -                | -                | -         |     3.82 | Lake, reck, s1n, slaxz-, Swisher |
|           42 |      612 | 2025-02-09 | Marsborne          | W   | 1.000      | -            | -                | -                | -         |     3.65 | Lake, reck, s1n, slaxz-, Swisher |
|           41 |      673 | 2025-02-08 | Bad News Capybaras | W   | 1.000      | -            | -                | -                | -         |     4.43 | Lake, reck, s1n, slaxz-, Swisher |
|           40 |      815 | 2025-02-06 | Zomblers           | W   | 1.000      | -            | -                | -                | -         |     1.35 | Lake, reck, s1n, slaxz-, Swisher |
|           39 |      820 | 2025-02-06 | Lumen              | W   | 1.000      | -            | -                | -                | -         |     1.31 | Lake, reck, s1n, slaxz-, Swisher |
|           38 |     1178 | 2025-01-16 | FaZe Clan          | L   | 0.906      | -            | -                | -                | -         |    -0.14 | k1to, Lake, s1n, slaxz-, Swisher |
|           37 |     3402 | 2024-11-15 | FURIA              | L   | 0.492      | -            | -                | -                | -         |    -0.97 | Lake, reck, s1n, slaxz-, Swisher |
|           36 |     3415 | 2024-11-14 | BESTIA             | W   | 0.489      | 0.143        | 0.069 (0.005)    | -                | 1 (0.489) |     7.83 | Lake, reck, s1n, slaxz-, Swisher |
|           35 |     3479 | 2024-11-13 | Complexity         | L   | 0.484      | -            | -                | -                | -         |    -3.54 | Lake, reck, s1n, slaxz-, Swisher |
|           34 |     3530 | 2024-11-12 | Legacy             | W   | 0.476      | -            | -                | -                | 1 (0.476) |     6.49 | Lake, reck, s1n, slaxz-, Swisher |
|           33 |     3554 | 2024-11-12 | RED Canids         | W   | 0.472      | -            | -                | -                | 1 (0.472) |     5.64 | Lake, reck, s1n, slaxz-, Swisher |
|           32 |     3575 | 2024-11-11 | BOSS               | L   | 0.470      | -            | -                | -                | -         |    -8.11 | Lake, reck, s1n, slaxz-, Swisher |
|           31 |     4576 | 2024-10-25 | BESTIA             | L   | 0.353      | -            | -                | -                | -         |    -5.64 | Lake, reck, s1n, slaxz-, Swisher |
|           30 |     4622 | 2024-10-24 | Aurora Gaming      | W   | 0.346      | 0.934        | 0.019 (0.006)    | 0.516 (0.166)    | -         |     3.42 | Lake, reck, s1n, slaxz-, Swisher |
|           29 |     4628 | 2024-10-24 | BESTIA             | L   | 0.345      | -            | -                | -                | -         |    -5.62 | Lake, reck, s1n, slaxz-, Swisher |
|           28 |     4759 | 2024-10-20 | NRG                | W   | 0.321      | 0.477        | 0.049 (0.008)    | 0.444 (0.068)    | -         |     5.79 | Lake, reck, s1n, slaxz-, Swisher |
|           27 |     4910 | 2024-10-17 | Legacy             | W   | 0.302      | 0.477        | 0.036 (0.005)    | 0.554 (0.080)    | -         |     4.17 | Lake, reck, s1n, slaxz-, Swisher |
|           26 |     4961 | 2024-10-16 | NRG                | W   | 0.295      | 0.477        | 0.049 (0.007)    | 0.444 (0.062)    | -         |     5.33 | Lake, reck, s1n, slaxz-, Swisher |
|           25 |     5302 | 2024-10-09 | BOSS               | W   | 0.249      | -            | -                | -                | -         |     3.63 | Lake, reck, s1n, slaxz-, Swisher |
|           24 |     5308 | 2024-10-09 | BOSS               | L   | 0.248      | -            | -                | -                | -         |    -4.27 | Lake, reck, s1n, slaxz-, Swisher |
|           23 |     5372 | 2024-10-08 | Legacy             | W   | 0.242      | 0.477        | -                | 0.554 (0.064)    | -         |     3.40 | Lake, reck, s1n, slaxz-, Swisher |
|           22 |     5378 | 2024-10-08 | Legacy             | L   | 0.242      | -            | -                | -                | -         |    -4.29 | Lake, reck, s1n, slaxz-, Swisher |
|           21 |     5385 | 2024-10-08 | Wildcard           | W   | 0.241      | 0.477        | 0.176 (0.020)    | 0.428 (0.049)    | -         |     6.89 | Lake, reck, s1n, slaxz-, Swisher |
|           20 |     5396 | 2024-10-08 | Wildcard           | W   | 0.241      | 0.477        | 0.176 (0.020)    | 0.428 (0.049)    | -         |     6.93 | Lake, reck, s1n, slaxz-, Swisher |
|           19 |     5578 | 2024-10-05 | Wildcard           | L   | 0.219      | -            | -                | -                | -         |    -0.58 | Lake, reck, s1n, slaxz-, Swisher |
|           18 |     5649 | 2024-10-04 | BIG                | L   | 0.214      | -            | -                | -                | -         |    -0.26 | Lake, reck, s1n, slaxz-, Swisher |
|           17 |     5656 | 2024-10-04 | Wildcard           | W   | 0.213      | 0.500        | 0.176 (0.019)    | -                | 1 (0.213) |     6.18 | Lake, reck, s1n, slaxz-, Swisher |
|           16 |     5810 | 2024-10-01 | Party Astronauts   | W   | 0.195      | -            | -                | -                | -         |     1.92 | Lake, reck, s1n, slaxz-, Swisher |
|           15 |     5816 | 2024-10-01 | Party Astronauts   | L   | 0.195      | -            | -                | -                | -         |    -4.28 | Lake, reck, s1n, slaxz-, Swisher |
|           14 |     5819 | 2024-10-01 | Nouns Esports      | W   | 0.195      | -            | -                | -                | -         |     1.60 | Lake, reck, s1n, slaxz-, Swisher |
|           13 |     5824 | 2024-10-01 | Nouns Esports      | L   | 0.194      | -            | -                | -                | -         |    -4.58 | Lake, reck, s1n, slaxz-, Swisher |
|           12 |     5884 | 2024-09-30 | Chill Guys         | W   | 0.188      | -            | -                | -                | -         |     1.10 | Lake, reck, s1n, slaxz-, Swisher |
|           11 |     5886 | 2024-09-30 | Chill Guys         | W   | 0.188      | -            | -                | -                | -         |     1.11 | Lake, reck, s1n, slaxz-, Swisher |
|           10 |     5990 | 2024-09-28 | Bad News Capybaras | W   | 0.175      | -            | -                | -                | -         |     1.01 | Lake, reck, s1n, slaxz-, Swisher |
|            9 |     5993 | 2024-09-28 | Bad News Capybaras | W   | 0.175      | -            | -                | -                | -         |     1.02 | Lake, reck, s1n, slaxz-, Swisher |
|            8 |     6163 | 2024-09-26 | Timbermen          | W   | 0.162      | -            | -                | -                | -         |     1.22 | Lake, reck, s1n, slaxz-, Swisher |
|            7 |     6164 | 2024-09-26 | Timbermen          | W   | 0.162      | -            | -                | -                | -         |     1.23 | Lake, reck, s1n, slaxz-, Swisher |
|            6 |     6242 | 2024-09-25 | NRG                | W   | 0.155      | -            | -                | -                | -         |     3.14 | Lake, reck, s1n, slaxz-, Swisher |
|            5 |     6247 | 2024-09-25 | NRG                | L   | 0.155      | -            | -                | -                | -         |    -1.77 | Lake, reck, s1n, slaxz-, Swisher |
|            4 |     6703 | 2024-09-19 | MIBR               | L   | 0.112      | -            | -                | -                | -         |    -0.17 | Lake, reck, s1n, slaxz-, Swisher |
|            3 |     6980 | 2024-09-14 | Imperial Esports   | W   | 0.080      | 0.889        | 0.091 (0.006)    | -                | 1 (0.080) |     1.50 | Lake, reck, s1n, slaxz-, Swisher |
|            2 |     7182 | 2024-09-11 | Fnatic             | W   | 0.060      | -            | -                | -                | 1 (0.060) |     1.31 | Lake, reck, s1n, slaxz-, Swisher |
|            1 |     7241 | 2024-09-10 | Complexity         | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.31 | Lake, reck, s1n, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,940.76)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $25,000.00     | $8,027.78       |
| 2024-10-06 |      0.227 | $3,000.00      | $681.88         |
| 2024-09-22 |      0.132 | $32,000.00     | $4,231.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
