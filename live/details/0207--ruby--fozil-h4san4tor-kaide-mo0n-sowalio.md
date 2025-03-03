### Roster Details<br />
Team Name: RUBY<br />
Roster: fozil, H4SAN4TOR, Kaide, mo0N, Sowalio<br />
Global Rank: [207](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [148]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.2<br />
<br />
Final Rank Value (709.2) = Starting Rank Value (688.2) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 688.2
- 400 + ( ( 0.144 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 688.2


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
|           27 |      158 | 2025-02-22 | K27                                       | L   | 1.000      | -            | -                | -                | -         |   -12.19 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           26 |      422 | 2025-02-15 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -16.40 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           25 |      425 | 2025-02-15 | Preasy Esport                             | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.701 (0.100)    | 0 (0.000) |    16.81 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           24 |      480 | 2025-02-14 | GhoulsW                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.48 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           23 |      708 | 2025-02-08 | ToxicAndCritic                            | L   | 1.000      | -            | -                | -                | -         |   -22.49 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           22 |      784 | 2025-02-07 | 8Sins                                     | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.233 (0.033)    | 0 (0.000) |    22.31 | fozil, H4SAN4TOR, Kaide, mo0N, Sowalio |
|           21 |     5965 | 2024-09-29 | Preasy Esport                             | W   | 0.171      | 0.333        | 0.012 (0.001)    | 0.701 (0.040)    | 0 (0.000) |     3.40 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           20 |     5989 | 2024-09-29 | FLuffy Gangsters                          | W   | 0.170      | 0.143        | 0.014 (0.000)    | 0.909 (0.022)    | 0 (0.000) |     3.29 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           19 |     6024 | 2024-09-28 | Partizan Esports                          | W   | 0.165      | 0.333        | 0.083 (0.005)    | 0.757 (0.042)    | 0 (0.000) |     4.64 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           18 |     6079 | 2024-09-28 | Alliance                                  | W   | 0.163      | 0.333        | 0.015 (0.001)    | 0.570 (0.031)    | 0 (0.000) |     3.83 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           17 |     6228 | 2024-09-26 | Preasy Esport                             | L   | 0.150      | -            | -                | -                | -         |    -1.70 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           16 |     6305 | 2024-09-25 | ENCE Academy                              | W   | 0.145      | 0.143        | 0.009 (0.000)    | -                | 0 (0.000) |     2.96 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           15 |     6315 | 2024-09-25 | FLuffy Gangsters                          | W   | 0.143      | 0.333        | 0.014 (0.001)    | 0.909 (0.043)    | 0 (0.000) |     2.83 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           14 |     6384 | 2024-09-24 | Daystar                                   | W   | 0.138      | -            | -                | -                | 0 (0.000) |     1.90 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           13 |     6412 | 2024-09-24 | ADEPTS                                    | W   | 0.137      | -            | -                | -                | -         |     1.56 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           12 |     6462 | 2024-09-23 | ALASKA                                    | W   | 0.132      | 0.333        | 0.031 (0.001)    | 0.867 (0.038)    | -         |     3.86 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           11 |     6517 | 2024-09-22 | Rhyno Esports                             | L   | 0.125      | -            | -                | -                | -         |    -2.06 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|           10 |     6544 | 2024-09-22 | Viperio                                   | W   | 0.122      | 0.333        | -                | 0.404 (0.017)    | -         |     2.29 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            9 |     6574 | 2024-09-21 | Alliance                                  | L   | 0.118      | -            | -                | -                | -         |    -0.90 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            8 |     6635 | 2024-09-20 | Copenhagen Wolves (American organization) | W   | 0.112      | -            | -                | -                | -         |     1.06 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            7 |     6661 | 2024-09-20 | Partizan Esports                          | L   | 0.109      | -            | -                | -                | -         |    -0.32 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            6 |     6701 | 2024-09-19 | FLuffy Gangsters                          | W   | 0.105      | 0.143        | 0.014 (0.000)    | 0.909 (0.014)    | -         |     2.13 | forkyz, Kaide, mo0N, Sowalio, tasman   |
|            5 |     7099 | 2024-09-13 | AMKAL ESPORTS                             | L   | 0.064      | -            | -                | -                | -         |    -0.81 | Chill, Kaide, mo0N, Something, Sowalio |
|            4 |     7164 | 2024-09-12 | ENCE Academy                              | W   | 0.056      | -            | -                | -                | -         |     1.18 | Chill, Kaide, mo0N, Something, Sowalio |
|            3 |     7213 | 2024-09-11 | AMKAL ESPORTS                             | L   | 0.050      | -            | -                | -                | -         |    -0.63 | Chill, Kaide, mo0N, Something, Sowalio |
|            2 |     7604 | 2024-09-05 | Dynamo Eclot                              | L   | 0.011      | -            | -                | -                | -         |    -0.04 | Chill, Kaide, mo0N, Something, Sowalio |
|            1 |     7682 | 2024-09-04 | Team Spirit Academy                       | L   | 0.004      | -            | -                | -                | -         |    -0.03 | Chill, Kaide, mo0N, Something, Sowalio |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,027.92)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-29 |      0.171 | $6,000.00      | $1,027.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
