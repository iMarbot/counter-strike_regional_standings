### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, land1n, lub, perez<br />
Global Rank: [481](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [106]( ../standings_americas.md)<br />
<br />
Final Rank Value:  530.7<br />
<br />
Final Rank Value (530.7) = Starting Rank Value (511.3) + Head To Head Adjustments (19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.3
- 400 + ( ( 0.056 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 511.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2727 | 2024-11-26 | 20/70                    | L   | 0.566      | -            | -                | -                | -         |    -6.02 | CSO, CutzMeretz, land1n, lub, perez  |
|           19 |     2782 | 2024-11-24 | LaChampionsLiga          | W   | 0.553      | 0.371        | 0.003 (0.001)    | 0.444 (0.091)    | 0 (0.000) |    11.50 | CSO, CutzMeretz, land1n, lub, perez  |
|           18 |     2939 | 2024-11-22 | Floripa Stars            | L   | 0.542      | -            | -                | -                | -         |    -5.59 | CSO, CutzMeretz, land1n, lub, perez  |
|           17 |     3071 | 2024-11-20 | AMIGOS (Brazilian team)  | W   | 0.528      | 0.371        | 0.000 (0.000)    | 0.164 (0.032)    | 0 (0.000) |     8.23 | CSO, CutzMeretz, land1n, lub, perez  |
|           16 |     3160 | 2024-11-19 | Nitro.GG                 | L   | 0.519      | -            | -                | -                | -         |    -5.26 | CSO, CutzMeretz, land1n, lub, perez  |
|           15 |     3593 | 2024-11-11 | Bad News Chickens        | L   | 0.467      | -            | -                | -                | -         |    -4.54 | CSO, CutzMeretz, Lcm, lub, perez     |
|           14 |     3864 | 2024-11-06 | Team Solid               | L   | 0.434      | -            | -                | -                | -         |    -1.90 | CSO, CutzMeretz, Lcm, lub, perez     |
|           13 |     3913 | 2024-11-05 | VELOX Argentina          | W   | 0.428      | 0.371        | 0.000 (0.000)    | 0.266 (0.042)    | 0 (0.000) |     8.21 | CSO, CutzMeretz, Lcm, lub, perez     |
|           12 |     3979 | 2024-11-04 | Players (Brazilian team) | L   | 0.421      | -            | -                | -                | -         |    -3.01 | CSO, CutzMeretz, Lcm, lub, perez     |
|           11 |     4176 | 2024-11-01 | Yawara E-Sports          | W   | 0.401      | 0.371        | 0.002 (0.000)    | 0.454 (0.067)    | 0 (0.000) |     9.32 | CSO, CutzMeretz, Lcm, lub, perez     |
|           10 |     4282 | 2024-10-30 | BeBold.gg                | W   | 0.387      | 0.371        | 0.000 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     6.78 | CSO, CutzMeretz, Lcm, lub, perez     |
|            9 |     4401 | 2024-10-28 | Game Hunters             | L   | 0.374      | -            | -                | -                | -         |    -3.19 | CSO, CutzMeretz, Lcm, lub, perez     |
|            8 |     5994 | 2024-09-28 | Sharks Esports           | L   | 0.175      | -            | -                | -                | -         |    -0.31 | CSO, CutzMeretz, jz, Lcm, perez      |
|            7 |     6040 | 2024-09-28 | Yokai                    | W   | 0.172      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.57 | CSO, CutzMeretz, jz, Lcm, perez      |
|            6 |     6091 | 2024-09-27 | Dusty Roots              | L   | 0.168      | -            | -                | -                | -         |    -0.92 | CSO, CutzMeretz, jz, Lcm, perez      |
|            5 |     6102 | 2024-09-27 | KRÜ Esports              | W   | 0.167      | 0.143        | 0.001 (0.000)    | 0.132 (0.003)    | 0 (0.000) |     3.91 | CSO, CutzMeretz, jz, Lcm, perez      |
|            4 |     6668 | 2024-09-19 | Floripa Stars            | L   | 0.115      | -            | -                | -                | -         |    -1.10 | CSO, CutzMeretz, Misfit, perez, zede |
|            3 |     6797 | 2024-09-17 | Bad News Chickens        | L   | 0.101      | -            | -                | -                | -         |    -0.89 | CSO, CutzMeretz, Misfit, perez, zede |
|            2 |     7221 | 2024-09-10 | PaiN Gaming Academy      | W   | 0.054      | 0.262        | 0.000 (0.000)    | 0.221 (0.003)    | 0 (0.000) |     0.85 | CSO, CutzMeretz, Misfit, perez, zede |
|            1 |     7410 | 2024-09-07 | Floripa Stars            | W   | 0.033      | 0.262        | 0.001 (0.000)    | 0.302 (0.003)    | 0 (0.000) |     0.72 | CSO, CutzMeretz, Misfit, perez, zede |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
