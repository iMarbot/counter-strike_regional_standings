### Roster Details<br />
Team Name: RUBY<br />
Roster: fozil, H4SAN4TOR, Kaide, mo0N, Sowalio<br />
Global Rank: [199](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [145]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.1<br />
<br />
Final Rank Value (712.1) = Starting Rank Value (689.7) + Head To Head Adjustments (22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.7
- 400 + ( ( 0.145 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 689.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      143 | 2025-02-22 | K27                                       | L   | 1.000      | -            | -                | -                | -         |   -12.33 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           27 |      410 | 2025-02-15 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -16.50 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           26 |      413 | 2025-02-15 | Preasy Esport                             | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.710 (0.101)    | 0 (0.000) |    16.81 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           25 |      468 | 2025-02-14 | GhoulsW                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.41 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           24 |      696 | 2025-02-08 | ToxicAndCritic                            | L   | 1.000      | -            | -                | -                | -         |   -22.61 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           23 |      772 | 2025-02-07 | 8Sins                                     | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.234 (0.033)    | 0 (0.000) |    22.16 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           22 |     5953 | 2024-09-29 | Preasy Esport                             | W   | 0.180      | 0.333        | 0.012 (0.001)    | 0.710 (0.043)    | 0 (0.000) |     3.55 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           21 |     5977 | 2024-09-29 | FLuffy Gangsters                          | W   | 0.178      | 0.143        | 0.014 (0.000)    | 0.925 (0.023)    | 0 (0.000) |     3.44 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           20 |     6012 | 2024-09-28 | Partizan Esports                          | W   | 0.173      | 0.333        | 0.082 (0.005)    | 0.768 (0.044)    | 0 (0.000) |     4.87 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           19 |     6067 | 2024-09-28 | Alliance                                  | W   | 0.171      | 0.333        | 0.015 (0.001)    | 0.573 (0.033)    | 0 (0.000) |     4.01 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           18 |     6216 | 2024-09-26 | Preasy Esport                             | L   | 0.158      | -            | -                | -                | -         |    -1.79 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           17 |     6293 | 2024-09-25 | ENCE Academy                              | W   | 0.153      | 0.143        | 0.009 (0.000)    | -                | 0 (0.000) |     3.11 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           16 |     6303 | 2024-09-25 | FLuffy Gangsters                          | W   | 0.152      | 0.333        | 0.014 (0.001)    | 0.925 (0.047)    | 0 (0.000) |     2.99 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           15 |     6373 | 2024-09-24 | Daystar                                   | W   | 0.146      | -            | -                | -                | 0 (0.000) |     2.01 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           14 |     6400 | 2024-09-24 | ADEPTS                                    | W   | 0.145      | -            | -                | -                | -         |     2.17 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           13 |     6450 | 2024-09-23 | ALASKA                                    | W   | 0.140      | 0.333        | 0.030 (0.001)    | 0.875 (0.041)    | -         |     4.10 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           12 |     6505 | 2024-09-22 | Rhyno Esports                             | L   | 0.133      | -            | -                | -                | -         |    -2.20 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           11 |     6532 | 2024-09-22 | Viperio                                   | W   | 0.131      | 0.333        | -                | 0.411 (0.018)    | -         |     2.45 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           10 |     6562 | 2024-09-21 | Alliance                                  | L   | 0.127      | -            | -                | -                | -         |    -0.97 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            9 |     6623 | 2024-09-20 | Copenhagen Wolves (American organization) | W   | 0.120      | -            | -                | -                | -         |     1.15 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            8 |     6649 | 2024-09-20 | Partizan Esports                          | L   | 0.117      | -            | -                | -                | -         |    -0.34 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            7 |     6689 | 2024-09-19 | FLuffy Gangsters                          | W   | 0.113      | 0.143        | 0.014 (0.000)    | 0.925 (0.015)    | -         |     2.29 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            6 |     7087 | 2024-09-13 | AMKAL ESPORTS                             | L   | 0.072      | -            | -                | -                | -         |    -0.91 | Chill, Kaide, mo0N, Something, Sowalio |
|            5 |     7152 | 2024-09-12 | ENCE Academy                              | W   | 0.064      | -            | -                | -                | -         |     1.35 | Chill, Kaide, mo0N, Something, Sowalio |
|            4 |     7201 | 2024-09-11 | AMKAL ESPORTS                             | L   | 0.058      | -            | -                | -                | -         |    -0.73 | Chill, Kaide, mo0N, Something, Sowalio |
|            3 |     7592 | 2024-09-05 | Dynamo Eclot                              | L   | 0.019      | -            | -                | -                | -         |    -0.06 | Chill, Kaide, mo0N, Something, Sowalio |
|            2 |     7670 | 2024-09-04 | Team Spirit Academy                       | L   | 0.012      | -            | -                | -                | -         |    -0.08 | Chill, Kaide, mo0N, Something, Sowalio |
|            1 |     7751 | 2024-09-03 | BC.Game Esports                           | W   | 0.004      | -            | -                | -                | -         |     0.10 | Chill, Kaide, mo0N, Something, Sowalio |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,077.08)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.180 | $6,000.00      | $1,077.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
