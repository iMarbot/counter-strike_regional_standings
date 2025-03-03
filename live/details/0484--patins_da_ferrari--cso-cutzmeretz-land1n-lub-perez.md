### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, land1n, lub, perez<br />
Global Rank: [484](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [108]( ../standings_americas.md)<br />
<br />
Final Rank Value:  528.5<br />
<br />
Final Rank Value (528.5) = Starting Rank Value (510.8) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.8
- 400 + ( ( 0.055 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 510.8


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
|           20 |     2739 | 2024-11-26 | 20/70                    | L   | 0.558      | -            | -                | -                | -         |    -5.91 | CSO, CutzMeretz, land1n, lub, perez  |
|           19 |     2794 | 2024-11-24 | LaChampionsLiga          | W   | 0.545      | 0.371        | 0.003 (0.001)    | 0.440 (0.089)    | 0 (0.000) |    11.35 | CSO, CutzMeretz, land1n, lub, perez  |
|           18 |     2951 | 2024-11-22 | Floripa Stars            | L   | 0.534      | -            | -                | -                | -         |    -5.48 | CSO, CutzMeretz, land1n, lub, perez  |
|           17 |     3083 | 2024-11-20 | AMIGOS (Brazilian team)  | W   | 0.520      | 0.371        | 0.000 (0.000)    | 0.162 (0.031)    | 0 (0.000) |     8.14 | CSO, CutzMeretz, land1n, lub, perez  |
|           16 |     3172 | 2024-11-19 | Nitro.GG                 | L   | 0.511      | -            | -                | -                | -         |    -5.14 | CSO, CutzMeretz, land1n, lub, perez  |
|           15 |     3605 | 2024-11-11 | Bad News Chickens        | L   | 0.459      | -            | -                | -                | -         |    -4.44 | CSO, CutzMeretz, Lcm, lub, perez     |
|           14 |     3876 | 2024-11-06 | Team Solid               | L   | 0.426      | -            | -                | -                | -         |    -1.86 | CSO, CutzMeretz, Lcm, lub, perez     |
|           13 |     3925 | 2024-11-05 | VELOX Argentina          | W   | 0.420      | 0.371        | 0.000 (0.000)    | 0.262 (0.041)    | 0 (0.000) |     6.84 | CSO, CutzMeretz, Lcm, lub, perez     |
|           12 |     3991 | 2024-11-04 | Players (Brazilian team) | L   | 0.412      | -            | -                | -                | -         |    -2.94 | CSO, CutzMeretz, Lcm, lub, perez     |
|           11 |     4188 | 2024-11-01 | Yawara E-Sports          | W   | 0.393      | 0.371        | 0.002 (0.000)    | 0.448 (0.065)    | 0 (0.000) |     9.12 | CSO, CutzMeretz, Lcm, lub, perez     |
|           10 |     4294 | 2024-10-30 | BeBold.gg                | W   | 0.379      | 0.371        | 0.000 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     6.66 | CSO, CutzMeretz, Lcm, lub, perez     |
|            9 |     4413 | 2024-10-28 | Game Hunters             | L   | 0.366      | -            | -                | -                | -         |    -3.11 | CSO, CutzMeretz, Lcm, lub, perez     |
|            8 |     6006 | 2024-09-28 | Sharks Esports           | L   | 0.166      | -            | -                | -                | -         |    -0.29 | CSO, CutzMeretz, jz, Lcm, perez      |
|            7 |     6052 | 2024-09-28 | Yokai                    | W   | 0.164      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.46 | CSO, CutzMeretz, jz, Lcm, perez      |
|            6 |     6103 | 2024-09-27 | Dusty Roots              | L   | 0.159      | -            | -                | -                | -         |    -0.88 | CSO, CutzMeretz, jz, Lcm, perez      |
|            5 |     6114 | 2024-09-27 | KRÜ Esports              | W   | 0.159      | 0.143        | 0.001 (0.000)    | 0.131 (0.003)    | 0 (0.000) |     3.72 | CSO, CutzMeretz, jz, Lcm, perez      |
|            4 |     6680 | 2024-09-19 | Floripa Stars            | L   | 0.106      | -            | -                | -                | -         |    -1.03 | CSO, CutzMeretz, Misfit, perez, zede |
|            3 |     6809 | 2024-09-17 | Bad News Chickens        | L   | 0.093      | -            | -                | -                | -         |    -0.82 | CSO, CutzMeretz, Misfit, perez, zede |
|            2 |     7233 | 2024-09-10 | PaiN Gaming Academy      | W   | 0.046      | 0.262        | 0.000 (0.000)    | 0.219 (0.003)    | 0 (0.000) |     0.72 | CSO, CutzMeretz, Misfit, perez, zede |
|            1 |     7422 | 2024-09-07 | Floripa Stars            | W   | 0.025      | 0.262        | 0.001 (0.000)    | 0.296 (0.002)    | 0 (0.000) |     0.54 | CSO, CutzMeretz, Misfit, perez, zede |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
